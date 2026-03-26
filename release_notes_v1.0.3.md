# 스타샌드 아일랜드 한글패치 v1.0.3

`2026.11.43.0` 최신 게임 업데이트 대응 릴리스입니다.

이번 버전은 새 원문 기준선으로 다시 동기화한 패치입니다.
- 추가: `647`
- 삭제: `3464`
- 변경: `939`

이 중 자동 반영 가능한 변경분은 먼저 안전하게 동기화했고,
의미 변화가 있는 줄은 수동 검토 후 반영했습니다.

## 포함 내용

- 최신 원문 업데이트 대응
- source update semantic review 완료
  - `reviewed fix: 526`
  - `reviewed keep: 377`
  - `remaining: 0`
- 최신 인게임 inject JSON 재생성
- 최신 로컬 번들 재패치 기준 반영
- 배포본 `v1.0.3` 재생성

## 대표 수정 항목

- `탄약 제작기` -> `탄약 작업대`
- `Forest Fawn` 계열 -> `달빛 새끼사슴`
- `Rectangular Aquarium` -> `큐브 수족관`
- `Silvan Notes` -> `실반 노츠`
- `Mirage Sunflowers` -> `미라지 해바라기`
- `Fluorite Ore` -> `형석 광석`
- `Waxberry Smoothie` 계열 -> `양매 스무디`
- `Star Dream Model` -> `스타드림 모형`
- `Grain God's Pitcher` -> `곡신의 주전자`

## 설치 메모

- 배포 파일: `StarsandIsland_KoreanPatch_2026-03-26_v1.0.3.zip`
- 지원 플랫폼: `Steam / Xbox PC`
- 최신 원문 동기화 기준 게임 버전: `2026.11.43.0`
- 기존 검증 기준 게임 버전: `2026.5.32.0`
- 게임 내 언어는 `English`를 선택해야 한글이 적용됩니다.

## 배포 구조

- 완성된 게임 번들 전체는 배포하지 않습니다.
- 설치 시 로컬 `589829.ab`에 한글 JSON을 직접 주입합니다.
- 폰트는 검증된 번들을 직접 복사합니다.
- Steam/Xbox 설치 경로 자동 탐지를 지원합니다.
