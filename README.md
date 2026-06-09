# AI 기반 보건의료·헬스케어 DX CS 과정 홈페이지

정종기 교수님의 「AI기반 고객응대·민원처리 CS 실무 과정」 소개용 배포-ready 랜딩페이지입니다.

## 구성 파일

- `index.html` — 홈페이지 본문, SEO/OG/구조화 데이터 포함
- `styles.css` — 반응형 디자인, 접근성 포커스, 인쇄 스타일 포함
- `assets/favicon.svg` — 파비콘
- `assets/og-image.svg` — SNS 공유 이미지
- `robots.txt` — 검색엔진 크롤링 허용
- `vercel.json` — Vercel 정적 배포 설정
- `package.json` — 로컬 미리보기 스크립트

## 로컬 확인

```bash
npx serve .
```

또는 `index.html`을 브라우저에서 직접 열어 확인할 수 있습니다.

## Vercel 배포

1. 이 폴더를 GitHub 저장소로 업로드
2. Vercel에서 해당 저장소 Import
3. Framework Preset은 `Other` 또는 자동 감지 사용
4. Build Command는 비워두고, Output Directory는 `.` 사용

## 배포 전 교체 권장값

- 문의 버튼 URL: 현재 `https://kohyeonsim-homepage.vercel.app` 연결
- 기관명/강사명/문의 이메일/전화번호가 확정되면 CTA 영역과 footer에 반영
- 최종 도메인이 확정되면 `sitemap.xml` 추가 가능
