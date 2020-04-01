Sample Project on Nuxt.js / Typescript / docker
====

Nuxt.js / Typescript / docker のベースプロジェクト

## Description
- programming language TypeScript
- the package manager Yarn
- Nuxt.js modules Axios, Progressive Web App (PWA) Support
- rendering mode Single Page App

## Requirement
- docker
- docker-compose

## Install
1. git clone
```bash
$ git clone https://github.com/numasa/nuxt_typescript_on_docker.git
$ cd nuxt_typescript_on_docker
```

2. build & yarn install
```bash
$ docker-compose run vue yarn install
```

3. service run on localhost
```bash
$ docker-compose run --service-ports vue yarn run dev
```

4. access localhost:3000 by browser
- [http://localhost:3000/](http://localhost:3000/)
