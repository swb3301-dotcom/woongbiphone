# 웅비통신 덕천만덕점 홈페이지

미니멀 디자인의 휴대폰 매장 홈페이지입니다.

## 기술 스택

- HTML5
- CSS3
- Vanilla JavaScript

## 파일 구조

```
├── index.html          # 메인 HTML 파일
├── style.css          # 스타일시트
├── script.js          # JavaScript 파일
├── images/            # 이미지 폴더
│   ├── KakaoTalk_20251201_123246956_01.jpg  # 매장 외부 전경
│   └── KakaoTalk_20251201_123246956_02.jpg  # 매장 내부
└── README.md          # 이 파일
```

## 로컬에서 실행하기

1. `index.html` 파일을 브라우저에서 직접 열기
2. 또는 로컬 서버 실행:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (http-server 설치 필요)
   npx http-server
   ```

## GitHub Pages 배포 방법

### 1. Git 설치
- Windows: https://git-scm.com/download/win 에서 다운로드
- 설치 후 터미널을 재시작

### 2. GitHub 저장소 생성
1. GitHub (https://github.com)에 로그인
2. 새 저장소 생성 (예: `woongbi-telecom`)
3. 저장소 이름 입력 후 "Create repository" 클릭

### 3. Git 사용자 정보 설정 (최초 1회만)
```bash
# 사용자 이름 설정
git config --global user.name "신웅비"

# 이메일 설정
git config --global user.email "swb3301@gmail.com"

# 설정 확인
git config --global user.name
git config --global user.email
```

### 4. Git 초기화 및 커밋
```bash
# Git 초기화
git init

# 파일 추가
git add .

# 커밋
git commit -m "Initial commit: 웅비통신 덕천만덕점 홈페이지"

# GitHub 저장소 연결 (YOUR_USERNAME과 YOUR_REPO_NAME을 실제 값으로 변경)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# 브랜치 이름을 main으로 설정
git branch -M main

# GitHub에 푸시
git push -u origin main
```

### 5. GitHub Pages 활성화
1. GitHub 저장소 페이지로 이동
2. Settings 탭 클릭
3. 왼쪽 메뉴에서 "Pages" 클릭
4. Source에서 "Deploy from a branch" 선택
5. Branch를 "main" 선택, 폴더는 "/ (root)" 선택
6. Save 클릭

### 6. 배포 확인
- 몇 분 후 `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME` 주소로 접속 가능

## 연락처

- 전화: 051-343-7677, 010-3267-4824
- 위치: 부산광역시 북구 만덕대로178번길 17
- 영업시간: 오전 11:00 - 오후 8:00

