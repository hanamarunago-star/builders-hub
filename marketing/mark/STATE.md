# MARK / 現在地

最終更新: 2026-10-09
状態: BOOTSTRAP — 公開運用未開始

## 事実として確認済み
- APP DOCK公開ドメイン: https://app-dock.jp/
- Vercelの `builders-hub-web` プロジェクトに `app-dock.jp` / `www.app-dock.jp` が紐付いている。
- GitHubに `hanamarunago-star/builders-hub` が存在する。
- ただし、このGitHubリポジトリの内容はNext.js初期テンプレートに近く、**Vercel本番コードとの一致は未確認**。
- マルク起動Issue: https://github.com/hanamarunago-star/builders-hub/issues/1

## 未確認・未実装
- Codex Cloud環境の作成・公開（本リポジトリでの実行確認）
- Codex Cloudを無人で日時指定起動する安全な正規手段
- 登録・継続指標の計測基盤とイベント定義
- ThreadsアカウントのMetricoolへの接続状況と投稿権限
- マルクによる実投稿・画像生成・成果分析は未実行

## 次の1手
1. Codex Cloud環境に本リポジトリを接続し、Issue #1を実行。
2. 本番サイトのソースとKPIのデータソースを読み取りで特定。
3. 1回のdry-runで課題/候補施策/根拠/次の仕事を記録し、無人起動の可否を検証。

## ガード
- 現段階では**本番変更・公開投稿禁止**。
- 確認できていない数値を「成功」「学習済み」と記載しない。