<div align="center">

<img src="assets/notium-icon.png" width="96" height="96" alt="Notium">

# Notium

**내 기기에 먼저 기록하고, 원할 때 내 Google Drive와 동기화하는 개인 노트 앱**

[![Latest release](https://img.shields.io/github/v/release/nonDeveloper0/Notium-releases?label=%EC%B5%9C%EC%8B%A0%20%EB%B2%84%EC%A0%84&color=17666b)](https://github.com/nonDeveloper0/Notium-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/nonDeveloper0/Notium-releases/total?label=%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C&color=4c6a6c)](https://github.com/nonDeveloper0/Notium-releases/releases)
![Platforms](https://img.shields.io/badge/platform-Windows%20%7C%20Android-5b6770)
![Status](https://img.shields.io/badge/status-beta-c58a1b)

[다운로드](#다운로드) · [새 기능](#v023-새-기능) · [시작하기](#시작하기) · [AI와 함께 쓰기](#ai와-함께-쓰기) · [개인정보](#개인정보와-데이터) · [문의](#문의)

</div>

---

> [!NOTE]
> 이 저장소는 Notium의 **설치 파일과 릴리스 정보**만 제공합니다. 소스 코드는 포함되어 있지 않습니다.

## 다운로드

<table>
  <tr>
    <th align="left">플랫폼</th>
    <th align="left">파일</th>
    <th align="left">비고</th>
  </tr>
  <tr>
    <td><b>Windows</b> 10/11 x64</td>
    <td>
      <a href="https://github.com/nonDeveloper0/Notium-releases/releases/latest/download/Notium-Windows-x64-setup.exe">
        <img src="https://img.shields.io/badge/Windows-%EC%84%A4%EC%B9%98%20%ED%8C%8C%EC%9D%BC-17666b?style=for-the-badge&logo=windows&logoColor=white" alt="Windows 설치 파일">
      </a>
    </td>
    <td>앱 안에서 자동 업데이트</td>
  </tr>
  <tr>
    <td><b>Android</b> arm64</td>
    <td>
      <a href="https://github.com/nonDeveloper0/Notium-releases/releases/latest/download/Notium-Android-arm64.apk">
        <img src="https://img.shields.io/badge/Android-APK-17666b?style=for-the-badge&logo=android&logoColor=white" alt="Android APK">
      </a>
    </td>
    <td>이전 버전 위에 덮어 설치</td>
  </tr>
  <tr>
    <td><b>iOS</b></td>
    <td colspan="2">아직 제공하지 않습니다.</td>
  </tr>
</table>

버전별 파일과 변경 내역은 [Releases](https://github.com/nonDeveloper0/Notium-releases/releases)에 있습니다. 내려받은 파일은 릴리스의 `SHA256SUMS.txt`로 확인할 수 있습니다.

## v0.2.6 새 기능

- **더 간결한 설정:** 자주 쓰지 않는 항목은 각 탭의 접힌 **고급**으로 옮겼습니다. 없어진 기능은 없습니다.
- **폰:** 설정 탭을 좌우로 밀어 넘기고, 오늘 일지는 문서 목록 맨 위 줄에서 엽니다.
- **기기 목록:** 이름이 같은 기기는 한 줄로, 연결 해제한 기기는 다시 켜면 숨깁니다.
- **업데이트 알림**이 더 안정적으로 뜨고, 작은 글자와 버튼 크기를 다듬었습니다.
- 0.2.4 이상이면 앱 안에서 바로 업데이트됩니다(설정 > 고급 > 앱 업데이트).

<details>
<summary><b>이전 버전</b></summary>

| 버전 | 주요 변경 |
| --- | --- |
| v0.2.5 | AI가 읽을 수 있는 폴더(로컬 .md·.txt), AI 웹 읽기 스위치 |
| v0.2.4 | 앱 안 업데이트(PC·Android), 검색 Aa·.* 버튼, AI 채팅 모델 선택, MCP 도구 추가, 연결 해제 개선, 폰 하단 탭 |
| v0.2.3 | 앱 안 AI 채팅(Claude Code·Codex), 계정 메뉴, 설치 중 `notium-mcp.exe` 멈춤 수정 |
| v0.2.2 | 다른 기기 변경을 15초마다 확인, 창으로 돌아오면 즉시 동기화, 폰에서 휴지통으로 이동 |
| v0.2.1 | 첫 공개 베타. 메모 보드, AI 앱 연결, 2글자 한글 검색, 첨부 개선, Android 패키지 변경 |

</details>

## 주요 기능

| 기록 | 정리 | 동기화와 연결 |
| --- | --- | --- |
| 페이지·폴더 트리와 블록 편집기 | 링크·백링크, 태그·속성 | 선택적 Google Drive 동기화 |
| 일지, 할 일, 빠른 메모 | 본문 검색, 즐겨찾기, 화면 분할 | PC와 Android 사이 동기화 |
| 첨부 파일과 모아보기 | 버전 기록, 휴지통, 백업 | 앱 안 AI 채팅과 AI 앱 연결(MCP) |
| Markdown·Notion 가져오기 | Markdown 내보내기 | 로컬 우선 저장 |

## 시작하기

<details open>
<summary><b>Windows 설치</b></summary>

1. 설치 파일을 내려받아 실행합니다.
2. "Windows의 PC 보호" 창이 나타나면 **추가 정보 → 실행**을 누릅니다. 아직 코드 서명이 없어 표시되는 안내입니다.
3. 설치를 마치면 Notium이 실행됩니다. 새 버전은 앱 안에서 안내합니다.

</details>

<details>
<summary><b>Android 설치</b></summary>

1. APK를 내려받아 엽니다.
2. 요청이 나오면 브라우저나 파일 앱에 **출처를 알 수 없는 앱 설치**를 허용합니다.
3. 설치를 마친 뒤 필요하면 그 권한을 다시 끕니다.

</details>

<details>
<summary><b>여러 기기 동기화</b></summary>

1. **첫 PC:** 설정 → 계정·동기화 → **Google Drive** → **Google 계정으로 로그인** 후 **이 PC의 노트로 새 공간 만들기**를 선택합니다.
2. **폰이나 다른 PC:** 같은 Google 계정으로 로그인합니다.
   - 새로 설치한 기기라면 **이 계정의 노트로 새로 시작**을 선택합니다. 저장소의 노트를 받아옵니다.
   - 이 기기에 이미 쓴 노트를 함께 합치려면 **이 기기의 노트로 연결**(PC는 **이 PC의 노트로 연결**)을 선택합니다.
3. 앱이 열려 있으면 다른 기기의 변경은 보통 30초 안에, 창이나 앱을 다시 열면 몇 초 안에 반영됩니다.

동기화는 Google Drive의 **앱 전용 숨김 공간**만 사용하며, 일반 Drive 파일에는 접근하지 않습니다.

</details>

## AI와 함께 쓰기

| 방식 | 대상 | 설명 |
| --- | --- | --- |
| 앱 안 AI 채팅 | Claude Code, Codex | Notium 안에서 대화하며 노트를 읽고 고칩니다. 사용량은 각 서비스 요금제에서 나갑니다. |
| AI 앱 연결 (MCP) | Claude Desktop, Claude Code, Codex, Cursor, VS Code Copilot, Gemini CLI | 다른 AI 앱에서 Notium 노트를 불러 씁니다. 설정 → AI 연결에서 연결합니다. |

기본은 읽기 전용이며, 쓰기는 설정과 승인 방식을 따릅니다. AI에게 숨긴 폴더는 어느 방식으로도 보내지 않습니다. 연결한 AI 서비스가 받은 내용은 해당 서비스의 정책을 따릅니다.

## 개인정보와 데이터

- 노트는 기기에 먼저 저장되고, 동기화를 켠 경우에만 내 Google Drive 앱 전용 공간에 올라갑니다.
- [개인정보처리방침](https://nondeveloper0.github.io/Notium-site/privacy.html) · [이용약관](https://nondeveloper0.github.io/Notium-site/terms.html) · [계정·데이터 삭제 안내](https://nondeveloper0.github.io/Notium-site/data-deletion.html)

## 베타 안내

> [!WARNING]
> Notium은 개인이 만든 **베타 버전**이며 있는 그대로 제공됩니다. 프로그램 오류, 동기화 문제, 기기 고장, 클라우드 계정·용량 문제 등으로 노트나 첨부 파일이 손상되거나 사라져도 개발자는 복구하거나 책임지지 않습니다. **중요한 자료는 항상 따로 백업해 두세요.** (PC: 설정 → 데이터 → 백업)

- 기능과 호환성은 바뀔 수 있으며, 동기화는 별도 백업을 대신하지 않습니다.
- v0.2.1부터 Android 패키지 이름이 바뀌어 그 이전 Android 앱 위에는 덮어 설치되지 않습니다. 이전 앱을 지우고 새로 설치한 뒤 같은 Google 계정으로 다시 연결하세요.
- Windows 설치 파일에는 코드 서명이 없습니다.

## 문의

버그 제보와 문의는 [GitHub Issues](https://github.com/nonDeveloper0/Notium-releases/issues)에 남겨 주세요. 공개 게시물에 노트 내용, 개인정보, 비밀번호나 인증 토큰을 올리지 마세요.

<div align="center">
<sub>개인 프로젝트로 개발하고 있습니다.</sub>
</div>
