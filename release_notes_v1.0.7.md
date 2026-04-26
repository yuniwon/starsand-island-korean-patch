# 스타샌드 아일랜드 한글패치 v1.0.7

## 주요 변경
- 게임 버전 `2026.16.54.0` 기준 호환성 확인
- 최신 번역 JSON 재생성 및 배포본 반영
- SUIT soft-weight 폰트 번들 반영
- `FishTank` 계열은 수족관, `FishPond` 계열은 어항으로 명칭 통일
- 양어장, 큐브 수조, 발광 해파리 어항 등 이전 명칭 drift 정리
- 설치 preflight 지원 기준을 `2026.16.54.0`으로 갱신

## 검증
- localization pytest: `27 passed`
- launcher core tests: `15 passed`
- QA gate: tone `0`, glossary `0`, UI token mismatch `0`
- package preflight: `2026.16.54.0 supported_version`
- zip package: 21 font bundles, inject JSON included, raw `589829.ab` not included

## 설치
기존 런처를 실행하면 최신 stable 릴리스를 확인하고 다운로드 후 설치할 수 있습니다.

직접 설치할 경우 ZIP을 풀고 `스타샌드 아일랜드 한글패치 런처.exe` 또는 `Start_Korean_Patch.bat`를 실행하세요.
