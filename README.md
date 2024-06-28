
<h1 align="center"> 📜 조은샘의 포트폴리오📜 </h1>
<h4 align="center"> 조은샘의 데이터 분석 및 학술적 성과를 정리한 자료 모음입니다. </h4>

---
## 1. (2023.07.05 - 2023.08.17) 중앙대학교 인공지능 인문학 청년캠프 해커톤 프로젝트(2인 팀)

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
> - (K-means 클러스터링 및 워드 클라우드) 인문학적인 관심이 순위에 관계없이 전반적으로 높게 나타나면서도, 세부적인 관심도가 미래 자아실현 욕구>자기관리 욕구>관계맺기>지식충족>고전명작 탐구 순으로 나타남을 확인
> - (BERTopic 토픽모델링) 구체적인 관심사의 주제가 '삶의 본질적인 부분, 최근 경제 이슈 및 부수입 창출에 대한 관심, 기술적 관심, 타인의 삶 간접경험 및 이해' 등에 있음을 확인

**[결론 및 시사점]**
> - 같은 데이터 자료임에도 클러스터링을 통한 워드클라우드 결과와 토픽모델링 결과 각각에서 또 다른 해석이 가능하다는 것에서, 데이터를 보다 다양한 시각에서 분석하고 해석해보아야겠다는 깨달음
> - 서점 데이터는 주간 데이터 또한 제공하고 있으며, 그만큼 실시간적인 사람들의 관심사를 분석 가능 -> 이러한 학습주체들의 실시간적 관심사나 트렌드를 따라 이행해간다면 평생교육 활성화에 조금 더 기여할 수 있을 것으로 기대
> - 추후 실제 K-MOOC 등 교육을 공급 가능한 교육매체들이 평생학습자 역량 자극을 위해 제공하는 교육들이 학습 주체들의 실시간적 관심사를 반영하고 있는지, 서점의 실시간적 데이터와 K-MOOC 제공 강의 데이터의 의미 관계성을 탐색해보고 싶음

**[성과]**
> - 장려상 수상
![image](https://github.com/SilverStream-Cho/SilverStream-Cho/assets/130419593/adabed8d-e17e-47fa-b270-9f2a5a896d6d)

---
## 2. (2023년 하반기) Dart-B 학술제 - 의료 주제분야(6인 팀)

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


## 🎵 Spotify status

&nbsp;<div align="center">
  [![Spotify](https://novatorem.vercel.app/api/spotify?background_color=0d1117&border_color=ffffff)](https://open.spotify.com/track/3qonjOrhFCfTnaaMruHzxW?si=f97b90cfc490406a)
</div>
