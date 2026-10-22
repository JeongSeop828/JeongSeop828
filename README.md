# 👋 안녕하세요! 클라이언트 성능 최적화와 매끄러운 UX를 고민하는 개발자 김정섭입니다.

> 💡 **"Android Native(Kotlin)·Web(React) 프론트엔드 연동부터 C#/Unity 런타임 자원 최적화까지, 사용자의 접점에서 서비스의 완성도와 시스템 안정성을 극대화합니다."**

---

## 👤 Profile & Contact
- **Email**: `wjdtjqrla123@naver.com`
- **GitHub**: [https://github.com/JeongSeop828](https://github.com/JeongSeop828)
- **Education**: 가천대학교 졸업 (2026.08)
- **Certifications**: 정보처리기사, DAsP, ADsP, SQLD | TOEIC 715점

---

## 🔗 Interactive Portfolios
- 🎮 **Game Client Developer Portfolio**: [게임 클라이언트 포트폴리오 (C# / Unity / Optimization)](https://jeongseop-full.notion.site/Game-Client-Developer-C-Unity-4015b7601a378095a996de970a7edd69)
- 📱 **SW Engineer Portfolio**: [SW 엔지니어 포트폴리오 (Kotlin / React / API Integration)](https://jeongseop-full.notion.site/SW-Engineer-3eb5b7601a378024a65bf8660965208d)

---

## 🛠 Tech Stack

| Category | Technologies | Focus & Usage |
| :--- | :--- | :--- |
| **Mobile** | `Kotlin`, `Android SDK`, `Coroutine`, `Retrofit2` | Android Native UI/UX 구현, Coroutine 기반 비동기 처리 및 네트워크 응답성 최적화 |
| **Web Frontend** | `React`, `JavaScript (ES6+)`, `Axios` | 컴포넌트 모듈화 설계, 관리자 대시보드 구축 및 CRUD 구현 |
| **Game & Optimization** | `C#`, `Unity Engine`, `Queue`, `Object Pooling` | 대량 동적 할당 자원 제어, 가비지 컬렉션(GC) 오버헤드 차단 및 런타임 최적화 |
| **Network & Backend** | `RESTful API`, `WebSocket`, `Java`, `Spring Boot` | 클라이언트-서버 간 HTTP 통신 인터페이스 설계 및 예외 처리 메커니즘 구축 |
| **Tools & VCS** | `Git`, `GitHub` | 형상 관리 및 버전 제어 |

---

## 🚀 Key Projects

### 📱 1. 🐶🐱 [멍냥케어] AI 기반 반려동물 피부질환 관리 서비스
- **Period / Type**: 2025.03 ~ 2025.06 (팀 프로젝트 / 교내 시연 및 내부 배포)
- **Role**: 개발 팀장 (PM) / Android App (Kotlin) / Admin Web (React) / Client-Server 연동
- **Key Contributions**:
  - **Android App (Kotlin)**: Coroutine 비동기 처리를 도입하여 고용량 이미지 전송 중 UI 스레드 멈춤 방지, 카메라/갤러리 API 및 Kakao Map API 연동
  - **Admin Web (React)**: 컴포넌트 단위 모듈화 설계를 적용한 대시보드 구축 및 데이터 CRUD 구현
  - **Client-Server Integration**: RESTful API 규격 설계 및 네트워크 예외 처리 메커니즘 정립
  - **Troubleshooting**: 시연 1주 전 로컬-서버 간 Python/TensorFlow 버전 차이로 인한 구동 중단 시, 환경 사양 비교 가설 수립 ➔ 개발 환경 다운그레이드 및 파이프라인 코드 리팩토링으로 무사 완공
- **Repository**: [graduation-project](https://github.com/JeongSeop828/graduation-project)

---

### 🎮 2. 🧟 [UndeadSurvivor] 2D 서바이벌 게임 & 런타임 자원 최적화
- **Period / Type**: 2026.08 ~ 2026.09 (개인 프로젝트 / Windows & Android 빌드)
- **Role**: C# / Unity 단독 개발 및 런타임 최적화
- **Key Contributions**:
  - C# 및 Unity 엔진 기반 게임 플레이 메커니즘 구축 및 메모리 생명주기 제어 아키텍처 설계
  - **Queue 기반 Object Pooling 패턴 구현**: `Instantiate`/`Destroy` 반복 호출에 따른 동적 메모리 할당 오버헤드 및 가비지 컬렉션(GC) 과부하 방지
  - **Dynamic Overflow Control**: 풀 초과 요청 발생 시 동적으로 풀 크기를 확장하는 예외 로직 구축으로 자원 관리 구조적 안정성 확보
- **Repository**: [UndeadSurvivor](https://github.com/JeongSeop828/UndeadSurvivor)
