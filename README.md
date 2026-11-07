# RuBP의 기록

GitHub Pages와 Jekyll로 운영하는 개인 블로그입니다.

주소: https://rubp-curved.github.io

## 글 작성

1. GitHub에서 _posts 폴더를 엽니다.
2. Add file → Create new file을 선택합니다.
3. 파일 이름을 YYYY-MM-DD-slug.md 형식으로 만듭니다.
4. 아래 내용을 넣고 제목, 날짜, 카테고리, 본문을 수정합니다.
5. Commit changes로 저장합니다. Pages 배포 완료 후 공개됩니다.

```markdown
---
layout: post
title: "글 제목"
date: 2026-11-08 12:00:00 +0900
categories: [기록]
---

여기에 본문을 작성하세요.
```

미래 날짜의 글은 표시되지 않습니다. 실제 작성 시각을 사용하세요.

## 수정 위치

- 블로그 이름과 설명: _config.yml
- 소개: about.md
- 첫 화면: index.html
- 디자인: assets/style.css
- 공통 메뉴/푸터: _layouts/default.html

## Pages 설정

Settings → Pages → Deploy from a branch → main → /(root) → Save.
