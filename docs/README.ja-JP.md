# ザ・シムズ 四季

**初の公開ベータ版 · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · **日本語** · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

The Sims Legacy Collection の街に四季がやってきます。嵐が来るとシムは屋内に駆け込み、冬には庭に雪が積もります。次にセーブデータを読み込むと、区画の天気と暦も前回の続きから始まります。ファンが制作した非公式の MOD です。

![住宅区画に立ちこめる霧](../media/weather.png)

[秋の木々](../media/autumn.png) · [雪の積もった庭](../media/winter.png) · [ギャラリー全体（ZIP、画像8枚）](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## 区画に起こる変化

- 季節に合わせて雨、雷雨、ひょう、雪、吹雪、霧が発生します。天気を自分で選ぶには、区画に気象観測所を設置します。魔法の雨や霧も選べます。
- 秋には木々が色づき、冬には道や草木、墓石などの屋外のオブジェクトに雪が積もります。子どもは水たまりで遊べます。十分に雪が積もれば、シムは雪だるまを作れます。
- シムも犬や猫も、ずぶぬれになったり、雨宿りしたりします。雨が屋外の火を消すこともあります。天気パネルでは各効果を調整できます。ロード画面にはオリジナル曲「Pocztówka z doliny」が流れます。

## ダウンロードとインストール

64 ビット版 Windows に製品版の The Sims Legacy Collection（ゲームバージョン **1.10.0** または **1.10.7**）と [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0) をインストールしてください。数 GB の空き容量に加え、セーブデータのバックアップ用の空き容量も必要です。

1. GitHub の [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1) で **1.0.0-beta.1** を開き、**Assets** から `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` をダウンロードします。
2. ゲームをセーブし、ゲームと天気アプリを終了します。ZIP 全体を新しいフォルダーに展開し、`data` フォルダーを `Setup.exe` と同じ場所に置きます。
3. `Setup.exe` を起動し、`sims.exe` があるゲームフォルダーを選びます。**互換性を確認** で確認してから **インストール** を選んでください。インストーラーは元のファイルを検証してバックアップを取り、インストール済みのゲームデータにパッチを適用します。必須ファイルが想定と異なる場合は処理が停止します。
4. 完了のメッセージが出るまでお待ちください。以後はデスクトップの **The Sims Cztery Pory Roku** ショートカットか、インストール先の `Launch-weather.cmd` から起動します。天気の処理と、セーブ読み込み時に天気を復元する機能がゲームと一緒に起動します。

ゲームファイルはインストーラーで更新してください。変更の前後に各ファイルのチェックサムが照合され、`sims.exe` は元のまま維持されます。追加のオブジェクトは、対応するバージョンがすでにインストールされている場合のみ更新されます。

## ゲーム内での操作

区画を読み込むと天気が自動で変化します。`Ctrl+Alt+R` でパネルを開き、降水、サウンド、暦、シムへの影響を設定できます。オブジェクトのメニューとパネルはゲームの言語で表示されます。パネルの言語を手動で選んだ場合は次回の起動時に切り替わります。

## バックアップ、更新、アンインストール

インストーラーは変更対象のファイル、セーブデータ、天気のデータをバックアップします。`%LOCALAPPDATA%\TS1CzteryPoryRoku` の下にあるインストール先では `backups` と `install-state.json` を一緒に保管してください。区画の天気の一部は `%LOCALAPPDATA%\TS1RainOverlay` に保存されます。セーブデータを手動で復元するときは、先にゲームを終了します。ゲームとアプリのインストール先はそのままにしてください。

Windows の「保存したゲーム」にある `Electronic Arts\The Sims 25` と、ゲームフォルダー内にある `UserData`, `UserData2` などのセーブデータもバックアップされます。バックアップは作成のたびに別のフォルダーに保存されます。手動で復元するファイルは、`save-backup.json` に記録された元のパスとチェックサムで特定できます。

更新時はゲームと天気アプリを終了し、新しい ZIP を別のフォルダーに展開したうえで、インストーラーで同じゲームフォルダーを指定します。削除するときは両方を終了して、保管してある `Setup.exe` から **オプション → アンインストール** を選びます。元のゲームファイルが復元され、セーブデータとバックアップは残ります。後で MOD のオブジェクトを再び使う場合は、MOD を外して遊ぶ前の区画のコピーを取っておいてください。

インストールが途中で中断した場合は **オプション → 変更を元に戻す** を選びます。復元時にファイルの変更が報告された場合は、エラーの全文とバックアップを保管してください。Windows で書き込みが拒否された場合は、同じ Windows アカウントで `Setup.exe` を管理者として実行してください。

## ベータ版の検証状況と不具合報告

インストーラーの検証対象は上記の 2 バージョンです。ほかの PC や低スペックの PC での動作、全 17 言語での通しプレイは引き続き検証中です。NVIDIA オーバーレイ使用中に天気の描画が遅くなる場合は、オーバーレイを無効にしてお試しください。

GitHub の [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) にゲームと MOD のバージョン、言語、再現手順をお知らせください。表示の不具合はスクリーンショットに加え、天気、ズーム倍率、カメラの向き、階、壁の表示状態も添えてください。インストール時のエラーは全文をご記入ください。ログを公開する前に、個人名を含むファイルパスなどがないか確認してください。
