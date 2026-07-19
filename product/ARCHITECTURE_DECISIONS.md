# Architecture Decisions

## AD-001 完全分離
SIMS Writer側のファイル、Runtime、Contract、Knowledgeを直接参照しない。

## AD-002 日本語SSOT
日本語版をSingle Source of Truthとする。

## AD-003 記事企画書必須
キーワードから本文へ直接進まない。

## AD-004 不足情報の可視化
不明点を推測で埋めず、警告・確認事項・公開停止判定として残す。

## AD-005 完成度と公開可否の分離
本文が完成していても、根拠・安全性・品質に問題があれば公開不可とする。

## AD-006 専用JSON Contract
SIMS_FEEDBACK_V1 / V2を流用しない。

## AD-007 記事タイプ別戦略
すべての記事を同一構成で生成しない。

## AD-008 工程内品質保証
品質検査を最終工程だけに限定しない。
