# Google Dialogflow를 이용하여 시나리오 구현하기
## 목차
  1. 시나리오
  2. Intent
  3. Entities
  4. Intent가 이어진 순서
  5. 테스트 및 훈련 문구
## 시나리오
  [시나리오 참고](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/blob/main/week2/report.md)
## Intent
  - condo_name
  - condo_checkin
  - condo_checkout
  - condo_option
  - condo_numberofpeople
  - condo_finalcheck
## Entities
  @bool (콘도가 있는지 확인하여 true면 예약진행, false면 로그아웃)
  @condo_option (오전, 야간, 대인, 소인을 int로 저장)
  @condo_type (서울한화콘도, 강원롯데콘도, 제주신화콘도를 저장
  @sys_date (예약 날짜를 date로 저장)
## Intent가 이어진 순서
  
## 테스트 및 훈련 문구
