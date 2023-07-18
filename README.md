# 프로젝트 세팅 순서

```shell
# 만약 pnpm이 설치되지 않은 경우
npm install -g pnpm

# pacakage.json 파일 구성
$ pnpm init

# react/react-dom 설치
$ pnpm install react react-dom

# index.html 구성
$ mkdir public && cd public/ && touch index.html && cd ..

# index.tsx 파일 구성
$ touch index.tsx 

# src 폴더 및 App.tsx 파일 구성
$ mkdir src && cd src/ && touch App.tsx && cd ..

# 개발 단계로 Typescript를 설치
$ pnpm install -D typescript @types/react @types/react-dom 

# Typescript 초기화 & tsconfig.json 파일이 구성
$ tsc --init

# 만약 zsh: command not found: tsc 에러 발생 시 아래 명령어를 입력
npm install typescript -g

tsc -v

# babel 설치
$ pnpm install -D babel-loader @babel/core @babel/preset-env 

# Typescript babel 설치
$ pnpm install @babel/preset-react @babel/preset-typescript

# babel.config.js 파일 생성
$ touch babel.config.js

# webpack 필수 구성을 설치합니다.
$ pnpm install -D webpack webpack-cli webpack-dev-server webpack-merge

# webpack의 플러그인 관련 구성을 설치합니다
$ pnpm install -D html-webpack-plugin clean-webpack-plugin ts-loader

# webpack 공통 파일을 생성합니다.
$ touch webpack.common.js

$ touch webpack.dev.js

$ touch webpack.prod.js

```

