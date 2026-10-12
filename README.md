<div align="center">

<a href="./README.md"><img src="https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-3B2F2F?style=for-the-badge"/></a><a href="./README.en.md"><img src="https://img.shields.io/badge/English-E8E8E8?style=for-the-badge&labelColor=E8E8E8"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFE29F,100:FFA99F&height=140&section=header&text=Danbi%20Oh&fontSize=40&fontColor=3B2F2F&fontAlignY=36&desc=Product%20Manager&descSize=14&descAlignY=58" width="100%"/>
<b>가능성을 가설로, 가설을 변화로</b><br/>
<sub>사람과 아이디어를 연결하고, 실험과 검증을 통해 가능성을 실제 제품의 변화로 만드는 PM 오단비입니다.</sub>

<a href="https://www.linkedin.com/in/stellaxdb"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>

</div>

---

## 👤 Profile

- 💼 **Product Manager** — 메이트(MATE) `2026.04 – 현재`
- 💼 **Product Manager** — 카타크로노스(Kata Cronos) `2025.12 – 현재`
- 💼 **Product Manager** — 팀피셜(Teamficial) `2025.10 – 2026.10`
- 🎓 **아주대학교** — 소프트웨어학과, 부전공 디지털미디어 `2023 – 현재`
- 🏫 **충남삼성고등학교(CNSA)** — 7기 · 제8대 학생회장 · 학생홍보단 IRIS · IT&Business 디플로마 `2020 – 2022`

---

## 🚀 Products

### 🧪 메이트 (MATE) — 앱인토스 기반 베타/UX 테스트 플랫폼
<sub>`2026.04 – 현재` · Product Manager</sub>

**출시 전**
- 앱테크 유저와 베타테스트·UT 경험 메이커를 2차에 걸쳐 **유저 리서치**하고, 유저 확보·피드백 품질·리워드 운영이라는 메이커 Pain Point 3가지 **도출**
- UX 테스트 템플릿 8종 기반 테스트 등록, 리워드 결제, 자동 지급, PDF/CSV 통계 보고서까지 핵심 플로우 **설계**
- A/B 선택, 질문 편집, 테스트 미리보기 3개 플로우를 가설 → UT → 개선 순서로 **재설계**
- 비즈니스 모델, TAM/SAM/SOM 시장 규모, RFM 고객 분류, 출시 후 3개월 KPI **수립**

**출시 후** (출시 후 1달 이내)
- 출시 **3주** 만에 3개월 누적 유저 KPI **달성**
- 신규 테스트 등록이 재방문 트리거임을 **발견** — 출시일 코호트 재방문율이 테스트 등록일에 평소 대비 **약 6배** 상승
- 3주간 WAU 중 기존 유저 비중을 **+30.4%p** **끌어올렸고**, 신규 테스트 등록 주간에 WAU 전주 대비 **+60.9%** **회복**
- 테스트 발행 주기, 발견 탭 디자인, 테스트별 퍼널을 검증할 후속 실험 **설계**

### 🤝 팀피셜 (Teamficial) — 소프트스킬 기반 팀빌딩 서비스
<sub>`2025.10 – 2026.10` · Product Manager</sub>

<table>
<tr>
<td align="center"><b>−34%</b><br/><sub>서비스 전체 이탈률</sub></td>
<td align="center"><b>2.2배</b><br/><sub>1인당 참여 시간</sub></td>
<td align="center"><b>12배</b><br/><sub>발표 후 주간 신규 사용자</sub></td>
<td align="center"><b>2.5배</b><br/><sub>랜딩페이지 후 활성 사용자</sub></td>
</tr>
</table>

- 서비스를 0→1로 **출시**하고 GA4 데이터로 **운영**
- 로그인 없이 열람하도록 **개선**해 서비스 전체 이탈률 **−34%**, 팀피셜록 목록 이탈률 **−58%** 달성
- 활성 사용자당 참여 시간 **2.2배**, 재방문 비중 **+22%p**로 탐색 깊이 **확대**
- 튀는 하루(이상치)를 제외하고 다시 **검증**해 방향이 유지됨을 확인하고, 보수적인 수치로 보고
- 오프라인 발표를 2회 **진행**해 주간 신규 사용자 **12배**, **+236%** 견인
- 랜딩페이지를 **적용**해 활성 사용자 **2.5배**, 이벤트 **+63.6%** 증가

---

## 🧠 Data & ML

<details>
<summary><b>💳 신용카드 이상거래 탐지</b> — 머신러닝 수업 프로젝트</summary>
<br/>

- 극심한 불균형 데이터에서 Logistic Regression, Random Forest, XGBoost **비교**
- SMOTE, ImbPipeline, GridSearchCV로 하이퍼파라미터 **튜닝**
- 최종 모델로 XGBoost(`scale_pos_weight=5`) **선정**

</details>

<details>
<summary><b>🚢 타이타닉 생존자 예측</b> — 머신러닝 수업 과제</summary>
<br/>

- Age는 KNN Imputer, Embarked는 1등석 최빈값으로 결측치를 채우고, Cabin은 Deck 단위로 묶어 Unknown 그룹을 따로 **구성**
- Fare 이상치를 IQR 기준으로 **보정**하고, 범주형 인코딩과 수치형 스케일링 **적용**
- GridSearchCV로 Logistic Regression의 penalty, 규제 강도, 반복 횟수를 **튜닝**해 기본 규제 모델 대비 테스트 정확도 **+6.2%p** 향상
- 회귀 계수를 **해석**해 성별이 생존에 가장 큰 영향을 주고, 좌석 등급과 운임이 뒤따름을 확인
- Decision Tree와 성능을 **비교**하고, 나이·운임 기준 결정 경계 **시각화**

</details>

---

## 🧭 Leadership

### 한국대학생IT경영학회 KUSITMS — 33기 학회장
- 64명 규모 학회를 **총괄**하고 19주 커리큘럼 **설계**
- LG전자 등 기업과의 미팅으로 프로젝트 지원금 1,000만원 이상 **확보**
- 3개월간 브랜드 도달 계정 **+627.6%**, 외부 링크 클릭 **+454.1%** **성장**

---

## 🏆 Awards

| | 수상 | 대회 |
|:---:|---|---|
| 🥇 | **수원시장상** | 2026 제4회 아시아청년포럼 |
| 🥇 | **대상** | 2026 아주대학교 창업경진대회 |
| 🥇 | **최우수상** | KUSITMS 33기 기업연계프로젝트 · LG전자 |
| 🏆 | **최우수상** | KUSITMS 밋업데이 · 메이트(MATE) |
| 🏆 | **우수상** | 직행 산학협력 프로젝트 |

## 📜 Certifications

- **데이터분석 준전문가(ADsP)** `2026.01`
- **Google Analytics** `2026.02`

---

## 🛠 Tools

<p>
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
<img src="https://img.shields.io/badge/GA4-E37400?style=for-the-badge&logo=googleanalytics&logoColor=white"/>
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>

<sub>그 외 사용 경험</sub><br/>
<img src="https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=black"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>

## 🌏 Global

- 🇨🇿 교환학생 — 체코공과대학교(CTU, 프라하) `2025.02 – 2025.07`
- 🇺🇸 하계 프로그램 — 스토니브룩 대학교 `2023.07`

## 🌱 Currently Exploring

**AI 에이전트 · AI 기반 프로덕트 · 프로덕트 애널리틱스 · 0→1 프로덕트 개발**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFA99F,100:FFE29F&height=100&section=footer" width="100%"/>
