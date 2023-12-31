> # Java Console Project - SSangYong Bank
자바 콘솔을 활용한 금융 상품 추천 프로그램 
<br/>

> ## 🖥 프로젝트 소개
적금, 대출, 카드 상품과 상세정보를 조회하고, 자신에게 맞는 상품을 추천 받을 수 있는 프로그램.

소비 습관, 금융 상황 등 고객 맞춤형 서비스를 제공하여 고객이 더욱 편리하게 자신에게 맞는 상품을 추천받을 수 있도록 하는것이 목표.  
<br/>


> ## 📅 개발기간
* 23.06.19 ~ 23.07.12  
<br/>
  
> ## ⚙ 개발 환경
* `Java 11`
* `JDK 11.0.1`
- **IDE** : Eclipse(2021-03 R)
<br/>
  
### ✔️Back-end
<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white">

### 📌 주요 기능  
<br/>

##  공통기능

> ### 메인 화면
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/f664100c-d7fb-4a7d-b31e-336ff1192336"/>
  
### 📋 구현 기능  
* 메인 화면으로 관리자, 고객 중 원하는 계정으로 로그인 할 수 있는 페이지입니다.

<br/>

## 관리자
#### 💡 관리자는 카드, 상품, 대출 중 원하는 상품을 선택 후 해당 상품의 목록 조회, 상세보기, 추가, 삭제가 가능합니다. 
#### *모든 상품의 추가, 삭제 방법은 동일합니다.
<br/>

> ### 대출 상품 관리 페이지
#### - 목록
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/a50edd29-4be0-46cb-a7f8-842e8e04c2a2"/>

#### - 추가
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/5e97a5c5-8145-4df0-9aa6-e70ebd625345"/>

#### - 삭제
<img width="350px" src="https://github.com/jinseobb/Banking-project/assets/131458472/125c639d-816b-4bf8-b70c-41a6cd203439"/>

  
### 📋 구현 기능  
* 현재 서비스 중인 대출 상품의 목록을 조회 할 수 있는 페이지입니다.
* 원하는 대출 상품을 추가 할 수 있습니다.
* 원하는 대출 상품을 삭제 할 수 있습니다.

<br/>

> ### 적금 상품 관리 페이지

#### - 목록
<img width="350px" src="https://github.com/jinseobb/Banking-project/assets/131458472/8a20cbb3-0a6f-41d6-90b4-7294f1da81c6"/>
<br/>

#### - 상세보기
<img width="550px"  src="https://github.com/jinseobb/Banking-project/assets/131458472/10c519c0-7727-4feb-afd1-12ecb8d2fd9c"/>
  
### 📋 구현 기능  
* 현재 서비스 중인 적금 상품의 목록을 조회 할 수 있는 페이지입니다.
* 원하는 상품의 번호를 입력하면 해당 상품의 상세 정보를 확인 할 수 있습니다. 

<br/>

> ### 카드 상품 관리 페이지

#### - 카드 종류 선택
<img width="250px" src="https://github.com/jinseobb/Banking-project/assets/131458472/0be7e215-223e-405e-86de-d6e0671c32a0"/>  
<br/>

#### - 목록
<img width="350px" src="https://github.com/jinseobb/Banking-project/assets/131458472/37d064e7-ab61-4563-bd4d-28cd00c7dd0b"/>  
<br/>

#### - 상세 보기
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/ea8c9472-7e06-4fa6-99b8-65dfbfc5618c"/>
   
### 📋 구현 기능  
* 현재 서비스 중인 카드상품의 목록을 조회 할 수 있는 페이지 입니다.(신용카드, 체크카드 별로 조회 가능)
* 원하는 상품의 번호를 입력하면 해당 상품의 상세 정보를 확인 할 수 있습니다.
  

<br/>

## 고객
#### 💡 고객 카드, 상품, 대출 중 원하는 상품을 선택 후 해당 상품 목록 조회 및 추천이 가능하고, 가입된 상품 조회가 가능합니다. 
#### *모든 상품의 조회 및 추천 방법은 동일합니다.
<br/>

> ### 가입된 상품 조회 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/6e4aa67c-8ee6-46c6-bc76-ab7aa3ae0c57"/>
  
### 📋 구현 기능  
* 고객 계정으로 로그인 하면, 로그인 한 고객 본인이 가입한 상품의 목록을 조회 할 수 있습니다.

<br/>

> ### 카드 

#### - 카드 추천 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/840d5920-0d66-4e79-a31e-f84bb502f700"/>
  
### 📋 구현 기능  
* 고객이 본인의 소비 패턴에 맞는 새로운 카드(신용카드, 체크카드) 를 추천 받을 수 있는 페이지 입니다.
<br/>

> ### 대출

#### - 대출 추천 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/d928683f-1ab7-49bc-96ce-c18b298cdbf2"/>
<br/>

#### - 신용 대출 추천 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/c8146e90-ac1f-4e1f-925c-f92246eaf304"/>
<br/>

#### - 대출 계산기 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/be5df517-a270-4e89-9822-17c7e052c884"/>
<br/> 
 
### 📋 구현 기능  
* 고객이 신용대출, 자동차 대출, 전 월세 반환보증 대출 중 가입하고 싶은 종류의 대출을 선택 후 추천 받을 수 있습니다.
* 고객이 대출 계산기를 활용하여 본인이 받을 대출에 대한 사전 계산을 할 수 있습니다.


<br/>

> ### 적금

#### - 적금 추천 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/fd640a69-2dfd-4be8-914e-2f90767c8a3b"/>  
<br/>

#### - 적금 계산기 페이지 (매일 일정 금액을 저축할 때)
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/38d1537b-3047-4102-b3e5-6e7fb51f8a07"/>  
<br/>

#### - 적금 계산기 페이지 (목표 금액을 만들 때)
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/de4c623b-f16c-4654-84d8-32e6afe6bc5b"/>  
<br/>

### 📋 구현 기능  
* 고객이 현재 이벤트 진행중인 적금 상품을 확인 할 수 있습니다.
* 고객이 적금 계산기를 활용하여 본인이 받을 적금에 대한 사전 계산을 원하는 목표 별로 계산 할 수 있습니다.



