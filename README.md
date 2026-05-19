# Hoon's — Modern Minimal Menswear

> 군더더기 없는 셔츠, 슬랙스, 자켓. 매일 입고 싶어지는 옷을 만듭니다.

**Hoon's**는 미니멀 남성복 브랜드의 랜딩 페이지입니다.  
절제된 디자인과 부드러운 인터랙션으로 브랜드 정체성을 전달합니다.

🔗 **Live Demo** — [https://imjhoon.github.io/Hoon-s/](https://imjhoon.github.io/Hoon-s/)

---

## ✨ 주요 기능

| 기능 | 설명 |
|------|------|
| **반응형 레이아웃** | 모바일 · 태블릿 · 데스크톱 완벽 대응 |
| **Hero 섹션** | 풀스크린 에디토리얼 이미지 + 타이포그래피 |
| **Marquee 스트립** | 무한 롤링 텍스트 배너 |
| **상품 카드** | 호버 시 이미지 확대 + 위시리스트 버튼 |
| **장바구니 토스트** | 상품 클릭 시 카운터 증가 + 알림 팝업 |
| **Lookbook 갤러리** | 호버 오버레이와 캡션 애니메이션 |
| **컬렉션 카테고리** | 셔츠 · 슬랙스 · 자켓 카드 그리드 |
| **뉴스레터 구독** | 이메일 입력 폼 |
| **검색 바** | 슬라이드 다운 방식의 검색 UI |
| **모바일 메뉴** | 햄버거 버튼 토글 네비게이션 |
| **스크롤 애니메이션** | Intersection Observer 기반 요소 등장 효과 |

---

## 🛠 기술 스택

- **HTML5** — 시맨틱 마크업
- **Tailwind CSS** (CDN) — 유틸리티 퍼스트 스타일링
- **Vanilla JavaScript** — 외부 라이브러리 없이 순수 JS로 인터랙션 구현
- **Google Fonts** — Cormorant Garamond (디스플레이) + DM Sans (본문)
- **Unsplash** — 고해상도 에디토리얼 이미지

---

## 📁 디렉토리 구조

```
Hoon's/
├── images/                        # 상품 및 에디토리얼 이미지
│   ├── abdiel-rosario-*.jpg       # 셔츠 컬렉션
│   ├── batuhan-dogan-*.jpg        # 히어로 메인 이미지
│   ├── boluwatife-oguns-*.jpg     # 슬랙스 상품
│   ├── florencia-simonini-*.jpg   # Lookbook — Weekend Ease
│   ├── fortune-vieyra-*.jpg       # Lookbook — Smart Casual
│   ├── robert-richman-*.jpg       # 린넨 셔츠 상품
│   ├── sprite_oxford.jpg          # 옥스퍼드 셔츠 상품
│   ├── tamara-harhai-*.jpg        # 슬랙스 컬렉션
│   └── og-preview.png             # Open Graph 썸네일
│
├── favicons/                      # 파비콘 및 웹 앱 아이콘
│   ├── favicon.ico                # 레거시 브라우저용
│   ├── favicon.svg                # 모던 브라우저용 (SVG)
│   ├── favicon-96x96.png          # PNG 파비콘
│   ├── apple-touch-icon.png       # iOS 홈 화면 아이콘
│   ├── web-app-manifest-192x192.png
│   └── web-app-manifest-512x512.png
│
├── index.html                     # 메인 랜딩 페이지 (단일 파일)
├── site.webmanifest               # PWA 웹 앱 매니페스트
└── README.md
```

---

## 🚀 시작하기

별도의 빌드 도구나 의존성 설치가 필요 없습니다.

```bash
# 저장소 클론
git clone https://github.com/ImJhoon/Hoon-s.git

# 브라우저에서 열기
open index.html
# 또는 Live Server 확장 사용 (VS Code 권장)
```

> **참고**: Tailwind CSS는 CDN으로 로드되므로 인터넷 연결이 필요합니다.

---

## 🎨 디자인 시스템

### 컬러 팔레트

| 이름 | HEX | 용도 |
|------|-----|------|
| **Ink** | `#1C1C1C` | 메인 텍스트, 다크 배경 |
| **Charcoal** | `#3A3730` | 보조 텍스트 |
| **Stone** | `#8C8980` | 비활성 텍스트, 힌트 |
| **Ivory** | `#F5F2EC` | 밝은 배경, 다크 위 텍스트 |
| **Linen** | `#EAE6DF` | 섹션 배경, 구분선 |
| **Cream** | `#D6D1C8` | 강조 포인트 |

### 타이포그래피

- **디스플레이**: Cormorant Garamond — 우아한 세리프 헤딩
- **본문**: DM Sans — 깔끔한 산세리프

---

## 📄 페이지 섹션 구성

```
┌─────────────────────────────┐
│     📢 Announcement Bar     │  무료 배송 안내
├─────────────────────────────┤
│     🧭 Navigation           │  로고 + 메뉴 + 검색/장바구니
├─────────────────────────────┤
│     🖼  Hero                 │  SS 2025 메인 비주얼
├─────────────────────────────┤
│     ◀▶ Marquee Strip        │  무한 롤링 텍스트
├─────────────────────────────┤
│     🆕 New In               │  신상품 4개 그리드
├─────────────────────────────┤
│     📂 Collection           │  카테고리별 컬렉션
├─────────────────────────────┤
│     📸 Lookbook             │  에디토리얼 갤러리
├─────────────────────────────┤
│     💬 Brand Statement      │  브랜드 철학
├─────────────────────────────┤
│     📏 Size Guide CTA       │  사이즈 안내 배너
├─────────────────────────────┤
│     📧 Newsletter           │  이메일 구독
├─────────────────────────────┤
│     🦶 Footer               │  링크 + 소셜 + 법적고지
└─────────────────────────────┘
```

---

## 📝 SEO & 소셜 미디어

- **Open Graph** 메타 태그 설정 완료 (제목, 설명, 이미지, URL)
- **시맨틱 HTML** 구조 (`header`, `nav`, `section`, `footer`)
- 한국어(`ko`) 언어 속성 설정
- PWA 매니페스트 (`site.webmanifest`)
- 다중 파비콘 포맷 (ICO, SVG, PNG, Apple Touch Icon)

---

## 📸 이미지 크레딧

본 프로젝트의 사진은 [Unsplash](https://unsplash.com/)에서 제공받았습니다.

- [Batuhan Doğan](https://unsplash.com/@batuhandogan) — Hero 이미지
- [Robert Richman](https://unsplash.com/@robertrichman) — 린넨 셔츠
- [Boluwatife Oguns](https://unsplash.com/@boluwatife) — 슬랙스
- [Abdiel Rosario](https://unsplash.com/@abdielrosario) — 셔츠 컬렉션
- [Tamara Harhai](https://unsplash.com/@tamaraharhai) — 슬랙스 컬렉션
- [Florencia Simonini](https://unsplash.com/@florenciasimonini) — Lookbook
- [Fortune Vieyra](https://unsplash.com/@fortunevieyra) — Lookbook

---

## 📜 라이선스

이 프로젝트는 학습 및 포트폴리오 목적으로 제작되었습니다.
