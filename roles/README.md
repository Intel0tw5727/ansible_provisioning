# roles

## 各ディレクトリの役割

- tasks
  - 個別の処理内容を格納するディレクトリ
  - brew管理やコマンドラインツールなどそれぞれの処理で分けると良さそう

- files
  - copy などで配備する元のファイルや script で実行するスクリプトを保管する

- templates
  - template で使用するテンプレートを格納する

- handlers
  - 特定の処理の実行結果に応じたトリガーを格納する

- vars
  - roleに基づく variables を格納する

- meta
  - role間の依存関係を定義する
    - デスクトップroleとCI roleが派生するみたいなときに使う
  - Macの環境構築程度では使わない？(わからん)
