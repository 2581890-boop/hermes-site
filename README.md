# LSD 모바일 홈페이지 - GitHub Pages용

Claude Design에서 한 개의 대형 HTML로 Export된 파일을 일반 웹사이트 구조로 분리한 버전입니다.

## 구조
- `index.html` : 메인 페이지
- `css/style.css` : 공통 스타일
- `js/dc-runtime.js` : Claude Design 페이지 동작용 런타임
- `images/` : 로고 및 홈페이지 이미지
- `js/react*.js` : 원본 번들에 포함된 라이브러리 보존본

## GitHub Pages 업로드
이 폴더 안의 파일과 폴더를 **그대로 저장소 루트**에 업로드하세요.
즉, `index.html`이 저장소의 최상위에 있어야 합니다.

## 변경 사항
- `<title>Bundled Page</title>` 문제 제거
- 제목을 `유한회사 엘에스디 | LSD CORPORATION`으로 변경
- Base64로 HTML 내부에 포함됐던 이미지를 `images/`로 분리
- Claude 런타임 JavaScript를 `js/`로 분리
- 공통 CSS를 `css/style.css`로 분리
- 원본 디자인과 모바일 레이아웃은 최대한 그대로 유지

주의: 본 페이지는 Claude Design의 `dc-runtime` 동작에 의존하므로 `js/dc-runtime.js`는 삭제하면 안 됩니다.
