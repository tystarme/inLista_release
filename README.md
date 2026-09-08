# inLista 릴리스

서버 없이 마크다운 `.md` 파일 하나에 쌓아 가는 로컬 우선 할 일 앱 inLista 의 정식 배포 저장소입니다.

## 최신 버전 · 1.10.1

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.10.1/inLista-Setup-1.10.1.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.10.1/inLista-1.10.1.apk)

## 릴리스 기록

<!-- INLISTA_RELEASES_START -->
<!-- INLISTA_RELEASE:1.10.1:START -->
### inLista 1.10.1

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.10.1/inLista-Setup-1.10.1.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.10.1/inLista-1.10.1.apk)

- **메모 편집칸이 비어 보이던 문제를 고쳤습니다.** Windows 메모 편집칸으로 보내는 메시지가 형식이 어긋나 **전부 버려지고 있었습니다** — 본문을 넣어 주는 신호도요. 그래서 이미 써 둔 글이 편집 모드에서 없는 것처럼 보였습니다.
- 입력한 글이 저장되지 않고 읽기 모드에서 사라지던 것도 같은 뿌리였습니다. 읽기 ↔ 편집을 오갈 때도 편집칸을 없앴다 다시 만들지 않습니다.
- **1.10.0의 자동 저장이 그 빈 화면을 파일에 반영해 메모를 지울 수 있었습니다.** 자동 저장은 이제 **본문을 지우지 못합니다** — 있던 글을 비우는 저장은 저장 버튼을 직접 눌러야 합니다.
- 1.10.0을 쓰셨다면 바로 올려 주세요.
<!-- INLISTA_RELEASE:1.10.1:END -->

<!-- INLISTA_RELEASE:1.10.0:START -->
### inLista 1.10.0

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.10.0/inLista-Setup-1.10.0.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.10.0/inLista-1.10.0.apk)

- **메모를 전체화면으로 쓸 수 있습니다.** 메모 창 위쪽 ⤢ 버튼을 누르면 진짜 본문 화면으로 넘어갑니다. 쓰던 글과 편집 상태를 그대로 들고 갑니다.
- **자동으로 저장됩니다.** 1.2초쯤 손을 멈추면 저장하고, 창을 어떻게 닫든 — 바깥을 누르든, 뒤로 가든, X를 누르든 — 저장하고 닫습니다. 이제 길게 쓰다 실수로 나가도 잃지 않습니다.
- **읽기 ↔ 편집을 오갈 때 쓰던 글이 사라지던 문제**를 고쳤습니다. Windows 메모 편집칸이 한글 조합 중에는 글을 밖으로 내보내지 않았는데, 조합이 끝났다는 신호가 오지 않으면 그대로 굳어 한 글자도 나가지 않았습니다.
- 메모를 거듭 저장할 때 **본문 조각이 하나씩 쌓이던 문제**를 고쳤습니다. 겉으로는 안 보이지만 파일에 아무도 가리키지 않는 본문이 남았습니다.
- 저장 상태를 헤더에 보여 줍니다 — `저장 중` · `저장됨`.
<!-- INLISTA_RELEASE:1.10.0:END -->

<!-- INLISTA_RELEASE:1.9.1:START -->
### inLista 1.9.1

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.9.1/inLista-Setup-1.9.1.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.9.1/inLista-1.9.1.apk)

- 충돌 사본 화면의 무리 이름을 **어디에 있는 할 일인지**가 먼저 보이게 바꿨습니다 — `서버 쪽에만 있음 · 가져오기`, `이 기기에만 있음 · 지우기`, `양쪽이 다름 · 서버 쪽으로`.
- "이 기기에만 있음"이 왜 기본으로 꺼져 있는지 그 자리에 적었습니다. 다른 기기에서 지운 것일 수도, 여기서 방금 추가해 저쪽이 아직 못 본 것일 수도 있어 앱이 구분할 수 없습니다.
<!-- INLISTA_RELEASE:1.9.1:END -->

<!-- INLISTA_RELEASE:1.9.0:START -->
### inLista 1.9.0

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.9.0/inLista-Setup-1.9.0.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.9.0/inLista-1.9.0.apk)

- **충돌을 앱 안에서 합칠 수 있습니다.** 설정 → 동기화 → **충돌 사본**에서 저쪽에만 있는 할 일을 하나씩 골라 가져오고, 내 쪽에서 지울 것도 골라 지웁니다.
- 완료 표시나 시각만 다른 할 일은 따로 모아 `미완료 → 완료`처럼 무엇이 달라지는지 보여 줍니다.
- **가져오기만 미리 켜져 있습니다.** 다른 기기에서 적은 할 일을 놓치는 쪽이 가장 흔한 손해라서입니다. 지우기와 바꾸기는 직접 켜야 합니다.
- **적용해도 사본은 남습니다.** 잘못 골랐을 때 되돌아갈 곳이 있어야 하기 때문입니다. 사본은 다 확인한 뒤 따로 지웁니다.
- 내보내기에 충돌 사본도 함께 나옵니다 — 다른 편집기로 견주고 싶을 때 쓰세요.
- 지금까지는 사본이 앱 폴더 안에 있어 폰에서 열 방법이 없었습니다. 그 구멍을 메웠습니다.
<!-- INLISTA_RELEASE:1.9.0:END -->

