# 나만의 포트폴리오 만들기

GitHub Pages를 이용해 무료로 자기소개 웹사이트를 만드는 방법을 안내합니다.

코딩을 몰라도 괜찮습니다. 이 폴더의 파일을 복사해서 내용만 바꾸면 됩니다.

---

## 전체 흐름

```
1. GitHub 가입  →  2. 저장소 만들기  →  3. 파일 올리기  →  4. 내용 바꾸기  →  5. 완성!
```

---

## Step 1. GitHub 가입하기

### 1-1. github.com에 접속합니다

[github.com](https://github.com)에 접속하면 아래와 같은 화면이 나옵니다.

![GitHub 메인 화면](images/step1-1-github-home.png)

### 1-2. Sign up 클릭

오른쪽 위의 **Sign up** 버튼을 클릭합니다.

![Sign up 버튼](images/step1-2-signup-button.png)

### 1-3. 이메일 입력

이메일 주소를 입력합니다. 학교 메일을 사용하면 나중에 GitHub Student Pack 혜택을 받을 수 있습니다.

![이메일 입력](images/step1-3-email.png)

### 1-4. 비밀번호 설정

비밀번호를 설정합니다.

![비밀번호 설정](images/step1-4-password.png)

### 1-5. 사용자 이름(username) 정하기

> **사용자 이름이 곧 내 웹사이트 주소가 됩니다!**
>
> 예: 사용자 이름이 `hong-gildong`이면
> 내 포트폴리오 주소는 `https://hong-gildong.github.io`

![사용자 이름 입력](images/step1-5-username.png)

**username 정하기 팁**
- 본명 또는 본명의 변형을 추천합니다
- 영어 소문자와 하이픈(-)만 사용 가능
- 예: `gildong-hong`, `youngsook-s`, `minjae-kim`

### 1-6. 이메일 인증

입력한 이메일로 인증 코드가 옵니다. 코드를 입력하면 가입 완료!

![이메일 인증](images/step1-6-verify.png)

---

## Step 2. 저장소(Repository) 만들기

저장소는 파일을 보관하는 폴더라고 생각하면 됩니다.

### 2-1. New repository 클릭

로그인한 상태에서 오른쪽 위 **+** 버튼 → **New repository**를 클릭합니다.

![New repository](images/step2-1-new-repo.png)

### 2-2. 저장소 이름 입력

**Repository name**에 `username.github.io`를 입력합니다.

반드시 본인의 사용자 이름을 넣어야 합니다.
예: 사용자 이름이 `hong-gildong`이면 → `hong-gildong.github.io`

![저장소 이름 입력](images/step2-2-repo-name.png)

### 2-3. 설정 선택

- **Public** 선택 (공개)
- **Add a README file** 체크

![설정 선택](images/step2-3-repo-settings.png)

### 2-4. Create repository 클릭

**Create repository** 버튼을 클릭합니다.

![Create repository](images/step2-4-create-repo.png)

### 2-5. 저장소 생성 완료

아래와 같은 화면이 나오면 저장소가 만들어진 것입니다.

![저장소 생성 완료](images/step2-5-repo-created.png)

---

## Step 3. 이 템플릿 파일 올리기

이 폴더에 있는 `index.html`과 `style.css`를 내 저장소에 올립니다.
이 두 파일이 포트폴리오의 전부입니다. `index.html`은 내용, `style.css`는 디자인을 담당합니다.

### 3-1. Upload files 클릭

저장소 메인 페이지에서 초록색 **Code** 버튼 옆에 있는 **Add file** 버튼을 찾습니다.
**Add file**을 클릭하면 드롭다운 메뉴가 나타나는데, 여기서 **Upload files**를 선택합니다.

![Upload files](images/step3-1-upload-files.png)

### 3-2. 파일 드래그

파일 업로드 화면이 나타나면 점선 테두리 영역이 보입니다.
미리 다운로드해 둔 `index.html`과 `style.css` 파일을 이 영역에 **드래그 앤 드롭**합니다.

파일을 드래그하면 영역이 파란색으로 바뀌면서 "Drop to upload your files"라고 표시됩니다.
놓으면 파일 이름이 목록에 나타납니다.

> **파일은 어디서 받나요?**
> 이 저장소의 `portfolio-template` 폴더에서 `index.html`과 `style.css`를 각각 클릭한 뒤,
> 오른쪽 위 다운로드 버튼(↓)을 눌러 내 컴퓨터에 저장합니다.

![파일 드래그](images/step3-2-drag-files.png)

### 3-3. Commit changes 클릭

파일이 목록에 나타난 것을 확인했으면 아래로 스크롤합니다.
**Commit changes** 영역이 보이는데, 메시지는 기본값 그대로 두어도 됩니다.

초록색 **Commit changes** 버튼을 클릭하면 파일이 저장소에 올라갑니다.

> **Commit이란?**
> "이 변경 사항을 확정합니다"라는 뜻입니다. 저장 버튼이라고 생각하면 됩니다.
> Commit할 때마다 변경 이력이 기록되므로, 나중에 실수해도 이전 상태로 돌아갈 수 있습니다.

![Commit changes](images/step3-3-commit.png)

### 3-4. 업로드 완료

저장소 메인 페이지로 돌아오면 파일 목록에 `index.html`과 `style.css`가 보입니다.
두 파일이 모두 나타나면 업로드 성공입니다!

![업로드 완료](images/step3-4-uploaded.png)

---

## Step 4. GitHub Pages 켜기

GitHub Pages는 저장소에 올린 HTML 파일을 웹사이트로 자동 변환해주는 무료 서비스입니다.
이 기능을 켜면 `https://username.github.io` 주소로 누구나 내 포트폴리오에 접속할 수 있습니다.

### 4-1. Settings 클릭

저장소 메인 페이지 상단에 탭 메뉴가 나열되어 있습니다.
**Code**, **Issues**, **Pull requests** 등이 보이는데, 맨 오른쪽에 있는 **Settings** 탭을 클릭합니다.

> 탭이 화면에 다 보이지 않으면 `···` 버튼을 눌러 숨겨진 메뉴에서 찾을 수 있습니다.

![Settings 탭](images/step4-1-settings.png)

### 4-2. Pages 메뉴 클릭

Settings 페이지에 들어오면 왼쪽에 세로로 메뉴 목록이 나열되어 있습니다.
스크롤을 내려서 **Pages**를 찾아 클릭합니다.
"Code and automation" 카테고리 아래에 있습니다.

![Pages 메뉴](images/step4-2-pages-menu.png)

### 4-3. Branch 설정

Pages 설정 화면에서 아래 항목을 차례로 설정합니다:

1. **Source**: **Deploy from a branch** 선택 (기본값)
2. **Branch**: 드롭다운에서 **main** 선택
3. **폴더**: **/ (root)** 선택 (기본값)
4. **Save** 버튼 클릭

> **Branch가 None으로 되어 있으면** 드롭다운을 클릭해서 `main`을 선택하세요.
> Save 버튼이 비활성화되어 있다면 Branch를 먼저 선택해야 합니다.

![Branch 설정](images/step4-3-branch-setting.png)

### 4-4. 배포 확인

Save를 클릭한 뒤 **1~2분** 정도 기다립니다.
페이지를 새로고침하면 상단에 초록색 배경으로 사이트 URL이 나타납니다:

```
Your site is live at https://username.github.io/
```

이 URL이 바로 내 포트폴리오 주소입니다!

> 바로 나타나지 않으면 1~2분 후 페이지를 새로고침해 보세요.
> 처음 배포할 때는 시간이 조금 더 걸릴 수 있습니다.

![배포 완료](images/step4-4-deployed.png)

### 4-5. 사이트 접속 확인

표시된 URL을 클릭하거나, 브라우저 주소창에 `https://username.github.io`를 직접 입력합니다.
더미 내용이 담긴 포트폴리오 페이지가 나타나면 성공입니다!

스마트폰에서도 같은 주소로 접속해서 모바일 화면이 잘 나오는지 확인해 보세요.

![사이트 확인](images/step4-5-site-live.png)

---

## Step 5. 내 정보로 바꾸기

### 5-1. 파일 편집 모드 열기

저장소 메인 페이지의 파일 목록에서 `index.html`을 클릭합니다.
파일 내용이 화면에 표시되면, 오른쪽 위에 있는 **연필 아이콘** (✏️ Edit this file)을 클릭합니다.

연필 아이콘은 파일 내용 바로 위, 오른쪽 끝에 있습니다.
아이콘 위에 마우스를 올리면 "Edit this file"이라는 툴팁이 나타납니다.

클릭하면 파일 내용이 편집 가능한 텍스트 에디터로 바뀝니다.
왼쪽에 줄 번호가 표시되고, 직접 내용을 수정할 수 있습니다.

> **Ctrl+F (Mac: Cmd+F)** 를 누르면 검색창이 나타납니다.
> `홍길동`을 검색하면 바꿔야 할 위치를 빠르게 찾을 수 있습니다.

![편집 모드](images/step5-1-edit-file.png)

### 5-2. 더미 내용 수정하기

파일 안에 `✏️` 표시가 주석으로 들어가 있습니다. 이 표시가 있는 곳이 수정해야 할 부분입니다.
**Ctrl+F로 `✏️`를 검색**하면 수정 포인트를 하나씩 찾아갈 수 있습니다.

아래 표를 보고 더미 내용을 내 정보로 바꿉니다:

| 바꿀 항목 | 찾을 텍스트 | 바꿀 내용 | 위치 (줄 번호) |
|----------|-----------|----------|--------------|
| 페이지 제목 | `홍길동 포트폴리오` | 내 이름 + 포트폴리오 | 7번 줄 `<title>` |
| 이름 | `홍길동` | 내 이름 | 21번 줄 `<h1>` |
| 태그라인 | `글과 데이터 사이에서 이야기를 찾는 사람` | 나를 한 줄로 소개 | 22번 줄 |
| 전공 | `국어국문학과` | 내 전공 | 42, 63번 줄 |
| 자기소개 | `단국대학교 국어국문학과에...` | AI로 만든 자기소개 | 42~49번 줄 |
| 학교/학년 | `단국대학교`, `4학년` | 내 학교/학년 | 62~64번 줄 |
| 경험 | `글쓰기 센터 튜터`, `캡스톤 프로젝트` 등 | 내 경험 | 58~87번 줄 |
| 프로젝트 | `글쓰기 센터 튜터 활동` 등 | 내 프로젝트 | 96~124번 줄 |
| 기술 | `한국어 글쓰기`, `Python` 등 | 내 기술 | 131~168번 줄 |
| 이메일 | `gildong@example.com` | 내 이메일 | 195~198번 줄 |
| GitHub | `hong-gildong` | 내 GitHub 사용자 이름 | 199~202번 줄 |

**수정 순서 추천:**

1. **이름과 태그라인부터** — 가장 눈에 띄는 부분이므로 먼저 바꿉니다
2. **소개(about)** — 4주차에 AI로 만든 자기소개를 붙여넣습니다
3. **경험과 프로젝트** — 항목 수를 늘리거나 줄여도 됩니다. `timeline-item`이나 `project-card` 블록을 통째로 복사하거나 삭제하면 됩니다
4. **기술 태그** — `skill-tag` 안의 텍스트만 바꾸면 됩니다
5. **연락처** — 이메일과 GitHub 주소를 바꿉니다

> **한 번에 다 바꾸지 않아도 됩니다.**
> 이름과 소개만 먼저 바꾸고 Commit한 뒤, 나머지는 나중에 수정해도 괜찮습니다.
> Commit할 때마다 변경 이력이 남으므로 걱정 없이 시도해 보세요.

![내용 수정](images/step5-2-editing.png)

### 5-3. Commit changes 클릭

수정이 끝나면 오른쪽 위의 초록색 **Commit changes...** 버튼을 클릭합니다.
팝업 창이 나타나면:

1. **Commit message**: 기본값을 그대로 두거나, `내 정보로 수정`처럼 짧게 적습니다
2. **Commit directly to the main branch**: 이 옵션이 선택된 상태로 둡니다
3. **Commit changes** 버튼을 클릭합니다

> Step 3에서와 마찬가지로 Commit은 "저장" 버튼과 같습니다.
> Commit 메시지는 나중에 "이때 뭘 바꿨지?" 확인할 때 유용합니다.

![Commit changes](images/step5-3-commit-edit.png)

### 5-4. 완성!

Commit 후 **1~2분** 기다린 다음, `https://username.github.io` 주소로 접속합니다.
내 이름과 정보가 반영된 포트폴리오가 나타나면 성공입니다!

**확인할 것:**
- 이름과 태그라인이 헤더에 제대로 표시되는가?
- 소개 글이 정상적으로 보이는가?
- 스마트폰에서도 같은 주소로 접속해서 모바일 화면을 확인합니다
- 이메일 링크를 클릭하면 메일 앱이 열리는가?

> **변경이 반영되지 않으면** 브라우저에서 **Ctrl+Shift+R** (Mac: Cmd+Shift+R)로 강력 새로고침을 시도하세요.
> 브라우저가 이전 버전을 캐시에 저장하고 있을 수 있습니다.

![완성된 포트폴리오](images/step5-4-done.png)

---

## 확인 체크리스트

- [ ] PC 브라우저에서 접속 가능한가?
- [ ] 스마트폰에서도 잘 보이는가?
- [ ] 이름과 자기소개가 정확한가?
- [ ] 이메일 주소가 맞는가?
- [ ] 링크가 정상 작동하는가?

---

## 자주 묻는 질문

### Q: 수정했는데 웹사이트에 반영이 안 돼요
Commit 후 1~2분 정도 기다려 보세요. GitHub Pages는 반영에 약간의 시간이 걸립니다.

### Q: 페이지가 404 에러가 나요
- 저장소 이름이 정확히 `username.github.io`인지 확인하세요
- Settings → Pages에서 Source가 `main` 브랜치로 설정되어 있는지 확인하세요

### Q: 사진을 넣고 싶어요
1. 저장소에 `images` 폴더를 만들고 사진을 업로드합니다
2. `index.html`에서 프로필 이미지 부분의 주석을 해제하고 파일 이름을 입력합니다

### Q: 디자인을 바꾸고 싶어요
`style.css` 파일에서 색상과 폰트를 수정할 수 있습니다.
AI에게 "이 CSS에서 포인트 색상을 초록색으로 바꿔줘"라고 요청해 보세요.

### Q: 섹션을 추가하고 싶어요
AI에게 "이 HTML에 블로그 섹션을 추가해줘"라고 요청하면 코드를 만들어줍니다.

---

## 스크린샷 목록

캡처해야 할 이미지 목록입니다. `images/` 폴더에 아래 파일명으로 저장하세요.

| 파일명 | 캡처 내용 |
|--------|----------|
| `step1-1-github-home.png` | GitHub 메인 화면 |
| `step1-2-signup-button.png` | Sign up 버튼 위치 |
| `step1-3-email.png` | 이메일 입력 화면 |
| `step1-4-password.png` | 비밀번호 설정 화면 |
| `step1-5-username.png` | 사용자 이름 입력 화면 |
| `step1-6-verify.png` | 이메일 인증 화면 |
| `step2-1-new-repo.png` | + → New repository 메뉴 |
| `step2-2-repo-name.png` | 저장소 이름 입력 |
| `step2-3-repo-settings.png` | Public + Add README 설정 |
| `step2-4-create-repo.png` | Create repository 버튼 |
| `step2-5-repo-created.png` | 저장소 생성 완료 화면 |
| `step3-1-upload-files.png` | Add file → Upload files 메뉴 |
| `step3-2-drag-files.png` | 파일 드래그 영역 |
| `step3-3-commit.png` | Commit changes 버튼 |
| `step3-4-uploaded.png` | 파일 업로드 완료 화면 |
| `step4-1-settings.png` | Settings 탭 위치 |
| `step4-2-pages-menu.png` | Pages 메뉴 위치 |
| `step4-3-branch-setting.png` | Branch를 main으로 설정 |
| `step4-4-deployed.png` | 배포 완료 URL 표시 |
| `step4-5-site-live.png` | 실제 사이트 접속 화면 |
| `step5-1-edit-file.png` | 연필 아이콘(편집) 위치 |
| `step5-2-editing.png` | 내용 수정 중 화면 |
| `step5-3-commit-edit.png` | 수정 후 Commit 화면 |
| `step5-4-done.png` | 완성된 포트폴리오 화면 |

---

## 파일 구성

```
portfolio-template/
├── README.md          ← 지금 읽고 있는 안내서
├── index.html         ← 포트폴리오 메인 페이지 (이것만 올려도 됨)
├── style.css          ← 디자인 파일
└── images/            ← 스크린샷 + 프로필 사진을 넣을 폴더
    ├── step1-1-github-home.png
    ├── step1-2-signup-button.png
    ├── ...
    └── step5-4-done.png
```

