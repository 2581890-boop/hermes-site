LSD 홈페이지 콘텐츠 보호 강화 버전

기존 유지:
- 모바일 이미지 최적화
- lazy loading / async decoding
- OG / 카카오톡 공유
- favicon / Apple touch icon
- SEO / robots.txt / sitemap.xml

추가:
- 데스크톱 우클릭 억제
- 이미지 드래그/선택 억제
- iPhone/iPad Safari 길게 누르기(callout) 억제
- 이미지 pointer-events 차단
- 텍스트 선택/복사/잘라내기 억제
- Claude/React가 나중에 생성한 이미지에도 MutationObserver로 자동 재적용
- input/textarea 등 입력 기능 유지

주의:
웹에 공개된 이미지/텍스트는 개발자 도구, 네트워크 캐시, 스크린샷 등으로
기술적으로 100% 복사 방지가 불가능합니다. 이 설정은 일반적인 저장/복사를 억제합니다.
