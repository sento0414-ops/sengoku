# sengoku

## Claude 連携

Issue や PR のコメントで `@claude` とメンションすると、Claude Code が GitHub Actions 上で動いて返信・コード修正をしてくれます。

設定: リポジトリの Settings → Secrets and variables → Actions に `CLAUDE_CODE_OAUTH_TOKEN` を登録してください
（ローカルで `claude setup-token` を実行すると取得できます。API キーを使う場合は `ANTHROPIC_API_KEY` を登録し、ワークフローの `claude_code_oauth_token` を `anthropic_api_key` に変更してください）。
