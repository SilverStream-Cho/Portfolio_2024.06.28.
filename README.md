<h1 align="center"> 📜 조은샘의 포트폴리오📜 </h1>
<h4 align="center"> 조은샘의 데이터 분석 및 학술적 성과를 정리한 자료 모음입니다. </h4>

---
## 1. (2023년 7-8월) 중앙대학교 인공지능 인문학 청년캠프 해커톤 프로젝트 / 2인 팀

### 📖텍스트마이닝 기법을 활용한 청소년 및 성인 학습자의 학습욕구 분석 *- 온라인 서점 5개년 데이터(2019~2023)를 활용하여-*

**[프로젝트 목적]**
> 평생학습이 강조되는 추세에 따라 실제 성인학습자들의 학슴 동기를 유발할 수 있는 최근 관심사, 즉 '학습 욕구의 경향성'을 서점 베스트셀러 데이터로 파악하고, 평생교육 공급매체들의 접근점과 관련한 시사점 제시

**[주요 역할]**
> - KONLPY를 활용한 도서명 주요 명사(일반명사, 고유명사) 추출 등 전처리 작업
> - K-means 클러스터링
> - 클러스터별 워드 클라우드 생성 및 그룹 의미화
> - 토픽 모델링(BERTopic) 및 시각화
> - PPT 제작 및 발표

**[주요 결과]**
> - (K-means 클러스터링 및 워드 클라우드) 인문학적인 관심이 순위에 관계없이 전반적으로333333333333 높게 나타나면서도, 세부적인 관심도가 미래 자아실현 욕구>자기관리 욕구>관계맺기>지식충족>고전명작 탐구 순으로 나타남을 확인
> - (BERTopic 토픽모델링) 구체적인 관심사의 주제가 '삶의 본질적인 부분, 최근 경제 이슈 및 부수입 창출에 대한 관심, 기술적 관심, 타인의 삶 간접경험 및 이해' 등에 있음을 확인

**[결론 및 시사점]**
> - 같은 데이터 자료임에도 클러스터링을 통한 워드클라우드 결과와 토픽모델링 결과 각각에서 또 다른 해석이 가능하다는 것에서, 데이터를 보다 다양한 시각에서 분석하고 해석해보아야겠다는 깨달음
> - 서점 데이터는 주간 데이터 또한 제공하고 있으며, 그만큼 실시간적인 사람들의 관심사를 분석 가능 -> 이러한 학습주체들의 실시간적 관심사나 트렌드를 따라 이행해간다면 평생교육 활성화에 조금 더 기여할 수 있을 것으로 기대
> - 추후 실제 K-MOOC 등 교육을 공급 가능한 교육매체들이 평생학습자 역량 자극을 위해 제공하는 교육들이 학습 주체들의 실시간적 관심사를 반영하고 있는지, 서점의 실시간적 데이터와 K-MOOC 제공 강의 데이터의 의미 관계성을 탐색해보고 싶음

