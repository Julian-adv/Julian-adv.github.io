# OpenMMO Devlog

`https://julian-adv.github.io`에 배포되는 Astro 기반 개발 블로그입니다.

## 로컬 실행

Node.js 24를 사용합니다.

```sh
nvm use
npm install
npm run dev
```

## 글 작성

`src/content/blog/_template.md`를 복사해 이름을 바꾸거나 Markdown 또는 MDX 파일을 추가합니다. 공개할 때는 `draft: false`로 변경합니다.

```md
---
title: 첫 번째 개발 기록
description: 글 내용을 한 문장으로 설명합니다.
pubDate: 2026-09-01
draft: false
---

본문을 작성합니다.
```

이미지를 사용할 때는 파일을 `src/assets/`에 넣고 `heroImage`에 상대 경로를 지정합니다.

## 배포

GitHub에 `Julian-adv/julian-adv.github.io` 저장소를 만든 뒤 이 프로젝트를 push합니다. 저장소의 **Settings → Pages → Build and deployment → Source**를 **GitHub Actions**로 설정하면 `main` 브랜치에 push할 때 자동 배포됩니다.

## 명령어

| 명령어 | 용도 |
| --- | --- |
| `npm run dev` | 개발 서버 실행 |
| `npm run build` | 배포용 정적 사이트 생성 |
| `npm run preview` | 생성 결과 미리 보기 |
