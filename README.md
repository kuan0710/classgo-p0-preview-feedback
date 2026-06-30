# Classgo AI Platform P0 Preview Feedback

這個 public repository 只用於 Classgo AI Platform P0 Preview 招生工作情境測試清單與外部回饋收集。

Preview URL: <a href="https://kyc-pc.tail2b14a1.ts.net:10000" target="_blank" rel="noopener noreferrer">https://kyc-pc.tail2b14a1.ts.net:10000（另開新分頁）</a>

GitHub Pages 測試入口 / 清單: <a href="https://kuan0710.github.io/classgo-p0-preview-feedback/" target="_blank" rel="noopener noreferrer">https://kuan0710.github.io/classgo-p0-preview-feedback/（另開新分頁）</a>

有 GitHub 帳號的內部同事可用: <a href="https://github.com/kuan0710/classgo-p0-preview-feedback/issues/new?template=p0-preview-feedback.yml" target="_blank" rel="noopener noreferrer">GitHub Issue Form（另開新分頁）</a>

Public feedback repo: <a href="https://github.com/kuan0710/classgo-p0-preview-feedback" target="_blank" rel="noopener noreferrer">https://github.com/kuan0710/classgo-p0-preview-feedback（另開新分頁）</a>

## 用途

- GitHub Pages 對外測試入口、畫面測試地圖與招生工作情境測試清單。
- 一般測試者不需要 GitHub 帳號；可複製測試摘要後貼到指定 LINE、Email 或測試群組。
- GitHub Issue Form 保留給有 GitHub 帳號的內部同事或協作者使用。
- 提醒測試者 preview 安全邊界與測試範圍。
- 用瀏覽器 localStorage 暫存勾選狀態與備註；沒有後端，不自動送出，不上傳資料。

## 不包含

- 不放產品程式碼。
- 不放密鑰。
- 不放 internal runbook / evidence。
- 不放正式環境憑證。
- 不放真實學生個資。

## Preview 邊界

這是 P0 Preview，不是正式上線。

目前 AI 建議回覆草稿是 deterministic stub。這次主要測招生追蹤流程、AI 回饋審核、權限邊界與 AI 回答追蹤，不代表正式 LLM 回答品質。

## 怎麼測

請從 GitHub Pages 的「怎麼對照畫面測試」開始。每個主要測試區塊都寫明：

- 入口頁面。
- 要點哪筆範例資料。
- 要看哪個 UI 區塊。
- 通過標準。

主要範例資料包含「小明英文試聽詢問」、「國中數學試聽後追蹤」與「缺少暑期班費用來源」回饋卡片。

## 測試資料安全規則

- 不輸入真實學生個資、密碼、token、cookie、付款資料或正式環境憑證。
- 不把 bearer token、資料庫連線資訊、服務設定、密鑰或技術錯誤細節貼進 issue。
- 截圖或錄影前先遮蔽任何疑似個資、密鑰、憑證或內部環境資訊。
- 不要把外部測試者導向 private product repo。

## 怎麼回報

### 沒有 GitHub 帳號

1. 在測試清單勾選項目並填寫備註。
2. 按「複製測試摘要」。
3. 把摘要貼到我們指定的 LINE、Email 或測試群組。
4. 如果有截圖或錄影，請一併附上；貼出前先遮蔽個資、密鑰或正式環境資訊。

### 有 GitHub 帳號

1. 在測試清單勾選項目並填寫備註。
2. 按「複製測試摘要」。
3. 開啟 GitHub Issue Form，貼上摘要並補上預期結果、實際結果、截圖或錄影。

## 安全提醒

請不要在 preview、GitHub issue、截圖或錄影中貼上：

- 真實學生個資。
- Bearer token。
- Cookie。
- Database URL。
- Service env。
- 正式環境憑證。

GitHub Issue Form 需要 GitHub login。沒有 GitHub 帳號的測試者請使用「複製測試摘要」後貼到 LINE、Email 或測試群組的方式回報。Checklist 不會自動送出任何資料；測試者需要手動貼上摘要與補充資料。

## 授權

No license is granted. 本 repository 的文字、頁面與回饋表只供 Classgo AI Platform P0 preview 測試入口與回饋收集使用；不構成產品程式碼或產品內容的開源授權。
