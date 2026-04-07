# 스타샌드 아일랜드 한글패치 v1.0.5

`2026.13.47.0` 기준 새 패치 대응 릴리스입니다.

이번 버전은 `v1.0.4`의 GUI 런처/설치 구조를 유지하면서, 새 원문 변경분을 safe sync한 뒤 플레이어가 바로 보게 되는 영어 잔존과 semantic drift를 추가 정리했습니다.

## 이번 버전 요약

- 최신 원문 동기화 기준: `2026.13.47.0`
- source update diff 반영
  - `added 327`
  - `removed 94`
  - `changed 193`
- user-facing hotfix 반영
  - `Starsand Shop`
  - `Golden Cudgel`
  - `Weed Barrier`
  - `Great Sage`
  - `Workbench/UI`
  - `Caiyun`, `Taohua`, `Shenti`
- 최신 inject JSON 재생성
- 로컬 번들 재패치 기준 반영

## 대표 수정 항목

- `Golden Cudgel` -> `여의금고봉`
- `Golden Cudgel Blueprint` -> `여의금고봉 설계도`
- `Weed Barrier` -> `잡초 방지포`
- `Weed Barrier Blueprint` -> `잡초 방지포 설계도`
- `Starsand Shop` -> `스타샌드 상점`
- `Complete` -> `완료`
- `Worktable I / II` -> `작업대 I / II`
- `Cotton / Sunflower / Sweet Potato` -> `목화 / 해바라기 / 고구마`
- `Community Center` -> `커뮤니티 센터`
- `Lex Woodworks` 관련 설계도 획득처 문구 현지화

## QA 메모

- tone gate `0`
- UI token mismatch `0`
- UI length risk `2`
- glossary hard gate `90`
  - 기존 canonical drift baseline 잔량이며, 이번 패치 대응의 신규 회귀는 아님

## 설치 메모

- 배포 파일: `StarsandIsland_KoreanPatch_2026-04-07_v1.0.5.zip`
- 지원 플랫폼: `Steam / Xbox PC`
- 최신 원문 동기화 기준 게임 버전: `2026.13.47.0`
- 게임 내 언어는 `English`를 선택해야 한글이 적용됩니다.

## 배포 구조

- GUI 런처 `스타샌드 아일랜드 한글패치 런처.exe` 포함
- `Start_Korean_Patch.bat` 포함
- 완성된 게임 번들 전체는 배포하지 않습니다.
- 설치 시 로컬 `589829.ab`에 한글 JSON을 직접 주입합니다.
- 폰트는 검증된 번들을 직접 복사합니다.
- Steam/Xbox 설치 경로 자동 탐지를 지원합니다.
