# Google Dialogflow를 이용하여 시나리오 구현하기
## 목차
  [1. 시나리오](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/blob/main/week3/report.md#시나리오)   
  [2. Intent](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/blob/main/week3/report.md#Intent)   
  [3. Entities](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/blob/main/week3/report.md#Entities)   
  [4. Intent가 이어진 순서](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/blob/main/week3/report.md#Intent가-이어진-순서)   
  [5. 테스트 및 훈련 문구](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/blob/main/week3/report.md#테스트-및-훈련-문구)
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
  @sys.date (예약 날짜를 date로 저장)
  @sys.number-integer(숙박인원을 int로 저장)
## Intent가 이어진 순서
  ![intent순서](https://user-images.githubusercontent.com/86049096/194510846-7011a8c9-208e-4bb3-b61e-95950c41a060.JPG)

## 테스트 및 훈련 문구
![condoname](https://user-images.githubusercontent.com/86049096/194510871-31b1d08b-e9d2-427f-8c00-74f2740a107e.JPG)
- 출력문구 : 
```
예약을 하고자 하는 콘도를 입력해주세요
```
![condodate](https://user-images.githubusercontent.com/86049096/194510880-25674857-7657-415e-85d8-bbf8e51fdc11.JPG)
- 출력문구 : 
```
체크인하고자 하는 날짜를 입력해주세요.( 예 : 2022-10-05 )
```
![condocheckout](https://user-images.githubusercontent.com/86049096/194510899-2e159179-4ee5-47ab-8438-34ba1fa43440.JPG)
- 출력문구 : 
```
체크아웃하고자 하는 날짜를 골라주세요( 예 : 2022-10-05 )
```
![condooption](https://user-images.githubusercontent.com/86049096/194510907-ea29487c-d9a3-4459-86a5-90bf84942f65.JPG)
- 출력문구 : 
```
예약하고자 하는 옵션을 숫자로 입력해주세요.
0. 오전
1. 야간 
2. 대인 
3. 소인
```
![condonumber](https://user-images.githubusercontent.com/86049096/194510914-0435ec31-73ad-4c0a-ada4-e17152e389d6.JPG)
- 출력문구 : 
```
숙박하고자 하는 인원을 입력해주세요.
```
![condocheck](https://user-images.githubusercontent.com/86049096/194510924-1c5582e9-aacf-45b1-9493-3c71d005b524.JPG)
- 출력문구 : 
```
예약하고자 하는 일정이 다음과 같다면 "예약한다"라고 입력해주세요.
```
