## Web

> STACK : Next.js 12 + Typescript + Tailwind CSS 3

```
Eslint 자동화 및 커밋 규칙은 다음 파일을 통해 규칙을 확인해주세요.
> Eslint - .eslintrc.js
> Prettier - .prettierrc.js
> Husky & Lint Staged / Conventional Commit Lint - commitlint.config.js

정 어쩔 수 없는 경우 다음 라인을 해당 에러 위에 추가해주세요
> any 타입 필요한 경우 (예시. 테이블 헤더 api fetch 할때 타입 바뀔 수 있음)
// eslint-disable-next-line @typescript-eslint/no-explicit-any
> 라이브러리 사용시 unused vars 생기는경우 커밋되지 않음
// eslint-disable-next-line unused-imports/no-unused-vars

로컬 테스트
1. 클론
2. yarn install
3. yarn dev (테스트)
4. yarn build (빌드)
5. yarn start (배포)

```

<br />

## Crawler

> STACK : Fast API

```
.env 파일이 필요합니다.

도커환경에서 테스트
docker-compose -f docker-compose.yml up -d

pipenv 가상환경에서 테스트
1. pipenv install
2. pipenv shell
3. python uvicorn src.main:app --reload --host -0.0.0.0 --port 8002

```

<br />

## Main API

> STACK : Fast API

```
진행중
```
