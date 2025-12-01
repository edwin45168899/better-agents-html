# better-agents-html
Better Agents 是一個 CLI 工具，也是一套用於建構 AI 代理（Agent）的標準。  

它能為您的程式碼助手（如 Kilocode, Claude Code, Cursor 等）增強能力，使其成為您選擇的任何代理框架（如 Agno, Mastra 等）及其最佳實踐的專家。  

```bash
▗▄▄▖ ▗▄▄▄▖▗▄▄▄▖▗▄▄▄▖▗▄▄▄▖▗▄▄▖
▐▌ ▐▌▐▌     █    █  ▐▌   ▐▌ ▐▌
▐▛▀▚▖▐▛▀▀▘  █    █  ▐▛▀▀▘▐▛▀▚▖
▐▙▄▞▘▐▙▄▄▖  █    █  ▐▙▄▄▖▐▌ ▐▌

 ▗▄▖  ▗▄▄▖▗▄▄▄▖▗▖  ▗▖▗▄▄▄▖▗▄▄▖
▐▌ ▐▌▐▌   ▐▌   ▐▛▚▖▐▌  █ ▐▌
▐▛▀▜▌▐▌▝▜▌▐▛▀▀▘▐▌ ▝▜▌  █  ▝▀▚▖
▐▌ ▐▌▝▚▄▞▘▐▙▄▄▖▐▌  ▐▌  █ ▗▄▄▞▘



Setting up your agent project following the Better Agent Structure.
```

## 說明文件
[better_agents_zh](./better_agents_zh.html)  

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

## 操作紀錄
[build.md](./docs/build.md)  
[build_zh_en.md](./docs/build_zh_en.md) 中英對照  

## Cursor - Vibe Coding
創建一個包含完整功能的 HTML 五子棋遊戲。

已創建五子棋 HTML 遊戲文件 `gomoku.html`。

## 遊戲功能

1. **15x15 棋盤**：標準五子棋棋盤
2. **雙人對戰**：黑白棋輪流下
3. **勝負判斷**：檢測橫向、縱向、兩條對角線是否五子連珠
4. **界面**：
   - 漸變背景
   - 木質棋盤
   - 立體棋子效果
   - 響應式設計（支持移動設備）
5. **遊戲控制**：
   - 顯示當前玩家
   - 重新開始按鈕
   - 獲勝提示

## 使用方法
直接在瀏覽器中打開 `gomoku.html` 即可開始遊戲。黑棋先手，點擊棋盤上的交叉點放置棋子，先連成五子的一方獲勝。

遊戲已可直接使用。
