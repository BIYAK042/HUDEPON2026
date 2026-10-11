# HUDEPON2026
# Violet Studio Virtual Phone

GitHub Pages용 정적 가상 휴대폰 프로토타입입니다.

## 배포
1. `index.html`, `style.css`, `script.js`를 저장소 루트에 업로드합니다.
2. 기존 아이콘 PNG는 `assets/icons/`에 그대로 둘 수 있습니다. 현재 홈 화면은 참고 이미지에 맞춘 CSS 타일/기호로 표시됩니다.
3. Settings → Pages → Deploy from a branch → `main` / `/(root)` → Save.

## 참고
- 데이터는 브라우저 `localStorage`에 저장됩니다. 같은 브라우저/기기에서 유지되며 다른 기기로 자동 동기화되지 않습니다.
- 사진과 인스타그램 게시물 이미지는 브라우저 저장 용량 제한을 받을 수 있습니다.
- DChannel은 사용자가 제공한 `https://2026td.dchannel.com` 주소를 가상 화면 라우트로 연결합니다. 실제 도메인이나 서버를 생성하는 것은 아니며, 앱 내부의 가상 게시판입니다.
- TDIDT의 상세 설정은 대화에서 구체화되지 않아 기본 기록 화면으로 구현했습니다.
- 전화/YouTube/QR은 실제 전화·영상 재생·QR 스캔이 아닌 시뮬레이션입니다.
