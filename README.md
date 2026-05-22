# MllBs_2Service- 목표 
공정거래위원회_통신판매사업자 등록현황을 활용한 통신판매사업자 폐업 (직권말소)관리

## 업무 절차
- 지역별 통신판매사업자 정보 확보(새올다운로드,open api)
- 국세청 상태조회(폐업,오류사업자번호) 확인
- 매칭 (통신판매사업자 중 국세청에 폐업신고된 자료)
- 공시송달 대상 자료 생성()
- 개인정보 마스킹(대표자명,소재지) apply

## 공시송달(pdf 읽기전용)
- 관리번호,법인또는상호,대표자명,우편번호,주소지
- 관리번호,사업소명,대표자명,소재지주소,사업자번호,사업자폐업일자,처분의 원인이 되는 사실,처분하고자하는 내용
- https://www.ui4u.go.kr/portal/saeol/gosiView.do?notAncmtMgtNo=65922&mId= 송산3동 15
- https://www.ui4u.go.kr/portal/saeol/gosiView.do?notAncmtMgtNo=66171&mId= 흥선동 104
- 
# Open api
## 활용신청
- https://www.data.go.kr/data/15126311/openapi.do 공정거래위원회_통신판매사업자 등록현황 제공 서비스 2024-01-11
- https://www.data.go.kr/data/15081808/openapi.do 국세청_사업자등록정보 진위확인 및 상태조회 서비스
## 국세청 서비스
- https://hometax.go.kr/websquare/websquare.html?w2xPath=/ui/pp/index_pp.xml&tmIdx=43&tm2lIdx=4306000000&tm3lIdx=4306080000 사업자등록상태조회
## filedata
- https://www.data.go.kr/data/15124692/fileData.do 경기도 파주시
- https://www.ftc.go.kr/www/selectBizCommOpenList.do?key=255  공정거래위원회

# 참고
- 파주시 동두천시 양주시 남양주시
- 등록면허세 통신판매업 담당자 # 56145

- https://pylife.tistory.com/entry/PythonPandas-ParserError-Error-tokenizing-data
- https://stackoverflow.com/questions/18039057/pandas-parser-cparsererror-error-tokenizing-data
- 데이터 중간에 첫 행과 다른 길이를 가진 데이터가 있는 경우 발생

## 지방행정인허가 정보 서비스 중단
- http://www.localdata.go.kr 2026.04.16. 지방행정인허가 정보
- 파주시 동두천시 양주시 남양주시
