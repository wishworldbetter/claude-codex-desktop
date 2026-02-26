# Claude Codex GUI

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md)

一個基於 Claude Code Cli 的輕量級桌面客戶端程式，基於 Electron 構建。

## 為什麼寫這個專案

這個專案主要是我在構建另外一個極其複雜的專案的時候，在終端開了 10+ 視窗，儘管我擁有超過 10 年的 terminal 經驗，但還是被這麼多視窗所困惑，尤其是在 AI 時代經常需要同時並行處理多個專案。

另外一個原因是最近發現體檢各項指標都不太對，需要花更多的時間在健身房，所以希望能在手機上指揮 Claude Code 編程。

## 這個專案是如何工作的

透過 spawn claude code 子程序來實現，合規合理合法。

## 核心特色

- 易於操作上手的 UI，無縫整合已有的 Claude Code 會話和工作流。
- 原生呼叫 Claude Code Cli，不是基於 Claude Agent SDK。（可以放心用官方套餐）
- 多任務並行，多模型切換，多供應商切換。
- 精確回滾程式碼，可以把對話和已經變更的程式碼或檔案恢復到指定哪一輪對話。(Doing)
- 手機端指揮電腦編碼（Todo）
- 無需在遠端伺服器部署 agent 也能在伺服器編程（Todo）

## 截圖

![Claude Codex GUI](CleanShot%202026-02-24%20at%2021.56.51@2x.png)

## 下載

[下載最新版本](https://github.com/wishworldbetter/claudecodex/releases/latest)

## 安裝

從 [Releases](https://github.com/wishworldbetter/claudecodex/releases) 頁面下載最新的 DMG 檔案，雙擊安裝即可。

### 前置要求

需要先安裝 [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code)：

```bash
npm install -g @anthropic-ai/claude-code
```

## 更新日誌

查看 [CHANGELOG.md](CHANGELOG.md) 了解版本歷史。

## 授權條款

MIT
