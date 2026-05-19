# 🚗 Auto Detailing Platform

### 자동차 디테일링 서비스 웹 플랫폼

> 사용자와 디테일링 업체를 연결하고, 서비스 소개·예약·상담·포트폴리오를 직관적으로 제공하는  
> 현대적인 웹 기반 플랫폼입니다.

---

## 📋 Project Overview

**Auto Detailing**은 자동차 디테일링 서비스의 신뢰도와 접근성을 높이기 위해 제작된 웹 프로젝트입니다.

기존 자동차 관리 업체들의 복잡하고 구식적인 인터페이스 대신, **깔끔한 레이아웃**과 **직관적인 사용자 경험(UI/UX)**을 중심으로 프리미엄 브랜드 웹사이트를 구현했습니다.

**핵심 목표:**
- ✅ 디테일링 업체의 브랜드 신뢰도 강화
- ✅ 사용자 중심의 직관적인 UI/UX 설계
- ✅ 반응형 웹 기반 모바일 최적화
- ✅ 서비스 소개 및 상담 접근성 향상
- ✅ 포트폴리오 중심의 비주얼 강조

---

## 🎯 Key Features

### 🏠 **메인 랜딩 페이지**
- 브랜드 임팩트를 살린 Hero Section
- 핵심 서비스 한눈에 보기
- 시각적 강조 및 Call-to-Action (CTA) 버튼

### 🚘 **디테일링 서비스 소개**
- 다양한 차량 관리 서비스 구성
- 프리미엄 서비스 패키지 강조
- Before/After 이미지 비교 영역
- 상세한 서비스 설명 및 가격 정보

### 📱 **반응형 웹 디자인**
- 모바일 / 태블릿 / 데스크탑 완벽 대응
- Flexbox & CSS Grid 기반 유연한 레이아웃
- 터치 친화적 인터페이스

### 🎨 **현대적 UI/UX 설계**
- 미니멀하면서도 프리미엄한 디자인 톤
- 직관적인 사용자 흐름 구성
- 사용자 집중도를 높인 인터페이스
- 부드러운 애니메이션 및 트랜지션 효과

### 📞 **상담 및 예약 시스템**
- 간편한 상담 신청 폼
- 예약 일정 관리 기능
- 사용자 정보 수집 및 관리

### 🎬 **포트폴리오 갤러리**
- 고품질 프로젝트 이미지 전시
- 카테고리별 서비스 포트폴리오
- 이미지 필터 및 검색 기능

---

## 🛠 Tech Stack

| 분야 | 기술 스택 |
|------|---------|
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla) |
| **Layout** | Flexbox, CSS Grid |
| **Design** | Responsive Web Design, Modern UI |
| **Tools** | Git, GitHub, VS Code |
| **Browser Support** | Chrome, Firefox, Safari, Edge |

---

## 📂 Project Structure

```
Auto_Detailing/
│
├── index.html              # 메인 페이지
├── style.css              # 스타일시트 (반응형 디자인)
├── script.js              # JavaScript 로직
│
├── essenceDetailing/       # 서브 폴더 (추가 페이지/리소스)
│   ├── portfolio.html
│   ├── service.html
│   └── ...
│
├── images/                # 이미지 파일 디렉토리
│   ├── hero/
│   ├── portfolio/
│   ├── services/
│   └── ...
│
└── README.md             # 프로젝트 문서
```

---

## 🚀 Getting Started

### 설치 및 실행

1. **저장소 클론**
   ```bash
   git clone https://github.com/wlsgns9607-blip/Auto_Detailing.git
   cd Auto_Detailing
   ```

2. **브라우저에서 실행**
   - `index.html` 파일을 브라우저에서 직접 열기
   - 또는 Live Server 사용:
   ```bash
   # VS Code Live Server 확장 사용
   # 또는 Python 로컬 서버
   python -m http.server 8000
   ```

3. **브라우저 접속**
   ```
   http://localhost:8000
   ```

---

## 🎨 Design Highlights

### 색상 팔레트
- **Primary**: 현대적 검정/흰색 조합
- **Accent**: 프리미엄 골드/실버 톤
- **Background**: 클린한 그레이스케일

### 타이포그래피
- 헤더: 굵은 산세리프 폰트 (임팩트)
- 본문: 가독성 높은 산세리프 폰트
- 라인 하이트: 1.6 이상 (가독성 최적화)

### 반응형 브레이크포인트
```css
/* Mobile: 320px ~ 479px */
/* Tablet: 480px ~ 767px */
/* Desktop: 768px 이상 */
```

---

## 📊 Performance & Optimization

- ✅ **이미지 최적화**: 웹용 이미지 압축 및 lazy loading
- ✅ **CSS 압축**: 최소화된 스타일시트
- ✅ **JavaScript 최적화**: 불필요한 코드 제거
- ✅ **SEO 최적화**: 의미 있는 HTML 구조 (Semantic HTML)
- ✅ **접근성**: WCAG 가이드라인 준수

---

## 💡 Key Implementation Details

### 1. **반응형 디자인**
```css
/* 예: Flexbox를 활용한 유연한 레이아웃 */
.service-container {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

/* 태블릿 이상 */
@media (min-width: 768px) {
  .service-container {
    grid-template-columns: repeat(2, 1fr);
  }
}
```

### 2. **JavaScript 인터랙션**
- 스무스 스크롤 네비게이션
- 동적 콘텐츠 로딩
- 폼 검증 및 제출
- 갤러리 필터링

### 3. **사용자 경험**
- 명확한 Call-to-Action 버튼
- 빠른 로딩 속도
- 직관적인 네비게이션
- 모바일-우선 접근

---

## 📈 Future Enhancements

- [ ] 백엔드 연동 (Node.js / Python)
- [ ] 데이터베이스 통합 (MongoDB / MySQL)
- [ ] 사용자 인증 시스템
- [ ] 결제 게이트웨이 통합
- [ ] 실시간 상담 채팅
- [ ] 고급 분석 대시보드
- [ ] PWA (Progressive Web App) 지원
- [ ] 다국어 지원 (i18n)

---

## 🔧 Browser Compatibility

| 브라우저 | 지원 |
|---------|------|
| Chrome | ✅ 최신 버전 |
| Firefox | ✅ 최신 버전 |
| Safari | ✅ 최신 버전 |
| Edge | ✅ 최신 버전 |
| IE 11 | ❌ 미지원 |

---

## 📝 License

이 프로젝트는 개인 포트폴리오 프로젝트입니다.  
상업적 목적의 사용은 제한됩니다.

---

## 👨‍💻 Developer

**GitHub**: [@wlsgns9607-blip](https://github.com/wlsgns9607-blip)

---

## 📞 Contact & Support

- 📧 이메일: [이메일 주소 입력]
- 🌐 포트폴리오: [포트폴리오 링크]
- 💼 LinkedIn: [LinkedIn 링크]

---

## 🙏 Acknowledgments

- 현대적인 웹 디자인 트렌드 참고
- 사용자 경험(UX) 최적화 원칙 적용
- 오픈소스 커뮤니티의 지식 활용

---

<div align="center">

**⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요!**

</div>
