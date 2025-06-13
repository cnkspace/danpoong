### 문제 정의

운동 예약 통합 서비스(ARIS)에 관한 문제는 다음과 같습니다. 
* 서비스 운영자 및 관리자
   1. 공지사항을 서비스 관리자가 필요시 프로그램 차원에서 수동으로 반영해야 한다.
   2. 매월 예약 오픈 일시 변경을 DB와 REST 차원에서 수동으로 반영해야 합니다.
   3. 새로운 운동 시설의 예약서빗 유형에 따라 전체 프로그램을 다시해야 합니다.
   4. 온라인 결제 서비스를 제공하지 않습니다.
   5. 운동 시설의 가격이 프로그램 코드에 존재하여, 특정일 기준으로 가격이 변경 될때 코드가 변경되어야 합니다.
 
* 예약 사용자
  1. 무조건 해당 시설의 여러 코트를 찾아가면서 예약 가능한 시설을 찾아야 한다.
  2. 계좌 이체만으로 예약하고, 담당자에게 연락해 취소 및 환불 받아야 한다.
 


### 예약 서비스 요구사항
* 가용한 운동 시설은 티켓 형식으로 제공되어야 합니다.
* 예약 사용자는 티켓 검색을 손쉽게 검색할 수 있어야 합니다.
* 가용한 티켓 사용 예약 서비스를 제공해야 하고, 결제 수단을 제공해야 합나다.
* 정해진 환불 정책에 따라 티켓을 취소 및 환불해야 합니다.
* 예약 사용자에게 필요한 공지사항을 제공할 수 있어야 합니다.

### 예약 관리 요구사항
* 예약 서비스 운영을 관리할 수 있어야 합니다.
* 티켓 판매 가격을 관리하고 운동 시설에 적용할 수 있어야 합니다.
* 예약 서비스를 확인하고 관리하류수 있어야 합니다.

### 서비스 구독 요구사항
* 가용한 운동시설을 관리할 수 있어야 합니다.
* 예약 서비스별로 구독 유효기간을 관리할 수 있어야 합니다.
  
