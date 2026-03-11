

---

## ✨ 機能ハイライト

**🌍 マルチチャネルサポート** — 1 つのアシスタント、どこでも接続：DingTalk、Feishu、QQ、Discord、iMessage、Telegram など。

**🔒 プライバシー優先** — あなたのデータはあなたの管理下に。ローカルまたはクラウドにデプロイ可能。メモリとパーソナライズはあなたが所有。

**🛠️ 拡張可能なスキル** — 組み込み cron スケジューラー。ワークスペースからカスタムスキルを自動読み込み。ベンダーロックインなし。

**🧠 スマートメモリ** — 対話から学習する長期的メモリを備えた、文脈認識型の会話。

**🚀 簡単セットアップ** — 3 つのコマンドでインストール、またはワンクリックデスクトップアプリ。Python の専門知識は不要。

**🤖 ローカル AI** — llama.cpp、MLX、または Ollama でモデルを完全にローカルマシンで実行。API キーは不要。

---

## 📋 クイックリファレンス

### よく使うコマンド

```bash
# インストールと初期化
pip install copaw
copaw init --defaults

# コンソールを起動
copaw app

# スキル管理
copaw skills list
copaw skills install <skill-name>

# モデル管理
copaw models download Qwen/Qwen3-4B-GGUF
copaw models

# Cron ジョブ
copaw cron list
copaw cron create "0 9 * * *" "Check my calendar"
```

### マジックコマンド（コンソール内）

- `/reset` — 会話コンテキストをリセット
- `/memory` — 現在のメモリを表示
- `/skills` — 利用可能なスキルを一覧表示
- `/help` — 全てのコマンドを表示

### ヘルプを取得

- 📖 [公式ドキュメント](https://copaw.agentscope.io/docs/)
- 💬 [GitHub Discussions](https://github.com/agentscope-ai/CoPaw/discussions)
- 🐛 [問題を報告](https://github.com/agentscope-ai/CoPaw/issues)
- 📝 [貢献ガイド](CONTRIBUTING.md)
