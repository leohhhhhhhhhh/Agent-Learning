# 說明
1. 開啟新的threads後，codex忘記之前的進度
2. 切換桌面版、CLI 或其他環境
3. 不要每次在 Prompt 都要求 Codex 讀取它。當前 Thread 已有足夠上下文時，讀這個檔案只會增加不必要的輸入
# Example
# Goal

Build a reliable Python tool for validating and analyzing engineering CSV data.

# Completed

- Repository created and connected to GitHub
- Project scaffold created
- Git privacy settings configured
- Initial commit pushed

# Current state

- No CSV analysis functionality has been implemented
- Synthetic sample data is available at `data/sample.csv`

# Decisions

- Use Python standard library first
- Use synthetic data only
- Require human approval before commit and push
- Save only reusable prompts, not full conversations

# Next task

Implement CSV row counting with tests.

# Open issues

- CSV blank-line behavior has not been formally defined
- More advanced data validation will be handled in later tasks
