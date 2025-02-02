# Vue Boilerplate Project

이 프로젝트는 **Vue 3**와 **Vite**를 사용해 본 후, 이후에 새로운 Vue 프로젝트를 빠르게 구축할 수 있는 보일러플레이트를 만드는 것을 목표로 합니다.

## 프로젝트 목적

- **Vue 경험**: Vue 3의 새로운 기능과 컴포지션 API 등을 직접 체험해보고 학습하기 위함입니다.
- **보일러플레이트 구축**: 앞으로 다양한 Vue 기반 프로젝트를 시작할 때 기반 템플릿(boilerplate)으로 활용할 수 있도록 프로젝트 구조와 설정을 정립합니다.

## 주요 기술 및 도구

- **Vue 3**: 최신 Vue 버전으로 구성된 프레임워크.
- **Vite**: 빠른 개발 서버와 빌드 성능을 제공하는 번들러.
- **TypeScript**: 정적 타입 체크를 통한 코드 품질 개선.
- **Pinia**: Vue 3를 위한 상태 관리 라이브러리.
- **Vue Router**: SPA 개발을 위한 라우팅 솔루션.
- **ESLint & Prettier**: 코드 스타일 및 품질 관리를 위한 도구.
- **테스트 도구**: Vitest (단위 테스트) 및 Cypress (엔드 투 엔드 테스트).

## 개발 환경 권장 사항

- **IDE**: [Visual Studio Code](https://code.visualstudio.com/)
- **VSCode 확장**: [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (Vetur 대신 사용)

## 프로젝트 구성

프로젝트는 다음과 같은 기본 폴더 및 파일 구조로 구성되어 있습니다.

```
vue-boilerplate/
├─ public/                # 정적 파일 (이미지, 폰트 등)
├─ src/                   # 애플리케이션 소스 코드
│  ├─ assets/             # 스타일, 이미지, 아이콘 등 정적 자원
│  ├─ components/         # 재사용 가능한 Vue 컴포넌트
│  ├─ views/              # 페이지 단위의 Vue 컴포넌트 (라우터와 연동)
│  ├─ router/             # Vue Router 설정 파일
│  ├─ stores/             # 상태 관리 (예: Pinia) 관련 파일
│  ├─ App.vue             # 최상위 Vue 컴포넌트
│  └─ main.ts             # 애플리케이션 진입점
├─ cypress/               # 엔드 투 엔드(E2E) 테스트 코드
├─ package.json           # 프로젝트 메타 정보 및 스크립트
├─ tsconfig.json          # TypeScript 설정 파일
└─ README.md              # 프로젝트 문서
```

## 프로젝트 설정 및 실행 방법

```sh
npm install
```

### 개발 서버 실행(Hot-Reload)

```sh
npm run dev
```

### 프로덕션 빌드

```sh
npm run build
```

### 단위테스트 실행 (Vitest)

```sh
npm run test:unit
```

### E2E 테스트 실행 (Cypress)

```sh
npm run test:e2e:dev
```

### 린트 검사

```sh
npm run lint
```
