<a href = https://dacon.io/competitions/official/235914/overview/description>
# KRX 금융 빅데이터 활용 아이디어 경진대회

## 부동산과 주식의 만남, 부동산 뉴스 심리지수와 주식정보를 결합한 상장리츠 등락예측 모델 개발

### 0. 모델 활용 예시 - Dashboard
![리츠 이미지 5](https://user-images.githubusercontent.com/93076425/181441057-32208f8d-4253-496f-804e-afed34fbf91a.png)
### 1.아이디어 개요
- 상장리츠 시장에 주식특성과 부동산 특성을 모두 반영한 정보 서비스가 없다는 점에서 착안하여, 해당 문제를 해결하고자 이번 프로젝트를 진행하게 되었습니다. 

### 2.아이디어 제안 배경 및 목적
- 상장리츠의 투자 수요가 증가하고 있고, 다양한 파생상품의 등장이 예고됨에 따라 상장리츠의 변동성 증가가 예상됨.
- 그러나 기존 리츠정보시스템은 부동산 중심의 정보서비스이기에 상장리츠를 기초자산으로 하는 투자상품의 변동성과 움직임을 모두 설명하는데에는 한계가 존재함.
- 따라서, 상장리츠의 부동산과 주식특성을 모두 반영한 정보시스템을 개발하여 향후 상장리츠 기반 투자상품의 확대 시 시장 참여자들이 의사결정에 참고할 수 있도록 하고자 함.

### 3.활용 데이터
- 상장리츠 일자별 거래 데이터 : KRX에서 유통된 상장리츠 18개 종목의 일단위 거래 데이터(종가,고가,저가,거래량)
- 부동산 경기 데이터 : 부동산 경기를 반영하는 경제 지표(주택매매가격지수, 부동산 소비심리지수, 종합매매 가격지수, 주택매매전체건수)
- 부동산 뉴스 데이터 : 물류,유통,리테일,오피스 4개 부동산 섹터별 네이버 뉴스 본문을 크롤링하여 일단위로 정리
- 코스피 지수 데이터 : 전체 주식 시장 움직임을 설명하는 일단위 코스피 지수
- 거시 경제 데이터 : 부동산과 주식시장에 영향을 미치는 거시 경제지표(시장 금리국고채10년,소비자물가지수,경기종합지수)
* 데이터 수집 기간 : 2019~2021(3개년)
