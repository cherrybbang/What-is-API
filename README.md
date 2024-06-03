# What-is-API
## [기획의도]
- 회사에서 Postman으로 API를 테스트해보며 그 작동방법을 상세히 알고 싶어졌다.

## [내용]
- 네이버 검색 API를 활용하여 API 작동방법을 하나하나 뜯어 보자.
- 최종적으로 Swagger를 통한 API 문서화까지.
  > 네이버 공식문서 정독하기!   
  > https://developers.naver.com/docs/serviceapi/search/blog/blog.md#%EB%B8%94%EB%A1%9C%EA%B7%B8

## [작업 툴]
Postman   
- API를 개발,테스트,공유 및 문서화하는데 사용되는 API 클라이언트이다.
- endpoint URL를 입력하는 테스트에 사용되며 서버로 요청을 보내고 서버에서 응답을 받아 API가 잘 동작하는지 확인 할 수 있다.

## [작동방법]
- 네이버 개발자 센터에서 '에플리케리션 등록' > '애플리케이션 정보' 의 'Client ID' & 'CLient Secret' 필요.
- endpoint
  > URL : https://openapi.naver.com/v1/search/blog.json   
  > HTTP Method : GET   
  > Headers : 'Client ID' & 'CLient Secret' 적어주기   
  > Params :
    1. 'query' : 검색어. url 인코딩하여 넣기.
    2. display : 한번에 표시할 검색 결과. 기본 10개가 디폴트 값.
