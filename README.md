# 장미원교회 모바일 감사예배 초대장

첨부된 긴 이미지 한 장을 4페이지로 나눠, 모바일에서 자연스럽게 아래로 스크롤하며 볼 수 있는 정적 웹페이지입니다.

## GitHub Pages에 게시하기

1. GitHub에서 새 **Public** 저장소를 만듭니다 (예: `rose-invitation`).
2. 이 ZIP 파일을 풀고 `index.html`과 `assets` 폴더를 **저장소 최상위(root)**에 업로드합니다.
3. 저장소의 **Settings → Pages → Build and deployment → Deploy from a branch**를 선택합니다.
4. Branch에서 `main`, 폴더에서 `/(root)`를 선택한 뒤 **Save**를 누릅니다.
5. 게시가 완료되면 `https://<GitHub사용자명>.github.io/rose-invitation/` 주소로 초대장을 볼 수 있습니다. (배포에 수 분이 걸릴 수 있습니다.)

## 특징

- HTML/CSS/JS 및 이미지 4개로만 구성되어 서버나 빌드 과정이 필요 없습니다.
- 모바일 화면 너비에 맞춰 이미지가 자동 축소됩니다.
- 스크롤에 따라 1~4페이지가 순서대로 나타납니다.
- 원본 이미지의 문구와 디자인을 변경하지 않았습니다.

## 이미지 교체

`assets/invite-1.webp` ~ `assets/invite-4.webp` 파일을 같은 이름으로 교체하면 됩니다. 새로운 이미지 비율이 다르면 `index.html`의 각 이미지 `width`, `height` 값도 조정하세요.
