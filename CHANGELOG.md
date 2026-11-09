# 변경 이력

## 2026-11-09 — 퀴즈 앱 서비스 이용약관 초안

- privacy-policy의 앱별 폴더 구조를 참고해 독립 로컬 저장소와 quiz/index.html 및 목록 페이지를 준비했다.
- 사용자 확인 운영자명 하진욱, 기존 앱 문의 이메일 nukabyte@gmail.com 반영.
- 계정/게스트, 학습 기록·포인트, 광고·결제, 구매 복구·환불, 퀴즈 기상 알람, AI 콘텐츠, 이용 제한·이의제기, 탈퇴·개인정보, 변경·중단·소비자 권리를12개 조항으로 작성.
- GitHub Pages용 .nojekyll, README의 게시 방법/예상 URL/실제 게시 전 확인 사항을 추가했다. 외부 스크립트·로그인·개인정보 수집 없음.
- 기존 개인정보처리방침 저장소/앱 런타임/AAB 변경 없음. 실제 Pages 게시·Play 등록·운영자 최종 약관 고지는 미실행.
- 검증: 두 HTML의 태그 중첩/닫힘·UTF-8·ko/viewport/h1·목차/상대링크·12개 조항·운영자/연락처 확인. 임시 로컬 HTTP 서버에서 / 및 /quiz/ 모두200·한국어 UTF-8 응답 확인. 실브라우저 시각/스크린리더 및 법률 적합성 검토는 별도.

## 2026-11-09 — GitHub 원격 연결 및 최초 push

- 사용자 지정 https://github.com/BrokenMental/terms-of-service.git 을 origin으로 연결.
- fetch --prune 및 ls-remote 확인: 원격 브랜치 없음, 기존 원격 이력 덮어쓰기 없이 main 최초 push 대상.
- README의 원격 상태 갱신, git diff --check 및 staged diff 확인 후 커밋. 강제 push 사용 안 함.
- Pages 설정/공개 URL 및 Play Console 등록은 별도 확인 대상. 최종 push·원격 커밋 일치 결과는 완료 응답에서 보고.
