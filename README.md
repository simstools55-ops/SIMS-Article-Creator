# SIMS Article Creator

メインキーワードから検索意図・読者課題・必要情報・根拠計画を設計し、SEOと読者満足度を両立した新規記事を作成する独立製品です。

## 製品の位置づけ

- **SIMS Writer**：公開済み記事の改善
- **SIMS Article Creator**：新規記事の企画・作成・公開前品質検査

SIMS WriterのRuntime、Knowledge、JSON Contract、Claude Project、GitHubリポジトリには依存しません。必要な品質資産は内容を評価して複製・再設計し、このリポジトリ内で独立管理します。

## 現在の開発段階

`v0.1.0` Repository Foundation / Design Phase

現在は実装前の設計段階です。本文生成RuntimeやClaude Project投入物は、入力仕様・出力仕様・品質基準・JSON Contract・テスト計画の確定後に実装します。

## 基本ワークフロー

```text
メインキーワード
→ 検索意図分析
→ 想定読者・読者課題の定義
→ 必要情報・論点・根拠の整理
→ 記事企画書
→ タイトル・メタ・見出し
→ 本文・FAQ
→ 内部リンク・収益導線
→ 品質検査
→ 完成記事・構造化JSON
```

## リポジトリ構成

- `docs/`：製品コンセプト、資産分類、Gap Analysis、アーキテクチャ
- `product/`：製品仕様、品質方針、開発ロードマップ
- `claude/`：Claude Project用Runtime、Knowledge、Pattern、Contract、Template
- `tests/`：回帰、Contract、品質、安全性テスト
- `distribution/`：配布物生成先

## 設計原則

- 実体験、口コミ、調査結果を捏造しない
- 根拠のない数値や断定を避ける
- 情報不足を推測で埋めない
- YMYL領域では慎重な判定を行う
- 検索順位だけでなく読者の問題解決を優先する
- 日本語をSingle Source of Truthとする

## ライセンス

ライセンス方針は正式リリース前に確定します。現段階の設計資産は開発プロジェクト内で管理してください。
