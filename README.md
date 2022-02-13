# lona-univ--vote-crawler

로나 유니버스 투표현황 크롤링 봇입니다.
매 시간 정각마다 크롤링하여 구글 스프레드 시트에 저장합니다.

## 의존성

- selenium(with chrome)
- telegram bot token 및 chat id(필요 없는 경우 관련 부분 주석 처리 후 사용)
- 구글 스프레드 시트 API 및 저장 될 문서

## 사용법

yarn 패키지 매니저를 사용합니다.

```bash
# 의존성 설치
yarn

# 빌드
yarn run build

# 실행
yarn run start
```

네이버 로그인 및 모든 회차에 대한 투표가 필요합니다.
네이버 로그인은 111번 라인의 주석을 해제하고 106번 라인을 주석 처리 후 봇 브라우저에서 로그인 후 재실행하면 됩니다.
