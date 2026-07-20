# Changelog

## 1.0.0 - 2026-07-20 - Official Baseline
- 実記事UAT 10記事と追加YMYL試験の結果を正式反映
- UAT Final ReportとSWLS Final Learning Reportを追加
- Pattern Library Update v1.1、Knowledge Update v1.1を正式化
- Runtime Improvement Proposal v1.1を追加
- README、Product Specification、Release Notesを正式版へ更新
- VERSION、Validation Report、Claude Project配布資産を同期
- JSON Contract v1.2.0とLearning Record v1.1.0を正式採用

## 0.7.2 - Learning Enhancement
- Learning Record v1.1.0へ更新
- 詳細な原因分類を追加
- 6項目の人間評価を追加
- asset_change_candidatesを追加
- 10記事レポートにarticle_historyとasset_rankingを追加
- Release Recommendation基準を実装
- UAT Human Feedbackテンプレートを拡張


## 0.7.1 - Learning Foundation
- Added per-article SIMS_ARTICLE_LEARNING_RECORD_V1 output.
- Added provisional and confirmed UAT record states.
- Added ten-record SIMS_ARTICLE_LEARNING_REPORT_V1 aggregation.
- Added human feedback template and asset-level root-cause routing.
- Added governance rules preventing unapproved automatic self-modification.
- Updated Article Creator contract to 1.2.0.

## 0.7.0 - 2026-07-19
- Personal Blogger Edition基盤を追加
- Runtime Lock、Monetization Router、Editorial Voice、Publish Modeを追加
- Blog Profile / Author Profile / Affiliate Inputテンプレートを追加
- Review Pattern 2.0とGolden Article「ピアノ講座 口コミ」回帰テストを追加
- Input/Output Contractを1.1.0へ拡張
- PR表記、アフィリエイトリンク、body_markdown完全性の品質ゲートを強化

## 0.6.0 - UAT Prototype
- 8種類のPattern Libraryを実装
- Pattern Manifest / Routing / Composer Rulesを追加
- Pattern Composer RuntimeをEditorial Pipelineへ統合
- UAT Request、Evaluation Sheet、Editorial Learning Recordを追加
- Pattern/UAT静的検証を追加
- Claude Project投入用プロトタイプを整備


## [0.5.0] - 2026-07-19

### Added
- Knowledge Architecture v1.0
- Knowledge Index、Manifest、Routing、Precedence、Conflict Resolution
- Search Intent、Reader Model、Helpful Content、E-E-A-T、SEO、Evidence、Freshness、Safety、YMYL、Readability、Originality、Internal Link、Monetization Knowledge
- Claim ClassificationとSource Quality階層
- Knowledge Load Runtime
- KnowledgeテストとManifest検証
- Claude Project Instructions

### Changed
- READMEの版表示と開発状況を修正
- Runtimeのロード順序をKnowledge Architecture対応へ更新
- Editorial CoreからKnowledgeへの参照境界を明文化

## [0.4.0] - 2026-07-19

### Added
- Editorial Core、Coverage Engine、Reader Journey Engine
- Evidence Gate、Fabrication Prevention
- Editorial Review、Publication Readiness Gate
- Quality Frameworkと関連テスト

## [0.3.0] - 2026-07-19

### Added
- Input / Output Specification
- SIMS_ARTICLE_CREATOR_V1 JSON Contract
- JSON Schema、Reason Codes、Warning Codes、Examples、Contract Test