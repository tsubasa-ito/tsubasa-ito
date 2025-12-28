# CLAUDE.md

このファイルは、Claude Code (claude.ai/code) がこのリポジトリで作業する際のガイダンスを提供します。

## リポジトリの目的

GitHubプロフィールリポジトリ (github.com/tsubasa-ito/tsubasa-ito)。個人開発者としてのアイデンティティとプロダクトを紹介するページ。

## README.mdの構成

1. **作ったもの** - 個人開発プロダクト一覧（テーブル形式・2列レイアウト）
2. **技術スタック** - 使用技術
3. **本業** - 会社での業務
4. **リンク** - SNS・外部プロフィール

## 編集時の注意点

- テーブル形式（2列レイアウト、`:--:`で中央揃え）を維持する
- 各プロダクトにはスクリーンショット画像・説明・技術バッジを付ける
- スクリーンショット画像は`images/`フォルダに配置
- shields.ioのバッジは`<img>`タグ形式を使用（`<img src="https://img.shields.io/badge/...">`）
- 個人開発者としてのトーンを維持する

## スクリーンショットの取得

Playwrightでスクリーンショットを自動取得可能:
```bash
npx playwright screenshot --viewport-size "1280,720" --wait-for-timeout 5000 "URL" images/ファイル名.png
```
