# WesternDuel — 법적 고지

게임 **WesternDuel** (`com.westernduel.game`) 의 처리방침·약관·환불 안내를 내주는 저장소입니다.
코드는 없습니다. HTML 세 장이 전부입니다.

| 파일 | 주소 |
|---|---|
| `index.html` | `/` — 개인정보 처리방침 |
| `terms.html` | `/terms.html` — 이용약관 |
| `refund.html` | `/refund.html` — 청약철회 · 환불 안내 |

## 왜 GitHub Pages 인가

Render 무료 **웹 서비스**는 15분 쓰지 않으면 잠들고, 깨는 데 최대 1분이 걸립니다.
Play Console 이 심사 중에 처리방침 URL 을 두드렸다가 타임아웃이 나면 그대로 반려될 수 있습니다.
GitHub Pages 는 정적 호스팅이라 잠들지 않고, 무료이며, 즉시 응답합니다.

## 고칠 때

원본은 `Western-Duel/store/` 입니다. 고쳤으면 여기로 복사해 푸시합니다.

```bash
cp Western-Duel/store/privacy.html <이 저장소>/index.html
cp Western-Duel/store/terms.html   <이 저장소>/terms.html
cp Western-Duel/store/refund.html  <이 저장소>/refund.html
git add -A && git commit -m "문서 갱신" && git push
```

## 이 저장소의 지난 내용

2026-10-01 이전에는 「십이지신 합체 게임」이 있었습니다. 더 쓰지 않게 되어 이 용도로 바꿨습니다.
지난 내용은 지워지지 않았습니다 — `git checkout 8f01478` 로 볼 수 있습니다.
