# 도화서 (圖畵署)

조선 시대 그림을 맡아 그리던 관서에서 이름을 따왔습니다. Claude와 함께 만든 시각 작업물(three.js 애니메이션, 3D 모형, 디오라마)을 보관하는 저장소입니다. 참조 문서를 모으는 [규장각](https://github.com/neosdc/kyujanggak)과 짝을 이루고, 화면 보호기는 [screensaver](https://github.com/neosdc/screensaver)에서 따로 관리합니다.

## 작업물

GitHub Pages에서 바로 볼 수 있습니다: <https://neosdc.github.io/dohwaseo/>

각 폴더의 `index.html`이 원본이고, 폴더 안 `README.md`에 보는 법과 구성이 있습니다.

| 폴더 | 내용 | 보기 |
|---|---|---|
| [`home-84a/`](home-84a/) | 우리 집 84A 3D 모형 (three.js) | [Pages](https://neosdc.github.io/dohwaseo/home-84a/) |
| [`coffee-shop/`](coffee-shop/) | 베이커리·로스터리 카페 경영 게임풍 3D 디오라마 (three.js) | [Pages](https://neosdc.github.io/dohwaseo/coffee-shop/) |
| [`haneul/`](haneul/) | 우주선 한울호 단면 3D 디오라마 (three.js) | [Pages](https://neosdc.github.io/dohwaseo/haneul/) |

## 규칙

- 작업물 하나당 폴더 하나, 폴더마다 `index.html`(원본)과 `README.md`를 둡니다.
- 새 작업물을 추가하면 위 표에 한 줄을 추가하고, 루트 `index.html`(Pages 첫 화면)의 목록에도 항목을 추가합니다.
- 브라우저로 `index.html`을 열면 실행됩니다. three.js와 웹 폰트를 CDN에서 불러오므로 인터넷 연결이 필요합니다.
- GitHub Pages는 `main` 브랜치의 루트(`/`)를 그대로 게시합니다. 루트의 `.nojekyll`은 Jekyll 처리를 끄는 파일이니 지우지 않습니다.
