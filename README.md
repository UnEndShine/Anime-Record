# Anime紀錄

<br />

<p align="center">
    <img src="icon.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Anime紀錄</h3>
  <p align="center">
    Anime1.me觀看紀錄儲存於本地
    <br />
    適用於Edge Extension、Google Extension
  </p>

</p>

# 前言

1. 我們強烈支持觀看正版動漫，並鼓勵大家通過合法途徑支持創作者和版權持有者。請勿使用本專案進行任何侵犯版權的行為。
2. 本專案僅用於學術研究目的，旨在探索和推進相關領域的知識和技術。專案中的所有資源和代碼均遵循學術誠信原則，並且僅供學術研究和教育用途。

# 目錄
- [前言](#前言)
- [目錄](#目錄)
- [功能介紹](#功能介紹)
  - [目錄頁功能](#目錄頁功能)
  - [影片頁功能](#影片頁功能)
  - [注意事項](#注意事項)
- [下載與安裝方法](#下載與安裝方法)
- [免責聲明](#免責聲明)
- [問題回報](#問題回報)
- [侵權疑慮](#侵權疑慮)

# 功能介紹

## 目錄頁功能
<p align="center">
<img src="/介紹圖/Anime_List.png">
</p>

1. `Anime按鈕`：左鍵：用於展開與收起觀看紀錄；右鍵：刪除所有觀看紀錄。

   (由於使用LocalStorage，可能占用記憶體，可右鍵刪除所有紀錄)
2. 下方按鈕排列由觀看順序下往上排(最近看的會在最上方)，可透過拖動改變順序。
3. 按鈕內部排列方式為：`動漫名稱` | `季(由動漫名稱搜索)` | `[已觀看/目前總集數]`。
4. 已追到最新一集則顯示`原色`，反之則呈現`灰色`。
5. `動漫按鈕`：左鍵：連接到該動漫網頁，可直接點選前往；右鍵：刪除該動漫觀看紀錄。


## 影片頁功能
<p align="center">
<img src="/介紹圖/Ep_Btn.png">
</p>

1. `Ep按鈕`：用於展開與收起觀看紀錄。
2. `Back to List按鈕`：連接至動漫目錄。
3. `Clear Mark按鈕`：清除該動漫的觀看紀錄。
4. 正在觀看的集數呈現`黃色`；已觀看呈現`原色`；未觀看呈現`灰色`。
5. `集數按鈕`：左鍵：連接到該集數網頁，可直接點選前往(不會自動播放)；右鍵：刪除該集數觀看紀錄。

## 注意事項
- 僅適用於網址為：`https://anime1.me/*`
- 無法跨裝置/瀏覽器紀錄(畢竟是記錄在本地端)
- 可能會占用記憶體(使用LocalStorage紀錄)
- 由於總集數是透過fetch實現，可能因server或使用者網速不同，載入時間出現差異
- 僅在`Google/Edge` `繁體中文`中測試完成

# 下載與安裝方法

1. 下載`Anime紀錄.crx`，將副檔名改為`.rar`並解壓縮。
2. 到`Google/Edge擴充功能`管理頁面，`開啟開發人員模式`。
3. 載入解壓縮資料夾
4. 記得重新整理頁面，將在目錄頁顯示有顯示`Anime按鈕`與在影片頁有顯示`Ep按鈕`等。

## 免責聲明

本專案中的資料和代碼僅供參考，不保證其準確性和完整性。使用者應自行承擔使用本專案所帶來的風險。專案作者不對任何因使用本專案而產生的直接或間接損失負責。

## 問題回報

由於作者專業偏向微處理器語法，對html、css與javascript語法較不熟悉，可能有更有效率的方法還請指教，如有其他意見指導，歡迎聯繫。

目前已研發出動漫OP與EN的自動標記，但礙於技術不足，無法實整合至目前專案(原本希望的主要功能="=)，但現有功能感覺已足夠目前使用，所以提供有需要的人使用。

## 侵權疑慮
如果您對本專案中的任何內容有侵權或其他疑慮，請聯繫作者，將在確認後立即刪除相關內容。
感謝您的理解和支持！

聯繫作者：leanna.kyrie591@flounderfantasy.com
