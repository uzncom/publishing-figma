# publishing-figma

`designcenter-figma`에서 생성된 디자인 토큰을 직접 참조해서 퍼블리싱에 사용하는 폴더입니다.

## 설치

```bash
cd /Users/leejeongmi/Desktop/Figma/packages/publishing-figma
npm install
```

## 토큰 빌드

```bash
npm run build:tokens
```

`designcenter-figma/build` 결과물이 그대로 참조됩니다.

## 토큰 변경사항 실시간 반영

```bash
npm run watch:tokens
```

`designcenter-figma/tokens` 변경 시 토큰이 재빌드됩니다.

## React 샘플 화면 실행

```bash
npm run dev
```

브라우저에서 `http://localhost:5173`로 접속하면 토큰이 적용된 버튼 샘플을 볼 수 있습니다.
