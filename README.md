# 일양익스프레스 랜딩페이지

일양익스프레스(해상·항공 포워더) 원페이지 랜딩페이지. 단일 `index.html`(외부 의존성은 Google Fonts뿐).

- 구성: 웨이브 배너 → 로고 줄 → 고정 내비 → 히어로(노선 애니메이션) → 핵심 수치 → 회사소개 → 주요서비스 5종 → 계열사 띠 → 강점 4종 → 지점·센터 6곳 → Contact Us → 푸터
- 디자인: ILYANG EXPRESS 디자인 시스템(문서 계열: 웨이브 배너, 둥근 카드), 다크 테마·모션 줄이기 대응
- 문의 폼은 미리보기용으로 실제 전송하지 않음

## 확인 필요
- 항공물류 대표번호: CONTACT 페이지 02-710-5822 / 메인 푸터 02-710-5823
- 대표 이메일(문의 폼 수신처), 운영시간, 사업자등록번호
- 로고 이미지 파일(현재 텍스트 워드마크)

## 미리보기
`index.html`을 브라우저로 열면 바로 확인할 수 있다.

## Vercel 배포
빌드 과정이 없는 정적 사이트다. `vercel.json`에는 깔끔한 URL과 보안 헤더 설정만 들어 있다.

1. https://vercel.com/new 에서 GitHub 저장소 `judyloobylee-ops/ilyang_website`를 Import
2. Framework Preset: **Other**, Build Command·Output Directory는 비워둔 채 **Deploy**
3. 이후 `main` 브랜치에 푸시할 때마다 자동으로 다시 배포된다

CLI로 올릴 때(Node.js 필요): `npx vercel` (미리보기) → `npx vercel --prod` (운영)
