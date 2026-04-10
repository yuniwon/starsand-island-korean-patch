# 스타샌드 아일랜드 한글패치 v1.0.6

`2026.14.49.0` 기준 소규모 원문 업데이트 대응 릴리스입니다.

이번 버전은 `v1.0.5`의 GUI 런처/설치 구조를 그대로 유지하면서, 새 원문 diff를 safe sync하고 남은 semantic change 1행을 반영했습니다.

## 이번 버전 요약

- 최신 원문 동기화 기준: `2026.14.49.0`
- source update diff 반영
  - `added 0`
  - `removed 1`
  - `changed 1`
- semantic review 반영
  - `reviewed fix 1`
  - `reviewed keep 0`
  - `remaining 0`
- 최신 inject JSON 재생성
- 기존 GUI 런처/자동 업데이트 구조 유지

## 대표 수정 항목

- `$$Item.Vehicle.FloatingBoard2.Extensions.Origin.OriginDescription$$`
  - `<style="Major">스타샌드 상점</style>에서 구매 가능`
- obsolete `LockedDescription` 키 제거 반영

## QA 메모

- `test_source_update_sync.py` `2 passed`
- `test_source_update_review_apply.py` `2 passed`
- `test_build_ingame_inject_aliases.py` `1 passed`
- `test_update_hotfix_20260407.py` `3 passed`
- `catalog integrity=PASS`
- glossary hard gate `90`
  - 기존 canonical drift baseline이며, 이번 패치 신규 회귀는 아님

## 설치 메모

- 배포 파일: `StarsandIsland_KoreanPatch_2026-04-10_v1.0.6.zip`
- 지원 플랫폼: `Steam / Xbox PC`
- 최신 원문 동기화 기준 게임 버전: `2026.14.49.0`
- 게임 내 언어는 `English`를 선택해야 한글이 적용됩니다.

## 배포 구조

- GUI 런처 `스타샌드 아일랜드 한글패치 런처.exe` 포함
- `Start_Korean_Patch.bat` 포함
- 완성된 게임 번들 전체는 배포하지 않습니다.
- 설치 시 로컬 `589829.ab`에 한글 JSON을 직접 주입합니다.
- 폰트는 검증된 번들을 직접 복사합니다.
- Steam/Xbox 설치 경로 자동 탐지를 지원합니다.
