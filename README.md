# YELOVELY — 브랜드 사이트

레몬 이너뷰티 브랜드 옐러블리(YELOVELY) 메인 페이지. 정적 HTML 한 장이라 GitHub Pages로 바로 배포됩니다.

## 구조
```
index.html
images/   로고(logo-symbol / logo-wordmark / logo-full) + 사이트 이미지
fonts/    프리젠테이션체 woff2 (Freesentation-3Light ~ 7Bold)
```

## 이미지 교체
아래 파일명으로 `images/`에 넣으면 자동으로 표시됩니다. 없으면 레몬 그라데이션이 대신 보입니다.
hero-product.png(메인 상단 제품 이미지) · signature-keyring.jpg · line-glow.jpg · line-slim.jpg · line-cleanse.jpg ·
ingredient-lemon.jpg · journal-01~04.jpg · insta-01~06.jpg · og-image.jpg

## 폰트
- 영문 Fahkwang: Google Fonts에서 자동 로드
- 한글 프리젠테이션체: `fonts/`에 woff2 파일을 넣으면 적용, 없으면 Pretendard로 표시

## 배포 (GitHub Pages)
Settings → Pages → Branch `main` / root → Save
