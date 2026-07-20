# 說明
1. 只有功能通過驗收後，才保存最終 Prompt。
2. 不要保存完整對話、失敗後已淘汰的長 Prompt、Terminal 完整輸出。

# example
記錄本次已通過驗收的工作。

1. 建立或更新 `prompts/002-read-csv.md`：
   - 保存可重複使用的最終 Prompt
   - 記錄實際驗證方式與結果
   - 記錄本次發現的 Prompt 改進
   - 不保存完整對話、私人路徑或帳號資訊

2. 更新 `docs/project-state.md`：
   - 將 CSV 資料列計數移到 Completed
   - 更新 Current state
   - 將下一步改為欄位名稱與缺失值驗證

只修改上述兩個文件，不修改程式，不 commit、不 push。
