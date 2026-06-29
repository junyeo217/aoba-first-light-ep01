# 青葉 첫빛 ep01 GitHub Pages

이 폴더는 Mina 예시처럼 GitHub Pages 저장소 루트에 그대로 올리는 정적 웹툰 페이지입니다.

## 포함 파일

- `index.html`: 공개용 웹툰 뷰어
- `panels/`: 1화 패널 이미지 54장
- `.nojekyll`: GitHub Pages의 Jekyll 처리를 비활성화

## GitHub Pages 설정

1. GitHub에서 새 저장소를 만듭니다. 예: `aoba-first-light-ep01`
2. 이 폴더 안의 파일들을 저장소 루트에 올립니다.
   - `index.html`
   - `panels/`
   - `.nojekyll`
   - `README.md`
3. GitHub 저장소의 `Settings` > `Pages`로 이동합니다.
4. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
5. Branch는 `main`, Folder는 `/root`로 설정합니다.
6. 저장 후 표시되는 Pages URL로 접속합니다.

예상 URL 형식:

```text
https://junyeo217.github.io/aoba-first-light-ep01/
```

저장소 이름을 다르게 만들면 URL의 마지막 경로도 그 저장소 이름으로 바뀝니다.

## 참고

기존 프로젝트의 `docs/`는 이 프로젝트 내부에서 확인하기 위한 Pages 소스 폴더입니다.
Mina 예시와 같은 별도 공개 저장소를 만들 때는 이 `_deploy/aoba-first-light-ep01/` 폴더의 내용을 저장소 루트에 올리면 됩니다.
