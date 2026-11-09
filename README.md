# terms-of-service

앱별 서비스 이용약관을 공개하기 위한 정적 HTML 저장소입니다. `C:/dev/privacy-policy`와 같이 앱별 하위 폴더를 사용합니다. 별도 설치·빌드·API 키 없이 동작합니다.

## 파일 구성

- `index.html`: 약관 목록
- `quiz/index.html`: 내가 쓰려고 만든 퀴즈 앱 서비스 이용약관 (운영자 하진욱, 문의 nukabyte@gmail.com)
- `.nojekyll`: GitHub Pages에서 정적 파일 그대로 게시
- `CHANGELOG.md`: 작성·검증·변경 이력
- `AGENTS.md`: 후속 변경 시 작업 지침

## 현재 상태

로컬 작성·검증본입니다. GitHub 원격 저장소 생성, push, GitHub Pages 활성화 및 Play Console 등록은 아직 하지 않았습니다. 기존 privacy-policy 저장소와 퀴즈 앱의 런타임·AAB는 변경하지 않습니다.

## 미리보기

`quiz/index.html`을 브라우저에서 직접 열거나 이 폴더에서 `python -m http.server 18090 --bind 127.0.0.1`을 실행한 뒤 `http://localhost:18090/quiz/`에 접속합니다. 인증·외부 스크립트·쿠키를 사용하지 않습니다.

## GitHub Pages 게시

1. 기존 정책 사이트와 같은 GitHub 계정 `BrokenMental`에 `terms-of-service` 저장소를 준비합니다. 로컬 저장소의 원격은 아직 설정하지 않았습니다.
2. 원격을 연결하고 `main` 브랜치를 push합니다. 원격에 기존 내용이 있다면 먼저 확인하며 강제 push하지 않습니다.
3. 저장소 Settings → Pages에서 `Deploy from a branch`, `main`, `/(root)`를 선택합니다. 계정의 Pages 이용 조건과 저장소 공개 범위를 확인합니다.
4. 배포 완료 후 아래 예상 URL이 로그인 없이 열리는지, 모바일 화면·개인정보처리방침 연결이 정상인지 확인합니다.
5. 공개 약관 내용과 Play Console에 입력한 운영자/연락처/상품 설명을 대조하고 앱별 서비스 약관 URL에 등록합니다.

**게시 후 예상 주소** (현재 공개 여부 미확인):
- 목록: https://brokenmental.github.io/terms-of-service/
- 퀴즈 앱: https://brokenmental.github.io/terms-of-service/quiz/

기존 개인정보처리방침은 https://brokenmental.github.io/privacy-policy/quiz/ 이며 이용약관과 별도입니다.

## 공개 전 확인

- 운영자 하진욱 및 이메일은 사용자 확인/기존 앱 정보를 반영했습니다. 판매자에 요구되는 전화번호·주소 등은 Play Console에서 별도로 확인해야 하며 이 페이지에 임의 추가하지 않았습니다.
- 약관 시행일은 2026-11-09로 작성했습니다. 실제 게시·고지 시점이 달라지면 시행일을 맞추고 앱 공지 등 필요한 고지를 진행합니다.
- 실제 판매 상품의 종류·기간·복구·환불 조건은 구매 화면 및 운영 정책과 일치해야 합니다. 정기 결제는 제공되는 경우에만 해당 조항이 적용됩니다.
- 약관에 기재한 이의제기·문의·공지·유료 이용 권리 보호 절차를 실제로 이행해야 합니다. 앱 내 약관 링크/동의 UI를 새로 구현한 것은 아닙니다.
- 현재 기능을 반영한 운영자 검토용 초안이며 법률 검토나 모든 배포 국가의 준수 여부가 보장된 문서는 아닙니다. 포괄적 환불 거절·고의/중과실 면책·강행적 소비자 권리 배제는 넣지 않았습니다.
- 개인정보처리방침의 최신성·광고/AI 처리 공개 범위 및 실제 배포 국가 등은 별도 점검 대상입니다. 기존 정책 문서를 이번에 자동으로 수정하지 않았습니다.

## 참고 자료

- Google Play 판매자 상태·앱별 약관: https://support.google.com/googleplay/android-developer/answer/17594752?hl=ko
- Google Play 환불 정책: https://support.google.com/googleplay/answer/2479637?hl=ko

게시·약관 내용 변경 시 CHANGELOG.md에 적용일과 검증 결과를 기록합니다. 계정 비밀번호, API 키, 주문 원본이나 이용자 기록은 이 저장소에 보관하지 않습니다.
