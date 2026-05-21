# Wealth Compounding Lab

자산 시뮬레이터 — 적립식 복리, 레버리지 ETF 포트폴리오, RIA 절세 전략.

## 배포 방법

### Vercel 배포 (드래그 앤 드롭)
1. https://vercel.com 접속 후 로그인
2. "Add New..." → "Project" → "Deploy a third-party Git Repository" 옆 "Or import directly"
3. 또는 https://vercel.com/new 에서 폴더 전체를 드래그
4. 배포 완료 후 URL 받음 (예: `wealth-sim-xxx.vercel.app`)

### Vercel CLI (선택)
```bash
npm install -g vercel
cd deploy/
vercel
```

## 파일 구성
- `index.html` — 메인 시뮬레이터 페이지
- `manifest.json` — PWA 매니페스트
- `sw.js` — 서비스 워커 (오프라인 캐싱)
- `icon-192.png`, `icon-512.png` — PWA 아이콘
- `vercel.json` — Vercel 배포 설정

## 모바일 홈 화면 추가
배포 후 모바일 브라우저에서 사이트 접속 → 공유 메뉴 → "홈 화면에 추가"
