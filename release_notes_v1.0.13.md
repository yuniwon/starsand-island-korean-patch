# 스타샌드 아일랜드 한글패치 v1.0.13

v1.0.13은 런처 업데이트 흐름을 다시 정리한 배포본입니다.

## 이번 버전에서 고친 것
- 기본 실행 파일을 `스타샌드 아일랜드 한글패치 런처.exe`로 명확히 정리했습니다.
- 런처 EXE를 실행하면 시작 직후 최신 stable 릴리스를 확인합니다.
- 새 런처/패치 버전이 있으면 다운로드 여부를 묻고, 동의하면 ZIP을 내려받아 SHA256 digest를 확인합니다.
- 검증이 끝나면 현재 폴더의 `patch`, `tools`, 루트 스크립트와 런처 EXE를 최신 파일로 교체한 뒤 새 런처를 다시 실행합니다.
- 다운로드 중에는 런처 화면에서 진행률이 표시됩니다.
- `Start_Korean_Patch.bat`는 유지하지만, 이제 기본 안내 대상이 아니라 EXE 실행이 막히는 환경을 위한 보조 실행 파일입니다.

## 사용 방법
- ZIP을 풀고 `스타샌드 아일랜드 한글패치 런처.exe`를 실행하세요.
- 새 버전이 있으면 런처가 직접 알려주며, 동의하면 최신 런처로 교체한 뒤 다시 열립니다.
- 다시 열린 최신 런처에서 `설치/업데이트`를 누르면 됩니다.
- 설치 후 게임 내 언어는 반드시 `English`로 선택해야 한글이 표시됩니다.

## 포함된 이전 수정
- v1.0.12의 ZIP SHA256 digest 검증 포함
- v1.0.11의 캐시 우선순위/self-update 흐름 개선 포함
- v1.0.10의 `warning` 속성 오류 설치 실패 수정 포함
- v1.0.9의 Steam 0.4.9647 제작/가공 UI 대응 포함
- Steam/Xbox 플랫폼별 한글 패치 자동 선택 유지

## 검증
- Launcher core tests: `26 passed`
- WinForms Release build: 통과
- Release package tests: 통과
- Bootstrap/release pytest: 통과
- 실제 Xbox 경로 preflight: `supported_version 2026.16.54.0`
- 실제 Steam 경로 preflight: `supported_steam_build 22932871`
