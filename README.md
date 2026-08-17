# Zenn CLI

Zennアカウント(ジロー / jiro2026)のコンテンツ用リポジトリです。

* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)

## 運用方針

Zennの仕様上、GitHub連携できるリポジトリ数に上限がある(2個まで)ため、プロジェクト単位でリポジトリを分けず、このリポジトリ1つに集約する運用とします。

**注意**: Zenn側のGitHub連携は、リポジトリ直下の `articles/`・`books/` ディレクトリしか認識しない(サブディレクトリを指定する機能がない)ため、実コンテンツは必ずリポジトリ直下の `articles/`・`books/` に置くこと。

- `books/dojoru-kaihatsu-hiwa/` — Dojoru開発秘話シリーズ(本)のソース
- 今後、別プロジェクト・別トピックの本を追加する場合も `books/<プロジェクト名>/` を直下に追加する
- 記事(article)を追加する場合は `articles/` 直下にフラットに置く(Zenn側はfrontmatterのtopicsで分類するため、記事単位のサブフォルダ分けは不要)
