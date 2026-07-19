# SIMS Article Creator

SIMS Article Creatorは、メインキーワードから検索意図・読者課題・必要根拠・記事企画を設計し、公開可能な新規記事と構造化データを生成する独立製品です。

## 現在のバージョン

`0.5.0 Knowledge Architecture`

## 製品境界

- SIMS Writerとは別リポジトリ・別Claude Project・別Runtime・別Knowledge・別Contractで管理する。
- SIMS Writerのファイルを実行時に参照しない。
- 日本語をSingle Source of Truthとする。
- 本文生成より前にEditorial Briefを必須生成する。
- 根拠不足を推測で埋めず、警告・確認事項・公開判定へ反映する。

## 中核フロー

入力検証 → Keyword Intelligence → Search Intent → Reader Model → Editorial Brief → Coverage Map → Evidence Plan → Article Blueprint → Writing → Editorial Review → Publication Gate → JSON出力

## v0.5.0の中核

Editorial Coreが利用するKnowledgeを、単なる参考文書ではなく、ロード順序・適用条件・優先順位・鮮度・競合解決を持つ実行可能な知識体系として整備しました。

## 主要ディレクトリ

- `claude/runtime/`：実行制御
- `claude/knowledge/`：品質・SEO・読者・根拠・安全性の知識
- `claude/contracts/`：入出力契約
- `claude/templates/`：中間生成物と最終出力
- `product/`：製品仕様とガバナンス
- `tests/`：Contract、Quality、Safety、Knowledge、Regression検証

## 使用順序

1. `claude/PROJECT_INSTRUCTIONS.md`
2. `claude/knowledge/KNOWLEDGE_INDEX.md`
3. `claude/runtime/RUNTIME_CONTROL.md`
4. `claude/runtime/ARTICLE_CREATION_RUNTIME.md`
5. 記事タイプに該当するKnowledgeと将来のPattern Library
6. `claude/contracts/SIMS_ARTICLE_CREATOR_CONTRACT.md`

## 開発状況

- v0.1.0 Repository Foundation
- v0.2.0 Product Architecture
- v0.3.0 Input / Output Contract
- v0.4.0 Editorial Core
- **v0.5.0 Knowledge Architecture（現在）**
- 次：v0.6.0 Pattern Library
