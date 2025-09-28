# demo-001

これは、GitHub Actions を活用して静的サイトをデプロイするデモプロジェクトです。

## 概要

このリポジトリは、シンプルな `index.html` ファイルをホスティングし、GitHub Actions のワークフローを通じて自動的にデプロイを行うサンプルです。CI/CD の基本的な流れを理解するためのテンプレートとして利用できます。

## ✨ 主な特徴

- **静的サイト**: `index.html` のみで構成されたシンプルな Web ページです。
- **自動デプロイ**: `.github/workflows/static-site.yml` により、`main` ブランチへのプッシュをトリガーとして自動で GitHub Pages にデプロイされます。
- **Gemini CLI 連携**: `.github/workflows/gemini-cli.yml` を通じて、Issue や PR をトリガーとした AI アシスタントによるリポジトリの自動操作を実現しています。

## 🚀 セットアップ方法

このプロジェクトをフォークまたはクローンして、ご自身のリポジトリで GitHub Pages を有効にすることで、同じ構成を再現できます。

1.  **リポジトリをフォークする**
    - このページ右上の "Fork" ボタンをクリックします。

2.  **GitHub Pages を有効にする**
    - フォークしたリポジトリの "Settings" > "Pages" に移動します。
    - "Build and deployment" の "Source" で "GitHub Actions" を選択します。

これだけで、あなたのリポジトリでも自動デプロイが有効になります。

## 使い方

`main` ブランチにコミットをプッシュすると、GitHub Actions が自動的に起動し、数分でサイトが公開・更新されます。

公開されたサイトの URL は、リポジトリの "Settings" > "Pages" で確認できます。

## 🤖 AI アシスタント (Gemini CLI)

このリポジトリでは、Issue に `@gemini-cli` とメンションすることで、AI アシスタントを呼び出すことができます。

**例:**
「`@gemini-cli index.html` の `<title>` を "デモページ" に変更してください。」

のように Issue を作成すると、AI が自動で PR を作成します。

## 📛 バッジ

[![CI](https://github.com/Sunwood-ai-labs/demo-001/actions/workflows/static-site.yml/badge.svg)](https://github.com/Sunwood-ai-labs/demo-001/actions/workflows/static-site.yml)

## 📜 ライセンス

このプロジェクトは [MIT License](LICENSE) のもとで公開されています。