# 구슬 드롭 · Marble Drop

3~20명의 차례를 정하는 구슬 추첨 게임입니다.

1. 참가 인원과 이름을 입력합니다.
2. **추첨 시작**을 누르면 참가자 이름이 무작위 순서로 표시됩니다. 표시된 이름을 누를 때마다 해당 구슬 하나가 떨어집니다. 추첨 화면에서 낙하 속도를 ×0.2~×4로 바꿀 수 있습니다.
3. 이미 구슬이 있는 칸에 떨어지면 왼쪽 또는 오른쪽을 무작위로 골라 첫 빈칸까지 이동합니다. 필요하면 판 가장자리 바깥에 칸이 생깁니다. 최종 순서는 구슬이 멈춘 위치를 왼쪽에서 오른쪽으로 읽습니다.
4. **이름만 순서대로 복사**를 누르면 순위 번호 없이 한 줄에 한 명씩 복사됩니다.

구슬은 14줄의 핀에서 왼쪽 또는 오른쪽으로 무작위로 튕긴 뒤 15개 칸 중 하나에 착지합니다. 참가자 이름은 브라우저 안에서만 사용됩니다.

## 실행

`index.html`을 브라우저에서 열면 바로 실행됩니다.

## GitHub Pages에 올리기

1. GitHub에 새 저장소를 만들고, 이 폴더의 파일을 `main` 브랜치의 루트에 올립니다.
2. **Settings → Pages → Build and deployment**에서 **Deploy from a branch**를 선택합니다.
3. 브랜치 `main`, 폴더 `/(root)`를 선택하고 **Save**를 누릅니다.
4. 배포가 완료되면 **Settings → Pages**에 표시되는 사이트 링크로 게임을 엽니다.

[GitHub Pages 배포 설정 안내](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
