# 웹사이트 올리기용 폴더

이 폴더의 `index.html`이 GitHub Pages에 올리는 팀원용 요약판(메카넘 모션제어 한눈에)이다.

- 원본: `docs/team_guide/summary_track.html`
- 다시 만들기 (프로젝트 루트에서):
  `python3 docs/team_guide/make_standalone.py docs/team_guide/vendor/three.min.js --src summary_track.html --out site/index.html`
- 사진은 파일 안에 들어 있어서 `index.html` 하나만 올리면 된다.
- 검색 엔진에 뜨지 않도록 `noindex` 표시가 들어 있다. 링크를 아는 사람만 볼 수 있다.
- 부품 사진(Jetson·Arduino·모터 드라이버·IMU)은 판매처 제품 사진이다. 공개 전에 사용 허락을 확인한다(`../assets/CREDITS.md`).
