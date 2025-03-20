# 📌 **ComeBackHome - 실종견 찾기 AI 앱**  
🦮 **반려견 실종 문제 해결을 위한 AI 기반 솔루션**  

## 📂 **레포지토리 구조**
컴백홈 프로젝트는 여러 개의 레포지토리로 나누어져 있으며, 각각의 역할은 다음과 같습니다.

| Repository Name | 역할 |
|---------------|-----------------------------------------------------------|
| **ComeBackHome-backend-main** | Spring Boot 기반 메인 백엔드 서버 |
| **ComeBackHome-backend-ai** | AI 품종 분류 및 유사도 매칭을 담당하는 AI 서버 (Flask) |
| **ComeBackHome-admin-web** | Next.js 기반 관리자 웹 페이지 |
| **ComeBackHome-android** | Android 사용자 앱 |

## 🐶 **프로젝트 소개**
컴백홈은 AI 기술을 활용하여 **실종된 반려견을 찾고 제보할 수 있도록 지원하는 플랫폼**입니다.  
- **AI 기반 품종 자동 분류 및 유사도 검색**  
- **실종견 위치 기반 제보 시스템**  
- **푸시 알림을 통한 신속한 제보 확인**  
- **안심번호를 이용한 보호자-제보자 간 연결**  

## ⚙️ **기술 스택**
| **구성 요소**  | **사용 기술** |
|-------------|----------------|
| **백엔드** | Spring Boot, MySQL, GCP Cloud Run |
| **AI 서버** | Python, Flask, TensorFlow, OpenCV |
| **웹 프론트엔드** | Next.js, TypeScript |
| **모바일 앱** | Android (Kotlin) |
| **클라우드** | GCP (Cloud Storage, Cloud SQL, Compute Engine) |

## 🎯 **주요 기능**
### 1️⃣ 실종 신고 & 제보
- 실종견 정보를 입력하고 AI가 유사한 개체를 매칭하여 추천  
- 실종견 발견 시 사진을 업로드하여 자동 품종 분석  
- 지도 기반 위치 선택 및 자동 저장  

### 2️⃣ AI 매칭 시스템
- 딥러닝 기반 **CNN 모델**로 품종 분류  
- **Siamese Network**를 활용한 유사도 비교  
- 90% 이상 유사도 시 보호자에게 즉시 푸시 알림  

### 3️⃣ 관리자 페이지
- 실종견 신고 및 제보 관리  
- AI 매칭 성능 모니터링 및 수동 보정  

## 🚀 **실행 방법**
### ✅ **백엔드 실행 (Spring Boot)**
```bash
cd ComeBackHome-backend-main
./gradlew bootRun
```

### ✅ **AI 서버 실행 (Flask)**
```bash
cd ComeBackHome-backend-ai
python app.py
```

### ✅ **웹 관리자 페이지 실행 (Next.js)**
```bash
cd ComeBackHome-admin-web
npm install
npm run dev
```

### ✅ **안드로이드 앱 실행**
Android Studio에서 `ComeBackHome-android` 프로젝트를 열고 실행

## 📌 **컨트리뷰션 가이드**
1. 이슈를 생성하여 논의 후 브랜치를 생성합니다. (`feature/기능명`)
2. PR을 생성하고 리뷰를 거친 후 머지합니다.
3. 코딩 스타일과 Git 커밋 메시지 규칙을 준수합니다.

## 🔗 **관련 문서**
- [제안서](링크)
- [API 명세서](링크)
- [AI 모델 설계](링크)
- [ERD 및 DB 설계](링크)
- [완료보고서](링크)
