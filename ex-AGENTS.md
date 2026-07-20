# 說明
1. 每一次任務都適用的規則

2. 會提供 Codex 固定的專案規則，因此適合保存測試、安全、Git 和輸出規範

3. 不適合保存某一項功能的完整 Prompt

# Example
# Repository instructions

## Scope

- Work only inside this repository.
- Make the smallest change required by the current task.
- Do not perform unrelated refactoring.
- Do not modify original data files unless the task explicitly requires it.

## Python

- Use Python 3 and follow the existing project structure.
- Prefer the Python standard library unless a dependency is explicitly approved.
- Handle expected user input errors without displaying a traceback.
- Add or update tests when behavior changes.

## Validation

- Run the smallest relevant test suite after code changes.
- When command-line behavior changes, run at least one success case and one failure case.
- Do not claim a check passed unless it was actually executed.
- Review the final diff for unrelated changes.

## Git and safety

- Do not commit or push unless explicitly requested.
- Never force push, delete branches, or rewrite Git history.
- Ask before installing dependencies, using network access, deleting files, or changing data.
- Never store credentials, tokens, private paths, or private research data.

## Final response

Report only:

- Files changed
- Tests or checks executed
- Results
- Remaining risks

Keep routine completion reports within 8 lines.
