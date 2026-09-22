# Japanese Proxy Web (Light based)

A fast, simple, and highly customizable web proxy based on **Light** + **Ultraviolet**.

同じ仕組み（Ultraviolet + Bare Server）で Render にデプロイできるプロキシです。

## Features

- Simple Design
- Fast Speeds
- Clean UI
- **About:Blank Cloaking**
- Easy Deployment on Render

## Deploy to Render (推奨)

1. [Render.com](https://render.com) にログイン（GitHub連携）
2. **New +** → **Web Service**
3. このリポジトリを選択
4. 設定:
   - **Name**: 好きな名前（例: `jpw-proxy`）
   - **Runtime**: Node
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
   - **Instance Type**: Free
5. **Create Web Service** をクリック

デプロイ完了後、`https://あなたのサービス名.onrender.com` でアクセスできます。

> **注意**: 無料枠は一定時間アクセスがないとスリープします。初回アクセス時に少し時間がかかることがあります。

## Local Run

```bash
git clone https://github.com/shunichi19990314/Light.git
cd Light
npm install
npm start
```

デフォルトで `http://localhost:8080` で起動します。

## Tech Stack

- Ultraviolet V2
- TompHTTP Bare Server
- Rammerhead
- Express

## Original Project

Based on [nonsnse/Light](https://github.com/nonsnse/Light) (formerly NightProxy/Light).

If you use this, please consider starring the original repository.

## License

GPL-3.0-or-later
