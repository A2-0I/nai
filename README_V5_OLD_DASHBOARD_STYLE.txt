AI 프로세스 독립 프로젝트 V5 - 예전 회원 대시보드 디자인 반영

기준: 사용자 첨부 a-main (10).zip 의 user/dashboard.html

변경: user/dashboard.html 의 텍스트 2곳 + 스타일 링크 1곳; shared/legacy-dashboard-v5.css 추가.
유지: V4 다중 투자, 오늘/누적 수익, 그래프, 기록, 회원 및 관리자 로그인, 관리자 회원 등록, Supabase 접속 로직.
유의: 예전 대시보드의 내부 데이터 조회 코드를 덮어쓰지 않았습니다. 실제 브라우저/DB E2E 검증 필요.
배포: 기존 shared/config.js 를 유지하고 나머지를 업로드하십시오.
