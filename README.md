# CoffeeOrder_Project
## 🔎 배경 개발 및 요구사항

- 카페 Grids&Circles 의 주문 관리 시스템 구축
- 고객들이 Coffe Bean Package를 온라인 웹사이트로 주문
- 매일 전날 오후 2시부터 오늘 오후 2까지의 주문을 모아서 처리
- 별도로 회원관리를 하지 않는다. Email정보만 받아 고객을 구분
- 하나의 Email로 하루에 여러번 주문을 받더라도 하나로 합쳐서 다음날 배송
- 상품이 존재하며, 추가적으로 상품을 추가 할 수 있다

## ⚙ 프로젝트 환경

- 언어 : Java 11, javascript
- 빌드 툴 : Maven
- 프레임워크 : Spring boot, react
- DB : Docker(Mysql8)
- 테스트 프레임워크 : Junit5
- IDE : Intellij

## 🎢 시스템 구성도
![image](https://user-images.githubusercontent.com/46310555/160363792-d87f42fb-d078-4974-a1fa-5c3caecf9686.png)


## 📁 데이터베이스 구조

products

- products는 상품에 대한 정보를 저장하는 테이블

orders

- 주문에 대한 정보를 담는 테이블

order_items

- 주문한 상품을 저장하는 테이블
- ![image](https://user-images.githubusercontent.com/46310555/160363861-68f9a3b3-ece1-45f5-ae6d-418551a2f818.png)
