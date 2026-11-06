# HidyGames — by HidyStudio (v4)

HidyGames는 **HidyStudio의 게임을 소개하는 GitHub Pages용 정적 웹사이트**입니다.
이 저장소는 실제 서비스용 페이지 파일(`index.html`, `gravtile.html`, `gacha.html`, `assets/`)을 담고 있습니다.

## 이번 버전(v4) 변경점
- 메인 페이지에서 게임을 **Android / APP** 와 **PC / STEAM** 카테고리로 구분
- GRAVTILE 페이지를 **실제 인게임 스크린샷 기반**으로 업데이트
- GRAVTILE 대표 화면, 모드 화면, 메뉴, 안내/설정 UI 반영
- Gacha Capsule Smasher는 **itch.io / YouTube / 문의 메일** 정보 유지
- 한국어 / 영어 전환 및 모바일 대응 유지

## 파일 구성
- `index.html` : 메인 페이지
- `gravtile.html` : GRAVTILE 상세 페이지
- `gacha.html` : Gacha Capsule Smasher 상세 페이지
- `assets/css/site.css` : 공통 스타일
- `assets/js/site.js` : 한국어 / 영어 전환 스크립트
- `assets/img/` : 로고 및 게임 이미지

## GitHub Pages 배포 방법
1. 이 ZIP 파일을 PC에 압축 해제합니다.
2. GitHub 저장소 `HIDYSTUDIO/HidyGames` 를 엽니다.
3. **압축 해제한 폴더 자체가 아니라 폴더 안의 파일들** (`index.html`, `gravtile.html`, `gacha.html`, `assets/` 등)을 저장소 최상위에 업로드합니다.
4. 기존 파일이 있으면 같은 이름으로 덮어씁니다.
5. Commit changes 를 눌러 저장합니다.
6. `Settings → Pages` 에서 `Deploy from a branch / main / (root)` 설정이 맞는지 확인합니다.
7. 배포 주소: `https://hidystudio.github.io/HidyGames/`

## README는 꼭 길어야 하나요?
아닙니다. README는 보통 아래 정도만 있으면 충분합니다.
- 이 저장소가 무엇인지
- 어떤 파일이 들어 있는지
- 어떻게 배포하는지

즉, **홈페이지의 모든 소개 문구를 README에 그대로 넣을 필요는 없습니다.**
README는 저장소 설명용, `index.html`과 각 상세 페이지는 방문자용 소개 페이지라고 생각하면 됩니다.

## 유의사항
- `PC / STEAM` 카테고리는 **PC 게임 분류**를 뜻합니다. Steam 상점 페이지가 이미 열렸다는 의미는 아닙니다.
- Gacha Capsule Smasher의 데모/구매 링크는 현재 itch.io 기준입니다.
- GRAVTILE 이미지는 실제 개발 중 스크린샷을 기반으로 반영했습니다.
