# chatMango
## 오늘의 운세를 말해주는 귀여운 강아지 챗봇
## chatGPT API를 활용한 서버리스 서비스

- FrontEnd : HTML (CloudType 배포)
- BackEnd : node.js (AWS Rambda 배포)
- API : chatGPT API and AWS Rambda API

## 통신
유저 질문 -> AWS Rambda API BackEnd 실행 -> 질문 입력 -> chatGPT API 실행 및 응답 -> AWS Rambda API BackEnd GPT API 값 받음 -> FrontEnd 응답 및 화면 표시   
