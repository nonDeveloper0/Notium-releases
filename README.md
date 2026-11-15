# 🗒️ Notium

내 기기에 기록하고, 원할 때 내 Google Drive 앱 전용 공간에 동기화하는 개인용 노트 앱입니다.

> **소스코드는 포함되어 있지 않습니다.** 이 저장소는 Notium 배포 파일과 릴리스 정보를 제공합니다.

## ✨ 주요 기능

- 페이지·폴더 트리와 블록 편집기
- 링크·백링크, 태그·속성, 일지와 할 일
- 첨부 모아보기, 본문 검색, 버전 기록, 휴지통, 백업
- Markdown·Notion 가져오기 및 내보내기, 즐겨찾기, 화면 분할
- 선택적 Google Drive 동기화와 Windows 데스크톱 MCP AI 연결

## ⬇️ 다운로드

| 플랫폼 | 파일 | 다운로드 |
| --- | --- | --- |
| 🪟 Windows | `Notium-Windows-x64-setup.exe` | [설치 파일](https://github.com/nonDeveloper0/Notium-releases/releases/latest/download/Notium-Windows-x64-setup.exe) |
| 🤖 Android | `Notium-Android-arm64.apk` | [APK](https://github.com/nonDeveloper0/Notium-releases/releases/latest/download/Notium-Android-arm64.apk) |
| 🍎 iOS | 준비 중 | 현재 제공하지 않습니다. |

버전별 파일은 [전체 릴리스](https://github.com/nonDeveloper0/Notium-releases/releases)에서 받을 수 있습니다.

📦 [전체 릴리스 보기](https://github.com/nonDeveloper0/Notium-releases/releases)

## 🛠️ 설치 방법

### Windows

1. 설치 파일을 내려받아 실행합니다.
2. SmartScreen 경고가 표시되면 **추가 정보 → 실행**을 선택합니다. Windows 코드 서명이 적용되지 않아 경고가 나타날 수 있습니다.
3. 설치 안내에 따라 진행합니다.

### Android

1. APK를 내려받아 엽니다.
2. Android가 요청하면 해당 브라우저나 파일 앱에 **출처를 알 수 없는 앱 설치**를 허용합니다.
3. 설치를 마친 뒤 필요하면 해당 설치 권한을 다시 끕니다.

## 🚀 첫 실행

1. **PC:** 설정 → 계정·동기화 → **Google 계정으로 동기화**를 선택합니다.
2. **PC:** **이 PC의 노트로 새 저장소 만들기**를 선택합니다.
3. **폰:** PC와 같은 Google 계정으로 로그인한 뒤 **기존 저장소에 연결**을 선택합니다.
4. 다른 PC에서도 같은 Google 계정으로 로그인하고 **기존 저장소에 연결**을 선택합니다.

Drive 동기화는 사용자의 Drive 앱 전용 숨김 공간을 사용합니다. 일반 Drive 파일에는 접근하지 않습니다.

## 🤖 AI 연결

Windows 데스크톱에서 Claude Desktop, Claude Code, Codex, Cursor, VS Code Copilot, Gemini CLI에 Notium MCP를 연결할 수 있습니다. 처음 실행할 때 이 PC에서 찾은 앱을 골라 연결하거나, 나중에 설정 → AI 연결에서 연결합니다. 기본은 읽기 전용이며 쓰기는 설정과 승인에 따릅니다. 연결한 AI 서비스가 받은 내용은 해당 서비스의 정책을 따릅니다.

## 🔒 개인정보·데이터

- [개인정보처리방침](https://nondeveloper0.github.io/Notium-site/privacy.html)
- [이용약관](https://nondeveloper0.github.io/Notium-site/terms.html)
- [계정·데이터 삭제 안내](https://nondeveloper0.github.io/Notium-site/data-deletion.html)

## ⚠️ 베타 안내 및 주의사항

Notium은 개인이 만든 베타 버전이며, 있는 그대로 제공됩니다. 프로그램 오류, 동기화 문제, 기기 고장, 클라우드 계정·용량 문제 등으로 노트나 첨부 파일이 손상되거나 사라져도 개발자는 복구하거나 책임지지 않습니다. **중요한 자료는 항상 따로 백업해 두세요.** (PC: 설정 → 데이터 → 백업)

## 📢 안내사항

- 베타 버전입니다. 기능과 호환성이 바뀔 수 있습니다.
- 동기화는 별도 백업을 대신하지 않습니다.
- v0.2.1부터 Android 패키지 이름이 바뀌어 이전 Android 앱 위에 덮어 설치되지 않습니다. 이전 앱을 지우고 새로 설치한 뒤 같은 Google 계정으로 다시 연결하세요.
- 릴리스의 `SHA256SUMS.txt`를 사용해 내려받은 파일의 SHA-256 해시를 확인할 수 있습니다.
- iOS 앱은 아직 제공하지 않습니다. Windows 설치 파일에는 코드 서명이 적용되지 않았습니다.

## 💬 문의

버그 제보와 문의는 [GitHub Issues](https://github.com/nonDeveloper0/Notium-releases/issues)에 남겨 주세요. 공개 게시물에 노트 내용, 개인정보, 비밀번호 또는 인증 토큰을 올리지 마세요.
