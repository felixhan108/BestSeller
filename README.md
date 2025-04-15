# 🔊 전화로 주문하기 - 수수료 없는 배달 플랫폼

한국의 배달앱은 편리함 뒤에 수수료라는 불편한 진실을 숨기고 있습니다.  
이로 인해 음식점은 고통받고, 사용자는 그 피해를 전가받고 있습니다.  
그리고 이 수수료 구조는 한국 개발 생태계까지 왜곡시키고 있습니다.

---

## 🎯 우리는 대항하기로 했습니다

> "더 이상 수수료에 휘둘리지 않는, 진짜 배달 서비스를 만들자."

이 프로젝트는 **한국 개발자들의 힘으로**,  
**가장 기본적인 데이터와 기술 협업만으로도 충분히 괜찮은 서비스를 만들 수 있다**는 걸 보여주기 위한 공유 레포지토리입니다.

---

## 💡 프로젝트 목표

- ✅ **전화 기반** 주문 플랫폼  
- ✅ **수수료 없는 구조**  
- ✅ **깔끔한 UI, 빠른 진입**  
- ✅ **가맹점 자율 등록 시스템**  
- ✅ **광고 기반의 운영 수익 모델**

---

## 🤝 함께하고 싶다면?

- 🛠️ 개발에 참여해주세요! (Spring Boot, React Native 등)
- 🗺️ 공공 데이터 정리/가공 도와주세요
- 📢 사장님께 알려주세요: "이건 수수료가 없습니다"

---

## 📌 철학

> "우린 기술로 사회를 바꿀 수 있다.  
> 그게 때론 전화 한 통을 다시 걸게 하는 일이라도."

---

## 🚀 프로젝트 스펙

> **기술 스택 및 아키텍처 설명**
이 프로젝트는 프론트엔드와 백엔드, 디자인 시스템이 유기적으로 연결된 구조를 갖고 있으며, 다음과 같은 기술 스택을 채택했습니다.

- **UI/UX**
    - `Figma` + `Atomic Design`: 디자인 시스템 구조화
    - `Headless UI`: 접근성 고려된 컴포넌트 베이스
    - `Storybook`: 컴포넌트 단위 문서화 및 개발 분리
        
- **Frontend**
    - `Next.js (App Router)`: CSR/SSR/Suspense 통합
    - `Tailwind CSS`: 빠른 UI 스타일링
    - `React Hooks`, `Context API`: 기본 상태 관리
    - 확장 옵션: `Recoil`, `Zustand`
        
- **Backend** _(선택형 모듈 구성)_
    - `Java (Spring Boot)`: 엔터프라이즈 수준 안정성
    - `Python (Flask)`: 경량 마이크로서비스 구축
    - `Node.js (Express + Apollo)`: GraphQL 서버 구축
    - `Next.js API Routes`: 프론트 통합 서버리스 함수
        
- **API Layer**
    - `GraphQL (Apollo Server / Client)`: 명확한 데이터 구조와 쿼리 최적화
        
- **Database**
    - `PostgreSQL`: 관계형 데이터 저장
    - `MongoDB / Firestore`: 실시간 / 문서 기반 데이터 처리
        
- **실시간 기능 & 인증**
    - `Firebase Authentication`
    - `Firestore` + `Cloud Functions` (서버리스 이벤트 대응 포함)

---

## 📬 문의 / 참여

- GitHub Issue 또는 PR로 연락주세요.
- 협업 문의: [thepub03@gmail.com](mailto:thepub03@gmail.com)
