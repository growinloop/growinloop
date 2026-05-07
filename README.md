# 👋 Hi, I'm Soyoung Kim

growinloop 이름처럼, 반복되는 과정 안에서 성장하는 개발자입니다.  
데이터 수집·ETL·모델링·서빙·품질 관찰까지 전 과정을 직접 설계하고 구현하는 것을 지향하며,  
Data Engineering / Data Science → Data Analytics 방향으로 성장하고 있습니다.

---

## 🛠 Tech Stack

`Python` `FastAPI` `Uvicorn` `KoBART` `FastText` `PostgreSQL` `Docker` `Nginx` `AWS` `HTML` `CSS` `JavaScript`

---

## 🚀 Projects

### signtalk-v2 — Text2Sign 파이프라인 독립 구현
> SignTalk(v1)에서 확인한 구조적 한계를 출발점으로, ETL 파이프라인·DB 설계·모델 재학습·서빙 환경을 처음부터 직접 구현한 개인 프로젝트

- XML 수어사전 수집 → title 쉼표 분리 기반 동의어 테이블(corpus_alias) 설계 → PostgreSQL ETL 적재 (3,620건, 검증 통과율 100%)
- KoBART 재학습 (v2-1 → v2-2): 토큰 길이 분포 EDA 기반 하이퍼파라미터 튜닝 → BLEU 3.66 → 11.77
- 평가 데이터셋 200건 구축, 추론 로그 PostgreSQL 적재, 실패 케이스 환류 구조 설계
- Docker + docker-compose 기반 로컬 재현 가능한 실행 환경 구성 (nginx / frontend / text2sign / db)

[→ Repository](https://github.com/growinloop/signtalk-v2)

---

### SignTalk — 농인/비농인 실시간 번역 채팅 서비스
> 4인 팀 프로젝트 | Text to Sign 파트 담당

- 텍스트 전처리 → KoBART gloss sequence 생성 → FastText/pgvector DB 매칭 → 영상 URL 재생
- FastText 지연 로드 구조 문제 파악 → 서버 기동 시 사전 로드로 수정 → timeout 해결 (P95 latency 약 62ms)
- PostgreSQL 정확 매칭 우선, miss 시 FastText 코사인 유사도 Top-K 후보 파이프라인 구현

[→ Repository](https://github.com/growinloop/SignTalk)

---

## 📚 Currently

- signtalk-v2 UI 개선 및 모델 교체 실험(v2-3) 진행 중

---

## 📫 Contact

- Email: growinloop@gmail.com
