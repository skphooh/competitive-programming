# Competitive Programming

![AtCoder Rank](https://img.shields.io/badge/AtCoder-Unrated-gray?style=for-the-badge&logo=atcoder)
![Solved Problems](https://img.shields.io/badge/Solved-0_Problems-blue?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-Python_3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)

AtCoderやpaizaなどの競技プログラミング・アルゴリズム練習用リポジトリです。
日々の学習記録や、作成した解答コードを管理しています。

## 📌 構成

- `atcoder/` : AtCoderの問題解答（ABC, ARCなど）
- `paiza/` : paizaのレベルアップ問題集の解答

## ⚠️ paizaに関する取り扱い方針

**paizaの「スキルチェック」問題の解答コードおよび問題文は、利用規約で公開が禁止されています。**
そのため、当リポジトリには「レベルアップ問題集」などの公開が許可されている練習問題の解答のみを配置しています。
（または、リポジトリ自体をPrivateに設定して管理しています）

## 🚀 環境構築・使用ツール

競技プログラミングを効率的に進めるために、以下のツールを導入しています（AtCoder用）。

- **[online-judge-tools (oj)](https://github.com/online-judge-tools/oj)**
  - テストケースのダウンロードから自動テスト、提出までをコマンドラインで行うツール。
- **[atcoder-cli (acc)](https://github.com/Tatamo/atcoder-cli)**
  - AtCoderに特化したコマンドラインツール。ojと連携して強力な自動化環境を構築。

### セットアップコマンド例 (Python環境の場合)

```bash
# online-judge-toolsのインストール
pip install online-judge-tools

# atcoder-cliのインストール (Node.jsが必要です)
npm install -g atcoder-cli

# accからojを使うための連携設定
acc config default-test-dirname test
```

## 📝 実行・提出のワークフロー例

```bash
# 1. コンテストのディレクトリを作成し、問題をダウンロード (例: ABC300)
acc new abc300
cd abc300/a

# 2. コードを記述 (例: main.py)

# 3. テストケースの実行
oj t -c "python main.py" -d test/

# 4. AC(正解)を確認したら提出
oj s https://atcoder.jp/contests/abc300/tasks/abc300_a main.py
```
