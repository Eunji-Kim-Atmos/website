# Eunji Kim — Modern Minimal Academic Website (v7)

**Quarto + GitHub Pages** 기반의 영문 반응형 연구자 홈페이지입니다.

## 구성

- **Home**: 연구자 소개와 프로필 사진만 표시 (01–03 하단 섹션 제거)
- **About Me**: 지도교수 Scholar 링크, 공주대·UNIST 학력, 수상 3건, 2021–2026년 1저자 학회 발표 23건, CV 다운로드 영역
- **Research**: Tropical Cyclone Rainfall / Seasonal Prediction / Regional Modeling
- **Publications**: Google Scholar 연결 및 논문 목록 공간
- **Photos**: 제공된 콜로라도 스프링스 사진 및 추후 사진 추가 공간

## v7에서 변경된 내용

- **About Me > Research Methods**에서 `Storm-centered Composites`를 삭제하고 `Dynamical Downscaling`을 추가했습니다.
- Research, Publications, Photos 등의 **페이지 제목 바로 아래 소개 문단**을 삭제했습니다. Home의 자기소개는 유지합니다.
- **Research**의 `Genesis potential`을 `Genesis Potential Index`로 바꾸고 `Tropical Cyclone Tracking`을 Prediction 키워드에 추가했습니다.
- Rainfall의 `Storm-centered analysis` 키워드는 `Rainfall Structure`로 교체했습니다.
- Research 하단을 `Methods & Programs` 키워드 태그로 바꾸고 `Storm-centered Composites`와 satellite 표현을 제거했으며 `CORDEX`를 마지막에 추가했습니다.
- 원본 Quarto 파일과 `preview/` 미리보기를 모두 업데이트했습니다.
- **실제 공개 링크 생성 안내**를 `PUBLISH_GITHUB.md`에 별도로 넣었습니다. 기존 연결된 GitHub 사용자명은 `Eunji-Kim-Atmos`이며, 아직 `academic-website` 저장소가 없으므로 홈페이지는 **미게시 상태**입니다.

## v6에서 변경된 내용

- About Me 페이지 제목 아래 소개 문단 삭제
- `A little about my work` 섹션과 중복 자기소개 문단 삭제
- 교수님 Google Scholar 링크는 제거하지 않고 Education의 지도교수 이름에 연결
- Education의 `Graduate Studies`를 없애고 `Ph.D. Candidate`만 표기
- Research Methods에서 서술형 문장을 없애고 `Methods`와 `Models & Tools` 키워드 태그로 변경
- `Satellite` 항목은 제외하고 `NCL`, `GrADS`, `Fortran`을 추가
- Quarto 원본, 정적 HTML 미리보기, 두 CSS 파일을 동기화

## v5에서 변경된 내용

- 첨부된 `김은지 대학원 학회 발표.docx`의 발표 이력을 기준으로 **김은지 / Eunji Kim이 첫 번째 저자인 학회 발표 23건(2021–2026)**을 About Me의 Conference Presentations에 추가했습니다.
- 다른 연구자가 첫 저자인 공동저자 발표 및 **2026 Next Generation Atmospheric Environment Modeling Workshop** 발표는 제외했습니다.
- 연도별 접기/펼치기 형태로 구성해 긴 목록을 보기 쉽게 정리했습니다. 2025·2026년은 기본 펼침, 이전 연도는 선택해서 열 수 있습니다.
- 발표 제목과 학회명은 제공 문서의 원문 언어를 유지했습니다. 발표 유형만 `Oral`, `Poster`, `Short oral`로 통일했습니다.
- 2024년 수상의 기관 표기는 `Korean Society of Climate Change Research`로 변경해 괄호 안 한글을 제거했습니다.
- Quarto 원본(`about.qmd`)과 독립 미리보기(`preview/about.html`), 스타일 파일을 함께 갱신했습니다.

## v4에서 변경된 내용

- Home의 01/Research interests, 02/How I work, 03/Beyond research 영역 삭제 — 소개와 사진만 유지
- About Me의 지도교수 **Professor Dong-Hyun Cha**의 Scholar 링크를 `user=1NXNPmUAAAAJ`로 변경 (학생 Scholar와 구별)
- Education: 공주대 2017.03–2021.02 학사 / UNIST 2021.03–현재 대학원 과정 반영
- Awards & Honors: 2024, 2023, 2022 수상 내역 3건 반영
- Quarto 원본과 `preview/` 정적 HTML 모두 동일 내용으로 갱신

## v3에서 변경된 내용

