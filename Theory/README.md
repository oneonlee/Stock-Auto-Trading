# Theory

## 퀀트 투자란?
* Quantitative Analysis의 약자로 정량적 분석이라는 뜻을 가짐
* 재무재표, 주식의 가격 등 숫자 데이터를 분석하여 매매하는 기법을 뜻함
* 퀀트 알고리즘 매매는 2020년 전세계 금융시장 평균 10.3%대로 증가
* 현재 퀀트 시장의 총 규모는 약 1조달러 이상으로 집계
<br>
* 왜 퀀트 투자가 주식 자동매매에 가장 적합한 것일까?
  * 오로지 데이터만을 가지고 매매하기 때문에 주식 자동매매에 적합함!
  * 여러 복잡한 수식과 매매기법을 사람이 따라하기 힘듬!

## 퀀트 투자 기법
### 1. 기술적 분석 : 나는 오직 챠트만을 보고 승부한다!
1. 래리 윌리엄스 - 변동성 돌파전략
  1. 매매기법 
    * 전날 양봉이며 금일 Range를 돌파 할 때 매수, 익일 장 시작 시 매도
      * ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fed74780e-cfec-487c-b375-d7d63f8fd5b2%2FUntitled.png?table=block&id=6c950744-1134-4ea2-9261-abac39583bdd&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=1680&userId=&cache=v2)
  2. 백테스팅 결과
    * 세금, 수수료, 슬리피지 미적용 시
      * ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F21f7bde4-74de-45cd-a0fc-7fa6a773bcc3%2FUntitled.png?table=block&id=d323e0e5-c87e-466d-b499-587797617102&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=2030&userId=&cache=v2)
    * 세금, 수수료, 슬리피지 적용 시
      * ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fc81cde0d-0f00-40b3-8608-a59c38fc50b6%2FUntitled.png?table=block&id=326c8458-0da0-4569-94a3-e4d631864928&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=1900&userId=&cache=v2)
  3. **따라서 국내주식에 적용 불가!**

### 2. 재무재표 분석 : 재무재표를 통해 좋은 종목을 골라내자!
1. 조엘 그린블라트 - 마법공식
  1. 매매기법
    * 고 ROA + 저 PER 종합순위 상위 20개 종목 선정 후 매월 리밸런싱
    * ROA란?
      * Return On Assets의 약자로 '총자산수익률' 이라는 뜻이다. 
      * ROA = 당기순이익/총자산\*100
    * PER이란?
      * Price Earnings Ratio의 약자로 '주가수익비율'이라는 뜻이다.
      * PER = 현재주가/주당순이익(EPS)
      * EPS = 당기순이익/발행주식수
    * 종합순위 산정방식
      * PER 오름차순 순위 및 ROA 내림차순 순위를 산정
      * 각 종목당 위 두 순위의 합을 구한 후 오름차순 순위를 산정
      * ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F3ff0a0e2-9177-47fe-8924-804ce351a3c5%2FUntitled.png?table=block&id=fedf4053-3ea5-4554-9562-43fb11282d38&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=2460&userId=&cache=v2)
      * 종합순위 1위~20위 총 20개 종목 매수
    - 리밸런싱이란?
        - 리밸런싱(Rebalancing)이란 포트폴리오 안에 있는 자산들의 비중을 조절하는 과정
        - 새로운 20개 종목에서 이탈 된 종목 일괄매도
        - 새로운 20개 종목에 편입된 종목 신규매수
        - 나머지 종목 중 많이 오른 자산은 일부 수익을 실현하고, 하락한 자산은 낮은 가격에 추가매수
        - ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F8be3a39a-4f2d-4e47-9034-2cf09b1dec50%2Fe21cd8a8-5b08-414a-b556-56ca26d55c15.jpg?table=block&id=0ac8ae05-d250-44c1-b11b-99ebfe7e52a5&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=1150&userId=&cache=v2)
  2. 백테스팅 결과
    - 10년 간 480% 순수익
    - 연평균 수익률 18%
    - 최대손실폭 -46.43%
    - ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fb04c189f-0529-4e10-88de-b11e4fc8fd7f%2FUntitled.png?table=block&id=d72cc1e2-670c-45b5-b033-d475697b5061&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=3270&userId=&cache=v2)
