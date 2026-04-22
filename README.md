# 레버리지 쇼케이스

> 40대 자영업자의 AI 시간 레버리지 증거 포트폴리오

바쁜 40대 자영업자(지식산업센터 중개사 준비생)가 `AI + 옵시디언 + Claude Code + 30+ 개인 에이전트`로 업무·공부·육아·운동을 어떻게 자동화했는지를 **수치·결과물·스크린샷**으로 묶은 쇼케이스입니다.

코드 저장소가 아니라 **증거 인덱스**입니다.

---

## 📊 숫자로 본 결과

| 항목 | 현황 |
|------|-----|
| 개인 에이전트 | **30+** 개 |
| 주간 회수 시간 | **약 10시간** |
| launchd 스케줄 자동화 | **7종** |
| MCP 통합 | **5종** |
| 운영 중인 도메인 | 부동산 · 블로그 · 공부 · 운동 · 육아 |

> 수치는 매월 말일 실측 갱신.

---

## 📂 자산 카테고리별 증거

### 1. 네이버 블로그 자동화 (키워드 → 글 → 이미지 → 발행)

![AI 부동산 데이터 연구소 블로그](images/01-blog-pipeline/cover.png)

- **구현:** [`harness-engineering-guide/templates/agents/blog-writer-naver.md`](https://github.com/alice840126-ship-it/harness-engineering-guide)
- **제품화:** [`naver-blog-auto`](https://github.com/alice840126-ship-it/naver-blog-auto) (전자책 구매자 설치 스크립트)
- **실제 발행:** [네이버 블로그 alice8401](https://blog.naver.com/alice8401) — AI 부동산 데이터 연구소

### 2. 부동산 데이터 수집 (호갱노노 + 국토부 실거래가)

![호갱노노 시세 자동 수집](images/02-realestate/cover.png)

- **구현:** `harness-engineering-guide/templates/agents/web_data_scraper.py`
- 지식산업센터 시세 브리핑 / 덕은동 아파트 시세 등 매월 자동 추적
- Playwright headless로 동적 페이지 수집 → 옵시디언 노트 자동 저장

### 3. 공인중개사 기출 AI 오답노트 (OCR + Claude)

![공인중개사 오답노트 퀴즈](images/03-exam/cover.png)

- 기출 PDF → OCR → Claude 해설 → 옵시디언 저장
- 틀린 문제만 모아 매일 아침 복습 리마인더
- 2026년 1차 시험(10월) 목표

### 4. 마라톤 훈련 대시보드 (Nike Run Club 스크린샷 → 자동 차트)

![러닝 훈련 대시보드](images/04-marathon/cover.png)

- 스크린샷 OCR → 페이스·거리·심박 추출 → HTML 대시보드
- 6월 7일 하프마라톤 · 11월 1일 풀마라톤 준비

### 5. 텔레봇 이안 (아침 7시 메타 에이전트 브리핑)

![이안 봇 아침 브리핑](images/05-telegram/cover.png)

- 07:00 데일리 노트 · 07:05 아침 메타 에이전트 보고 · 17:00 문자 요약 · 17:50 저녁 브리핑
- 목표 진척도 · 미리알림 · D-Day 카운터 자동 집계
- 부동산 이슈 자동 스캔 후 즉시 텔레그램 알림

### 6. 옵시디언 × Claude Code × MCP 통합

![옵시디언 볼트 홈](images/06-obsidian/cover.png)

- 30+ 개인 에이전트 오케스트레이션
- MCP 5종: 옵시디언 · 캘린더 · 텔레그램 · 웹서치 · 웹리더
- 구조도: [`obsidian-claude-code-workflow`](https://github.com/alice840126-ship-it/obsidian-claude-code-workflow)

---

## 🧭 이 쇼케이스의 목적

- 지피터스 · 더 배러 커뮤니티 케이스 공유
- 인프런 · 패스트캠퍼스 강의 제안 시 포트폴리오
- 40대 자영업자에게 **"AI로 이렇게 쓸 수 있다"** 실제 증거

---

## 🔗 연결

- 네이버 블로그: [alice8401](https://blog.naver.com/alice8401)
- 에이전트 방법론: [harness-engineering-guide](https://github.com/alice840126-ship-it/harness-engineering-guide)
- 블로그 자동화 전자책: [naver-blog-auto](https://github.com/alice840126-ship-it/naver-blog-auto)
- 옵시디언 워크플로우: [obsidian-claude-code-workflow](https://github.com/alice840126-ship-it/obsidian-claude-code-workflow)

---

## 📝 개인정보 보호 원칙

이 저장소는 **구조·개념·결과 스크린샷**만 담습니다.
개인정보(집주소·가족명·실수입·API 키·비밀번호·로그인 정보)는 커밋하지 않으며, 스크린샷에 포함된 민감 정보는 블러 처리합니다.

---

**저자:** 류웅수 · 구해줘 부동산 · 지식산업센터 전문 중개사 준비 중
**마지막 갱신:** 2026-04-22 (v0.1 스켈레톤)
