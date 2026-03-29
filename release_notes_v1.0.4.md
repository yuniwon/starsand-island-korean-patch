# 스타샌드 아일랜드 한글패치 v1.0.4

`2026.11.43.0` 대응본 위에 사용자 노출 영어 잔존과 제작 UI 호환 문제를 추가 정리한 hotfix 릴리스입니다.

## 이번 버전 요약

- 최신 원문 동기화 기준 유지: `2026.11.43.0`
- `v1.0.3` 이후 post-update user-facing hotfix 반영
- 최신 inject JSON 재생성
- 로컬 번들 재패치 기준 반영

## 포함 내용

- `Caiyun`, `Taohua`, `Shenti` 신규 영어 문장 클러스터 정리
- `DialogLib` 당화 반응 일부 정리
- `Timber*` 가구군, `Captain Shu`, `Cotton / Sunflower / Sweet Potato` 계열 현지화
- `LostAndFound`, `QuickShop_Delivery` 우편 현지화
- `UIWorkBench` alias 및 제작 UI 호환 보강 유지

## 대표 수정 항목

- `Timber View Desk` -> `팀버 뷰 책상`
- `Timbergrove Tea Table` -> `팀버그로브 찻상`
- `Timbervine Wardrobe` -> `팀버바인 옷장`
- `Timberleaf Cabinet` -> `팀버리프 캐비닛`
- `Woven Rattan Sofa` -> `라탄 짜임 소파`
- `Captain Shu Watering Can` -> `대장 슈 물뿌리개`
- `Captain Shu Cruiser` -> `대장 슈 크루저`
- `Captain Shu Skateboard` -> `대장 슈 스케이트보드`
- `Cotton / Sunflower / Sweet Potato` -> `목화 / 해바라기 / 고구마`
- `Community Center` -> `커뮤니티 센터`

## 설치 메모

- 배포 파일: `StarsandIsland_KoreanPatch_2026-03-30_v1.0.4.zip`
- 지원 플랫폼: `Steam / Xbox PC`
- 최신 원문 동기화 기준 게임 버전: `2026.11.43.0`
- 기존 검증 기준 게임 버전: `2026.5.32.0`
- 게임 내 언어는 `English`를 선택해야 한글이 적용됩니다.

## 배포 구조

- 완성된 게임 번들 전체는 배포하지 않습니다.
- 설치 시 로컬 `589829.ab`에 한글 JSON을 직접 주입합니다.
- 폰트는 검증된 번들을 직접 복사합니다.
- Steam/Xbox 설치 경로 자동 탐지를 지원합니다.
