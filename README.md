# Bungee local recreation — prototype

Responsive HTML/CSS/vanilla JavaScript study based on https://bungee.framer.website/.

## Run locally

Open `index.html` in a modern browser. All pages use hash-based routing, so they work without a server. Optionally, from this folder run `python3 -m http.server 5173` and visit `http://localhost:5173`.

## Implemented

- Home, Works and a representative THINGS® project detail page (plus other project routes using a shared template)
- About, Blog, Contact navigational stubs
- Fullscreen navigation, scroll-reveal, hover image zoom, custom cursor on desktop, FAQ accordion, testimonials slider, progress indicator, New York clock
- Responsive layouts for desktop/tablet/mobile; `prefers-reduced-motion` accommodation

## Important limits

- This is a **visual/functional approximation**, not the purchased Framer template, source code, or pixel-perfect clone.
- Due to external download restrictions, no third-party media was downloaded. Two public `framerusercontent.com` URLs are linked for illustrative use while online; when offline these assets will not appear and the CSS/typographic backup should be used.
- Additional work is needed to map every original media asset, obtain usage rights, reproduce exact motion timing and verify screenshot parity across breakpoints.
- Blog/About/Contact pages are navigable placeholders, not full original-page clones.
- Forms are demonstration UI and **do not submit data** to a server.
- Original creator's template has a single-use license. Verify rights before distributing or publishing this recreation and its source media.

No build process or dependency installation required.


## 버전_02 상세 페이지 수정 (2026-11-22)
- 프로젝트 상세 페이지(`/projects/things` 등): 데스크톱에서 **왼쪽 설명 sticky 고정**, 오른쪽 프로젝트 이미지 및 소개가 일반 페이지 스크롤로 이동합니다.
- 모바일(760px 이하): 좌측 고정 해제 후 한 열로 표시되어 본문/이미지를 순서대로 볼 수 있습니다.
- 원본 미디어 전체가 로컬에 포함된 것은 아닙니다. 초기 프로토타입의 외부 이미지 URL과 대체 그래픽이 그대로 사용됩니다.
- 버전_01은 수정 대상이 아닙니다. 이 파일들을 사용자의 `버전_02` 폴더에 덮어쓰기 전에 백업하세요.
