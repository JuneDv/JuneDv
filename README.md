# 박준우 · JuneDv

진행 프로젝트 정리용

## 프로젝트

| | |
|---|---|
| **공간 Talk** — 건축주 소통 · 현장 운영 프로그램 | 현장마다 만들던 구글 시트 공정현황과 카카오톡 단톡방을 앱 하나로 통합. 건축주 앱(진행 단계·대화·알림, 초대 링크 접속) + 관리자 앱(현장 목록·대화·서류함·건축주 초대) + Jira 자동 동기화. 진행 중 현장 700여 개 운영. → [소개 보기](https://github.com/JuneDv/JuneDv/tree/main/gonggan-talk) |
| **iris** — 적대적 멀티모델 코드 리뷰 플러그인 | Claude가 쓴 코드를 다른 회사 모델들이 공격하고, 그 지적을 또 다른 모델이 반박하게 한 뒤 살아남은 결함만 되돌려 고치게 하는 Claude Code 플러그인. 의존성 0, CLI·CI 게이트로도 사용. → [JuneDv/iris](https://github.com/JuneDv/iris) |
| **연구일지 (research-note-app)** | 연구과제별 연구노트 앱. 사진 첨부, 검토·서명 기록, 선택 항목 Word 내보내기, AI 문장 다듬기. HTML 한 파일로 동작. → [JuneDv/research-note-app](https://github.com/JuneDv/research-note-app) |

## 주로 쓰는 것

- **데이터·백엔드**: Supabase(Postgres, RLS, Edge Functions, Realtime, Vault), SQL 마이그레이션
- **자동화·연동**: n8n, Jira REST API, Google Sheets, 웹 푸시(FCM/APNs)
- **프런트**: 바닐라 JS PWA, Android TWA, Cloudflare Pages 배포, Playwright 시각 회귀 테스트
- **일하는 방식**: Claude Code와 짝 개발. 기획·데이터 설계·검수는 직접, 구현은 함께. 결과물은 리뷰 플러그인(iris)으로 교차 검증.

## 연락

tareura@gmail.com
