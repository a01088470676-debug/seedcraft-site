# SeedCraft 랜딩페이지

SeedCraft 마인크래프트 플러그인 스토어의 정적 랜딩페이지 2개입니다. GitHub Pages로 호스팅합니다.

- `index.html` — 전체 브랜드/플러그인 목록 페이지
- `myBTC-landing.html` — myBTC 플러그인 상세 페이지

## 채워야 할 placeholder

아직 실제 정보가 들어가지 않은 자리가 총 4곳 있습니다 (코드에 `<!-- TODO -->` 주석으로 표시):

1. `myBTC-landing.html`의 `[ 카카오페이 링크 또는 계좌번호를 여기에 입력하세요 ]`
2. `index.html`의 디스코드 초대 링크 2곳 (`href="여기에_디스코드_초대_링크_입력"`)
3. `myBTC-landing.html`의 디스코드 초대 링크 2곳 (`href="여기에_디스코드_초대_링크_입력"`) — 상단 CTA와 하단 CTA

각 파일에서 `여기에_디스코드_초대_링크_입력` 문자열을 실제 초대 링크(`https://discord.gg/xxxxxxx`)로 바꾸면 됩니다.

## 새 플러그인 추가하기

`index.html`의 `<div class="products">` 안에 상품 카드 템플릿 주석이 있습니다. 그 블록을 복사해서 아이콘/배지/이름/설명/가격/링크만 바꿔 넣으면 새 카드가 추가됩니다.
