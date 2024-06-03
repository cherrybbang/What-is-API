# What-is-API
## API란?
API : 소프트웨어 간 상호작용을 가능하게 하는 인터페이스.   
- 특정 소프트웨어의 기능을 호출하고 사용할 수 있게 해주는 규칙과 프로토콜을 일컫는다.
- 데이터 교환
-  기능 호출

다양한 API가 있다. ex) 웹 API, 라이브러리 API, 운영체제 API 등...

## REST API란?
REST API : API 종류 중 하나. API의 한 구현방식. (Representational State Transfer API)   
- URI를 통해 리소스(자원)를 명시하고 HTTP Method를 통해 해당 리소스에 대한 CRUD를 적용하는 것을 의미.
  > 리소스를 HTTP Method 방식으로 리소스를 처리하는 아키텍쳐.
- REST는 Client와 Server 사이의 통신 방식 중 하나.
- HTTP 프로토콜 사용
- 웹서비스, 모바일 앱 백엔드, 클라우드 서비스 등에 사용된다.

## 추가사항
- 자원의 표현 : DB의 학생정보가 자원일 때, students를 자원의 표현으로 정한다.
- 상태전달 : 데이터가 요청되는 시점에서 자원의 상태를 전달한다. (JSON or XML를 통해 주고 받는 것이 일반적.)
- HTTP Method : GET/POST/PUT/DELETE 과 같은 메서드 제공.

##### 따라서, API는 소프트웨어 간 상호작용을 가능하게 하는 모든 종류의 인터페이스를 의미하는 포괄적인 개념이고, REST API는 API의 구현방식 중 하나인 것이다.

##### URI는 네트워크 상 리소스를 가리키는 일종의 고유식별자(ID)이다. URL/URN은 URI에 포함되는 개념이며, URL은 리소스의 위치, URN은 리소스의 이름을 의미한다.
