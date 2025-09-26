# 건축환경기술 회사 홈페이지

건축환경기술 회사의 공식 홈페이지입니다.

## 프로젝트 개요

이 웹사이트는 건축환경기술 회사를 소개하는 반응형 웹사이트입니다. 회사 소개, 대표 인사말, 연혁, 경력/실적, 위치 정보, 연락처 등의 정보를 제공합니다.

## 주요 기능

- **반응형 디자인**: 모바일, 태블릿, 데스크톱 모든 기기에서 최적화된 경험
- **현대적인 UI/UX**: 깔끔하고 전문적인 디자인
- **부드러운 애니메이션**: 스크롤 기반 애니메이션과 호버 효과
- **모바일 친화적**: 햄버거 메뉴와 터치 친화적 인터페이스
- **SEO 최적화**: 검색 엔진 최적화를 위한 메타 태그 설정

## 사이트 구조

### 주요 섹션

1. **홈 (Hero Section)**: 회사 메인 소개 및 주요 액션 버튼
2. **회사소개**: 회사 개요 및 주요 특징
3. **대표인사말**: 대표이사의 인사말과 비전
4. **회사연혁**: 회사의 주요 역사와 발전 과정
5. **경력/실적**: 프로젝트 경험, 자격증, 수상 경력
6. **오시는길**: 회사 위치 및 교통 정보
7. **연락처**: 연락처 정보 및 문의 양식

## 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, 애니메이션
- **Vanilla JavaScript**: 인터랙티브 기능
- **Font Awesome**: 아이콘
- **Google Fonts**: 웹 폰트 (Noto Sans KR)

## 설치 및 실행

### 필요 조건

- Node.js (v14 이상)
- npm 또는 yarn

### 설치

```bash
# 의존성 설치
npm install

# 개발 서버 실행
npm run dev

# 또는 프로덕션 서버 실행
npm start
```

### 브라우저에서 확인

개발 서버 실행 후 `http://localhost:3000`에서 웹사이트를 확인할 수 있습니다.

## 파일 구조

```
/
├── index.html          # 메인 HTML 파일
├── css/
│   └── style.css       # 스타일시트
├── js/
│   └── script.js       # JavaScript 파일
├── images/             # 이미지 리소스
├── package.json        # 프로젝트 설정
└── README.md          # 프로젝트 문서
```

## 커스터마이징 가이드

### 회사 정보 수정

1. **기본 정보**: `index.html`에서 회사명, 주소, 연락처 등을 수정
2. **로고**: `images/logo.png` 파일 교체
3. **대표 사진**: `images/ceo-photo.jpg` 파일 교체
4. **회사 건물 사진**: `images/company-building.jpg` 파일 교체
5. **히어로 배경**: `images/hero-bg.jpg` 파일 교체

### 색상 테마 변경

`css/style.css`에서 CSS 변수를 수정하여 색상 테마를 변경할 수 있습니다:

```css
:root {
    --primary-color: #2c5aa0;
    --secondary-color: #1e3d6f;
    --accent-color: #667eea;
}
```

### 지도 연동

현재는 지도 플레이스홀더가 표시됩니다. 실제 지도를 연동하려면:

1. **Google Maps API** 또는 **네이버 지도 API** 키 발급
2. `js/script.js`의 `initMap()` 함수에서 실제 지도 API 연동 코드 작성

### 문의 양식 연동

현재는 클라이언트 사이드 검증만 구현되어 있습니다. 실제 서버로 전송하려면:

1. 백엔드 서버 구성 (Node.js, PHP, Python 등)
2. `js/script.js`의 폼 제출 처리 부분에서 서버 API 호출 코드 추가

## 브라우저 호환성

- Chrome (최신)
- Firefox (최신)
- Safari (최신)
- Edge (최신)
- Internet Explorer 11+

## 성능 최적화

- 이미지 최적화 (WebP 형식 권장)
- CSS/JS 파일 압축
- CDN 사용 고려
- 레이지 로딩 구현

## 배포

### GitHub Pages

1. GitHub 저장소에 코드 푸시
2. Settings > Pages에서 소스 선택
3. 도메인 설정 (선택사항)

### Netlify

1. Netlify에 저장소 연결
2. 빌드 설정: 빌드 명령어 없음, 배포 폴더: `/`
3. 도메인 설정

### 기타 호스팅

- Vercel
- GitHub Pages
- Firebase Hosting
- AWS S3 + CloudFront

## 라이선스

MIT License

## 연락처

프로젝트 관련 문의사항이 있으시면 언제든 연락주세요.

---

© 2024 건축환경기술. All rights reserved.
