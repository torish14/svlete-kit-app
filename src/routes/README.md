# ファイルベースのルーティング

- `.svelte` ファイルを作成すると、そのファイルをクライアントで表示できる
- `.js / .ts` ファイルを作成すると、サーバーで動く
  - クライアントに DL されない
  - DB アクセスや環境変数に使える
- `_` から始まるファイルはルーティングに含まれない
  - ディレクトリ名にもこのルールは適用される

## 共通レイアウトとエラー

- `__layout.svelte` ファイルを作成すると、そのディレクトリで共通レイアウトを指定できる
- `__error.svelte` ファイルを作成すると、そのディレクトリでエラーページを指定できる
