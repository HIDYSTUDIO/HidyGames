# HidyGames — by HidyStudio (v3)

HidyStudio 공식 게임 소개 사이트. GitHub Pages로 배포하는 정적 웹사이트입니다.

## 업데이트 (v3)
- 메인 화면의 PLAY / CREATE / EXPLORE / MORE 줄 제거 (로고 자체의 슬로건은 유지)
- 게임 목록을 **Android / APP**와 **PC / STEAM**으로 구분
- GRAVTILE은 Android 쪽에, Gacha Capsule Smasher는 PC 쪽에 배치
- Gacha Capsule Smasher에 개발자가 제공한 실제 게임 화면 12개를 갤러리로 배치 (총 16장 WebP 포함)
- [itch.io](https://hidystudio.itch.io/gacha-capsule-smasher) 무료 Windows 데모 및 유료 버전($4.99부터) 링크 추가
- [YouTube 채널](https://www.youtube.com/@HidyGames) 링크 추가
- 고객 문의: [hidygames.studio@gmail.com](mailto:hidygames.studio@gmail.com)
- 한국어 / 영어 전환 유지, 모바일 대응

## GitHub Pages 배포 방법
1. 기존 저장소 https://github.com/HIDYSTUDIO/HidyGames 로 이동합니다.
2. 이번 ZIP을 압축 해제합니다.
3. **압축 해제 폴더 자체가 아니라 폴더 안에 있는 파일·폴더** (`index.html`, `gacha.html`, `gravtile.html`, `assets/` 등)를 저장소 **최상위에 업로드하여 같은 이름의 기존 파일을 대체**합니다.
4. Commit changes 후 Settings → Pages에서 `Deploy from a branch`, `main`, `/(root)` 확인합니다.
5. 배포 주소: https://hidystudio.github.io/HidyGames/

## 게임 추가
- `index.html`: 각 플랫폼 섹션에 새로운 `platform-card`를 추가합니다.
- 게임 상세 페이지를 `<game-name>.html`로 신규 작성하면 됩니다.
- 게임 스크린샷은 `assets/img/`에 보관합니다.

## 유의사항
- **PC / STEAM은 PC 게임을 분류하는 카테고리**입니다. Gacha Capsule Smasher의 Steam 판매 페이지가 이미 열렸다는 뜻이 아닙니다.
- itch.io의 무료 데모와 유료 게임은 2026-11-06 확인 당시 Windows 전용으로 제공됩니다. 판매 정보는 변동될 수 있습니다.
- GRAVTILE 그림은 실제 게임 플레이 화면이 아닌 콘셉트 이미지입니다.
- 사진·로고는 HidyStudio가 제공한 이미지를 사용했습니다.
