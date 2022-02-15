# lona-univ--vote-crawler

로나 유니버스 투표현황 크롤링 봇입니다.
매 시간 정각마다 크롤링하여 구글 스프레드 시트에 저장합니다.

https://docs.google.com/spreadsheets/d/1qFYioVZKq6dvO9HaQ-CXK2lD1gp1GpQ4a4CA_Rw5FiY/edit#gid=1304601804

## 의존성

- selenium(with chrome driver)
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
네이버 로그인은 "USRE_DATA_DIR"설정에 저장된 프로필으로 브라우저를 열고 `로그인 상태 유지`를 체크 후 로그인 하면 로그인이 유지됩니다.

## Links

- 투표 링크([소스](https://cafe.naver.com/ronaronakr/2476))
- 큐에 ([트위치](https://www.twitch.tv/yu_0w0r)) ([유튜브](https://www.youtube.com/c/9yueeeee))
- 기유미 ([트위치](https://www.twitch.tv/ki_yumi)) ([유튜브](https://www.youtube.com/c/%EA%B8%B0%EC%9C%A0%EB%AF%B8KiYimi))
