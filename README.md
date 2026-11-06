# HidyGames — by HidyStudio

HIDYSTUDIO GitHub 계정의 **HidyGames** 저장소에 올리기 위한 정적 게임 포트폴리오 사이트입니다.

## 현재 페이지
- `index.html`: HidyGames 메인 / 게임 목록 / HidyStudio 소개
- `gravtile.html`: GRAVTILE 게임 상세
- `gacha.html`: Gacha Capsule Smasher 게임 상세
- `404.html`: 페이지 오류
- `assets/css/site.css`: 전체 스타일
- `assets/js/site.js`: 한국어/영어 언어 전환
- `assets/img/`: 사용자가 제공한 HidyStudio 로고를 웹에 맞게 여백 크롭한 이미지와 이전 사이트의 콘셉트 일러스트

**주의**: 게임 그림은 실제 인게임 스크린샷이 아니라 별도 제작한 콘셉트 그래픽입니다. 출시 전 실제 게임 스크린샷으로 바꿔도 됩니다. 공식 스토어 및 연락처 링크는 미확정 상태라 넣지 않았습니다.

## 기존 저장소에 업로드하기 (새 저장소 생성 불필요)

저장소: https://github.com/HIDYSTUDIO/HidyGames

1. ZIP 파일을 PC에 압축 해제합니다.
2. 위 링크의 GitHub 저장소를 엽니다.
3. 빈 저장소라면 중앙의 `uploading an existing file` 링크를 누릅니다. 이미 파일이 있는 경우 `Add file → Upload files`를 누릅니다.
4. ZIP 파일 **자체**가 아니라, 압축을 푼 폴더의 `index.html`, `gravtile.html`, `gacha.html`, `404.html`, `assets` 폴더, `.nojekyll` 파일을 **한 번에 업로드**합니다. `README.md`도 함께 올려도 됩니다. 숨김 파일 `.nojekyll`이 보이지 않으면 없어도 페이지는 표시되지만 동봉 권장입니다.
5. 페이지 아래 `Commit changes` 버튼을 눌러 저장합니다.
6. `Settings → Pages → Build and deployment → Source: Deploy from a branch`를 선택합니다.
7. `Branch: main`, `Folder: /(root)`를 선택하고 `Save`를 누릅니다.
8. 게시 후 주소는 보통 **https://hidystudio.github.io/HidyGames/** 입니다. GitHub Pages의 `Visit site`에서 실제 게시 주소를 확인하세요.

**중요**: 대소문자 포함 저장소 이름은 `HidyGames` 입니다. HTML과 이미지 경로는 모두 상대 경로라 GitHub Pages 프로젝트 경로 아래에서 정상 동작하도록 구성했습니다.

## 새 게임 추가
1. `gravtile.html`을 복사해 새 파일을 만듭니다(예: `newgame.html`).
2. 게임명, 설명, 장르, 정보와 이미지 경로를 수정합니다. 한국어 문구는 `data-ko`, 영어 문구는 `data-en`에 함께 기록합니다.
3. `index.html`의 `id="games"` 섹션 내부 `<div class="card-grid">`에 게임 카드 `<a class="game-card" ...>` 블록을 하나 복사해서 새 게임 정보를 입력합니다.
4. `assets/img/`에 게임의 정식 스크린샷 또는 제작한 소개 이미지를 추가합니다.
5. GitHub에 변경 파일을 커밋하면 사이트가 다시 배포됩니다.

## 로컬 확인
브라우저로 `index.html`을 열면 됩니다. 언어 전환 설정은 사용자의 브라우저 로컬 저장소에만 보존합니다. 분석 스크립트와 광고/추적 코드는 포함하지 않았습니다.

## 나중에 교체하면 좋은 항목
- 실제 GRAVTILE / Gacha Capsule Smasher 게임 스크린샷
- 공개가 확정된 스토어 주소 / 문의 이메일
- 유효한 공개 URL이 정해진 후 OG 이미지 절대 URL 및 canonical 추가
- 게임의 출시 일정이나 상태가 바뀔 때 상태 문구 수정
