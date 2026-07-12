# RocketSnapshot 배포 저장소

RocketSnapshot(Android WebView API 캡처·inspect 도구)의 **설치 파일 배포 전용** 저장소입니다.
소스 코드는 별도 저장소에서 관리됩니다.

## 설치

[Releases](https://github.com/computer8938/rocket-snapshot-release/releases/latest)에서 다운로드:

- **`RocketSnapshot-<버전>-setup.exe`** — 설치형(권장). 설치하면 백그라운드 상주 + 자동 업데이트가 동작합니다.
- `RocketSnapshot-<버전>-portable.exe` — 무설치 실행형. 자동 업데이트는 지원하지 않습니다.

폰(Android) 컴패니언 앱은 별도 설치가 필요 없습니다 — PC 앱 설치 후
설정 → "폰 앱 설치 → QR 코드 표시"로 받거나, 폰 연결 시 자동 설치/업데이트됩니다.

## 자동 업데이트

설치형은 이 저장소의 최신 릴리스를 주기적으로 확인해 자동 갱신됩니다.
(`latest.yml`, `.blockmap`은 자동 업데이트용 메타데이터 파일입니다 — 직접 받을 필요 없음)

## 첫 실행 안내

- "알 수 없는 게시자" 경고가 뜨면: **추가 정보 → 실행**
- 방화벽 허용 팝업이 뜨면: **액세스 허용** (폰이 PC를 찾는 데 필요)
