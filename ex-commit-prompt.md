# 說明
1. 功能、測試、Prompt 紀錄和專案狀態全部審查通過後使用。
2. 不必指定特定git方式。
3. 重點指定哪些內容可以進入 Commit、Commit message、禁止修改及Push。

# example
將目前已人工確認的相關變更建立一個 Commit。

Commit message：

feat: add CSV row counting

要求：
- 只提交本次 CSV 資料列計數、測試及相關文件。
- 不再修改任何檔案。
- 不執行 push。
- 若存在未確認或無關變更，停止並回報。

完成後回報 Commit ID、提交檔案與工作目錄狀態。
