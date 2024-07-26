# 帳戶

帳戶是記帳的核心[概念](concept.md)中的第二項。您可以在`帳戶管理`頁面管理同一帳本下的帳戶。

## 帳戶分類

帳戶以<mark style="color:green;">`收入`</mark>，<mark style="color:yellow;">`資產`</mark>，<mark style="color:red;">`支出`</mark>，<mark style="color:purple;">`債務`</mark>及<mark style="color:blue;">`其他`</mark>等共五大類頁籤分類。

<div align="center">

<img src="imgs/account-2.png" alt="" width="375">

</div>

## 新增帳戶

點選`新增帳戶`後，將進入新增帳戶頁面。在新增帳戶時，請考慮您要使用的名稱，並且可以用 `.` 字元來進行樹狀分類。在[資產負債表](balancesheet.md#jie-ceng-shi-biao-ge)中，這樣的分類方式將根據父節點進行合併加總。例如：`住.房租管理費`、`住.水電瓦斯` 和 `住.電話網路`，這些項目將分別加總至 `住` 這一父節點。

<div align="center">

<img src="imgs/account-3.png" alt="" width="375">

</div>

除了名稱外，您還必須為帳戶選擇一個帳戶類型，這樣的分類有助於 DMO 在呈現上的處理。

<div align="center">

<img src="imgs/account-4.png" alt="" width="375">

</div>

## 帳戶功能

您可點選各帳戶進行編輯，或利用左右滑動來查看個項不同功能操作。在帳本左邊為`刪除`功能。

<div align="center">

<img src="imgs/account-7.png" alt="" width="375">

</div>

在帳本右邊為`編輯`，`帳目列表`及`初始化`功能。

<div align="center">

<img src="imgs/account-8.png" alt="" width="375">

</div>

## 編輯帳戶

編輯帳戶時，您可以變更帳戶的名稱和類型。資產負債表的統計是即時的，只要維持正確的名稱和類型，您不必擔心會對統計結果造成錯誤。

<div align="center">

<img src="imgs/account-5.png" alt="" width="375">

</div>

## 帳目列表

帳目列表列出該帳戶在特定區間內的所有相關的帳目，包含不同帳本間的轉帳。

<div align="center">

<img src="imgs/account-9.png" alt="" width="375">

</div>

## 初始化帳戶

初始化帳戶的實際動作是為為帳戶添加一筆單向的初始帳目，通常發生在您最初建立新帳戶或開始使用DMO時進行，用來為帳戶設定初始值，例如銀行存款、已使用的信用卡金額或手上的現金。初始化帳目不需要設定轉帳的時間。並且只在資產負債表統計區間不包含開始日期時才會被計算。

<div align="center">

<img src="imgs/account-6.png" alt="" width="375">

</div>

## 刪除帳戶

刪除帳戶後，相關的帳目部份資料也會被刪除，此操作會影響該帳本的資產負債表統計，且不可逆，請小心執行。由於DMO支援不同帳本間的轉帳，如果一個帳目屬於多個帳本，則只有該帳本中的部分資料會被刪除，不會影響相關聯帳本的總帳。但在查詢相關非帳本的該帳目時，被刪除的單邊資料（轉出或轉入）會丟失。