**[성과]**
> - 장려상 수상
![image](https://github.com/SilverStream-Cho/SilverStream-Cho/assets/130419593/adabed8d-e17e-47fa-b270-9f2a5a896d6d)

---
## 2. (2023년 하반기) Dart-B 학술제 - 의료 주제분야 / 6인 팀

### 😷 이번주 아토피 위험 지수 예측모델 분석

**[프로젝트 목적]**
> 환경성 질환인 아토피 피부염 관리 및 증상 악화 예방을 위해 증상 악화에 영향을 미치는 것으로 확인된 날씨 관련 환경인자 데이터를 분석 대상인 아토피 환자 수에 대응하여 학습모델에 적용함으로써, 환자에 대한 아토피 증상 악화 위험성이 있는 주간을 예측하는 모델 개발

**[주요 역할]**
> - 팀장으로서 팀 전체 회의(12회) 주관, 협업 및 역할 분배 총괄
> - 활용할 아토피 데이터 추출 및 전처리, 시각화 작업
> - 시각화 및 예측 모델 관련 해석 및 의미 도출 
> - PPT 제작 및 발표

**[기대 효과 및 활용 방안]**
> - (의사결정나무) 각 지역별로 변수 값에 따라 분기점을 기준으로 샘플이 분리되어 환자 수를 예측 가능
> - (Shaply value) 설명 변수들의 값 변화에 따른 환자 수 변화를 직관적으로 파악 가능
> - 지역이 주간 아토피 환자 수를 예측하는 데 생각보다 크게 영향을 주는 것을 확인하였으므로, 지역 입력 후 설명변수의 중요도에 따라 스코어링을 다르게 하여 지수화를 통해 위험도를 예측하고 서비스로 활용 가능
> - 기상청 API와 연동하는 경우, 지역 입력했을 떄 주간 데이터를 받아와 자동으로 위험지수 도출 가능
> - 각 변수별로 위험도를 파악할 수 있도록 향후 변수별 위험도를 제공 가능

**[프로젝트 이후 사고의 변화/성장]**
> - 환경성 질환에 영향을 미칠 수 있는 다른 변수들을 추가한다면 더 좋은 예측모델을 만들 수 있을 것으로 생각됨
> - 한편으로는 다중공선성 문제를 고려하여 모델을 보완해야 할 필요가 있다는 점을 발견함
> - 아토피 환자 수 등 기초 수집 데이터 수량의 제한으로 한계가 있었으나, 추후 더 활발하게 공개된 의료 데이터를 통해 예측 모델을 개발한다면 환자들에게 도움이 될 것임

**[성과]**
> - 최우수상 수상
![image](https://github.com/SilverStream-Cho/Portfolio_2024.06.28./assets/130419593/746d0bd6-2dee-4ebf-a1df-d21e543bbeeb)

---
## 3. (2023년 하반기) 한국프롭테크포럼 부동산 데이터 활용 아이디어 공모전 / 4인 팀

### 😷 서울 청년세대를 위한 주거 시세 시각화 비교 분석 서비스

**[프로젝트 목적]**
> 최근 전세사기 등의 문제가 발생하는 가운데 청년세대들은 집을 구할 때 정보 부족 및 정보 비대칭으로 인한 어려움을 겪고 있음. 이에 따라 실거래가, 거래량 등 생소한 단어가 아니라 청년 세대가 알기 쉬운 정보들을 함께 시각적으로 제공함으로써 더 나은 주거를 선택 가능한 서비스를 제공하고자 

**[주요 역할]**
> - 관련 전문가(공인중개사) 섭외 후 면담 진행하여 팀원들에게 정보 공유: 부동산 구할 때 청년들이 주로 겪는 문제점, 필요하다고 생각하는 서비스 등
> - 기존에 선행되었던 서비스나 현재 관련 데이터 활용 실태 등 조사하여 공유
> - 생활지수 데이터 전처리
> - Tableau 시각화 파트 총괄 
> - PPT 제작

**[기대 효과 및 활용 방안]**
> - 금융기관의 대출을 위해 알아보는 경우, 관심있는 자치구에 대한 동별 정보 함께 비교하여 사전에 파악할 수 있는 지표 제공
> - 서울 자치구별 생활지수를 10점 만점으로 환산하여 관심 있는 지역의 생활 특성을 파악하고, 자신의 생활패턴에 따라 거주하기에 적절한 지역을 선정하는 데 도움받을 수 있음

**[프로젝트 이후 사고의 변화/성장]**
> - 피그마 화면설계를 시도하여 청년 주거 스트레스 완화 및 다양한 선택지를 편리하게 제공할 수 있는 방안을 고민함
> - 이후 연령별 니즈를 확보해 타겟을 확대하는 등 전국의 임차인에게 서비스를 제공할 수 있을 것으로 생각됨

**[성과]**
> - 대상 수상
![image](https://github.com/SilverStream-Cho/Portfolio_2024.06.28./assets/130419593/49718a4a-e5b1-492d-a014-09ca7a781a21)

---
## 4. (2024년 1월 24-25일) 한국데이터산업진흥원 데이터안심구역 분석 캠프 / 5인 팀
학회 활동의 일환으로 총 12시간 동안 데이터 안심구역에 적재되어 있는 미개방 소비데이터를 중심으로 데이터 기반 문제해결, 의사결정 등 미니 프로젝트를 통한 데이터 활용 분석 캠프에 참여

### 💸 위드 코로나 시기 소비유형별 맞춤 서비스 제안

**[프로젝트 목적]**
> 업종별 중분류를 기준으로 고객집단의 소비 현황을 파악하고, 군집 분석 진행 후 각 클러스터별 소비패턴과 고객 유형을 분석하고 데이터 기반 개인화를 통한 맞춤형 서비스를 제안함

**[주요 역할]**
> - 엘보우(elbow) 기법 활용한 K-Means 클러스터링
> - EDA 결과에 따른 의미해석
> - Tableau 시각화 총괄
> - 클러스터별 고객 유형 분석 및 군집별 카드사 서비스 제안

**[기대 효과 및 활용 방안]**
> - 각 클러스터별 고객 유형 분석에 따라 '직장인 전용 단골집 눈도장 스탬프', 'AI를 활용한 여행 플래너 챗봇 도입', '편의점 효자상품 OR 트렌드몰이 상품 관련 전략적 프로모션', '자녀 학생증 발급에 따른 학생 할인 혜택 및 포인트 제도 보급' 등의 카드사 서비스 제안 가능

**[프로젝트 이후 사고의 변화/성장]**
> - 실제 클러스터마다 각각의 특징이 확인되는지 샘플 사례로 추가 검증이 필요
> - 매출금액 이외에도 매출건수를 함께 군집분석에 활용하여 향후 분석하고자 함
> - 이외에도 성별, 연령대, 시간대별, 직업군 등을 분류 문제로도 결과를 도출

**[성과]**
> - 수상 X, 학회 공유 발표회만 진행
![image](https://github.com/SilverStream-Cho/Portfolio_2024.06.28./assets/130419593/ad231652-4ae9-4f87-a207-9a0b00451ad9)

---
## 5. (2024년 1월 24-25일) 한국데이터산업진흥원 데이터안심구역 분석 캠프 / 5인 팀
학회 활동의 일환으로 총 12시간 동안 데이터 안심구역에 적재되어 있는 미개방 소비데이터를 중심으로 데이터 기반 문제해결, 의사결정 등 미니 프로젝트를 통한 데이터 활용 분석 캠프에 참여

### 💸 위드 코로나 시기 소비유형별 맞춤 서비스 제안

**[프로젝트 목적]**
> 업종별 중분류를 기준으로 고객집단의 소비 현황을 파악하고, 군집 분석 진행 후 각 클러스터별 소비패턴과 고객 유형을 분석하고 데이터 기반 개인화를 통한 맞춤형 서비스를 제안함

**[주요 역할]**
> - 엘보우(elbow) 기법 활용한 K-Means 클러스터링
> - EDA 결과에 따른 의미해석
> - Tableau 시각화 총괄
> - 클러스터별 고객 유형 분석 및 군집별 카드사 서비스 제안

**[기대 효과 및 활용 방안]**
> - 각 클러스터별 고객 유형 분석에 따라 '직장인 전용 단골집 눈도장 스탬프', 'AI를 활용한 여행 플래너 챗봇 도입', '편의점 효자상품 OR 트렌드몰이 상품 관련 전략적 프로모션', '자녀 학생증 발급에 따른 학생 할인 혜택 및 포인트 제도 보급' 등의 카드사 서비스 제안 가능

**[프로젝트 이후 사고의 변화/성장]**
> - 실제 클러스터마다 각각의 특징이 확인되는지 샘플 사례로 추가 검증이 필요
> - 매출금액 이외에도 매출건수를 함께 군집분석에 활용하여 향후 분석하고자 함
> - 이외에도 성별, 연령대, 시간대별, 직업군 등을 분류 문제로도 결과를 도출

**[성과]**
> - 수상 X, 학회 공유 발표회만 진행
![image](https://github.com/SilverStream-Cho/Portfolio_2024.06.28./assets/130419593/ad231652-4ae9-4f87-a207-9a0b00451ad9)

## 🎵 Spotify status

&nbsp;<div align="center">
  [![Spotify](https://novatorem.vercel.app/api/spotify?background_color=0d1117&border_color=ffffff)](https://open.spotify.com/track/3qonjOrhFCfTnaaMruHzxW?si=f97b90cfc490406a)
</div>
