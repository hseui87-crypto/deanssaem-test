# 딘쌤 홍상의 — 퍼스널 브랜딩 페이지

호텔관광 · CS · 커리어 강사 **딘쌤 홍상의**의 퍼스널 브랜딩 페이지입니다.

### 🌐 https://careerbuilder-dean.vercel.app

> 대표 주소는 Vercel입니다. GitHub Pages(https://hseui87-crypto.github.io/deanssaem-test/)에도
> 동일한 내용이 배포되지만, `canonical`이 Vercel을 가리키므로 검색 결과에는 Vercel 주소가 노출됩니다.

## 파일

| 파일 | 설명 |
|---|---|
| `index.html` | 브랜딩 페이지 전체 (단일 파일) |
| `og-image.jpg` | 링크 공유용 카드 이미지 (1200×630) |

외부 의존성이 없는 단일 HTML 파일입니다. 이미지는 모두 base64로 내장되어 있어
파일 하나만 있으면 어디서든 그대로 열립니다. 웹폰트(Noto Sans KR / Noto Serif KR)만
Google Fonts에서 불러오며, 인터넷이 없어도 시스템 폰트로 정상 표시됩니다.

## 보기

`index.html`을 브라우저로 열면 됩니다. 별도 빌드나 서버가 필요 없습니다.

## 구성

1. 히어로 — 핵심 메시지 및 주요 지표
2. 전문 영역 — 4개 교육 분야
3. 소개 — 강사 소개
4. 커리어 스토리 — 15년 경력 타임라인
5. 숫자로 보는 성과 — 실적 및 수상
6. 강의 포트폴리오 — 4개 강의 영역
7. 경력 — 회사별 상세 이력
8. 대외활동 — 위원 활동 및 보유 자격
9. 전자책 — 『호텔관광 커리어 설계법』
10. 강의 문의 — 연락처 및 문의 양식

## 기술 사항

- 단일 HTML 파일 (약 390KB), 프레임워크·빌드 도구 없음
- 반응형 (375px ~ 1440px 검증)
- 스크롤 등장 효과, 숫자 카운트업, 모바일 햄버거 메뉴
- `prefers-reduced-motion` 및 인쇄용 스타일 대응
- JavaScript가 비활성화되어도 모든 내용이 정상 표시됨
- Open Graph / Twitter Card 메타 태그 — 카카오톡·Threads 등에서 링크 공유 시 카드 노출
- JSON-LD 구조화 데이터 (Person / Book / WebSite) — 검색엔진 프로필 인식용

## 배포

`main` 브랜치에 푸시하면 **Vercel과 GitHub Pages 양쪽이 자동으로 재배포**합니다 (1~2분 소요).

```bash
git add -A
git commit -m "내용 수정"
git push
```

## 문의

- Email : hseui87@gmail.com
- Threads : [@careerbuilder.dean](https://www.threads.com/@careerbuilder.dean)

---

© 2026 홍상의(딘쌤). All rights reserved.
