# Claude Codex GUI

[简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md)

A lightweight desktop client for Claude Code CLI, built with Electron.

## Why This Project

I started this project while building another highly complex project — I had 10+ terminal windows open. Despite having over 10 years of terminal experience, managing that many windows was overwhelming, especially in the AI era where you often need to work on multiple projects in parallel.

Another reason: my recent health checkup showed some concerning numbers, so I need to spend more time at the gym. I wanted a way to direct Claude Code from my phone.

## How It Works

By spawning Claude Code as a child process. Simple, compliant, and legitimate.

## Key Features

- Easy-to-use UI that seamlessly integrates with your existing Claude Code sessions and workflows.
- Natively invokes Claude Code CLI — not built on Claude Agent SDK. (Safe to use with your official subscription.)
- Multi-task parallel sessions, multi-model switching, multi-provider switching.
- Precise code rollback — revert conversations and changed code/files to any specific turn. (In Progress)
- Control your computer's coding from your phone. (Todo)
- Code on remote servers without deploying an agent. (Todo)

## Screenshot

![Claude Codex GUI](CleanShot%202026-02-24%20at%2021.56.51@2x.png)

## Download

[Download the latest release](https://github.com/wishworldbetter/claude-codex-desktop/releases/latest)

## Install

Download the latest DMG from the [Releases](https://github.com/wishworldbetter/claude-codex-desktop/releases) page and install.

### Prerequisites

Install [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code) first:

```bash
npm install -g @anthropic-ai/claude-code
```

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for release history.

## License

MIT
