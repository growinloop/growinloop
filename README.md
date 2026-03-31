# 👋 Hi, I'm Soyoung Kim

growinloop 이름처럼, 반복되는 과정 안에서 성장하는 개발자입니다.  
**Data Engineer**를 목표로 하고 있습니다.  
AI 서비스 개발 경험이 있으며, 데이터 파이프라인 설계에 관심이 많습니다.

---

## 🛠 Tech Stack

**SignTalk — 실사용 기술**
`Python` `FastAPI` `Uvicorn` `KoBART` `FastText` `AWS` `HTML` `CSS` `JavaScript`

**SignTalk v2 — 개선 작업 적용 예정**
`PostgreSQL` `Docker` `Nginx`

---

## 🚀 Projects

### SignTalk — 농인/비농인 실시간 번역 채팅 서비스
> Text to Sign 모델 파트 담당

- 텍스트 전처리 → KoBART gloss sequence 생성 → FastText/pgvector DB 매칭 → 영상 URL 재생
- FastText 지연 로드 구조 문제 파악 → 서버 기동 시 사전 로드로 수정 → timeout 해결 (P95 latency 약 62ms)
- **v2 진행 중:** 학습/서비스 데이터 표현 체계 불일치 근본 원인 파악 → 학습 데이터 재설계, 추론 로그 적재, 평가 데이터셋 파이프라인 구축
- [Repository] — 현재 private 레포, v2 완성 후 공개 예정

---

## 📚 Currently

- SignTalk v2 고도화 진행 중 (DB 스키마 재설계, Docker 환경 구성)
- 취업 서류 Git 기반 버전 관리 운영 중 (이력서·자소서·포트폴리오·면접 준비 통합 관리) — 현재 private, PPT 완성 후 공개 예정

---

## 📫 Contact

- Email: growinloop@gmail.com
