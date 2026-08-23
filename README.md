# ibbusiness.kr

IB Business Management 강사 변희정 소개 페이지.

정적 HTML. 빌드 과정 없음.

## 구조

```
site/
├── index.html    랜딩페이지 (JSON-LD 구조화 데이터 포함)
├── img/          이미지 자산 (jpg / webp / OG)
├── robots.txt    검색·AI 크롤러 정책
├── sitemap.xml
├── llms.txt      LLM 요약 파일
├── _headers      Cloudflare Pages 헤더 (캐싱·보안)
└── _redirects    www → non-www 301
```

## 배포

Cloudflare Pages. `main` 브랜치에 푸시하면 자동 배포됩니다.

| 설정 | 값 |
|---|---|
| Framework preset | None |
| Build command | (없음) |
| Build output directory | `site` |
| Root directory | (비움) |
