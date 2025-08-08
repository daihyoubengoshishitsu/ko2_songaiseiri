# KO2 損害整理

一件資料から損害整理表へのマッピングを行うWebアプリケーション

## 技術スタック

- **フロントエンド**: Next.js 14 (App Router)
- **言語**: TypeScript
- **スタイリング**: Tailwind CSS
- **UIコンポーネント**: shadcn/ui
- **バックエンド**: Supabase
- **デプロイ**: Vercel

## セットアップ

1. 依存関係のインストール:
```bash
npm install
```

2. 環境変数の設定:
```bash
cp .env.example .env.local
```

3. 開発サーバーの起動:
```bash
npm run dev
```

## 環境変数

以下の環境変数を `.env.local` に設定してください：

- `NEXT_PUBLIC_SUPABASE_URL`: SupabaseプロジェクトのURL
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`: Supabaseの匿名キー
- `SUPABASE_SERVICE_ROLE_KEY`: Supabaseのサービスロールキー

## Vercelへのデプロイ

このプロジェクトはVercelでのデプロイ用に最適化されています。

1. GitHubリポジトリをVercelに接続
2. 環境変数を設定
3. 自動デプロイが開始されます 