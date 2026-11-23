# STRUCTURE · hunmin-sample (v0.2.0 · 레퍼런스 형식(화면 폭 사진 장 + 가운데 명조 문장) · 흰 바탕 · 배포 예정 hunmin-sample.lgt3232.workers.dev)

```
hunmin-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = hunmin-sample
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ hm-gilda.woff2             영문 제목 · 라벨 · 번호 (Gilda Display 400, 영문만)
├─ hm-serif.woff2            사진 위 문장 · 히어로 · 인용 (Noto Serif KR 300–500)
├─ hm-pretendard.woff2        본문 · 한글 (Pretendard 200–600, 페이지 글자 전부)
├─ hm-logo.svg                "Hunmin" 로고 (잉크 #1E1C1A, potrace)
├─ hm-hero.webp · hm-hero-m.webp  히어로 · 거실 큰 창 (1440×810 · 1080×1440)
├─ hm-c1(-m).webp · hm-c2(-m).webp  장 1 주방 · 장 2 천장 (1920×1080 · 1080×1350)
├─ hm-w1 · w2 · w4 · w5 · w6 · w9 · w11 · w12 .webp  작업 8장 (v0.2.0에서 w3 · w10 삭제)
├─ hm-cafe.webp               사례 · 동탄 목동 카페 (1080×575)
├─ favicon.png · og-hm.jpg
├─ img/                       다올 제공 원본 66장 + _원문.md + 미사용 로고 (배포 제외 · 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(+ 900px 미만 `.snav`) → 히어로(사진 + 아래 그라데이션) → `#about`(#F6F4F0) → `#service`(#ECE8E1) → `#works`(#F6F4F0) → `#case`(#ECE8E1) → 시선(#F6F4F0) → `#contact`(#ECE8E1 · 지도) → 푸터 + 모바일 `.quick`.

## 버튼 · 링크
- 전화 `tel:01026414877`(010-2641-4877, 메인): 헤더 · 히어로 · 문의 · 푸터 · 하단 바
- 네이버 톡톡 `https://talk.naver.com/wyzcagw`: 히어로 · 문의 · 하단 바
- 인스타 `https://www.instagram.com/hunmin_interior/`: 히어로 · 작업 안내 · 문의 · 푸터 · 하단 바
- 전화번호(네이버) `tel:050713294877`: 오시는 길 정보 (위 줄 "상담 전화" = 010)
- 블로그 버튼 `https://blog.naver.com/dongmin8888`: 작업 섹션 끝
- 블로그 시공기 `https://m.blog.naver.com/dongmin8888/223927714362` · 블로그 · 네이버 지도 `map.naver.com/p/entry/place/1274583180` · 네이버 플레이스(푸터)

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 한글은 Pretendard만, Gilda는 영문만.
