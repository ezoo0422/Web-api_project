# api_project
api를 활용한 데이터 적재 웹 서비스

- 웹 개발에 대해서 전혀 모르는 상태로 공부하며 개발한 첫 프로젝트
- 요구사항분석부터 설계, 구현까지 모두 진행
- 프로젝트 기간: 21.04.05 ~ 21.04.30 (1달)

## 프로젝트 후기
- 개발 기초가 잡혀있지 않은 상태로 프로젝트를 진행하여 프로젝트의 완성도는 떨어진다. 하지만 프로젝트를 수행하며 단 기간에 많은 것을 배울 수 있었다. 
- 설계 단계도 완벽하지 않다. 누군가에게 가이드를 받지 않고 오로지 검색으로만 수행하였기에 부족함이 많다.
- 프로젝트를 통하여 API를 통해 데이터를 통신하는 방법을 알게되었다.
- 웹 서버와 DB가 어떻게 연결이 되고 작동하는 지와 데이터의 흐름을 이해할 수 있게 되었다. 
- 아쉽게도 프로젝트 최종 화면은 캡쳐하지 못하였다.. (DB 폭파..)

다음은 프로젝트 관련 분석/설계 내용이다.

### 요구사항 분석
- 사용자는 정해진 5개 API 목록 중 데이터를 선택
- 사용자가 선택한 API를 통한 데이터 호출
- 앞서 호출한 데이터를 DB에 저장

### 프로세스 흐름도
![image](https://user-images.githubusercontent.com/82800203/136960667-f88c4f84-6537-4e08-9b51-f0aa1c38bcbb.png)

### Activity Diagram
![image](https://user-images.githubusercontent.com/82800203/136960856-d2f1d2e0-6850-4aea-9eef-d5d7b33c11e1.png)

### 클래스 설계
![image](https://user-images.githubusercontent.com/82800203/136960932-0baeaa21-7907-434b-8aef-2bbeb462c665.png)

### Sequence Diagram
![image](https://user-images.githubusercontent.com/82800203/136961140-7f2cfae0-88fc-4fa3-98af-54dec8dbb427.png)

### 화면 설계
#### 1
![image](https://user-images.githubusercontent.com/82800203/136961369-7d802a45-0cc6-4f27-a655-63b9c6059224.png)

#### 2
![image](https://user-images.githubusercontent.com/82800203/136961415-ca29a5c5-b367-4012-bfac-669d98ee5e61.png)

#### 3
![image](https://user-images.githubusercontent.com/82800203/136961470-85697ac7-75e6-4f8e-a9f2-f81948e8ea3e.png)

#### 4
![image](https://user-images.githubusercontent.com/82800203/136961530-5776fdc6-6912-4c99-a9a5-c541b15d7cd6.png)

#### 5
![image](https://user-images.githubusercontent.com/82800203/136961571-627d105d-6f64-4f7e-89df-4b77a783030e.png)

### 테이블 설계
![image](https://user-images.githubusercontent.com/82800203/136961711-b5c1f302-9118-4a85-bd49-a116d161a0eb.png)

### 시스템 설계
![image](https://user-images.githubusercontent.com/82800203/136961667-c41e38c4-1fde-417f-b6e0-f4d4687bcf49.png)

