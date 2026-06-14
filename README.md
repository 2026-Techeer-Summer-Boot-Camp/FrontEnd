# FrontEnd

2026 Techeer Summer Boot Camp — 프론트엔드 레포지토리

## 기술 스택

- **React** + **TypeScript**
- **Vite** (빌드 도구)
- **ESLint** (린트)

## 시작하기

```bash
npm install      # 의존성 설치
npm run dev      # 개발 서버 (http://localhost:5173)
npm run build    # 프로덕션 빌드
npm run lint     # 린트 검사
npm run preview  # 빌드 결과 미리보기
```

## CI

`main` 브랜치로의 push / PR 시 `.github/workflows/ci.yml`가 실행됩니다.

- `npm ci` — 의존성 설치
- `npm run lint` — 린트
- `npm run build` — 빌드 검증
