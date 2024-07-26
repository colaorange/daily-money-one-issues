## 資料維護

資料維護頁面可進行各類資料形式的備份、還原或匯出、匯入作業。

### 取得手機儲存空間權限

在進行資料庫備份或匯出時，您必須先允許 App 存取手機目錄的權限。請點選`要求存取外部目錄許可`，並指定一個特定的目錄給 App 用於資料庫備份及資料匯出。

<div align="center">
<img src="imgs/data-9.png" alt="" width="375">
</div>


### 資料庫備份及還原

資料庫的備份會將資料庫檔案複製到手機目錄，而還原程序的最後一步會直接取代 App 的資料庫檔案，這是最快速且全面的資料處理方式。點選`備份資料庫`即可將資料庫檔案[^1]依日期時間格式為檔名備份到手機目錄中。

[^1]: 備份的資料庫不會包含[密碼](password.md)

<div align="center">
<img src="imgs/data-10.png" alt="" width="375">
</div>

點選`進行資料庫還原`後，會跳出資料庫檔案選取畫面，請選取要用來還原的資料庫備份檔案。隨後請重新啟動 App (用手機程序管理刪除App程序) 進入還原步驟。
<div align="center">
<img src="imgs/data-6.png" alt="" width="375">
</div>

App 在重新啟動後，會再次詢問是否確定要進行還原，點選 確定 則進行還原，點選 取消 則略過還原。請注意，還原是不可逆的，請確定您有確實的備份，且選取了正確的還原檔案。
<div align="center">
<img src="imgs/data-7.png" alt="" width="375">
</div>

### 自動備份資料庫

您可以選擇是否開啟`自動備份資料庫`功能。啟用後，App 將根據您的設定自動進行資料庫備份。

<div align="center">
<img src="imgs/data-1.png" alt="" width="375">
</div>

您可以在自動備份資料庫頁面設定備份的間隔天數、保留的備份數量及保留的天數。

<div align="center">
<img src="imgs/data-2.png" alt="" width="375">
</div>

### 自動上傳到GoogleDrive

您可以選擇是否開啟`自動上傳 Google Drive`功能。啟用後，App 會要求您登入 Google Drive 帳號並提供存取權限。

<div align="center">
<img src="imgs/data-11.png" alt="" width="375">
</div>

在您登入並提供存取權限後，App 會在 Google Drive 根目錄下建立一個 DailyMoneyOne 目錄，並在您進行資料庫備份或資料匯出時，自動將檔案上傳至該目錄。您可以在該功能頁面進行簡易的檔案刪除及下載管理。

<div align="center">
<img src="imgs/data-3.png" alt="" width="375">
</div>

### 匯出及匯出資料JSON檔

點選使用`匯出JSON`功能將帳本、帳戶及帳目等記帳資料匯出成JSON格式。您可以選擇要匯出的帳本和帳戶，以及是否要匯出其中涵蓋的帳目。

<div align="center">
<img src="imgs/data-4.png" alt="" width="375">
</div>

點選`進行JSON匯入`功能來匯入先前匯出的 JSON 格式檔案。您可以選擇要匯入的帳本和帳戶，以及是否要匯入其帳目。App 會建立全新的帳本和帳戶，且同名的帳本不會被取代或覆蓋。

<div align="center">
<img src="imgs/data-5.png" alt="" width="375">
</div>

### 匯入Daily Money+ CSV

若您是從 Daily Money+ 轉移過來的舊用戶，請先在 Daily Money+ 上匯出 CSV 檔案，然後點選 `進行 CSV 匯入` 功能來匯入由 Daily Money+ 匯出的 CSV 檔案。若您所在的區域使用的千位符號及小數點格式非 `,` 及 `.`，請選取適合您的字符設定，並選擇要匯入的 CSV 檔案。App 會建立全新的帳本和帳戶，且同名的帳本不會被取代或覆蓋。

<div align="center">
<img src="imgs/data-8.png" alt="" width="375">
</div>