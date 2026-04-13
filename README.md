# Student Consultation Registration Mockup

학생 상담 등록 화면 시안입니다.

이 프로젝트는 단일 정적 HTML 파일로 구성되어 있으며, 아래 내용을 포함합니다.

- 학생 상담 등록 메인 화면
- 학생 조회 영역 접기/펼치기 인터랙션
- 시험 정보 상세 모달
- 신규 학생 등록 대형 모달

## Files

- `index.html`: 메인 시안 파일

## How To Preview

### Option 1. Open directly

브라우저에서 `index.html` 파일을 직접 열면 됩니다.

### Option 2. Run a local server

간단한 로컬 서버로 확인하려면 아래 명령을 사용할 수 있습니다.

```bash
python3 -m http.server 8000
```

그 다음 브라우저에서 아래 주소로 접속합니다.

```text
http://localhost:8000
```

## Upload To GitHub

### 1. Create a new repository on GitHub

예: `student-consultation-mockup`

### 2. Initialize git in this folder

```bash
git init
git add .
git commit -m "Add student consultation registration mockup"
```

### 3. Connect the remote repository

```bash
git branch -M main
git remote add origin https://github.com/YOUR_ID/YOUR_REPOSITORY.git
git push -u origin main
```

## Deploy As A Static Site

GitHub Pages, Netlify, Vercel 같은 정적 호스팅으로 바로 배포할 수 있습니다.

이 프로젝트는 루트에 `index.html`이 있기 때문에 추가 빌드 과정 없이 배포가 가능합니다.
