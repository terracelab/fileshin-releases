# 파일의신 설치 파일

파일의신 데스크톱 앱의 설치 파일과 업데이트 정보를 두는 곳입니다. 소스 코드는 여기에 없습니다.

- 앱은 설정 › 정보 › "업데이트 확인"을 누를 때 이곳의 `latest.json`을 읽고, 새 판이 있으면 설치 파일을 받습니다.
- 받은 설치 파일은 앱에 든 공개 키로 서명을 확인한 뒤에만 설치합니다.
- 지금은 시험판입니다. 코드서명이 없어 처음 설치할 때 운영체제가 경고를 보일 수 있습니다.

| 파일 | 쓰임 |
| --- | --- |
| `fidx-<판>-windows-x64-setup.exe` | Windows 설치 파일 |
| `fidx-<판>-macos-universal.dmg` | macOS 설치 파일(Apple Silicon · Intel) |
| `fidx-<판>-macos-universal.app.tar.gz` | macOS 앱 안 업데이트용 |
| `latest.json` | 업데이트 정보 |
