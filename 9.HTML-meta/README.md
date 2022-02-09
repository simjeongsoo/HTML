## HTML meta
* Meta tag
* HTML 문서에 대한 메타데이터를 정의
* 메타데이터란 데이터에 대한 데이터, 즉 ‘정보’를 의미
* meta 태그는 항상 head 태그의 안에 들어가며, 일반적으로 문자 세트, 페이지 설명, 키워드, 문서의 작성자 및 뷰포트 설정을 지정하는데 사용 
* meta 태그 사용하는 이유 -> 웹페이지에 대한 정보 제공 -> 검색엔진이 페이지를 검색할 때 참고할 수 있고, 검색 결과에도 반영 할 수 있음  
 
- meta tag  
charset : 문자 세트  
http-equiv : 콘텐츠 속성 정보에 대한 http 헤더  
name : 문서 정보  
content : 메타데이터 내용   

- charset  
문자 인코딩에 대한 요약 정보를 기입하는 속성 / utf-8  
`<meta charset=“utf-8”>`  

- http-equiv  
데이터를 주고받는데 필요한 정보 지정  
`<!-— IE 브라우저의 최신 버전의 엔진을 사용하라는뜻 —->`  
`<meta http-equiv=“x-ua-compatible” content=“IE=edge”>` 
<br/>
`<!—- 10초마다 페이지 새고로침하라는뜻 -—>`  
`<meta http-equiv=“refresh” content=“10”>`  

- name  
Name 속성을 이름으로, content 속성을 값으로 하여 문서 정보를 이름 + 값 쌍의 형태로 제공할 때 사용할 수 있음  
`<!-—문서 제작자—->`  
`<meta name=“author” content=“제작자”>`  
<br/>
`<!-—페이지에 대한 요약, 브라우저 즐겨찾기 페이지의 기본 설명 값—->`  
`<meta name=“description” content=“페이지에 대한 짧고 명확한 요악”>`  
<br/>
`<!-—페이지의 콘텐츠와 관련된, 쉼표로 구분한 키워드 목록 —->`  
`<meta name=“keywords” content=“1,2,3,4,5,등등”>`  
