# 심즈 사계절

**첫 공개 베타 · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · **한국어** · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

The Sims Legacy Collection에 사계절이 찾아옵니다. 폭풍이 몰아치면 심들은 집 안으로 뛰어가고, 겨울이면 정원에 눈이 쌓입니다. 저장한 게임을 다시 불러오면 부지의 날씨와 달력도 이어집니다. 팬이 만든 비공식 모드입니다.

![안개가 낀 주거 부지](../media/weather.png)

[가을 단풍](../media/autumn.png) · [눈 덮인 정원](../media/winter.png) · [전체 갤러리(ZIP, 이미지 8장)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## 부지에서 달라지는 점

- 계절에 따라 비, 뇌우, 우박, 눈, 눈보라, 안개가 나타납니다. 날씨를 직접 고르고 싶다면 기상 관측소를 설치하세요. 마법 비와 마법 안개도 선택할 수 있습니다.
- 가을이면 나뭇잎이 물들고, 겨울이면 길, 식물, 묘비를 비롯한 야외 사물에 눈이 쌓입니다. 어린이는 물웅덩이에서 물장구를 칠 수 있고, 눈이 충분히 쌓이면 심들이 눈사람을 만들 수 있습니다.
- 심과 개, 고양이는 비에 흠뻑 젖거나 비를 피할 곳을 찾아갑니다. 야외에서 난 불이 비에 꺼지기도 합니다. 날씨 패널에서 개별 효과를 조절할 수 있습니다. 로딩 화면에는 모드를 위해 만든 곡 *Pocztówka z doliny*가 흐릅니다.

## 다운로드 및 설치

64비트 Windows에 The Sims Legacy Collection 정식 게임 **1.10.0** 또는 **1.10.7** 버전과 [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0)을 설치해야 합니다. 몇 GB의 디스크 여유 공간과 저장 데이터를 백업할 공간이 필요합니다.

1. GitHub에서 [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1)의 **1.0.0-beta.1**을 열고 **Assets** 항목에서 `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` 파일을 받습니다.
2. 게임을 저장한 뒤 게임과 날씨 앱을 모두 종료합니다. 새 폴더에 ZIP 전체를 풀어 `data` 폴더와 `Setup.exe` 파일을 같은 위치에 둡니다.
3. `Setup.exe` 파일을 실행하고 `sims.exe` 파일이 있는 게임 폴더를 선택합니다. **호환성 확인** 버튼으로 파일을 확인한 뒤 **설치** 버튼을 누릅니다. 설치 프로그램은 기존 파일을 확인하고 백업한 후 설치된 게임 파일에 패치를 적용합니다. 필수 파일이 예상과 다르면 설치가 중단됩니다.
4. 완료 메시지가 뜰 때까지 기다립니다. 이후에는 바탕 화면의 **The Sims Cztery Pory Roku** 바로 가기나 앱 설치 폴더의 `Launch-weather.cmd` 파일로 실행하세요. 게임과 함께 날씨 기능 및 저장된 날씨를 복원하는 기능이 시작됩니다.

게임 파일은 설치 프로그램을 통해 수정하세요. 파일을 변경하기 전과 후에 체크섬을 검사하며 `sims.exe` 파일은 그대로 유지됩니다. 선택 사항인 사물은 지원하는 버전이 이미 설치되어 있을 때만 패치됩니다.

## 게임에서 사용하기

부지를 불러오면 날씨가 자동으로 바뀝니다. `Ctrl+Alt+R` 키를 눌러 패널을 열면 강수 효과, 소리, 달력, 날씨가 심들에게 미치는 영향을 설정할 수 있습니다. 사물 메뉴와 패널은 기본적으로 게임 언어를 따릅니다. 패널에서 다른 언어를 선택하면 다음에 실행할 때 적용됩니다.

## 백업, 업데이트 및 삭제

설치 프로그램은 변경할 파일, 게임 저장 데이터, 날씨 데이터를 백업합니다. `%LOCALAPPDATA%\TS1CzteryPoryRoku` 아래의 앱 설치 폴더에 있는 `backups` 폴더와 `install-state.json` 파일은 함께 보관하세요. 부지의 날씨 데이터 일부는 `%LOCALAPPDATA%\TS1RainOverlay` 폴더에 저장됩니다. 저장 데이터를 직접 복구할 때는 먼저 게임을 종료하세요. 게임과 앱은 설치된 위치에 그대로 두세요.

백업에는 Windows의 저장된 게임 폴더에 있는 `Electronic Arts\The Sims 25` 폴더와 게임 폴더에 있는 `UserData`, `UserData2` 등의 폴더가 포함됩니다. 백업할 때마다 별도 폴더가 생깁니다. 직접 복구할 파일은 `save-backup.json` 파일에 적힌 원래 경로와 체크섬으로 확인할 수 있습니다.

업데이트하려면 게임과 날씨 앱을 종료하고 새 ZIP을 별도 폴더에 푼 뒤 설치 프로그램에서 기존 게임 폴더를 선택합니다. 모드를 삭제하려면 두 프로그램을 종료하고 보관해 둔 `Setup.exe` 파일을 실행해 **옵션 → 제거** 항목을 선택합니다. 원래 게임 파일이 복원되며 저장 데이터와 백업은 유지됩니다. 나중에 모드의 사물을 다시 쓰려면 모드를 뺀 상태에서 플레이하기 전에 부지의 복사본을 보관하세요.

설치가 도중에 끊겼다면 **옵션 → 변경 사항 되돌리기** 항목을 선택합니다. 복원 중 파일이 변경되었다는 메시지가 나오면 오류 메시지와 백업을 보관하세요. Windows가 쓰기 권한을 거부하면 같은 Windows 계정에서 `Setup.exe` 파일을 관리자 권한으로 실행하세요.

## 베타 테스트 및 오류 제보

위 두 게임 버전에 대해 설치 프로그램을 검사했습니다. 다른 PC와 저사양 PC에서의 테스트, 17개 언어 각각으로 진행하는 전체 플레이 테스트는 계속 진행 중입니다. NVIDIA 오버레이를 사용할 때 날씨 효과가 느려지면 오버레이를 끈 상태로 실행해 보세요.

GitHub의 [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues)에 게임 및 모드 버전, 언어, 문제를 재현하는 방법을 알려 주세요. 화면 표시 문제라면 스크린샷과 함께 날씨, 확대 수준, 카메라 방향, 층, 벽 표시 모드도 적어 주세요. 설치 오류라면 오류 메시지 전문을 첨부해 주세요. 로그를 공개하기 전에 개인 정보가 담긴 파일 경로가 있는지 확인해 주세요.
