# mini-react
mini-react는 **Vanilla JavaScript를 사용하여 React의 핵심 기능을 구현**한 프로젝트입니다. 이 프로젝트는 React의 내부 동작 원리를 이해하고, 프론트엔드 개발의 핵심 개념을 학습하기 위해 개발되었습니다.

## 프로젝트 개요
이 프로젝트는 React의 주요 기능을 직접 구현함으로써, 프론트엔드 라이브러리의 작동 방식을 깊이 이해하고자 하는 목적으로 만들어졌습니다. 주요 구현 사항은 다음과 같습니다:
1. JSX 트랜스파일링
2. Virtual DOM 구현
3. useState 훅 구현

## 기술 스택
<p>
<img src="https://shields.io/badge/JavaScript-F7DF1E?logo=JavaScript&logoColor=000&style=flat-square" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=Vite&logoColor=white" />
</p>

## 주요 기능

### 1. JSX 트랜스파일링

JSX 문법을 JavaScript 코드로 변환하는 기능을 구현했습니다. 이를 통해 React와 유사한 컴포넌트 작성 방식을 지원합니다.


### 2. Virtual DOM

효율적인 DOM 업데이트를 위해 Virtual DOM을 구현했습니다. 이를 통해 실제 DOM 조작을 최소화하고 성능을 개선했습니다.

주요 구현 내용:
- `createElement` 함수로 Virtual DOM 노드 생성
- `createDOM` 함수로 Virtual DOM을 실제 DOM으로 변환
- `updateDOM` 함수로 변경된 부분만 효율적으로 업데이트

### 3. useState 훅

React의 `useState` 훅과 유사한 기능을 구현하여 컴포넌트의 상태 관리를 가능하게 했습니다.


## 설치 및 실행 방법

1. 저장소 클론:
   ```
   git clone https://github.com/your-username/js-mini-react.git
   cd js-mini-react
   ```

2. 의존성 설치:
   ```
   yarn install
   ```

3. 개발 서버 실행:
   ```
   yarn dev
   ```

4. 브라우저에서 `http://localhost:5173` 접속

## 프로젝트 구조

```
js-mini-react/
├── src/
│   ├── mini-react/
│   │   ├── react.js              # React 코어 기능 구현
│   │   └── jsx-transpiler.js   # JSX 변환 로직
│   ├── App.jsx                    # 메인 애플리케이션 컴포넌트
│   └── main.js                    # 애플리케이션 진입점
├── index.html
├── vite.config.js                # Vite 설정 파일
└── package.json
```

## 학습 내용 및 성과

1. **프레임워크의 내부 동작 이해**: React의 핵심 기능을 직접 구현함으로써, 깊이 이해했습니다.
2. **JavaScript 고급 기능 활용**: 클로저, 고차 함수 등 JavaScript의 고급 기능을 실제 프로젝트에 적용하는 경험을 쌓았습니다.
3. **성능 최적화 기법**: Virtual DOM을 통한 효율적인 DOM 업데이트 방식을 구현하며, 웹 애플리케이션의 성능 최적화 기법을 학습했습니다.
4. **빌드 도구 활용**: Vite를 사용하여 모던 프론트엔드 개발 환경을 구축하고 활용하는 방법을 학습했습니다.

## 향후 계획

- 추가적인 React 훅 구현 (useEffect, useContext 등)
- Fiber, working queue 등
- 테스트 코드 작성을 통한 품질 향상
