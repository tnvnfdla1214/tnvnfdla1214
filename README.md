# 임민규 | Frontend Developer & Mobile Specialist

> **신뢰성, 책임감, 확장성**을 핵심 가치로 기술을 만들어가는 개발자  
> 안드로이드 네이티브에서 크로스 플랫폼, 웹 프론트엔드까지 영역을 확장하며 모바일 풀스택 개발자를 지향합니다.

---

## 👨‍💼 About Me

**8만 명 규모의 전자책 서비스에서 비정상 종료율을 6.4%에서 0.2%까지 낮추고**, 안정적으로 유지하며 서비스 신뢰성의 중요성을 체득했습니다.

**49만 명 규모의 MBC OTT 서비스에서는 대규모 기능 개발과 마이그레이션을 주도하며**, 일정과 품질을 동시에 책임지는 경험을 쌓았습니다.

현재 **iMBC AI 전략 사업팀**에서 Web/Mobile 크로스 플랫폼 기술을 바탕으로 신사업 발굴에 참여하고 있으며, 기술 영역에 한정되지 않는 **모바일 개발자**를 목표로 성장하고 있습니다.

---

## 🛠 Tech Stack

### Mobile & Cross-Platform
- **Android** : Kotlin, Jetpack Compose, ExoPlayer, Room, Coroutine, Flow
- **Architecture** : MVVM, Clean Architecture, Repository Pattern, Hilt/Dagger DI
- **React Native** : TypeScript, React Query, Firebase Cloud Messaging

### Web Frontend
- **Framework** : React 18, React Router, Next.js
- **Language** : TypeScript, JavaScript
- **State & Data** : Zustand, TanStack Query, Redux
- **Styling** : Tailwind CSS, CSS-in-JS
- **3D & Graphics** : Three.js, CSS2DRenderer

### Backend & Infrastructure
- **Backend** : Spring Boot, Node.js
- **Database** : PostgreSQL, SQLite, Firebase
- **DevOps** : Docker, AWS
- **AI** : ComfyUI, AI 오픈소스 검증 및 적용

---

## 💼 Work Experience

### iMBC | AI 전략 사업팀 | 프론트엔드 개발 (Web, Mobile)
**2026.01 - 현재**

#### 🎯 주요 성과

**Live 스트리밍 중 광고 교체 방식 개선**
- 광고 전환 시마다 발생하던 깜빡임 및 재버퍼링 문제를 식별
- Player 재생성 구조가 근본 원인임을 분석, 본편/광고 Player 분리 및 재사용 구조로 개선
- **전환 latency 감소** 및 **재생 안정성 향상** → 사용자 시청 흐름 단절 최소화

**WebView Hybrid 구조 전환 및 보안 기반 Web-Native 브릿지 설계**
- URL 검증, Intent 하이재킹 방지 등 보안 이슈 보완
- Web ↔ Native 브릿지 구조 정의 및 팀 전파 → **개발 컨벤션 표준화**
- 기능 확장 시에도 일관된 개발이 가능한 구조 구축
- 보안 안정성을 유지하면서 UI 변경을 웹으로 분리 → **서비스 개선 속도와 운영 유연성 확보**

**사내 GPU 서버에 Docker 기반 AI 실행 환경 구축**
- AI 모델마다 다른 개발환경으로 인한 충돌 사전 방지
- 설정 파일 기반으로 동일한 환경 실행 → **여러 개발자 동시 AI 실험 가능**
- AI 오픈소스(자막 생성, 영상 시점 변환, OutPainting) 미디어 AI 검증 및 적용
- 자막 생성 AI의 신규 국책사업 도입 의사결정에 기여

---

### iMBC | 모바일 부서 안드로이드 팀
**2025.02 - 2026.01**

#### 📊 주요 성과

**CrashReport 기반 비정상 종료율 개선**
- **6.4% → 0.2% 감소** 및 안정화 달성

**오디오북 재생 구조 개선 및 MediaPlayer → ExoPlayer 전환**
- 백그라운드 재생 불안정 및 저사양 기기에서의 재생 불가 문제 식별
- Android 권장 미디어 재생 구조(ExoPlayer, MediaSessionService)로 전환
- 비정상 종료율 **7.53% → 0.01%** 개선, 백그라운드 재생 안정성 및 기기 호환성 확보

