## OpenSrc_JsoupCrawling

### 1주차[05/10-05/17]
-----
- Maven Project , webapp type 사용
- 오픈소스 라이브러리 Jsoup 사용 
- enter.jsp 파일 통해, 찾고자 하는 년도 입력 
- 전달받은 서블릿ChartFind 에서 요청 받음 
> 간단한 로직만 필요한 것 같아, 스프링말고 서블릿 사용했다. (프로젝트 해본 경험이 더 잘 나는 듯 하여..)
- getChart 메소드에서 크롤링 진행 
------

### 2주차[05/18-05/24]
-----
- a태그의 text 를 가져오면 제목,가수,앨범 명을 가져올 수 있지만 json 에 각각 저장이 불가해서, a태그들을 순회하면서 값을 가져오는 형태로 수정
- 제목,가수,앨범명 형태로 jsonObject 에 저장하고 jsonArray 생성 
-----

### 4주차[05/31-06/07]
-----
- 서블릿에서 데이터 크롤링 수행 후, response 로 얻어온 jsondata 보내주기
- result.jsp 에서는 json데이터 받아서 jsp el 문법 사용해서 출력 
- 디자인 마무리 
-----

<img src="enter.PNG" width="65%"></img>
-----
<img src="result.PNG" width="65%"></img>
-----
