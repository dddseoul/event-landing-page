# DDD Seoul 행사 페이지

DDD Seoul의 티켓타코 행사 소개용 정적 HTML, 콘텐츠 원본과 이미지 자산을 관리합니다.

- 현재 페이지: [DDD Seoul 2026](ticketaco/2026/12/dddseoul/index.html)
- 콘텐츠 원본: [index.md](ticketaco/2026/12/dddseoul/index.md)
- 작성 규칙: [AGENTS.md](AGENTS.md)
- 공식 홈페이지: https://dddseoul.kr/

## 로컬 미리보기

저장소 루트에서 실행합니다. 서버를 이미 실행했다면 기존 서버를 사용합니다.

```powershell
npx --yes serve .
```

기본 확인 주소: http://localhost:3000/ticketaco/2026/12/dddseoul/

## 페이지 작성과 게시

행사별 파일은 `ticketaco\{YYYY}\{MM}\{event-slug}\`에 보관합니다. 새 페이지를 만들거나 수정하기 전에 `AGENTS.md`의 티켓타코 스타일 제약을 확인하세요.

티켓타코에는 `index.html`의 **`<body>` 안쪽 전체 내용**을 복사합니다. 외부 래퍼의 인라인 스타일까지 포함해야 합니다. GitHub에 파일을 반영하는 것만으로 티켓타코 행사 소개가 바뀌지는 않습니다.
