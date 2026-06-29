# Classgo AI Platform P0 Preview Feedback

這個 public repository 只用於 Classgo AI Platform P0 preview 人工驗測清單與外部回饋收集。

Preview URL: <https://kyc-pc.tail2b14a1.ts.net:10000>

GitHub Pages 測試入口 / checklist: <https://kuan0710.github.io/classgo-p0-preview-feedback/>

唯一正式外部回饋入口: <https://github.com/kuan0710/classgo-p0-preview-feedback/issues/new?template=p0-preview-feedback.yml>

## 用途

- GitHub Pages 對外測試入口與人工驗測 checklist。
- GitHub Issue Form 是唯一正式外部回饋入口。
- 提醒測試者 preview 安全邊界與測試範圍。
- 用瀏覽器 localStorage 暫存勾選狀態與備註；沒有後端，不自動送出，不上傳資料。

## 不包含

- 不放產品程式碼。
- 不放 secrets。
- 不放 internal runbook / evidence。
- 不放 production credentials。
- 不放真實學生個資。

## Preview 邊界

這是 preview，不是 production。

目前 AI draft 是 deterministic stub。這次只驗證 feedback-loop mechanics、權限邊界、Review Tray、audit trace 與回饋流程，不驗證真實 LLM provider quality，也不代表 production AI answer quality ready。

## 測試資料安全規則

- 不輸入真實學生個資、密碼、token、cookie、付款資料或 production credential。
- 不把 bearer token、database URL、service env、raw secret 或 stack trace 貼進 issue。
- 截圖或錄影前先遮蔽任何疑似個資、secret、credential 或內部環境資訊。
- 回饋只提交到 public Issue Form；不要把外部測試者導向 private product repo。

## 安全提醒

請不要在 preview、GitHub issue、截圖或錄影中貼上：

- 真實學生個資。
- Bearer token。
- Cookie。
- Database URL。
- Service env。
- Production credentials。

測試者需要 GitHub login 才能提交 Issue Form。Issue Form 不會由 checklist 自動送出；測試者需要手動貼上摘要與補充資料。

## 授權

No license is granted. 本 repository 的文字、頁面與回饋表只供 Classgo AI Platform P0 preview 測試入口與回饋收集使用；不構成產品程式碼或產品內容的開源授權。
