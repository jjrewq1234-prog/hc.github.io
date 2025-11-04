# 이희창 - 자기소개 페이지

개인 포트폴리오 및 자기소개 웹 페이지입니다. HTML, CSS, JavaScript만으로 구현된 반응형 웹사이트입니다.

## 📋 프로젝트 소개

교육 콘텐츠 전문 편집자 이희창의 자기소개 페이지입니다. Notion 스타일의 다크 테마 디자인으로 제작되었으며, 경력, 학력, 역량, 가치관 등을 소개합니다.

## 🚀 주요 기능

- **반응형 디자인**: 모바일, 태블릿, 데스크톱 지원
- **다크 테마**: 눈의 피로를 줄이는 어두운 배경
- **인터랙티브 요소**:
  - 스크롤 인디케이터
  - 섹션별 페이드인 애니메이션
  - 네비게이션 하이라이트
  - 스킬 바 애니메이션
  - 호버 효과
- **부드러운 스크롤**: 네비게이션 클릭 시 부드러운 스크롤 이동

## 📁 파일 구조

```
cursorstudy/
├── introduction.html          # 메인 자기소개 페이지
├── assets/
│   ├── css/
│   │   └── style.css         # CSS 스타일 파일
│   └── js/
│       └── script.js         # JavaScript 파일
├── profile-photo.jpg          # 프로필 사진
├── README.md                  # 프로젝트 설명서
├── LICENSE                    # 라이선스 파일
└── .gitignore                 # Git 제외 파일 목록
```

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 
  - Flexbox & Grid
  - 애니메이션 및 트랜지션
  - 미디어 쿼리 (반응형 디자인)
- **JavaScript (Vanilla)**:
  - Intersection Observer API
  - 스크롤 이벤트 처리
  - 스무스 스크롤

## 📖 사용 방법

1. 저장소를 클론하거나 파일을 다운로드합니다.
2. `introduction.html` 파일을 웹 브라우저에서 엽니다.
3. 프로필 사진 파일(`profile-photo.jpg`)이 같은 폴더에 있는지 확인합니다.

### 로컬 서버 실행 (선택사항)

```bash
# Python 3 사용
python -m http.server 8000

# Node.js 사용 (http-server 설치 필요)
npx http-server
```

브라우저에서 `http://localhost:8000/introduction.html` 접속

## 🎨 디자인 특징

- **색상 팔레트**: 다크 테마 기반
  - 배경: `#1a1a1a`, `#2d2d2d`, `#252525`
  - 텍스트: `#ffffff`, `#e9ecef`, `#d0d0d0`
  - 강조: `#818cf8`, `#a78bfa`
- **타이포그래피**: 시스템 폰트 스택 사용
- **레이아웃**: 최대 너비 900px의 중앙 정렬 컨테이너
- **파일 구조**: HTML, CSS, JavaScript 분리된 구조

## 📱 섹션 구성

1. **헤더**: 프로필 사진, 이름, 직업, 연락처
2. **소개**: 간단한 자기소개
3. **학력**: 교육 이력 타임라인
4. **경력**: 직장 경력 타임라인
5. **역량**: 기술 스택 및 자격증
6. **가치관**: 개인 철학 및 특성
7. **포트폴리오**: 주요 프로젝트 및 성과

## 🔧 커스터마이징

### 색상 변경

`assets/css/style.css` 파일에서 색상 값을 직접 수정하여 테마를 변경할 수 있습니다.

```css
/* 다크 테마 색상 예시 */
body {
    background: #1a1a1a;
    color: #e9ecef;
}
```

### 프로필 사진 변경

1. 새로운 프로필 사진을 준비합니다.
2. 파일명을 `profile-photo.jpg`로 변경하거나
3. HTML 파일의 이미지 경로를 수정합니다:
   ```html
   <img src="profile-photo.jpg" alt="이희창 프로필 사진" class="profile-photo">
   ```

### 스타일 수정

- **CSS**: `assets/css/style.css` 파일에서 스타일을 수정할 수 있습니다.
- **JavaScript**: `assets/js/script.js` 파일에서 인터랙티브 기능을 수정할 수 있습니다.
- **HTML**: `introduction.html` 파일에서 내용을 수정할 수 있습니다.

### 내용 수정

각 섹션의 내용은 `introduction.html` 파일 내에서 직접 수정할 수 있습니다.

## 📄 라이선스

MIT License - 자세한 내용은 [LICENSE](LICENSE) 파일을 참고하세요.

## 👤 작성자

**이희창 (HeeChang Lee)**
- 이메일: hclee9@kakao.com
- 전화: 010-2618-6596
- 위치: 경기 고양시 일산동구

## 🔗 링크

- [Notion 포트폴리오](https://www.notion.so/PORTFOLIO-40df4c73664545f799abdfd4c2bfc5b3?pvs=4)

## 📝 업데이트 이력

- **2024**: 초기 버전 생성
  - Notion 스타일 다크 테마 적용
  - 반응형 디자인 구현
  - 프로필 사진 추가
  - 인터랙티브 요소 추가
  - HTML, CSS, JavaScript 파일 분리
  - assets 폴더 구조로 정리

## 🚀 배포 방법

### GitHub Pages

1. GitHub 저장소에 파일을 업로드합니다.
2. Settings > Pages로 이동합니다.
3. Source를 `main` 브랜치로 설정합니다.
4. 저장 후 `https://사용자명.github.io/저장소명/introduction.html`로 접속 가능합니다.

### 다른 호스팅 서비스

- Netlify
- Vercel
- Firebase Hosting
- 등

---

⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요!
