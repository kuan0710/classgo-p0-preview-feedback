# Classgo AI Platform P0 Preview Feedback

這個 public repository 只用於 Classgo AI Platform P0 preview 測試入口與回饋收集。

Preview URL: <https://kyc-pc.tail2b14a1.ts.net:10000>

GitHub Pages 入口: <https://kuan0710.github.io/classgo-p0-preview-feedback/>

提交回饋: <https://github.com/kuan0710/classgo-p0-preview-feedback/issues/new?template=p0-preview-feedback.yml>

## 用途

- GitHub Pages 對外測試入口。
- GitHub Issue Form 收集 P0 preview 測試回饋。
- 提醒測試者 preview 安全邊界與測試範圍。

## 不包含

- 不放產品程式碼。
- 不放 secrets。
- 不放 internal runbook / evidence。
- 不放 production credentials。
- 不放真實學生個資。

## Preview 邊界

這是 preview，不是 production。

目前 AI draft 是 deterministic stub。這次只驗證 feedback-loop mechanics、權限邊界、Review Tray、audit trace 與回饋流程，不驗證真實 LLM provider quality，也不代表 production AI answer quality ready。

## 安全提醒

請不要在 preview、GitHub issue、截圖或錄影中貼上：

- 真實學生個資。
- Bearer token。
- Cookie。
- Database URL。
- Service env。
- Production credentials。

測試者需要 GitHub login 才能提交 Issue Form。

## 授權

No license is granted. 本 repository 的文字、頁面與回饋表只供 Classgo AI Platform P0 preview 測試入口與回饋收集使用；不構成產品程式碼或產品內容的開源授權。
