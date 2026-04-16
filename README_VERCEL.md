# Vercel Deployment

이 폴더는 정적 HTML 리포트 배포용으로 구성되어 있습니다.

## 포함 내용

- `index.html`: Vercel 기본 진입 페이지
- `mlbkids_season_pl_report.html`: 원본 리포트 파일
- `vercel.json`: 정적 배포 설정

## 배포 방법

### 1. Vercel 웹에서 배포

1. [Vercel New Project](https://vercel.com/new)로 이동
2. `Import Third-Party Git Repository` 또는 `Browse`로 이 폴더 업로드
3. Framework Preset은 `Other` 선택
4. Build Command 비우기
5. Output Directory 비우기
6. Deploy 실행

### 2. Vercel CLI로 배포

```powershell
npm install -g vercel
vercel
vercel --prod
```

프로젝트 설정 질문이 나오면 아래처럼 선택하면 됩니다.

- Set up and deploy: `Y`
- Which scope: 본인 계정 선택
- Link to existing project: `N` 또는 기존 프로젝트 선택
- Project name: 원하는 이름 입력
- In which directory is your code located: `.`
- Want to modify settings: `N`