- 왼쪽 상단 사이트 이름을 `Eunji Kim.` → `Eunji Kim`으로 수정
- Home의 `Atmospheric & Climate Science`, `Weather. Climate. Possibilities.`, 하단 키워드(`Based in South Korea` 등), 사진 위 About me 상자 제거
- 첫 화면의 영문 소개를 확장하고 `Ulsan National Institute of Science and Technology (UNIST)` 정식 명칭 및 `Professor Dong-Hyun Cha` 지도 사실 반영
- 메뉴를 `Home / About Me / Research / Publications / Photos`로 변경
- 이전 `CV` 및 `Contact` 메뉴를 제거하고 CV/이력 관련 정보를 About Me로 통합
- Photos에 사용자가 제공한 원본 사진(최적화본) 추가
- `preview/`의 **5개 정적 HTML 페이지**도 함께 업데이트

## 반드시 나중에 채워야 하는 정보

교육 이력과 수상 3건, 학회 발표 23건은 제공된 정보대로 기재했습니다. **학회 발표 세부 정보**는 2021–2026년 자료에서 1저자 발표 23건을 반영했습니다. **실제 CV PDF**는 제공되지 않았으므로 자리표시자를 유지했습니다. UNIST 항목은 재학 시작일만 명시했고, 취득 여부가 확인되지 않은 학위를 기재하지 않았습니다.

**CV 다운로드:** 실제 CV PDF를 받지 않았으므로 작동하지 않는 다운로드 버튼을 만들지 않았습니다. 현재 사이트에서는 `CV PDF · Coming soon`으로 표시됩니다. 이후 아래 순서로 활성화하세요.

1. 프로젝트 폴더에 `files/`를 만들고 `files/Eunji_Kim_CV.pdf`를 저장
2. `_quarto.yml`의 `project.resources`에 `- files/**` 추가
3. `about.qmd`의 CV 섹션에서 안내 주석을 참고하여 `<span class="cv-unavailable">...</span>`을 `<a class="btn-primary-site" href="files/Eunji_Kim_CV.pdf" download>Download CV (PDF) ↧</a>`로 교체
4. `quarto render` 또는 push하여 사이트에 반영

## 확인하기

**Quarto 설치 전:** 압축을 푼 뒤 `preview/index.html`을 웹 브라우저에서 열면 Home, About Me, Research, Publications, Photos를 로컬에서 모두 볼 수 있습니다.

**Quarto 사용:** 프로젝트 폴더에서 아래 명령을 실행하세요.

```bash
quarto preview
```

사이트 빌드만 하려면:

```bash
quarto render
```

이 환경에는 Quarto CLI가 없어 실제 `quarto render`를 실행 검증할 수 없었습니다. HTML 미리보기와 내부 링크는 별도로 테스트했습니다.

## GitHub Pages 배포

1. GitHub에 공개 저장소 `academic-website`를 생성합니다. (현재 미생성; 상세 설명은 `PUBLISH_GITHUB.md` 참조)
2. 폴더에서 다음 명령을 실행합니다. `Eunji-Kim-Atmos`을 GitHub 사용자명으로 교체하세요.

```bash
git init
git add .
git commit -m "Publish academic website v7"
git branch -M main
git remote add origin https://github.com/Eunji-Kim-Atmos/academic-website.git
git push -u origin main
```

3. **Actions** 탭에서 `Publish Quarto website` 실행 완료 여부를 확인합니다.
4. **Settings → Pages → Build and deployment**에서 **Deploy from a branch → gh-pages → /(root)**를 선택합니다.
5. 사이트 주소는 `https://Eunji-Kim-Atmos.github.io/academic-website/` 형식입니다.

기존 GitHub 저장소를 이미 연결했다면 파일 교체 후 `git add . && git commit -m "Update website v7" && git push`면 됩니다.

`Resource not accessible by integration` 오류 발생 시 **Settings → Actions → General → Workflow permissions**에서 `Read and write permissions` 설정을 확인하세요.

## 직접 수정할 파일

- `_quarto.yml` — 메뉴, 사이트 이름과 설정
- `index.qmd` — 홈 소개 문구
- `about.qmd` — 학력·수상·학회·CV 다운로드
- `research.qmd` — 세부 연구 분야
- `publications.qmd` — 논문 제목·DOI
- `photos.qmd` — 사진 갤러리
- `styles.css` — 반응형 CSS 및 색상
- `images/eunji-profile.jpg` — Home 프로필 이미지
- `images/eunji-photo-original.jpg` — Photos 갤러리 이미지
- `.github/workflows/publish.yml` — GitHub 자동 배포 설정

## 참고

- [Quarto Websites](https://quarto.org/docs/websites/)
- [Quarto GitHub Pages](https://quarto.org/docs/publishing/github-pages.html)
