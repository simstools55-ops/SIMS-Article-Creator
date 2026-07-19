# SIMS Article Creator

SIMS Article Creatorは、メインキーワードから検索意図・読者課題・必要根拠・記事企画を設計し、公開可能な新規記事と構造化データを生成する独立製品です。

## 現在のバージョン

`0.2.0 Product Architecture`

## 製品境界

- SIMS Writerとは別リポジトリ・別Claude Project・別Runtime・別Knowledge・別Contractで管理する。
- SIMS Writerのファイルを実行時に参照しない。
- 日本語をSingle Source of Truthとする。
- 本文生成より前にEditorial Briefを必須生成する。
- 根拠不足を推測で埋めず、警告・確認事項・公開判定へ反映する。

## 中核フロー

入力検証 → キーワード理解 → 検索意図 → 読者課題 → 記事企画 → 根拠計画 → 構成 → 本文 → FAQ・内部リンク・収益導線 → 品質検査 → 公開判定 → JSON出力

## 主要ドキュメント

- `docs/product-architecture.md`
- `docs/runtime-workflow.md`
- `docs/editorial-brief-specification.md`
- `docs/article-blueprint-design.md`
- `docs/data-flow.md`
- `product/ENGINE_SPECIFICATIONS.md`
- `claude/runtime/ARTICLE_CREATION_RUNTIME.md`

## 開発状況

この版はProduct Architecture確立版です。Knowledge本文、Article Blueprint本文、JSON Schemaおよび実記事生成Runtimeの完成版は後続フェーズで実装します。
