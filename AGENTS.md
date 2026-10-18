# 저장소 메모 (Codex 등 에이전트용)

## 13 사이트 배포 주소 (Vercel)

- 제품: 브라우저에서 하는 5대5 전술 FPS, 제품명 **13**
- 현재 주소: https://13fps.vercel.app/
- Vercel 프로젝트: 이름 `13fps`, id `prj_864Ai6cINJIuv0CeRp7lVYCxA8T0`, team `team_dimm5OCcxhmGfo5mIi5unvR3`
- 기존 주소 https://lotus-garden-protocol.vercel.app/ 도 같은 프로젝트에 연결되어 있어서 지금도 열립니다. 끊으려면 프로젝트 도메인에서 제거하면 되며, 아직 제거하지 않았습니다.
- https://13.vercel.app/ 은 다른 팀 프로젝트가 쓰고 있어서 붙일 수 없습니다 (409 `owned-on-other-team`).
- 이름 변경 이력 (2026-10-18): `lotus-garden-protocol` → `13` → `13fps`
  - 프로젝트 이름을 바꿔도 기존 도메인은 남습니다.
  - 새 이름의 `.vercel.app` 도메인은 자동으로 붙지 않을 수 있으니, 바꾼 뒤 도메인을 붙이고 주소를 curl로 확인하세요.

## 홍보 영상

- 위치: `motion-graphics/site-promo/` (HyperFrames 프로젝트, 21.5초, 1920×1080)
- 마무리 화면 주소는 `index.html`의 `#url` 텍스트입니다. 현재 `13fps.vercel.app`입니다. 주소를 바꾸면 여기도 같이 바꾸고 다시 렌더링하세요.
- 렌더: `npx hyperframes render -o renders/site-promo.mp4` (Chrome 경로가 없으면 `HYPERFRAMES_BROWSER_PATH`를 지정하거나 `npx hyperframes browser`를 실행하세요.)
- `renders/`와 `.hyperframes/`는 git에서 제외되어 있습니다.

## 작업 브랜치

- `ccr-7ee26181-xpxdgw`
