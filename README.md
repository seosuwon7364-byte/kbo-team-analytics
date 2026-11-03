

\# KBO TEAM ANALYTICS



KBO 10개 구단의 팀 성적과 경기 데이터를 분석하기 위한 개인 포트폴리오 웹사이트입니다.



\## 1. 프로젝트 소개



야구 데이터 분석과 구단 전력 분석에 대한 관심을 바탕으로 제작한 개인 포트폴리오입니다.



Hugo 정적 웹사이트 생성기를 이용해 사이트를 구축하고, GitHub Actions를 통해 GitHub Pages에 자동 배포합니다.



\- 웹사이트: https://seosuwon7364-byte.github.io/kbo-team-analytics/

\- GitHub 저장소: https://github.com/seosuwon7364-byte/kbo-team-analytics



\## 2. 주요 페이지



\### HOME

프로젝트 소개와 주요 분석 주제를 보여주는 메인 페이지입니다.



\### TEAM ANALYSIS

KBO 10개 구단의 타격, 투수, 수비 지표를 비교하기 위한 분석 계획을 소개합니다.



\### GAME ANALYSIS

이닝별 득점, 홈·원정 경기, 선취점과 승리의 관계 등을 분석하기 위한 계획을 소개합니다.



\### ABOUT ME

관심 분야, 기술 역량, 포트폴리오 제작 과정 및 학습 목표를 소개합니다.



\## 3. 사용 기술



\- Hugo

\- HTML / CSS

\- Git / GitHub

\- GitHub Actions

\- GitHub Pages



\## 4. 프로젝트 진행 상태



\- Hugo 웹사이트 구축: 완료

\- GitHub Pages 자동 배포: 완료

\- 홈페이지 및 분석 소개 페이지: 완료

\- 디자인 및 접근성 개선: 진행 중

\- 실제 KBO 데이터 수집 및 분석: 진행 예정



현재 표시된 분석 프로젝트의 이미지와 그래프는 소개용 시각 자료이며, 실제 KBO 데이터 분석 결과를 의미하지 않습니다.





\## 5. 개발 환경



이 프로젝트는 Hugo 정적 웹사이트 생성기를 사용하여 제작했습니다.



\### 사용 도구



\- 운영체제: Windows

\- Hugo: v0.143.0 Extended

\- Git 및 GitHub

\- GitHub Actions

\- GitHub Pages

\- HTML / CSS



GitHub Actions에서는 Hugo v0.143.0 Extended를 설치하여 사이트를 빌드합니다.



\## 6. 설치 및 실행 방법



\### 1. 저장소 복제



```powershell

git clone https://github.com/seosuwon7364-byte/kbo-team-analytics.git

cd kbo-team-analytics

```



\### 2. Hugo 설치



로컬에서 실행하려면 Hugo Extended v0.143.0을 설치해야 합니다.



공식 다운로드:

https://github.com/gohugoio/hugo/releases/tag/v0.143.0



Windows에 맞는 Extended 버전을 다운로드하고, hugo.exe가 포함된 폴더를 PATH에 등록합니다.



설치 확인:



```powershell

hugo version

```



\### 3. 로컬 서버 실행



```powershell

hugo server

```



브라우저에서 다음 주소로 접속합니다.



http://localhost:1313/kbo-team-analytics/



로컬 미리보기에서 일부 이미지는 배포된 GitHub Pages URL을 참조할 수 있습니다.



\### 4. 정적 사이트 빌드



```powershell

hugo --minify

```



빌드에 성공하면 public 폴더에 배포용 파일이 생성됩니다.



\### 5. GitHub Actions 빌드



로컬에 Hugo가 설치되지 않아도 GitHub Actions에서 자동으로 빌드할 수 있습니다.



워크플로 파일:



.github/workflows/hugo.yaml



main 브랜치에 변경 사항을 push하면 GitHub Actions가 Hugo 사이트를 빌드하고 GitHub Pages에 배포합니다.





\## 7. 주요 파일 및 수정 위치



웹사이트의 주요 설정과 콘텐츠는 다음 파일에서 관리합니다.



| 파일 및 폴더 | 역할 |

|---|---|

| `hugo.yaml` | 사이트 제목, 메뉴, 자기소개, 프로젝트 설정 |

| `content/team-analysis.md` | KBO 10개 구단 전력 분석 소개 |

| `content/game-analysis.md` | KBO 경기 흐름 분석 소개 |

| `static/style.css` | 글씨체, 카드 디자인, 반응형 CSS |

| `static/images/` | 홈페이지 및 프로젝트 이미지 |

| `themes/template/` | Hugo 테마 파일 |

| `.github/workflows/hugo.yaml` | GitHub Actions 자동 배포 설정 |



사이트 내용을 수정할 때는 해당 파일을 편집하고 저장합니다.



\## 8. 수정 사항 배포 방법



\### 1. 변경 파일 확인



```powershell

git status

```



\### 2. 변경 사항 커밋



수정한 파일만 지정해서 추가합니다.



```powershell

git add README.md

git commit -m "Update project documentation"

```



실제 작업에서는 변경 내용에 맞게 파일 이름과 커밋 메시지를 수정합니다.



\### 3. GitHub에 업로드



```powershell

git push origin main

```



\### 4. GitHub Actions 확인



다음 주소에서 가장 최근 워크플로 실행을 확인합니다.



https://github.com/seosuwon7364-byte/kbo-team-analytics/actions



\- Build 작업 성공 여부 확인

\- Deploy 작업 성공 여부 확인

\- 실패 시 실행 로그를 통해 오류 확인



\### 5. 공개 사이트 확인



https://seosuwon7364-byte.github.io/kbo-team-analytics/



브라우저에서 Ctrl + Shift + R로 새로고침한 뒤 다음 항목을 확인합니다.



\- 수정한 내용이 반영되는지

\- 이미지가 정상적으로 표시되는지

\- TEAM ANALYSIS와 GAME ANALYSIS 페이지가 열리는지

\- 모바일 화면에서 레이아웃이 깨지지 않는지



최종 제출 시에는 GitHub의 main 브랜치에 있는 커밋과 GitHub Actions 배포 결과가 일치하는지 확인합니다.

