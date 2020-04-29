# Finance-meter
> 다양한 거시경제 지표, 기업 재무 정보 등과 관련된 시계열 데이터의 수집, 조회가 가능한 web page 제공을 목적으로 한다

# TODO
* Feature1 - 장단기 국채 수익률 곡선
  * springboot 기반의 backend 개발
    * java 기반의 크롤링 기능 개발
      * 우선 파일로 write, test 코드도 추가
    * 스케쥴링 기능 추가
    * amazon mysql DB 연동
    * DB table 추가
    * API 개발
  * frontend
    * API 조회해서 chart 생성
