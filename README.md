# 菜園ナビ（Garden Navi）- ランディングページ

イチゴ栽培完全ガイド - 初心者から上級者まで

## 概要

菜園ナビは、イチゴ栽培の全てをサポートするWebアプリです。年間スケジュール、栽培のコツ、日々の記録管理まで、家庭菜園に必要なすべてがここに。

## 主な機能

- **📅 栽培カレンダー**: 9月～8月の年間スケジュール
- **📖 イチゴ図鑑**: 栽培成功の秘訣10のポイント
- **📝 栽培日記**: 毎日の栽培記録をメモで保存
- **🏠 ダッシュボード**: 現在の月の作業内容を一目で確認

## ファイル構成

```
garden-navi-landing/
├── index.html              # ランディングページ
├── strawberry_ebook.pdf    # 電子書籍（完全ガイド）
├── package.json            # プロジェクト設定
├── vercel.json             # Vercelデプロイ設定
├── .gitignore              # Git設定
└── README.md               # このファイル
```

## ローカルで実行

```bash
# Pythonの簡易HTTPサーバーを使用
python3 -m http.server 3000

# ブラウザで以下にアクセス
http://localhost:3000
```

## デプロイ

### Vercelへのデプロイ

1. GitHubにリポジトリをプッシュ
2. Vercelにログイン（GitHub連携）
3. 「New Project」から`garden-navi-landing`を選択
4. デプロイ完了

### カスタムドメイン設定

Vercelダッシュボードから「Settings」→「Domains」でカスタムドメインを設定可能

## 技術スタック

- **フロントエンド**: HTML5 + CSS3
- **Webアプリ**: Expo + React Native
- **デプロイ**: Vercel
- **ホスティング**: Vercel Static

## ライセンス

MIT License

## 作成者

Garden Navi Team