2. 파마-프렌치 - 3팩터 모델
  1. 3팩터 모델이란?
    - 낮은 시가총액, 높은 순자산, 낮은 시장의 관심
    - **시가총액이 낮다고 모두 위험한 것은 아니라는 것을 증명!**
  2. 매매기법
    - 낮은 시가총액 + 낮은 PBR 종합순위 20개 종목 선정 후 리밸런싱
    - PBR이란?
        - Price to Book Ratio의 약자이며 '주당 순자산 비율'을 뜻함
        - PBR = 현재 주식 가격/주당 순자산(BPS)
    - BPS란?
        - Book-value Per Share의 약자이며 '주당순자산' 을 뜻함
        - BPS = 회사 총 자산/발행 주식 수}
  3. 백테스팅 결과
    - 10년 간 1248% 순수익
    - 연평균 수익률 29.69%
    - 최대손실폭 -32.01%
    - ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fc3126ba9-e089-40e1-be21-baebd3768c64%2FUntitled.png?table=block&id=7a2ce6a6-6791-4073-8978-472e89f89257&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=3080&userId=&cache=v2)

### 3. 모멘텀 : 주식도 관성이 존재한다! 가격이 오르는 종목은 계속 올라가려는 성질이 있다!
1. 토비 모스코비츠 - 시계열 모멘텀
  1. 매매방식
    - 시계열 모멘텀을 통한 20개 종목 선정 및 리밸런싱
    - 시계열 모멘텀 = 한 달 전 주가/일 년 전 주가\*100
    - 시장 하위 20% 종목만 매매
    - ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F24ddf594-8b4e-4cfa-8ae7-a3fe05667501%2FUntitled.png?table=block&id=f7cb4798-1264-43d8-b71d-2362e2fd0ba9&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=2420&userId=&cache=v2)
    
  2. 백테스팅 결과
    - 10년 간 1110% 순수익
    - 연평균 수익률 26.89%
    - 최대손실폭 -35.55%
    - ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F7d871191-4372-4ba5-9d30-a9b0cb5bd1bb%2FUntitled.png?table=block&id=6ff8ee11-8317-45a3-b73e-5d10c13986f4&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=3210&userId=&cache=v2)
  
2. 게리 안토나치 - 듀얼 모멘텀
  1. 매매방식
    - 듀얼 모멘텀(상대 모멘텀 + 절대 모멘텀)을 활용한 매매
    - 상대 모멘텀
        - 시계열 모멘텀과 같음
    - 절대 모멘텀
        - 은행 이자보다 작년 주식 수익률이 낮으면 한 해 매매 중지
    - 주식 ETF, 채권 ETF, 인버스 ETF 종목 위주 리밸런싱
  2. 백테스팅 결과
    - 10년 간 32% 순수익
    - 연평균 수익률 2.76%
    - 최대손실폭 -45.5%
    - ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F8f46a54b-7593-4ad0-bd4e-bb7bf8366993%2FUntitled.png?table=block&id=02ff2806-c7ef-4d80-971b-582386d8b774&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=2690&userId=&cache=v2)
 
### 4. 기타 : 나는 남들과 다르게 간다! 내 방식이 곧 법이다!
1. 조셉 피오트로스키 - F-Score
  1. 매매방식
    - 9가지 재무건전성 지표를 만들어서 각 항목 당 점수(0 or 1)을 매김
    - 재무건전성 점수가 높은 20개 종목 선정 후 리밸런싱
    - ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Ff89c56e8-8864-4fe7-8fc2-55eb5ccbd3b6%2FUntitled.png?table=block&id=80142bfe-09c2-4c51-b4c9-3faf71026825&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=1820&userId=&cache=v2)
  2. 백테스팅 결과
    - 10년 간 400% 순수익
    - 연평균 수익률 16%
    - 최대손실폭 -33.43%
    - ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F07c9e30a-3d47-41f1-960c-e182c69fcf34%2FUntitled.png?table=block&id=4e3fc274-0b7b-417d-960e-3f1fe956dc6a&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=4770&userId=&cache=v2)
    
2. 레이달리오 - 올웨더 포트폴리오
  1. 매매기법
    - 주식, 장기국채, 중기국채, 원자재, 금 자산배분 방식
    - 미국 ETF를 통한 매매 및 매년 리밸런싱
        - 주식 30%+장기국채 40%+중기국채 15%+원자재, 금 7.5%씩
  2. 백테스팅 결과
    - 10년 간 173% 순수익
    - 연평균 수익률 7.13%
    - 최대손실폭 -30.5%
    - ![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Ff642999e-c4a8-4eee-92d3-549f44208b50%2FUntitled.png?table=block&id=5fc25e04-bcc5-4106-9482-c1b8f5a77943&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=2200&userId=&cache=v2)

# 참고
- [스파르타코딩클럽 주식 자동매매 종합반 - 1주차](https://www.notion.so/1-34cc8ba487074a2a957f92e57d79bb61)

    

