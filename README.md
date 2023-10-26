기능 목록 작성
==========

## 사용자
- [ ] 자동차 이름 입력
  * 이름이 여러 개면 쉼표(,)로 구분한다.
  * 이름은 5자 이하만 가능하다.
- [ ] 시도할 횟수 입력
### 예외 발생
- [ ] :boom: 이름이 5자를 초과할 때  
- [ ] :boom: 이름이 여러 개인데 쉼표(,)로 구분하지 않았을 때  
- [ ] :boom: 횟수의 입력값이 숫자가 아닐 때

## 자동차
- [ ] 0 ~ 9 숫자 랜덤 생성
- [ ] 주행
  * 생성된 숫자가 4 이상이면 전진한다.
  * 생성된 숫자가 4 미만이면 멈춘다.
## 트랙
- [ ] 입력 받은 자동차 이름으로 자동차들 생성
  * 생성된 자동차를 리스트에 추가한다.
- [ ] 입력 받은 횟수로 자동차 주행
  * 주행이 끝나면 최종 우승자를 발표한다.
    * 최종 우승자가 여러 명이면 쉼표(,)로 구분한다.


# 공공 데이터를 이용한 간단한 데이터 시각화

대전광역시에서 2017~2020년도에 발생한 유기동물 데이터를 csv 파일로 가져와 간단하게 시각화 하는 프로젝트.

1. 두 csv 파일을 조인하여 2017-2020 자료로 전환
2. 연도별 데이터 표현
3. 지도 시각화
