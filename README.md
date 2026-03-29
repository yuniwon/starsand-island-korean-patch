# Starsand Island Korean Patch

비공식 스타샌드 아일랜드 한글패치 배포 저장소입니다.

## 최신 배포본

- 패치 버전: `v1.0.4`
- 최신 원문 동기화 기준 게임 버전: `2026.11.43.0`
- 기존 검증 기준 게임 버전: `2026.5.32.0`
- 지원 플랫폼: `Steam / Xbox PC`

최신 배포 파일은 Releases 탭에서 받을 수 있습니다.

## 설치 방법

1. `StarsandIsland_KoreanPatch_2026-03-30_v1.0.4.zip`을 다운로드합니다.
2. 압축을 원하는 위치에 풉니다.
3. `Install_Korean_Patch.bat`를 실행합니다.
4. 자동 탐지에 실패하면 게임 `Content` 폴더 또는 게임 루트 폴더를 직접 입력합니다.
5. 설치 후 게임 내 언어를 `English`로 선택하면 한글이 적용됩니다.

## 복원 방법

- `Restore_Original_589829.bat`를 실행하면 텍스트 번들과 폰트 번들을 원본으로 복원합니다.

## 특징

- 완성된 게임 번들 전체를 배포하지 않습니다.
- 설치 시 로컬 `589829.ab`에 번역 JSON을 직접 주입합니다.
- 게임의 `English` 언어 슬롯을 한글로 덮어쓰는 방식입니다.
- Steam/Xbox 경로 자동 탐지를 지원합니다.
- `v1.0.4`는 `v1.0.3`의 설치 구조를 유지하면서, `2026.11.43.0` 대응분 위에 post-update hotfix를 추가로 반영합니다.

## 이번 버전 주요 내용

- `2026.11.43.0` 원문 대응 유지
- post-update user-facing hotfix 반영
  - `Caiyun`, `Taohua`, `Shenti` 신규 영어 문장 클러스터 정리
  - `DialogLib` 당화 반응 일부 정리
  - `Timber*` 가구군, `Captain Shu`, `Cotton / Sunflower / Sweet Potato`, 분실물/상점 우편 등 사용자 노출 영어 다수 정리
- 제작 UI 호환 보강 유지
  - `UIWorkBench` alias
  - `WorkBench.TrackingGroup`, `WorkBench.CurrentWorkBench`
- 최신 인게임 inject JSON 재생성 및 로컬 번들 재패치 반영

## 대표 수정 항목

- `Timber View Desk` -> `팀버 뷰 책상`
- `Timbervine Wardrobe` -> `팀버바인 옷장`
- `Woven Rattan Sofa` -> `라탄 짜임 소파`
- `Captain Shu Watering Can` -> `대장 슈 물뿌리개`
- `Captain Shu Cruiser` -> `대장 슈 크루저`
- `Captain Shu Skateboard` -> `대장 슈 스케이트보드`
- `Cotton / Sunflower / Sweet Potato` -> `목화 / 해바라기 / 고구마`
- `Community Center` -> `커뮤니티 센터`
- `Lex Woodworks` 설계도 획득처 문구 현지화

## 안내

- 비공식 팬 패치이며 개발사/퍼블리셔와 무관합니다.
- 게임 업데이트로 번들 구조가 바뀌면 새 패치가 필요할 수 있습니다.
- 설치 후 게임 내 언어는 반드시 `English`를 선택해야 합니다.
