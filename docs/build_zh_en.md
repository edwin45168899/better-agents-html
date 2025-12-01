# Build Log (Chinese-English Comparison) / 建置日誌 (中英對照)

此文件為 `better-agents init .` 指令執行過程的中英對照說明。

```bash
better-agents init .
```

---

### Initialization Process / 初始化過程

**English:**
```text
Setting up your agent project following the Better Agent Structure.

✔ What programming language do you want to use? Python
✔ What agent framework do you want to use? Agno
✔ What LLM provider is your agent going to use? OpenRouter
To get your OpenRouter API key, visit:
https://openrouter.ai/keys
✔ Enter your OpenRouter API key: *************************************************************************
✔ What is your preferred coding assistant for building the agent? Cursor (not installed)
✔︎ Your coding assistant will finish setup later if needed

To get your LangWatch API key, visit:
https://app.langwatch.ai/authorize
✔ Enter your LangWatch API key (for prompt management, scenarios, evaluations and observability): ******************************************************
To get your Smithery API key (optional), visit:
https://smithery.ai/account/api-keys
Smithery enables your coding agent to auto-discover MCP tools to integrate with your agent.
✔ Enter your Smithery API key (Optional - press Enter to skip):
✔ What is your agent going to do? test
✔ Project setup complete!
✔ Your agent project is ready!
ℹ Project location: /mnt/d/github/chiisen/better-agents-html
✅ Project setup complete!
```

**中文說明:**
```text
正在根據 Better Agent 架構設定您的代理專案。

✔ 您想要使用什麼程式語言？ Python
✔ 您想要使用什麼代理框架？ Agno
✔ 您的代理將使用哪家 LLM 提供商？ OpenRouter
獲取 OpenRouter API 金鑰請訪問：
https://openrouter.ai/keys
✔ 輸入您的 OpenRouter API 金鑰： *************************************************************************
✔ 您首選用於建構代理的程式碼助手是什麼？ Cursor (未安裝)
✔︎ 如果需要，您的程式碼助手稍後將完成設定

獲取 LangWatch API 金鑰請訪問：
https://app.langwatch.ai/authorize
✔ 輸入您的 LangWatch API 金鑰（用於提示詞管理、情境測試、評估和可觀測性）： ******************************************************
獲取 Smithery API 金鑰（選填）請訪問：
https://smithery.ai/account/api-keys
Smithery 使您的程式碼代理能夠自動發現 MCP 工具以整合到您的代理中。
✔ 輸入您的 Smithery API 金鑰（選填 - 按 Enter 跳過）：
✔ 您的代理要做什麼？ test (測試)
✔ 專案設定完成！
✔ 您的代理專案已準備就緒！
ℹ 專案位置： /mnt/d/github/chiisen/better-agents-html
✅ 專案設定完成！
```

---

### Initial Prompt / 初始提示詞

這是工具生成的初始提示詞，您需要將其複製到 Cursor Composer 中以開始開發。

**English:**
```text
Initial prompt:
"You are an expert AI agent developer. This project has been set up with Better Agents best practices.

First steps:
1. Read and understand the AGENTS.md file - it contains all the guidelines for this project
2. Update the AGENTS.md with specific details about what this project does
3. Create a comprehensive README.md explaining the project, setup, and usage
4. Set up the Python with uv + pytest (install uv for them if they don't have it)
5. Review the .cursorrules and llms.txt files for Agno best practices
6. Execute any installation steps needed yourself, for the library dependencies, the CLI tools, etc
7. Use the LangWatch MCP to learn about prompt management and testing
8. Start implementing the core agent functionality
9. Instrument the agent with LangWatch
10. Use Scenario tests to ensure the agent is working as expected, integrate with the agent and consider it done only when all scenarios pass, check scenario docs on how to implement
11. If available from the framework, tell the user how to open a dev server give them the url they will be able to access so they can play with the agent themselves, don't run it for them


Remember:
- The LLM and LangWatch API keys are already available in the .env file, you don't need to set them up
- ALWAYS use LangWatch Prompt CLI for prompts (ask the MCP how)
- ALWAYS write Scenario tests for new features (ask the MCP how)
- DO NOT test it "manually", always use the Scenario tests instead, do not open the dev server for the user, let them do it themselves only at the end of the implementation with everything working
- Test everything before considering it done

Agent Goal: test"
```

**中文翻譯:**
```text
初始提示詞：
"您是一位專家級的 AI 代理開發者。此專案已根據 Better Agents 最佳實踐進行設定。

第一步：
1. 閱讀並理解 AGENTS.md 檔案 - 它包含此專案的所有指南
2. 更新 AGENTS.md，加入關於此專案具體功能的詳細資訊
3. 建立一個詳盡的 README.md，說明專案、設定和使用方法
4. 設定 Python 環境，使用 uv + pytest（如果使用者沒有安裝 uv，請幫他們安裝）
5. 檢閱 .cursorrules 和 llms.txt 檔案，了解 Agno 的最佳實踐
6. 自行執行任何所需的安裝步驟，包括函式庫依賴、CLI 工具等
7. 使用 LangWatch MCP 來學習提示詞管理和測試
8. 開始實作核心代理功能
9. 使用 LangWatch 為代理安裝儀器（Instrument）
10. 使用 Scenario 測試確保代理運作符合預期，將其與代理整合，只有在所有情境測試通過時才視為完成，請查閱 scenario 文件了解如何實作
11. 如果框架支援，告訴使用者如何開啟開發伺服器，提供他們可以存取的 URL 讓他們自己試玩代理，不要幫他們執行

記住：
- LLM 和 LangWatch API 金鑰已經在 .env 檔案中，您不需要設定它們
- 永遠使用 LangWatch Prompt CLI 來處理提示詞（詢問 MCP 如何操作）
- 永遠為新功能編寫 Scenario 測試（詢問 MCP 如何操作）
- 不要「手動」測試，永遠使用 Scenario 測試代替，不要為使用者開啟開發伺服器，讓他們在實作結束且一切正常後自己開啟
- 在認為完成之前測試所有內容

代理目標：test"
```

---

### Next Steps / 下一步

**English:**
```text
Project location: /mnt/d/github/chiisen/better-agents-html
⚠️  To start with Cursor:
  1. Open Cursor
  2. Open the folder: /mnt/d/github/chiisen/better-agents-html
  3. Use the initial prompt above with Cursor Composer
```

**中文說明:**
```text
專案位置： /mnt/d/github/chiisen/better-agents-html
⚠️  使用 Cursor 開始：
  1. 開啟 Cursor
  2. 開啟資料夾： /mnt/d/github/chiisen/better-agents-html
  3. 使用上方的「初始提示詞」在 Cursor Composer 中開始
```
