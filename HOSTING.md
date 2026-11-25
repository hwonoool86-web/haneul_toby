# 카드뉴스 이미지 호스팅

인스타그램(neul_toby) 게시용 공개 JPEG 저장소입니다.

- 브랜치: `haneul`
- 폴더: `ai-tips/`, `travel/<세트>/`, `world-news/<YYYY-MM-DD>/`
- 파일: `card_01.jpg` ~ `card_09.jpg` (JPEG, 1080x1350, 8MB 이하)
- 공개 주소: `https://raw.githubusercontent.com/hwonoool86-web/haneul_toby/haneul/<폴더>/card_NN.jpg`

## 게시 절차
1. 이미지를 위 폴더 규칙대로 커밋하고 `haneul` 브랜치에 푸시
2. raw 주소가 200으로 열리는지 확인
3. Windsor.ai `instagram` → `create_carousel_post` (account 17841427398693285), `image_urls`에 card_01~09 순서대로, `caption` 지정
