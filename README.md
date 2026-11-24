# dlgycjf90-maker.github.io

캠순이(https://dlgycjf90-maker.github.io/camsuni/)의 **같은 주소 로그인 도우미**를 두는 곳입니다.

- `__/auth/` — Firebase Authentication 이 제공하는 로그인 도우미 파일(handler·iframe)의 사본. Firebase 안내
  "Best practices for using signInWithRedirect on browsers that block third-party storage access — 방법 3: 도우미 코드를 직접 호스팅"을 따른 것입니다.
  원본: `https://camsuni.firebaseapp.com/__/auth/{handler,handler.js,experiments.js,iframe,iframe.js}` (© Google). 고치지 않고 그대로 두었습니다.
- `index.html` — 이 주소로 오면 캠순이로 보냅니다.
- `.nojekyll` — `__` 로 시작하는 폴더도 게시되게 합니다.

도우미 파일은 Firebase 가 바꿀 수 있으니 로그인이 이상하면 위 원본에서 다시 받아 바꿉니다.
