# WAQ 分析レポート集

WAQ株式会社の各種分析レポート（Amazon・楽天・Yahoo・Shopify・KW分析等）を集約するリポジトリです。

## 🌐 公開URL

Vercel でデプロイ済み（社内共有用）:
- Production: `https://waq-reports.vercel.app`（構築後に確定）

## 📂 ディレクトリ構成

```
waq-reports/
├── index.html          # レポート一覧トップページ
├── reports/
│   ├── amazon/         # Amazon分析
│   ├── rakuten/        # 楽天分析（今後追加）
│   ├── yahoo/          # Yahoo分析（今後追加）
│   └── shopify/        # Shopify分析（今後追加）
└── README.md
```

## 📊 レポート一覧

### Amazon
- `2026-08-06_WAQリクライニングローチェア_Amazon特化分析.html` — Amazon特化 売上減少要因分析
- `2026-08-06_WAQリクライニングローチェア_売上減少要因分析.html` — 全チャネル版（参考）

## 🔒 セキュリティ

- **Private リポジトリ**：Vercel経由でのみ社内共有
- 自社売上データ・競合分析情報を含むため、URL共有時は範囲に注意

## 🛠 更新ルール

1. `reports/{チャネル}/YYYY-MM-DD_{商品名}_{分析タイプ}.html` の形式で追加
2. `index.html` に新規レポートのリンクを追記
3. `git commit` → `git push` で自動デプロイ

## 📅 更新履歴

- 2026-08-07: リポジトリ作成、Amazon特化レポート配置
