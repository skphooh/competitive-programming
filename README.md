# Competitive Programming Portfolio

![AtCoder Rank](https://img.shields.io/badge/AtCoder-Unrated-gray?style=for-the-badge&logo=atcoder)
![Solved Problems](https://img.shields.io/badge/AtCoder_Solved-0_Problems-blue?style=for-the-badge)
![paiza Rank](https://img.shields.io/badge/paiza_Rank-A-success?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-Python_3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)

競技プログラミング（アルゴリズム学習）の解答コードと実績を管理するポートフォリオ用リポジトリです。
本リポジトリは**Public（公開）**として運用しており、主に**AtCoder**の解答コードを格納しています。

## 🏆 実績・スキル

- **AtCoder**: 〇〇ランク（Highest: 〇〇） / 〇〇問正解
- **paiza**: スキルチェック Aランク獲得（202X年X月）

> **Note**
> コンプライアンス遵守（利用規約違反の防止）のため、paizaの解答コードや問題文は別リポジトリ（Private）にて厳密に管理しています。

## 📌 リポジトリ構成

- `atcoder/` : AtCoderの問題解答（ABC, ARCなど）
- `utils/`（任意）: 競技プログラミング用の共通処理やスニペットなど

## 🚀 環境構築・使用ツール (AtCoder環境)

テストの実行や提出をコマンドラインで完結させるため、以下のツールを導入し、効率的なワークフローを構築しています。

- **[online-judge-tools (oj)](https://github.com/online-judge-tools/oj)**
- **[atcoder-cli (acc)](https://github.com/Tatamo/atcoder-cli)**

### コンテスト参加時のワークフロー例

```bash
# 1. コンテストディレクトリの作成と各問題のテストケースをダウンロード
acc new abc300
cd abc300/a

# 2. 解答コード (main.pyなど) を作成

# 3. テストの実行 (oj)
oj t -c "python main.py" -d test/

# 4. 全てのテストケースがAC(正解)になったら提出
oj s https://atcoder.jp/contests/abc300/tasks/abc300_a main.py
```
