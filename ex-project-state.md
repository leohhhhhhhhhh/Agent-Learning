# 說明
1. 開啟新的threads後，codex忘記之前的進度
2. 切換桌面版、CLI 或其他環境
3. 不要每次在 Prompt 都要求 Codex 讀取它。當前 Thread 已有足夠上下文時，讀這個檔案只會增加不必要的輸入
# Example
# 專案目標 Goal

建立一個可靠的 Python 工具，用來檢查與分析工程實驗 CSV 資料。

# 已完成 Completed

- 建立 GitHub Private Repository
- 建立專案骨架
- 設定 Git commit email
- 將初始專案骨架推送至 GitHub

# 目前狀態 Current State

- 專案尚未實作 CSV 分析功能。
- `data/sample.csv` 為人工建立的示範資料。
- 目前沒有外部 Python 套件相依。

# 重要決策 Decisions

- 初期優先使用 Python 標準函式庫。
- 不將真實私人研究資料提交至 Repository。
- Commit 與 Push 需要使用者明確要求。
- 只保存可重複使用的 Prompt，不保存完整對話。

# 下一步 Next Task

實作 CSV 資料列計數功能及相關測試。

# 未解決問題 Open Issues

- 空白列是否計入資料列尚未定義。
- 尚未決定何時導入 pandas。
