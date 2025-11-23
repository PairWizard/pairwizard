# 초기 세팅 완료 내역

## 프로젝트 구조

- ✅ Monorepo 구조 (pnpm workspace + Turborepo)
- ✅ Frontend: `apps/frontend`
- ✅ Backend: `apps/backend`
- ✅ Shared packages: `packages/*`

## Frontend (Next.js)

- ✅ Next.js 16.0.3
- ✅ React 19.2.0
- ✅ Tailwind CSS 4
- ✅ TypeScript 5
- ✅ React Query (@tanstack/react-query)
- ✅ Zustand (상태 관리)
- ✅ React Hook Form + Zod (폼 검증)

## Backend (NestJS)

- ✅ NestJS 10
- ✅ Prisma (PostgreSQL)
- ✅ TypeScript 5

## 개발 환경

- ✅ Node.js >= 18.0.0
- ✅ pnpm 8.15.5
- ✅ Prettier (코드 포맷팅)
- ✅ ESLint (코드 린팅)

## CI/CD

- ✅ GitHub Actions
  - Lint & Type check
  - Build

## GitHub 설정

- ✅ PR Template
- ✅ Issue Templates (bug, feature, question)
- ✅ CodeRabbit 설정

## 스크립트

- `pnpm dev` - 개발 서버 실행
- `pnpm build` - 빌드
- `pnpm lint` - 린트 검사
- `pnpm format` - 코드 포맷팅
- `pnpm type-check` - 타입 체크
