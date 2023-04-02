# chatMango
## 오늘의 운세를 말해주는 귀여운 강아지 챗봇
## chatGPT API를 활용한 서버리스 서비스

- FrontEnd : HTML (CloudType 배포)
- BackEnd : node.js (AWS Rambda 배포)
- API : chatGPT API and AWS Rambda API

## 통신
유저 질문 -> AWS Rambda API BackEnd 질문 GET -> chatGPT API에 질문 요청 및 응답
-> AWS Rambda API BackEnd chatGPT 답변 값 GET -> FrontEnd response 답변 화면 표시   
