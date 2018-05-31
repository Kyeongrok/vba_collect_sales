# 매출 집계기
여러 브랜드 미팩토리, 머지, 바디홀릭, 생활도감, 어니시, TFT의 매출을 집계 한다.

## 기능 상세
1. raw_data 가공기능
2. 매출 집계 기능
3. 채널별, 제품별 서브토탈 기능

## 중간에 취소 하려면
esc를 두번 누르면 됩니다.

## 사용방법
1. raw_data를 다운로드 받아서 오클릭에서 받는다.
2. 엑셀의 raw_data시트에 붙여넣기 한다.
3. 컨트롤패널 시트에서 '채널위탁사입', 'TFT만들기'버튼을 누른다.
4. 시트별로 날짜를 추가 한다.
5. 시트별로 '계산하기'버튼을 누른다.

## 채널이 추가되거나 삭제 되었을 때
1. 위탁사입수출구분 시트에서 더하거나 뺀다.
2. 각 시트별로 '지우기'버튼을 누른다.
3. 각 시트별로 '제품명출력'버튼을 누른다.

### 주의사항
1. 매출, 수량 시트의 A1:C3에는 아무것도 있으면 안됩니다.

## raw_data의 열 순서는 다음과 같다
월,	주,	일,	판매처,	품번	브랜드명,	제조사명,	복종명,	성별	, 추가분류	,년도,	시즌,	입력일,	품명,	사입명,	사입가,	TAG가,	판매가,	원가	,할인,	생산(물류),	재고(물류),	재고(기타창고가용),	판매금액(원장),	판매수량(원장)
