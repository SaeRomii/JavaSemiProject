# JAVA Semi Project  

테슬라사조(4조) : 이하림(팀장), 박나현, 선혜연, 이새롬, 장서현
- 진행 기간 : 2021.03.10(수) ~ 2021.03.23(화)
- 대주제 : 자판기(Vending Machine)
- 선정 주제 : 렌터카 자판기 
- 제출 항목: 기획안, 회의록, 결과물, 발표 및 보고자료(후기 포함)
- 클래스 개념~자바 기초 과목을 통틀어 공부한 내용을 모두 적용시킬 수 있도록 구성
- 자판기의 핵심 기능 기획 및 구현  
  
## 프로젝트 목표
자바를 응용하여 프로그램을 구현할 수 있다. 여러 클래스 간의 연결과 객체 활용을 익힌다. API 도큐먼트를 적극 활용하여 수업 시간에 다루지 않은 새로운 기능을 구현한다.   
  
## 프로젝트 개요
뚜또 렌터가는 바쁜 현대사회에서 사용자들에게 즉각적인 실시간 차량 정보를 안내하고 편리한 비대면 대여서비스를 제공하여 시간 절약을 가능케하는 자판기이다. - 프로그램을 실행하면 회원가입을 받는다. 회원가입을 하면 대여 가능한 상태가 된다.

1. 사용자로부터 원하는 대여 날짜/시간과 반납 날짜/시간을 입력 받는다.
2. 사용자가 입력한 기간에 대여가능한 자동차 리스트를 출력한다.
3. 사용자로부터 원하는 자동차를 선택 받고 보험 옵션을 선택 받는다.
4. 사용자의 선택에 따른 대여요금 총합을 계산한다. 현금 결제 시 잔돈 반환이 가능하다.
5. 선택된 자동차는 대여가능한 자동차 리스트에서 제거된다.

## 프로젝트 진행 시 사용 기술
1. 각 클래스들을 하나의 클래스(Start)에 객체화 하여 ‘뒤로 가기’ 구현.
2. ‘Thread sleep(ms)’을 활용하여 3초 지연 효과를 추가.
3. Calendar 클래스를 활용하여 현재 날짜/시간을 호출. 이를 활용하여 달력 출력.
4. Vector 자료구조를 활용하여 보유한 차량 중 대여 가능한 차랑만 리스트로 출력.
5. 객체화와 Vector 자료구조를 활용하여 예약된 차량을 다음 실행 시 가능한 차량 목록에서 제거.
6. Date 클래스와 HashMap 자료구조를 활용하여 로그인 시점에 조건에 맞는 쿠폰을 자동 발급한다. Array 정렬 기능을 활용하여 가장 할인율이 높은 쿠폰을 자동으로 적용시켜 총 금액을 계산한다.
7. Vector 자료구조를 활용하여 예약정보를 저장하고 사용자 요청 시 예약 확인서 출력.  
## 실행 화면
1. 시작화면    
![1](https://user-images.githubusercontent.com/82256410/131675574-407ede00-ed3a-4188-a9a7-4a19fa5b865a.png)
2. 회원가입  
![2](https://user-images.githubusercontent.com/82256410/131675979-b04ebc30-4698-4f61-a6e6-2a7d7edac45f.png)
3. 로그인  
![3](https://user-images.githubusercontent.com/82256410/131675994-c01e39a4-6732-4ec6-b4a6-19842d153bf5.png)
4. 당월, 익월 달력 출력  
![4](https://user-images.githubusercontent.com/82256410/131676004-c7af0718-4b5d-466a-bcac-327577c490ae.png)
5. 대여/반납 날짜 및 시간 입력  
![5](https://user-images.githubusercontent.com/82256410/131676015-dbe8d575-2480-40ca-b8c5-ed117234faf7.png)
6. 대여 가능한 차량 목록 출력 및 차량 선택  
![6](https://user-images.githubusercontent.com/82256410/131676023-38bd1f62-1b3d-4bc0-9a31-a18e5106968f.png)
7. 보험 옵션 선택  
![7](https://user-images.githubusercontent.com/82256410/131676035-746102f9-bd13-4f83-a640-dcf03d5703d3.png)
8. 총 결제 금액 계산 및 예약 내용 확인  
![8](https://user-images.githubusercontent.com/82256410/131676044-39ab0996-01e8-4f09-a999-5220e4f5c6dc.png)
9. 쿠폰 적용 및 결제  
![9](https://user-images.githubusercontent.com/82256410/131676052-b8145d68-5afd-4971-85a3-ef25096f9a10.png)
10. 결제 방식 선택 및 결제  
![10](https://user-images.githubusercontent.com/82256410/131676061-f66d27a9-09ac-4bdd-bdee-26c43582853d.png)
11. 현금 결제 시 거스름 돈 출력  
![11](https://user-images.githubusercontent.com/82256410/131676068-01795bf6-b8af-40db-8a2e-b19b106e46a2.png)
12. 예약확인서 출력  
![12](https://user-images.githubusercontent.com/82256410/131676075-7d781587-7f66-44ba-8eb2-fd768f701955.png)
13. 재로그인 시 예약 내역서 발급  
![13](https://user-images.githubusercontent.com/82256410/131676079-cde6cfea-4749-4e38-b474-83c2d8b293ad.png)
14. 관리자 모드  
![14](https://user-images.githubusercontent.com/82256410/131676087-a03a5a95-d3d9-4973-a87b-e2a8f9e9cfb2.png)
