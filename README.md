<p>
  <img src="assets/PaEmotion.webp" alt="프로젝트 로고" width="500" />
</p>

### 소비에 감정을 더하고, AI로 돌아보는 소비습관 리마인드 앱 <br><br> 감정 기반 소비 기록 + 지출 예측 + 챌린지로 습관 교정까지!

<br><br>
## 🔍프로젝트 소개
- **PaEmotion**은 감정과 소비 패턴을 통합 분석해 개인 맞춤 AI 코칭으로 현명한 소비 습관 형성을 돕는 감정 인식 가계부 앱입니다.
- 사용자는 소비 내역과 함께 자신의 감정을 기록하고, 학습된 머신러닝 모델이 사용자의 소비 유형을 판단해주며, 과거 소비 데이터를 바탕으로 다음 주 예상 지출을 산출하여 체계적인 재정 관리를 지원합니다.
- 또한, 맞춤형 예산 설정과 친구들과 함께하는 챌린지 기능을 통해 지속 가능한 재정 관리를 실현할 수 있습니다.
- 이 앱은 단순 지출 기록을 넘어, 감정과 소비를 연결해 사용자가 자신의 소비 습관을 직관적으로 이해하고 개선할 수 있도록 지원합니다.

<br><br>
## 📌프로젝트 개요
- **팀 구성:** 프론트엔드 1명 · 백엔드 2명
- **목표:**
    - 즉흥적·감정적 소비 인지 & 개선 유도
    - 소비-감정 관계를 AI로 분석하고 맞춤 피드백 제공
    - 예측 모델로 미래 지출 경향 점검 및 조절

<br><br>
## 👩‍💻팀원 소개
- **김도윤(팀장)** : AI, Back
- **박예린** : Back
- **김시연** : Design, Front

<br><br>
## 🏗️ 개발 아키텍처
<img src="assets/services.png" alt="ERD 이미지" width="800" />

<br><br>
## 🔗ERD
<img src="assets/erd.png" alt="ERD 이미지" width="740" />

<br><br>
## 🛠 기술 스택
### Backend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Asyncio](https://img.shields.io/badge/Asyncio-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Logging](https://img.shields.io/badge/Logging-FFD43B?style=for-the-badge&logo=python&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Frontend
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Provider](https://img.shields.io/badge/Provider-4285F4?style=for-the-badge&logo=flutter&logoColor=white)
![Dio](https://img.shields.io/badge/Dio-FFCA28?style=for-the-badge&logo=flutter&logoColor=black)

### AI & Model
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenAI GPT](https://img.shields.io/badge/OpenAI%20GPT-412991?style=for-the-badge&logo=openai&logoColor=white)

### Tools & Infra
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)

<br><br>
## 🤖 AI & 머신러닝
| 기술 | 역할 |
| --- | --- |
| **OpenAI GPT API** | 소비·감정 기반 리포트 생성 |
| **Random Forest Regression** | 다음 주 지출 예측 |
| **Random Forest Classification** | 소비 성향 분석 |

<br><br>
## 📋 개발 기간 및 작업 관리
**개발 기간**
- 개발 기간 : 2025-06-30 ~ 2025-08-10

**작업 관리**
- GitHub Projects와 Issues를 사용하여 개발 진행 상황 공유
- 주간회의를 진행하며 작업 순서와 방향성에 대한 고민을 나누고 Notion을 통해 전체적인 진행 상황 공유


<br><br>
## 📜 컨벤션 전략
**[ 브랜치 컨벤션 ]**
- Git-flow 전략을 기반으로 main, develop 브랜치와 feature 보조 브랜치 운용
- main, develop, Feat 브랜치로 나누어 개발 진행
- main : 배포 단계에서만 사용
- develop : 개발 단계에서 git-flow의 master 역할
- Feat : 기능 단위로 독립적인 개발 환경을 위하여 사용 후 develo으로 merge
  
**[ PR 컨벤션 ]**
- [Issue 종류] 구현내용 #이슈_번호
- ex) [Feature] 로그인 #1
- Back : Pull Request만 날리고, Approve는 reviewer 담당 / Front : 독립적 합병

**[ 커밋 컨벤션 ]**
- [Issue 종류] 구현내용
- ex) [Feature] 소비내역 생성 API 구현

<br><br>
## 📱 어플 실행 화면
<table>
  <tr>
    <td align="center">
      <b>로그인 화면</b><br/>
      <img src="assets/login.png" alt="Login 화면" width="300"/>
    </td>
    <td align="center">
      <b>홈 화면</b><br/>
      <img src="assets/home.png" alt="Home 화면" width="300"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>주간 리포트 화면</b><br/>
      <img src="assets/weeklyReport.png" alt="Weekly Report 화면" width="300"/>
    </td>
    <td align="center">
      <b>월간 리포트 화면</b><br/>
      <img src="assets/monthlyReport.png" alt="Monthly Report 화면" width="300"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>예산 현황 화면</b><br/>
      <img src="assets/budget.png" alt="Budget 화면" width="300"/>
    </td>
    <td align="center">
      <b>참여 중인 챌린지 화면</b><br/>
      <img src="assets/challenge.png" alt="Challenge 화면" width="300"/>
    </td>
  </tr>
</table>



