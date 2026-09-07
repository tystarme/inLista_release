# inLista 릴리스

서버 없이 마크다운 `.md` 파일 하나에 쌓아 가는 로컬 우선 할 일 앱 inLista 의 정식 배포 저장소입니다.

## 최신 버전 · 1.6.0

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.6.0/inLista-Setup-1.6.0.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.6.0/inLista-1.6.0.apk)

## 릴리스 기록

<!-- INLISTA_RELEASES_START -->
<!-- INLISTA_RELEASE:1.6.0:START -->
### inLista 1.6.0

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.6.0/inLista-Setup-1.6.0.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.6.0/inLista-1.6.0.apk)

- **기기 간 동기화의 첫 단계가 열렸습니다.** 설정 → 서버 동기화에서 로그인하고 이 기기를 서버에 연결할 수 있습니다. **계정은 inLoco 와 같은 것을 씁니다** — inLoco 에 이미 가입했다면 그 이메일과 비밀번호를 그대로 쓰세요.
- **연결 확인** 버튼을 누르면 서버까지 실제로 한 바퀴 돌아 잘 닿는지 알려 줍니다.
- **아직 파일이 오가지는 않습니다.** 계정과 연결까지 준비된 단계이고, 실제로 맞추는 일은 다음 업데이트에서 켜집니다. 그때까지 할 일은 지금처럼 이 기기의 파일에만 있습니다.
- 동기화 스위치는 **기본이 꺼짐**입니다. 로컬 전용이 이 앱의 기본값이고, 켜는 것은 선택입니다.
<!-- INLISTA_RELEASE:1.6.0:END -->

<!-- INLISTA_RELEASE:1.5.1:START -->
### inLista 1.5.1

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.5.1/inLista-Setup-1.5.1.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.5.1/inLista-1.5.1.apk)

- **앱 아이콘이 생겼습니다.** 홈 화면·시작 메뉴·작업 표시줄에 inLista 로고가 뜹니다.
- **Windows 에서 메모를 쓸 때 한글이 뒤섞이던 문제**를 우회했습니다. Flutter 엔진의 한글 입력기 버그라 앱 코드로는 못 고쳐서, 메모 편집칸만 WebView2 로 바꿔 브라우저의 입력기 경로를 쓰게 했습니다. Android 는 원래 멀쩡해 그대로입니다.
- **삭제 알림이 화면에서 안 내려가던 문제**를 고쳤습니다. 실행취소 버튼이 달린 알림은 스스로 사라지지 않는 것이 Flutter 기본값이었습니다. 이제 6초 뒤 내려가고, 잇달아 지워도 알림이 줄 서지 않습니다.
- **홈 위젯이 "로드 중…" 에서 멈춰 있던 문제**를 고쳤습니다. 목록이 뜨고 체크도 됩니다. 크기도 **2×2 부터** 원하는 대로 조절할 수 있습니다(전에는 가로 3 세로 2 고정).
- 메모 편집칸을 눌렀을 때 제목 표시줄이 흐려지던 것을 고쳤습니다.
- 기기 간 동기화를 위한 준비 작업이 들어갔습니다. **아직 켜지지 않으며** 지금까지처럼 완전히 로컬로 동작합니다.
<!-- INLISTA_RELEASE:1.5.1:END -->

<!-- INLISTA_RELEASE:1.5.0:START -->
### inLista 1.5.0

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.5.0/inLista-Setup-1.5.0.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.5.0/inLista-1.5.0.apk)

- **앱 아이콘이 생겼습니다.** 홈 화면·시작 메뉴·작업 표시줄에 inLista 로고가 뜹니다.
- **Windows 에서 메모를 쓸 때 한글이 뒤섞이던 문제**를 우회했습니다. Flutter 엔진의 한글 입력기 버그라 앱 코드로는 못 고쳐서, 메모 편집칸만 WebView2 로 바꿔 브라우저의 입력기 경로를 쓰게 했습니다. Android 는 원래 멀쩡해 그대로입니다.
- **삭제 알림이 화면에서 안 내려가던 문제**를 고쳤습니다. 실행취소 버튼이 달린 알림은 스스로 사라지지 않는 것이 Flutter 기본값이었습니다. 이제 6초 뒤 내려가고, 잇달아 지워도 알림이 줄 서지 않습니다.
- **홈 위젯이 "로드 중…" 에서 멈춰 있던 문제**를 고쳤습니다. 목록이 뜨고 체크도 됩니다. 크기도 **2×2 부터** 원하는 대로 조절할 수 있습니다(전에는 가로 3 세로 2 고정).
- 메모 편집칸을 눌렀을 때 제목 표시줄이 흐려지던 것을 고쳤습니다.
- 기기 간 동기화를 위한 준비 작업이 들어갔습니다. **아직 켜지지 않으며** 지금까지처럼 완전히 로컬로 동작합니다.
<!-- INLISTA_RELEASE:1.5.0:END -->
<!-- INLISTA_RELEASES_END -->
