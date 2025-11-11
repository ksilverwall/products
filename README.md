# Products

個人プロジェクトのランディングや試作 UI をまとめて管理するリポジトリです。\
GitHub Pages でホスティングしており、公開 URL は [https://ksilverwall.github.io/products/](https://ksilverwall.github.io/products/) です。

## 構成

- `index.html`: 公開トップ。各プロジェクトへのリンク集。
- `x-auto-follow/`: 自動フォロー系デモ用のサブディレクトリ。`terms.html` など個別ページを配置。
- `_config.yml`: GitHub Pages (Jekyll) 用の設定ファイル。不要なドキュメントを公開対象から除外。
- `README.md`: このドキュメント。公開対象外。

## 運用メモ

- 公開対象に含めたくないファイルは `_config.yml` の `exclude` に追加してください。
- 主要な変更を加えた際は、`README.md` に概要を追記してコンテキストを保ちます。
