# 현준이 맞춤 말하기 연습 — 간편 앱(PWA)

Play Store 없이, 갤럭시 탭 홈 화면에 앱처럼 설치해서 쓰는 버전입니다.
한 번 열고 나면 인터넷 없이도 열립니다.

## 올리는 법 (GitHub Pages, 10분)

1. github.com 에 로그인 → New repository → 이름 `hyunjun-speak` → Public → Create
2. "uploading an existing file" 클릭 → 이 폴더 안의 파일 전부(`index.html`, `manifest.json`, `sw.js`, `icons` 폴더)를 끌어다 놓기 → Commit
3. 저장소 Settings → Pages → Branch: `main`, 폴더 `/ (root)` → Save
4. 1~2분 뒤 `https://<아이디>.github.io/hyunjun-speak/` 주소가 생깁니다.

## 갤럭시 탭에 설치

1. Chrome으로 위 주소를 엽니다.
2. 화면 아래 "앱처럼 쓰기 → 추가" 버튼을 누르거나, Chrome 메뉴(⋮) → **홈 화면에 추가**.
3. 홈 화면의 "말하기 연습" 아이콘으로 엽니다. 주소창 없이 전체 화면으로 열립니다.

## 내용 바꾸기

`index.html` 안의 `PACKS` 배열이 상황 데이터입니다. 상황을 추가하거나 바꾼 뒤 같은 파일을 다시 올리면 됩니다.
`sw.js`의 `CACHE` 이름을 `hj-speak-v2`처럼 바꿔야 설치된 탭에서 새 버전이 받아집니다.
