# 인공지능을 활용한 챗봇 구축 기획부터 설계, 구현 A to Z - 5주차 과제
## 목차
1. [챗봇 서비스에 대한 사전조사](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/tree/main/week5#챗봇-서비스에-대한-사전조사)
2. [챗봇 서비스 예상 시나리오](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/tree/main/week5#챗봇-서비스-예상-시나리오)
3. [시나리오를 기반으로 한 Dialogflow 작성](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/tree/main/week5#시나리오를-기반으로-한-Dialogflow-작성)
4. [고객에게 예약내역을 확인하는 remind기능 추가](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/tree/main/week5#고객에게-예약내역을-확인하는-remind기능-추가)
  - [변경한 부분]
  - [추가한 부분]
  - [결과]
### 챗봇 서비스에 대한 사전조사
![image](https://user-images.githubusercontent.com/86049096/196031314-bf19e50b-cc7f-44f4-9bec-9fb12980e636.png)   
[1주차 수행내용](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/blob/main/week1/report.md#%EC%B1%97%EB%B4%87-%EA%B8%B0%ED%9A%8D%EC%84%9C)
### 챗봇 서비스 예상 시나리오
![image](https://user-images.githubusercontent.com/86049096/196031333-c955d128-25a5-48c6-a870-5924c8bdb667.png)   
[2주차 수행내용](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/blob/main/week2/report.md#%EC%BD%98%EB%8F%84-%EC%8B%A0%EC%B2%AD-%EC%98%88%EC%95%BD-%EC%84%9C%EB%B9%84%EC%8A%A4%EC%9D%98-%EC%8B%9C%EB%82%98%EB%A6%AC%EC%98%A4-%EC%9E%91%EC%84%B1)
### 시나리오를 기반으로 한 Dialogflow 작성
![image](https://user-images.githubusercontent.com/86049096/196031352-486a15ec-eb0b-4f25-8af4-41d9dbb54574.png)   
[3주차 수행내용](https://github.com/Chun-Jihun/Comento_From_planning_to_chatbot/blob/main/week3/report.md#google-dialogflow%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%98%EC%97%AC-%EC%8B%9C%EB%82%98%EB%A6%AC%EC%98%A4-%EA%B5%AC%ED%98%84%ED%95%98%EA%B8%B0)
### 고객에게 예약내역을 확인하는 remind기능 추가
- 변경한 부분
1. 처음 기획과는 다르게 condo_checkout intent를 제거하고 바로 condo_option으로 이어지도록 변경   
![image](https://user-images.githubusercontent.com/86049096/196025436-33b0ddbd-664c-416f-9164-131bd489ee5c.png)   
이유 : checkout에서 입력을 받으면 checkin의 데이터가 날라가기 때문에 해결하지 못하고 checkout을 삭제하는 방향으로 잡음   
![image](https://user-images.githubusercontent.com/86049096/196026083-da04487d-1b7f-4a74-8a20-04664db14bf7.png)   
2. option을 받는 entities의 구성을 다음 사진과 같이 변경   
![image](https://user-images.githubusercontent.com/86049096/196026464-f8b9105a-e1c3-45d0-93c8-740bc0ae293c.png)   
이유 : remind부분을 원활하게 출력하기 위함   
- 추가한 부분
1. number of people intent밑에 흡연실 여부를 묻는 smoking intent와 이어지는 yes, no intent 추가   
![image](https://user-images.githubusercontent.com/86049096/196026250-29470bd8-61a6-4b94-8de4-ab3a99a2d4c8.png)   
2. smoking intent의 구성   
![image](https://user-images.githubusercontent.com/86049096/196026276-6e7507ba-6bf5-4a6d-afb3-2c3e4148d8f4.png)   
- 결과   
![finalcheck](https://user-images.githubusercontent.com/86049096/196026429-f5c83337-c768-4041-aa86-03e6b3efe86c.jpg)
