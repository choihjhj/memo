# 📖 < COCOA WEBTOON > 서비스 소개
 이 프로젝트는 **Spring framework**와 **Mybatis**를 활용해 보고자 만든 프로젝트입니다. 회원가입, 로그인, 결제, 충전, 댓글, 좋아요 등의 간단한 **CRUD** 기능을 포함하고 싶었고, 
이 기능들을 포함한 **웹툰 사이트**가 가장 적합한 주제라고 생각하여 웹툰 사이트로 주제를 설정하였습니다.     
 따라서 **COCOA WEBTOON** 사이트를 통해 사용자는 요일별 연재되는 유/무료 웹툰을 코코아 가상 충전/결제를 통해 즐길 수 있고, 이와 더불어 댓글과 좋아요, 보관함 기능을 통해
다양하게 즐길 수 있도록 구현하였습니다.
<!--템플릿 엔진으로 JSP를 선택한 이유는 원래는 spring framework에 Thymeleaf를 dependencies추가 했었는데 spring에서는 타임리프가 잘 호환이 되지 않는 문제가 생겼고
타임리프는 스프링부트와 잘 맞는 템플릿 엔진이라는 것을 깨닫고 JSP로 다시 변경하게 되었습니다.-->
    
<br>
<br>
      
## 💻 개발 환경 및 기술 스택
![image](https://github.com/choihjhj/CocoaWebtoon/assets/148078504/2318e067-a707-4c46-bc05-0324d8f022b8)

 
<!--
- **Java** : JDK 11
- **Editor** : STS(Spring Tool Suite)3
- **Database** : Oracle SQL Developer
- **Framework** : Spring
-->
   <br>
   <br>
       
## 🧩 ERD 
![image](https://github.com/choihjhj/CocoaWebtoon/assets/148078504/793eb738-460f-4eb7-a617-276522c5bb43)
<br>
<br>
<br>

## ✨기능 별 페이지 구성 (메뉴 트리)
![image](https://github.com/choihjhj/CocoaWebtoon/assets/148078504/ceb8f748-5c03-458f-acb1-61989e71a357)

![image](https://github.com/choihjhj/CocoaWebtoon/assets/148078504/21aab200-43d3-453a-a883-d659bbbbe05d)
    
## 👉 개선 사항
- 코코아 충전 기능을 카카오 결제 API를 연동하여 QR 단건 결제로 개선해 볼 것
