# 스타샌드 아일랜드 한글패치 v1.0.12

v1.0.12는 배포용 패치의 업데이트 신뢰성을 보강한 버전입니다.

## 이번 버전에서 고친 것
- `Start_Korean_Patch.bat`에 작은 부트스트랩 업데이터를 추가했습니다.
- `Start_Korean_Patch.bat` 실행 시 최신 stable 릴리스를 먼저 확인하고, 새 버전이 있으면 ZIP을 받아 현재 폴더의 패치 파일과 런처 파일을 최신 상태로 교체한 뒤 런처를 실행하도록 했습니다.
- GitHub release asset에 SHA256 digest가 있으면 다운로드한 ZIP의 해시를 확인합니다.
- ZIP이 깨졌거나 GitHub digest와 다르면 압축 해제와 설치를 진행하지 않습니다.
- GUI 런처의 다운로드 경로에도 같은 SHA256 검사를 추가했습니다.

## 사용 방법
- `스타샌드 아일랜드 한글패치 런처.exe` 또는 `Start_Korean_Patch.bat`를 실행하세요.
- 새 버전이 있으면 부트스트랩 또는 런처가 자동으로 최신 배포본을 확인합니다.
- 설치 후 게임 내 언어는 반드시 `English`로 선택해야 한글이 표시됩니다.

## 포함된 이전 수정
- v1.0.11의 캐시 우선순위/self-update 흐름 개선 포함
- v1.0.10의 `warning` 속성 오류 설치 실패 수정 포함
- v1.0.9의 Steam 0.4.9647 제작/가공 UI 대응 포함
- Steam/Xbox 플랫폼별 한글 패치 자동 선택 유지

## 검증
- Launcher core tests: `22 passed`
- Bootstrap/release pytest: 통과
- Release package tests: 통과
- 실제 Xbox 경로 preflight: `supported_version 2026.16.54.0`
- 실제 Steam 경로 preflight: `supported_steam_build 22932871`
