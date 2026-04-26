# 스타샌드 아일랜드 한글패치 v1.0.10

v1.0.10은 v1.0.9 설치 중 일부 환경에서 발생한 설치 실패를 고친 긴급 수정 버전입니다.

## 이번 버전에서 고친 것
- v1.0.9 설치 중 `[STEP] Preflight 1/6: 게임 경로가 유효합니다.` 다음에 멈추며 아래 오류가 나오던 문제를 수정했습니다.
  - `The property 'warning' cannot be found on this object.`
- 지원 범위 경고가 있는 항목과 없는 항목을 모두 안전하게 처리하도록 설치 스크립트를 수정했습니다.
- 기존 v1.0.6 런처가 이미 받아 둔 `cache\v1.0.9`를 재사용하지 않도록 새 태그 `v1.0.10`으로 배포했습니다.

## v1.0.9 내용도 그대로 포함
- Steam 2026-04-24 업데이트 이후 숯가마/용광로 같은 가공 UI에서 `$$UI:UIQueueProcessView/...$$` 문구가 보이던 문제 대응
- Steam용 새 제작/가공 UI 문구 포함
  - 예: `가공 시간:`, `필요`, `획득처:`, `가격:`, `모두 수령`
- Steam/Xbox 설치 경로 자동 판별 및 플랫폼별 한글 패치 적용
- GUI 런처에서 지원 범위 경고 후 숨은 `y/N` 입력을 기다리던 문제 수정

## 업데이트 방법
- 기존 런처를 다시 실행하면 최신 stable 릴리스를 확인하고 다운로드 후 설치할 수 있습니다.
- 직접 설치할 경우 ZIP을 풀고 `스타샌드 아일랜드 한글패치 런처.exe` 또는 `Start_Korean_Patch.bat`를 실행하세요.
- 설치 후 게임 내 언어는 반드시 `English`로 선택해야 한글이 표시됩니다.

## 검증
- v1.0.9 재현 오류 회귀 테스트 추가
- 실제 Xbox 경로 preflight: `supported_version 2026.16.54.0`
- 실제 Steam 경로 preflight: `supported_steam_build 22932871`
- Steam 제작/가공 UI 핵심 키 확인
- Python tests: `25 passed`
- Launcher core tests: `15 passed`
