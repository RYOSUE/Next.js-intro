# Next.js Dashboard

このリポジトリは、Next.js（App Router）とTailwind CSSを使ったダッシュボードアプリケーションのサンプルです。

## 主な技術

- Next.js
- React
- Tailwind CSS
- TypeScript
- PostCSS
- @heroicons/react

## セットアップ方法

1. リポジトリをクローン
   ```sh
   git clone https://github.com/あなたのユーザー名/nextjs-dashboard.git
   cd nextjs-dashboard
   ```

2. 依存パッケージのインストール
   ```sh
   pnpm install
   ```
   ※ `npm` や `yarn` でも可

3. 開発サーバーの起動
   ```sh
   pnpm dev
   ```
   ブラウザで `http://localhost:3000` にアクセス

## ディレクトリ構成

- `app/` … ページやUIコンポーネント
- `public/` … 画像などの静的ファイル
- `package.json` … 依存パッケージ管理
- `tailwind.config.ts` … Tailwind CSS設定
- `tsconfig.json` … TypeScript設定
