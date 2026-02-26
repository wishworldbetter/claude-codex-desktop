# Claude Codex GUI

[English](README.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md)

一个基于 Claude Code Cli 的轻量级桌面客户端程序，基于 Electron 构建。

## 为什么写这个项目

这个项目主要是我在构建另外一个及其复杂的项目的时候，在终端开了 10+ 窗口，尽管我拥有超过 10 年的 terminal 经验，但是还是被这么多窗口所困惑，尤其是在 AI 时代经常需要同时并行处理多个项目。

另外一个原因最近发现体检各项指标都不太对，需要花更多的时间在健身房，所以希望能在手机上指挥 Claude Code 编程。


## 这个项目是如何工作的

通过 spawn claude code 子进程来实现，合规合理合法。


## 核心特色

- 易于操作上手的 UI, 无缝集成已有的 Claude Code 会话和工作流。
- 原生调用 Claude Code Cli，不是基于 Claude Agent SDK。（可以放心用官方套餐）
- 多任务并行，多模型切换，多供应商切换。
- 精确回滚代码，可以把对话和已经变更的代码 or 文件恢复到指定哪一轮对话。(Doing)
- 手机端指挥电脑编码（Todo）
- 无需在远端服务端部署 agent 也能在服务器编程（Todo）




## 截图

![Claude Codex GUI](CleanShot%202026-02-24%20at%2021.56.51@2x.png)

## 下载

[下载最新版本](https://github.com/wishworldbetter/claudecodex/releases/latest)

## 安装

从 [Releases](https://github.com/wishworldbetter/claudecodex/releases) 页面下载最新的 DMG 文件，双击安装即可。

### 前置要求

需要先安装 [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code)：

```bash
npm install -g @anthropic-ai/claude-code
```


## 更新日志

查看 [CHANGELOG.md](CHANGELOG.md) 了解版本历史。

## 许可证

MIT