<!-- INLISTA_RELEASE:1.8.1:START -->
### inLista 1.8.1

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.8.1/inLista-Setup-1.8.1.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.8.1/inLista-1.8.1.apk)

- **폰에서 로그인이 안 되던 문제를 고쳤습니다.** 앱에 인터넷 권한이 빠져 있었습니다 — 지금까지 완전히 로컬로만 동작하던 앱이라 넣을 일이 없었고, PC에서는 멀쩡해서 늦게 발견됐습니다.
- **동기화 결과에 무엇이 바뀌었는지 파일 이름까지 나옵니다.** "올림 2"만 보면 무엇이 올라갔는지 알 수 없었습니다. 충돌 사본과 치워 둔 파일은 어디로 갔는지도 함께 적습니다.
- **좁은 화면에서 날짜 구간이 잘리던 것**을 고쳤습니다. `2026.09.07 - 2026.09.13`의 뒷부분이 `…`로 잘렸습니다. 날짜와 설정·범위 버튼을 아랫줄로 옮겨 한 줄을 넉넉히 쓰게 했습니다.
- 동기화 설명 문구를 고쳤습니다 — "앞으로 돌아올 때"가 무슨 뜻인지 알기 어려워 "다른 앱 갔다 돌아올 때"로 바꿨습니다.
<!-- INLISTA_RELEASE:1.8.1:END -->

<!-- INLISTA_RELEASE:1.8.0:START -->
### inLista 1.8.0

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.8.0/inLista-Setup-1.8.0.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.8.0/inLista-1.8.0.apk)

- **동기화가 알아서 됩니다.** 켜 두면 앱을 켤 때 · 앞으로 돌아올 때 · 할 일을 고친 뒤 잠잠해지면 스스로 맞춥니다. 더 이상 버튼을 누르지 않아도 됩니다.
- 한 글자마다 서버로 보내지 않습니다. 손을 뗀 뒤 한 번만 가고, 앞뒤로 오가며 앱을 껐다 켜도 최소 2분 간격을 지킵니다.
- **자동 동기화가 실패해도 화면을 막지 않습니다.** 할 일을 적던 손을 멈추게 하지 않기 위해서입니다. 무엇이 잘못됐는지는 동기화 화면에서 「지금 동기화」를 눌러 보면 나옵니다.
- 서버에 쌓인 옛 버전 기록을 이따금 정리합니다(경로마다 최근 20벌). 되살리기는 그대로 되면서 용량은 안 늘어납니다.
- 동기화는 여전히 **기본이 꺼짐**입니다. 켜지 않으면 타이머조차 돌지 않고, 데이터가 기기 밖으로 나가지 않습니다.
<!-- INLISTA_RELEASE:1.8.0:END -->

<!-- INLISTA_RELEASE:1.7.0:START -->
### inLista 1.7.0

- [Windows Setup](https://github.com/tystarme/inLista_release/releases/download/v1.7.0/inLista-Setup-1.7.0.exe)
- [Android APK](https://github.com/tystarme/inLista_release/releases/download/v1.7.0/inLista-1.7.0.apk)

- **기기 간 동기화가 실제로 동작합니다.** 설정 → 서버 동기화를 켠 뒤 **지금 동기화**를 누르면 할 일과 메모가 서버와 맞춰집니다. 폰과 PC에서 같은 목록을 볼 수 있습니다.
- **두 기기에서 같은 날짜를 고쳤을 때 어느 쪽도 버리지 않습니다.** 서버 쪽 내용을 `conflicts/` 폴더에 사본으로 남기고, 어디에 뒀는지 화면에 적어 줍니다. 자동으로 합치지 않는 이유는 조용히 할 일이 사라지는 것보다 파일이 두 개인 편이 낫기 때문입니다.
- **서버에서 지워진 파일도 영구삭제하지 않습니다.** 다른 기기에서 지운 메모는 `.inlista/removed/` 로 옮겨 두어 되돌릴 수 있습니다.
- 올라가는 것은 `todo.md` 와 메모뿐입니다. **휴지통·설정·충돌 사본은 올라가지 않습니다.**
- 동기화 도중 어디까지 왔는지, 끝난 뒤 무엇이 오갔는지 보여 줍니다. 실패한 파일이 있으면 감추지 않고 그대로 적습니다.
- 동기화는 여전히 **기본이 꺼짐**이고, 켜도 직접 눌러야 맞춰집니다. 자동으로 맞추는 시점은 다음 업데이트입니다.
<!-- INLISTA_RELEASE:1.7.0:END -->

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
