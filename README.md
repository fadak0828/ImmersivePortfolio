# Kai Yu - Immersive Media Artist Portfolio

몰입형 미디어 아티스트 Kai Yu의 포트폴리오 웹사이트입니다.

## 기술 스택

- HTML5
- Tailwind CSS
- Google Fonts (Inter)
- Material Symbols Icons

## 로컬 개발

```bash
# 의존성 설치
npm install

# 개발 서버 실행 (http://localhost:3000)
npm start
```

## Railway 배포 가이드

### 1. Railway 계정 설정
1. [Railway](https://railway.app/)에 가입하거나 로그인합니다
2. GitHub 계정을 연동합니다

### 2. 프로젝트 배포

#### 방법 A: Railway Dashboard 사용
1. Railway Dashboard에서 "New Project" 클릭
2. "Deploy from GitHub repo" 선택
3. 이 리포지토리 선택
4. Railway가 자동으로 감지하고 배포를 시작합니다

#### 방법 B: Railway CLI 사용
```bash
# Railway CLI 설치
npm install -g @railway/cli

# Railway 로그인
railway login

# 프로젝트 초기화
railway init

# 배포
railway up
```

### 3. 환경 설정
Railway는 자동으로 다음을 감지합니다:
- `package.json`의 `start` 스크립트
- 포트 3000 (Railway의 `PORT` 환경변수로 자동 설정됨)

### 4. 도메인 설정
1. Railway Dashboard에서 프로젝트 선택
2. "Settings" → "Domains" 탭
3. "Generate Domain" 클릭하여 무료 도메인 생성
4. 또는 커스텀 도메인 추가 가능

## 프로젝트 구조

```
ImmersivePortfolio/
├── index.html          # 메인 HTML 파일
├── screen.png          # 스크린샷/프리뷰 이미지
├── package.json        # Node.js 설정
├── .gitignore          # Git 제외 파일 목록
└── README.md           # 프로젝트 문서
```

## 주요 섹션

- **Hero**: 메인 히어로 이미지와 타이틀
- **About**: 아티스트 소개
- **Works**: 작품 갤러리
- **Exhibitions**: 전시 이력 (타임라인)
- **Contact**: 연락처 및 소셜 링크

## 라이선스

MIT License
