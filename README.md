# analysis_apt-price


## month

2023년 11월 기준 서울시 아파트 실거래가 데이터(국토교통부자료)를 이용하여 

각 구별 평균 가격과 서울시 전체 평균가격을 확인

국토부 실거래가 공시 사이트
https://rtdown.molit.go.kr/

에서 2023년 11월 기준 자료를 excel로 다운로드 'data'로 저장

12월 28일 기준 계약이 취소된 건은 모두 제외하고 만들었음.
자료가 계약일 기준임으로, 잔금일 이전 계약취소가 발생할 수도 있음.

평균 가격보다 높은 구와 낮은 구를 구별, png 파일로 그래프 저장
data === >> 년월 데이터
해당 년 월에 해당하는 데이터를 기반으로 서울시 아파트 평균가격과 각 구별 평균가격을 확인 가능
전체 평균보다 높은 구와 낮은 구를 구별하여 막대 그래프로 확인 가능

==========================================

## annually_mean

+ 추가 작업

2006년부터 2023년까지(국토교통부 실거래가 자료는 2006년부터 제공되고 있음)

실거래가 데이터를 기반으로 서울시의 아파트 가격 평균을 시계열 그래프로 확인

Prophet 적용하여 이후 아파트가격을 예측해보았으나, 정확도는 매우 떨어짐으로 재미로만 봐주세요.

2006년부터 지금까지 대체적으로 아파트가격이 우상향 했기 때문에 model이 이후에도 우상향 하는 그래프를 그린 것으로 보임
