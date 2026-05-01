# NextTrack 소개 페이지

NextTrack의 앱 소개용 랜딩 페이지 프로젝트입니다.  
습관 기록 앱의 핵심 가치(기록이 아닌 누적)를 전달하는 카피 구조와 다크 UI 톤을 반영했습니다.

## 프로젝트 목적

- 사용자의 행동을 유도하는 소개 페이지 제공
- 문제 인식 -> 공감 -> 기능 -> 가치 -> 행동 흐름으로 콘텐츠 설계
- 검색 엔진과 답변 엔진에 잘 노출되도록 SEO/AEO 메타데이터 반영

## 주요 구성

- `index.html`
  - Hero, About, 기능, 철학, CTA, Footer 섹션
  - 다크 테마 + 네온 민트 포인트 스타일
  - 예시 UI 이미지(`xc481.jpg`, `xc482.jpg`) 삽입
  - 구조화 데이터(JSON-LD: `WebApplication`, `FAQPage`) 포함
- `xc481.jpg`, `xc482.jpg`
  - 소개 페이지 내 UI 예시 이미지

## 기술 스택

- HTML
- CSS
- JavaScript(정적 페이지 내 메타/구조 중심)

## SEO / AEO 반영 포인트

- 기본 메타: `title`, `description`, `keywords`, `canonical`, `robots`
- 소셜 메타: Open Graph, Twitter Card
- 구조화 데이터:
  - `WebApplication`
  - `FAQPage`

## 실행 방법

별도 빌드 없이 정적 파일로 동작합니다.

1. 프로젝트 클론
2. `index.html` 브라우저로 열기

## 배포 / 앱 링크

- 앱 데모: https://junsang-dong.github.io/goorm-260501-vibecoding-habit-tracking-v1/
- 저장소: https://github.com/junsang-dong/goorm-next-tracker

## 작성 정보

- 개발사: NextPlatform
- 개발자: JUN.VIBE
- 이메일: naebon@naver.com
- 최초 작성일: 2026-05-01