**데이터베이스 구조 개선 및 SQLite → Room 전환**
- SQLite 직접 쿼리 방식의 생산성 및 일관성 문제 분석
- Room 기반 구조로 전환 → 컴파일 타임 쿼리 검증, DAO 기반 접근, Coroutine 지원
- DB 접근 방식 표준화 → 개발 생산성 향상 및 비동기 데이터 처리 확장 가능 구조 확보

**책 데이터 동기화 구조 개선**
- 전체 데이터 반복 호출로 인한 과도한 로딩 시간(8초+) 및 트래픽(10MB+) 문제 식별
- Coroutine + Flow 기반으로 구조 전환, Repository 패턴 도입
- 캐시 전략 적용 → API 호출 최소화, 오프라인 환경에서도 일관된 데이터 상태 유지

---

### iPortPolio | 안드로이드 팀
**2023.03 - 2025.01**

#### 📱 프로젝트

**Reading & - 전자책 서비스**
- MAU 8만 명 규모의 안드로이드 앱 운영 및 개발
- CrashReport 기반 비정상 종료율 감소, 재생 구조 개선, DB 마이그레이션, 데이터 동기화 구조 개선 주도

**사내 디자인 시스템 Android 개발**
- 일관된 UI/UX 구현을 위한 디자인 시스템 구축

---

## 🚀 Side Projects

### Virgin Road | 웹 프론트엔드 (모바일 규격의 Web)
**2026.02 - 현재**

**결혼 축하 편지를 타임캡슐로 전달하는 모바일 웹 서비스**

- **기술 스택** : React 18, TypeScript, Tailwind CSS, Zustand, TanStack Query
- **링크** : [virginroad.store](https://virginroad.store)
- **주요 작업**
  - Three.js Ballpit 커스터마이징 (CSS2DRenderer)
  - React SPA 아키텍처 설계
  - UX 마이크로카피 작성 (편지 수 표시, 기능 카드, FAQ)
  - Instagram 커뮤니티 홍보 및 마케팅 콘텐츠 제작
  - AI 이미지 생성을 통한 홍보 포스터 제작

---

### 청정어스 | 크로스 플랫폼 (React Native)
**2025.05 - 2025.08**

**사용자 조건 기반 맞춤 청년 정책 추천 서비스 (iOS/Android)**

- **기술 스택** : React Native, TypeScript, React Query, Firebase Cloud Messaging
- **링크** : [Google Play Store](https://play.google.com/store) / [App Store](https://apps.apple.com)

---

## 📚 Education & Community

**세종대학교 | 소프트웨어학과**  
**2016.02 - 2021.06**

- 4년간 기술 블로그 운영 (안드로이드 및 다양한 개발 주제)
- 누적 조회수 3.5만+

**개발동아리 NEXTERS 16기**  
**2022.06 - 2022.08**

---

## 📖 Blog & Resources

- **기술 블로그** : [androidpangyo.tistory.com](https://androidpangyo.tistory.com)  
  안드로이드 개발, React Native, 크로스 플랫폼 개발, ComfyUI, 개인 지식 관리 등 다양한 주제 포스팅

---

## 📞 Contact

- **Email** : tnvnfdla12@gmail.com
- **Phone** : 010-3174-3063
- **GitHub** : [github.com/tnvnfdla1214](https://github.com/tnvnfdla1214)
- **Blog** : [androidpangyo.tistory.com](https://androidpangyo.tistory.com)

---

## 🎯 Core Values

| 가치 | 설명 |
|------|------|
| **신뢰성** | 6.4%의 비정상 종료율을 0.2%까지 낮춘 경험에서 나오는 품질 관리 |
| **책임감** | 49만 명 규모의 서비스에서 일정과 품질을 동시에 책임지는 리더십 |
| **확장성** | 안드로이드에서 크로스 플랫폼, 웹 프론트엔드까지 영역을 확장하며 성장 |

---

**계속 학습하고, 더 나은 사용자 경험을 만드는 개발자가 되기 위해 노력합니다.**
