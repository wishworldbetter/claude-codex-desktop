# Claude Codex GUI

[English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md)

Claude Code CLI ベースの軽量デスクトップクライアント。Electron で構築。

## なぜこのプロジェクトを作ったのか

非常に複雑な別のプロジェクトを構築している最中、ターミナルで 10 以上のウィンドウを開いていました。10 年以上のターミナル経験があるにもかかわらず、これだけ多くのウィンドウの管理には混乱しました。特に AI 時代では、複数のプロジェクトを同時に並行処理することが頻繁にあります。

もう一つの理由は、最近の健康診断でいくつかの数値が良くなかったため、ジムにもっと時間を使う必要があること。スマートフォンから Claude Code に指示を出してプログラミングしたいと思いました。

## 仕組み

Claude Code を子プロセスとして spawn することで実現しています。シンプルで、適正かつ合法です。

## 主な特徴

- 使いやすい UI で、既存の Claude Code セッションやワークフローとシームレスに統合。
- Claude Code CLI をネイティブに呼び出し — Claude Agent SDK ベースではありません。（公式プランで安心して利用可能）
- マルチタスク並行、マルチモデル切替、マルチプロバイダー切替。
- 正確なコードロールバック — 会話と変更されたコード・ファイルを指定のターンまで復元可能。(開発中)
- スマートフォンからPCのコーディングを指揮。（Todo）
- リモートサーバーに agent をデプロイせずにサーバー上でコーディング。（Todo）

## スクリーンショット

![Claude Codex GUI](CleanShot%202026-02-24%20at%2021.56.51@2x.png)

## ダウンロード

[最新版をダウンロード](https://github.com/wishworldbetter/claudecodex/releases/latest)

## インストール

[Releases](https://github.com/wishworldbetter/claudecodex/releases) ページから最新の DMG ファイルをダウンロードし、インストールしてください。

### 前提条件

先に [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code) をインストールしてください：

```bash
npm install -g @anthropic-ai/claude-code
```

## 変更履歴

リリース履歴は [CHANGELOG.md](CHANGELOG.md) をご覧ください。

## ライセンス

MIT
