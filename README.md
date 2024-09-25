# はじめに
GitHubでCI（継続的インテグレーション）のHello World的なものを試すには、GitHub Actionsを使うのが簡単です。GitHub ActionsはGitHubが提供するCI/CDサービスで、リポジトリにイベントが発生したときに自動的にテストやビルド、デプロイなどを行えます。

# コーディングルール
1. コンテキストはシェルコマンドへハードコードせず、環境変数を経由して渡す
2. 環境変数は全てダブルクォーテーションで囲む


