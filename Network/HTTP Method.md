# HTTP Method
REST를 지키면서 행위를 전달하는 방법

## REST란?
HTTP URI을 통해 자원을 명시하고 HTTP Method을 통해 해당 자원에 대한 CRUD Operation을 적용하는 것

## HTTP Method의 종류
* GET
* POST
* PUT
* PATCH
* DELET

### GET: 리소스 조회
* GET을 통한 요청은 URL 주소 끝에 key-value 쌍으로 paramete를 포함하여 전송을 하는데, 이 부분을 Query String이라 함
* GET의 주요 특징으로는 캐시가 가능하다는 것, 한 번 서버에 GET 요청을 한 적이 있다면 브라우저가 그 결과를 저장함. 이후 동일한 요청은 브라우저에 저장된 값을 가져올 수 있음

### POST: 요청 데이터 처리 (주로 생성) 
* 클라이언트가 Body를 통해 전달한 데이터를 서버가 처리하도록 요청하는 메소드
* 데이터를 생성, 변경하기 하지만 특정 프로세스를 처리하기도 함

### PUT, PATCH
서버의 리소스르 업데이트 한다는 공통점이 있지만 
* PUT: 리소스를 대체, 해당 리소스가 없으면 대체
* PATCH: 리소스를 일부만 수정
