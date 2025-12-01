# better-agents-html
Better Agents 是一個 CLI 工具，也是一套用於建構 AI 代理（Agent）的標準。

它能為您的程式碼助手（如 Kilocode, Claude Code, Cursor 等）增強能力，使其成為您選擇的任何代理框架（如 Agno, Mastra 等）及其最佳實踐的專家。


## 前置需求
- Node.js 22
```bash
npm install -g @langwatch/better-agents
```

因為 @langwatch/better-agents 依賴了一個名為 posix 的套件，該套件需要 Linux/macOS 環境（具體來說是 unistd.h 標頭檔），因此無法直接在 Windows 上安裝。

解決方案： 建議您使用 WSL (Windows Subsystem for Linux) 來安裝與執行此工具。如果您已經安裝了 WSL，請進入 WSL 終端機後再執行安裝指令。

## 初始化專案
```bash
better-agents init .
```



