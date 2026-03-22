# HCD資格 学習ロードマップ

UI/UXデザイナー・UX実務者のための、HCD（人間中心設計）資格取得を支援するインタラクティブ学習ツールです。

## 対応資格

| 資格 | 主催 | 形式 |
|------|------|------|
| HCD基礎検定 | 人間中心社会共創機構 | CBT 50問/50分 |
| 認定HCD専門家/スペシャリスト | HCD-Net | 書類審査（コンピタンス記述） |

## 機能

- **学習ロードマップ** — カテゴリ別のモジュールとトピックをチェックリスト形式で進捗管理
- **参考リソース** — 公式サイト・推薦図書へのリンク集と試験/審査概要
- **学習計画** — 基礎検定12週間プラン / 専門家6ヶ月プランの進捗バー付きタイムライン
- **進捗保存** — localStorage によりブラウザに学習進捗を自動保存

## 使い方

### ローカルで開く

`index.html` をブラウザで開くだけで動作します（インターネット接続が必要です — CDN から React を読み込みます）。

### GitHub Pages で公開

1. このリポジトリを GitHub にプッシュ
2. Settings > Pages > Source を `main` ブランチ / `/ (root)` に設定
3. 数分後に `https://<username>.github.io/hcd-learning-roadmap/` でアクセス可能

## 技術スタック

- React 18（CDN）
- Babel Standalone（CDN、JSX トランスパイル）
- バニラ CSS（Tailwind 風ユーティリティクラス）
- localStorage（進捗永続化）

## 参考情報

- [HCD基礎検定 公式](https://hcs-cc.org/hcd/)
- [HCD-Net 認定制度](https://www.hcdnet.org/certified/)
- [HCD基礎検定 出題範囲](https://hcs-cc.org/wp-content/uploads/2024/05/scope_202408.pdf)

## ライセンス

MIT
