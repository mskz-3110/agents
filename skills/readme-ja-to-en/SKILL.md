---
name: readme-ja-to-en
description: Translate README.ja.md into README.md while preserving the Markdown structure, technical meaning, links, code, and project-specific terminology. Use when creating or updating the English README from the Japanese README.
---

# README日本語→英語

## 正本（SSOT）

- `README.ja.md` を唯一の正本とする。
- `README.md` は `README.ja.md` から生成される英訳版とする。
- コンテンツの正しい情報源として `README.md` を扱わない。

## 手順

1. `README.ja.md` 全体を読む。
2. 既存の `README.md` がある場合は読む。
3. `README.ja.md` を自然で簡潔な技術英語に翻訳する。
4. `README.md` を更新または作成する。
5. 作成した `README.md` と `README.ja.md` を比較する。
6. 欠落、追加、誤訳があれば修正する。

## 翻訳ルール

- Markdownの構造を維持する。
- セクションの順序を維持する。
- 見出しとその階層を維持する。
- リスト、テーブル、引用、Admonitionを維持する。
- リンクとリンク先を維持する。
- 画像パスと画像URLを維持する。
- ファイルパス、ファイル名、コマンド、オプション、環境変数、識別子を維持する。
- コードブロックは、周囲の自然言語を翻訳する必要がある場合を除き変更しない。
- ソースコード、コマンド名、API名、クラス名、メソッド名、設定キーは翻訳しない。
- 製品名、プロジェクト名、固有名詞、確立された技術用語は、一般的に受け入れられている英語表現がある場合を除き変更しない。
- `README.ja.md` に存在しない情報を追加しない。
- `README.ja.md` の情報を削除しない。
- 英語として自然にするために技術的な意味を変更しない。
- 単語単位の直訳ではなく、自然な技術英語を優先する。
- ドキュメント全体で用語を統一する。

## README.mdの更新方針

`README.md` がすでに存在する場合：

- `README.ja.md` の現在の内容を反映するように更新する。
- 日本語版が変更されている場合、古い英訳をそのまま残さない。
- 無関係な変更を行わない。
- 翻訳および必要なフォーマット修正に変更を限定する。

`README.md` が存在しない場合：

- `README.ja.md` から作成する。

## 検証

完了前に以下を確認する。

- `README.ja.md` のすべてのセクションが `README.md` に反映されている。
- 情報が欠落していない。
- 情報が追加されていない。
- Markdown構造が維持されている。
- リンクと画像参照が変更されていない。
- コードブロックと技術的な識別子が変更されていない。
- 用語が統一されている。
- 英語が技術READMEとして自然に読める。

日本語READMEの内容が曖昧な場合は、勝手に解釈を決めない。意図された意味をできるだけ忠実に維持し、推測による情報を追加しない。
