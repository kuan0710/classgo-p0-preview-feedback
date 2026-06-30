# Classgo AI Platform P0 Preview Feedback

這個 public repository 只用於 Classgo AI Platform P0 Preview 招生工作情境測試清單與外部回饋收集。

Preview URL: <https://kyc-pc.tail2b14a1.ts.net:10000>

GitHub Pages 測試入口 / 清單: <https://kuan0710.github.io/classgo-p0-preview-feedback/>

唯一正式外部回饋入口: <https://github.com/kuan0710/classgo-p0-preview-feedback/issues/new?template=p0-preview-feedback.yml>

## 用途

- GitHub Pages 對外測試入口與招生工作情境測試清單。
- GitHub Issue Form 是唯一正式外部回饋入口。
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

## 測試資料安全規則

- 不輸入真實學生個資、密碼、token、cookie、付款資料或正式環境憑證。
- 不把 bearer token、資料庫連線資訊、服務設定、密鑰或技術錯誤細節貼進 issue。
- 截圖或錄影前先遮蔽任何疑似個資、密鑰、憑證或內部環境資訊。
- 回饋只提交到 public Issue Form；不要把外部測試者導向 private product repo。

## 安全提醒

請不要在 preview、GitHub issue、截圖或錄影中貼上：

- 真實學生個資。
- Bearer token。
- Cookie。
- Database URL。
- Service env。
- 正式環境憑證。

測試者需要 GitHub login 才能提交 Issue Form。Issue Form 不會由 checklist 自動送出；測試者需要手動貼上摘要與補充資料。

## 授權

No license is granted. 本 repository 的文字、頁面與回饋表只供 Classgo AI Platform P0 preview 測試入口與回饋收集使用；不構成產品程式碼或產品內容的開源授權。
