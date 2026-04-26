# 스타샌드 아일랜드 한글패치 v1.0.8

## 주요 변경
- Steam 설치본 buildid `22932871` 대응 추가
- Steam/Xbox의 589829 원문 차이를 반영해 플랫폼별 텍스트 패치 JSON 분리
- 설치기가 선택된 게임 경로를 기준으로 Steam/Xbox를 자동 판별해 알맞은 패치 적용
- Xbox `2026.16.54.0` 기준 기존 v1.0.7 번역/폰트/이름 정리 유지
- Steam 신규 DLC/의상/달팽이 펌프/플랫폼 UI/획득처 변경분 반영

## Steam 원문 반영
- Steam 기준 원문 추출: `589829_en.steam_20260426.json`
- Xbox 기준 대비 차이: `added 196 / removed 377 / changed 605`
- Steam 전용 inject: `patch/platforms/steam/589829_ko.ingame.inject.json`
- Xbox 전용 inject: `patch/platforms/xbox/589829_ko.ingame.inject.json`

## 검증
- 실제 Steam 경로 preflight: `supported_steam_build`
- 실제 Xbox 경로 preflight: `supported_version`
- Steam 원본 번들 복사본에 Steam inject 주입 성공
- Steam localization report: `unmapped 0`
- Python tests: `20 passed`
- launcher core tests: `15 passed`
- zip package: 21 font bundles, Steam/Xbox inject included, raw `589829.ab` not included

## 설치
기존 런처를 실행하면 최신 stable 릴리스를 확인하고 다운로드 후 설치할 수 있습니다.

직접 설치할 경우 ZIP을 풀고 `스타샌드 아일랜드 한글패치 런처.exe` 또는 `Start_Korean_Patch.bat`를 실행하세요.
