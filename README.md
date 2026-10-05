# mf_notify-data

[mf_notify](https://github.com/myumoon/mf_notify) の設定データ置き場のテンプレートです。

このテンプレートから **private** リポジトリを作り（Use this template）、設定画面から接続してください。

| ファイル | 内容 |
| --- | --- |
| `settings.yml` | 予算・カテゴリ・警告・1Password 参照などの設定。秘密情報そのものは書かない（`op://` 参照のみ） |
| `categories.json` | PC 側の `mf-notify run` が MoneyForward の明細から見つけた大項目/中項目の一覧。設定画面の選択肢に使う。自動更新されるので手で編集しない |
