# MailCat

## 描述

## 功能
### 標記銀行信件
- 目前支援：
  - `013 國泰世華`
  - `803 聯邦銀行`
  - `805 遠東銀行`
  - `807 永豐銀行`
  - `812 台新銀行`
  - `822 中國信託`
  - `824 連線銀行`

### 標記特定信件
- 銀行信件分成三類：
    - 0.登入通知
    - 1.交易通知
    - 2.電子帳單

### 定時刪除信件
- 主要針對登入通知、~~驗證信~~的信件。
- 使用者可以決定信件要在多少天後自動刪除。

### 自動封存信件
- 主要針對登入通知、交易通知的信件。
- MailCat 會將已讀的信件進行封存。

### 備份附件
- 主要針對電子帳單的信件。
- MailCat 會將資料夾建立在 Google Drive 的根目錄下。

## 使用方法
1. 首先，Clone 此專案。
    
    ```
    git clone https://github.com/HeiTang/MailCat.git
    ```

2. 登入 Google 帳戶並且開啟 [Apps Script](https://script.google.com/home/start) 頁面。 

3. 建立新專案，然後將 `.gs` 檔案複製進去並存檔。

4. 選擇「觸發條件」點選「新增觸發條件」。