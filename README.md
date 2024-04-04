# 프로젝트 개요

- React 프로젝트에서 SEO 대응을 위한 최소 작업 대응

## 개발환경 세팅

### 패키지 설치

#### Yarn

```
yarn install
```

## Favicon 세팅

### 각 파일의 역할

- favicon.ico: 브라우저 title 옆에 보이는 16x16 사이즈의 이미지
- webmanifest.json: 여러 기기에 맞는 icon을 Web Application Manifest specification에 맞게 정의한 JSON 파일
- apple-icon-xxx: iOS application을 위한 아이콘
- android-icon-xxx: Android application을 위한 아이콘
- ms-icon: MS application을 위한 아이콘
- ...

## SEO 스코어 분석

- 스코어 분석에 사용한 서비스: https://www.seobility.net/en/seocheck/

### 개선점

- headings(H1~H6) 추가하기

- 최소 250자 이상의 text를 넣기

- Internal link가 적어 페이지 구조를 알기 어려움. Intro page라면 제거할 것을 검토

- Backlink 늘리기
  - 3Social network에 페이지 홍보하기
