# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## このリポジトリの目的

Qiitaに投稿する技術記事を生成するためのワークスペース。README.mdに記事生成の指示書と技術ブログ執筆チェックリストが含まれている。

## 記事生成の流れ

README.mdに定義された手順に従う：

1. `README.md`の「記事の概要」を読んで記事の方向性を把握する
2. 「AIとの相談ログ」に記載されたファイル（`claude_session_備品管理貸出管理アプリ.md`、`claude_session_CSVデータの分布比較アプリ.md`）を読んで実例を把握する
3. 「リポジトリ」のGitHub URL（https://github.com/notfolder/roo_code_test）の各ファイルを読む
4. 「技術ブログ執筆チェックリスト」に照らして不足情報を確認し、ユーザーに質問する
5. 必要情報が揃ったらMarkdown形式で記事を生成する

## 記事の必須要件

- 記事の概要付近に「リポジトリ」のURLを埋め込む
- 記事末尾に「この記事の作成過程」という章を設け、AIとの相談ログのURLを埋め込む

## 記事の主題

AIによるソフトウェア開発において、要件定義書→設計書→コードという**ウォーターフォール的アプローチ**が効果的であるという知見の共有。

- 要件定義用プロンプト: https://github.com/notfolder/roo_code_test/blob/main/agents/REQUREMENTS_DEFINITION_AGENT.md
- 設計書用プロンプト: https://github.com/notfolder/roo_code_test/blob/main/agents/DESIGN_SPEC_AGENT.md
- 実例: 備品管理貸出管理アプリ、CSVデータの分布比較アプリ

## 執筆チェックリスト（要確認項目）

記事生成前に以下を確認・補完する：

- 対象読者の技術レベル
- バージョン情報・前提条件
- 試行錯誤の経緯（成功・失敗）
- SEO向けキーワード・Qiitaタグ
