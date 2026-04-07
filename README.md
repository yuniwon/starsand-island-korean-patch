# Starsand Island Korean Patch

비공식 스타샌드 아일랜드 한글패치 배포 저장소입니다.

## 최신 배포본

- 패치 버전: `v1.0.5`
- 최신 원문 동기화 기준 게임 버전: `2026.13.47.0`
- 기존 검증 기준 게임 버전: `2026.5.32.0`
- 지원 플랫폼: `Steam / Xbox PC`

최신 배포 파일은 Releases 탭에서 받을 수 있습니다.

## 설치 방법

1. `StarsandIsland_KoreanPatch_2026-04-07_v1.0.5.zip`을 다운로드합니다.
2. 압축을 원하는 위치에 풉니다.
3. `스타샌드 아일랜드 한글패치 런처.exe` 또는 `Start_Korean_Patch.bat`를 실행합니다.
4. 자동 탐지에 실패하면 런처에서 게임 `Content` 폴더 또는 게임 루트 폴더를 직접 선택합니다.
5. 설치 후 게임 내 언어를 `English`로 선택하면 한글이 적용됩니다.

## 복원 방법

- GUI 런처의 `원본 복구` 버튼 또는 `Restore_Original_589829.bat`를 실행하면 텍스트 번들과 폰트 번들을 원본으로 복원합니다.

## 특징

- 완성된 게임 번들 전체를 배포하지 않습니다.
- 설치 시 로컬 `589829.ab`에 번역 JSON을 직접 주입합니다.
- 게임의 `English` 언어 슬롯을 한글로 덮어쓰는 방식입니다.
- Steam/Xbox 경로 자동 탐지를 지원합니다.
- `v1.0.5`는 GUI 런처 구조를 유지하면서, `2026.13.47.0` 원문 대응분과 user-facing hotfix를 추가로 반영합니다.

## 이번 버전 주요 내용

- `2026.13.47.0` 원문 diff 반영
  - `added 327`
  - `removed 94`
  - `changed 193`
- user-facing hotfix 반영
  - `Starsand Shop`, `Golden Cudgel`, `Weed Barrier`, `Great Sage`, `Workbench/UI`
  - `Caiyun`, `Taohua`, `Shenti`
- 제작 UI 호환 보강 유지
- 최신 인게임 inject JSON 재생성 및 로컬 번들 재패치 반영

## 대표 수정 항목

- `Golden Cudgel` -> `여의금고봉`
- `Weed Barrier` -> `잡초 방지포`
- `Starsand Shop` -> `스타샌드 상점`
- `Complete` -> `완료`
- `Worktable I / II` -> `작업대 I / II`
- `Cotton / Sunflower / Sweet Potato` -> `목화 / 해바라기 / 고구마`
- `Community Center` -> `커뮤니티 센터`
- `Lex Woodworks` 설계도 획득처 문구 현지화

## 안내

- 비공식 팬 패치이며 개발사/퍼블리셔와 무관합니다.
- 게임 업데이트로 번들 구조가 바뀌면 새 패치가 필요할 수 있습니다.
- 설치 후 게임 내 언어는 반드시 `English`를 선택해야 합니다.
