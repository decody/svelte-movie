# Svelte Movie App

스벨트 설치, 스노우팩 설치. 스노우팩 빌드할때 지원플러그인 설치
npm install -D svelte snowpack @snowpack/plugin-svelte

스노우팩 설정파일 생성


`snowpack.config.js`에 `scripts` 실행 명령어 추가
npm run dev

favicon 파일과 assets 파일 복사


autoprefixer와 postcss, node-sass 설치
`npm install -D autoprefixer postcss @snowpack/plugin-sass`
autoprefixer를 설치할 때 같이 `package.json`에서 `browserslist`를 추가해 주어야 한다.


바벨 세팅
`npm install -D --save-dev @snowpack/plugin-babel`

바벨 플러그인 콘솔로그 삭제
`npm install -D babel-plugin-transform-remove-console --save-dev`


환경변수 설정 파일 설치
`npm install -D @snowpack/plugin-dotenv`

경로 별칭 설정
프로젝트 경로가 바뀌어도 경로 별칭을 사용하고 절대경로로 지정해 주면 전체 경로를 변경시 별칭에 설정된 경로만 바꾸면 된다.

스노우팩 최적화
스노우팩으로 빌드시 압축하고 코드 난독화를 하여 코드 최적화를 함
`npm install -D @snowpack/plugin-optimize`

스벨트 라우터 설치
`npm install -D svelte-spa-router`