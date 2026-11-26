# 模擬市民 四季

**首個公開測試版 · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · **繁體中文**

為 The Sims Legacy Collection 的社區帶來春夏秋冬。暴風雨來時，模擬市民會跑進屋裡，冬天的雪則會慢慢覆上庭院。下次載入存檔時，用地的天氣和日曆也會接續上次的進度。這是玩家製作的非官方模組。

![薄霧籠罩的住宅用地](../media/weather.png)

[秋天的樹葉](../media/autumn.png) · [積雪覆蓋的庭院](../media/winter.png) · [完整圖集（ZIP，8 張圖片）](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## 用地裡的四季

- 隨著季節變換，用地會出現降雨、雷雨、冰雹、降雪、暴風雪和霧。想自己決定天氣時，可以放置氣象站，還能選擇魔法雨或魔法霧。
- 秋天的樹葉會變色，冬天的積雪會覆蓋道路、植物，以及墓碑等戶外物品。小孩可以在水窪裡踩水玩。積雪夠厚時，模擬市民就能堆雪人。
- 模擬市民、狗和貓會被雨淋得全身溼透，也會找地方躲雨。下雨時，戶外的火有可能被澆熄。你可以在天氣面板個別調整這些效果。遊戲載入時會播放模組的原創主題曲《Pocztówka z doliny》。

## 下載與安裝

請先在 64 位元 Windows 上安裝 The Sims Legacy Collection 完整版（遊戲版本 **1.10.0** 或 **1.10.7**）和 [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0)。請預留數 GB 的磁碟空間，並另外準備足夠空間來備份存檔。

1. 前往 GitHub 的 [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1) 頁面，開啟 **1.0.0-beta.1**，從 **Assets** 下載 `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip`。
2. 儲存遊戲，結束遊戲和天氣程式。將整個 ZIP 檔解壓縮到新的資料夾，讓 `data` 資料夾和 `Setup.exe` 放在同一層。
3. 執行 `Setup.exe`，選取包含 `sims.exe` 的遊戲資料夾。先按 **檢查相容性** 檢查檔案，再按 **安裝**。安裝程式會驗證並備份檔案，接著修補電腦上已安裝的遊戲資源。若必要檔案的內容與預期不符，安裝程序會停止。
4. 等候安裝完成的訊息。往後請使用桌面的 **The Sims Cztery Pory Roku** 捷徑，或執行程式安裝資料夾中的 `Launch-weather.cmd` 來開啟遊戲。天氣服務和讀取存檔時還原天氣的功能會一併啟動。

請透過安裝程式修補遊戲檔案。程式會在每次修補前後比對檔案的雜湊值，並保留原本的 `sims.exe`。選用物品只有在電腦上已經安裝支援的版本時才會套用修補。

## 在遊戲中使用

進入用地之後，天氣會自動變化。按下 `Ctrl+Alt+R` 開啟面板，即可調整降水、音效、日曆及天氣對模擬市民的影響。物品選單和面板預設會跟隨遊戲語言。在面板裡另選語言後，下次啟動才會套用。

## 備份、更新與解除安裝

安裝程式會備份將要修改的檔案、遊戲存檔和天氣資料。請將 `%LOCALAPPDATA%\TS1CzteryPoryRoku` 下程式安裝資料夾裡的 `backups` 資料夾和 `install-state.json` 檔案保存在一起。部分用地天氣資料存放在 `%LOCALAPPDATA%\TS1RainOverlay`。手動還原存檔時，請先結束遊戲。遊戲與天氣程式請保留在原本的安裝位置。

存檔備份包含 Windows 的已儲存遊戲資料夾中的 `Electronic Arts\The Sims 25`，以及遊戲目錄裡現有的 `UserData`, `UserData2` 等資料夾。每次備份會建立專屬的資料夾。`save-backup.json` 記錄了原始路徑與檢查碼，方便你在手動還原時找到對應的檔案。

更新時，請關閉遊戲和天氣程式，將新的 ZIP 檔解壓縮到另一個資料夾，接著在安裝程式中選取原來的遊戲資料夾。要移除模組，請先關閉兩者，再開啟先前保留的 `Setup.exe` 並選擇 **選項 → 解除安裝**。程式會還原原有的遊戲檔案，並保留存檔與備份。如果之後還想使用模組的物品，請先備份用地，再移除模組繼續遊玩。

若安裝中途意外中斷，請選擇 **選項 → 復原變更**。還原時若收到檔案已變更的訊息，請保留備份和完整錯誤訊息。若 Windows 拒絕寫入，請在同一個 Windows 帳戶下以系統管理員身分執行 `Setup.exe`。

## 測試進度與問題回報

上述兩個遊戲版本都已進行過安裝程式檢查。其他電腦、較低規格的硬體，以及全部 17 種語言的完整遊玩測試仍在進行中。若開啟 NVIDIA 遊戲內覆蓋功能後天氣畫面變慢，可以先關閉該功能再試一次。

請在 GitHub 的 [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) 提供遊戲版本、模組版本、語言和重現問題的步驟。回報畫面問題時，請附上截圖，並註明當時的天氣、縮放程度、鏡頭方向、樓層和牆面顯示模式。若安裝發生問題，請附上完整錯誤訊息。公開紀錄檔前，記得檢查其中是否有含個人資訊的檔案路徑。
