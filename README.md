# 株式AI分析プラットフォーム

## 📋 概要

日本市場専門の株式AI分析プラットフォームです。最新の人工知能技術を活用し、投資判断をサポートします。

## 🚀 機能

- **AI株式分析**: 最新のAI技術による高精度分析
- **リアルタイムデータ**: 市場データの即座な分析
- **投資判断サポート**: データに基づく投資アドバイス
- **モバイル対応**: スマートフォンでも快適に利用可能

## 📁 ファイル構成

- `index.html` - メインページ
- `analysis.html` - AI分析機能ページ
- `contact.html` - お問い合わせ・リダイレクトページ
- `package.json` - プロジェクト設定
- `vercel.json` - Vercelデプロイ設定

## 🔧 技術仕様

- **フロントエンド**: HTML5, CSS3, JavaScript (ES6+)
- **スタイリング**: Tailwind CSS, カスタムCSS
- **アニメーション**: CSS Animations, Keyframes
- **レスポンシブ**: モバイルファーストデザイン
- **セキュリティ**: 強化されたセキュリティヘッダー

## 🚀 デプロイ方法

### 1. GitHubにプッシュ
```bash
git init
git add .
git commit -m "Initial commit: Stock Analysis Platform v1.0.1"
git remote add origin https://github.com/your-username/stock-analysis-platform.git
git branch -M main
git push -u origin main
```

### 2. Vercelでデプロイ
1. [Vercel](https://vercel.com)にアクセス
2. "New Project"をクリック
3. GitHubリポジトリをインポート
4. 自動デプロイが完了

## ⚙️ 設定

### リダイレクトURL設定
`contact.html`内の`targetUrl`を変更:
```javascript
var targetUrl = 'https://your-redirect-url.com';
```

### Google Analytics設定
`analysis.html`内の`ANALYTICS_TRACKING_ID`を変更:
```javascript
window.ANALYTICS_TRACKING_ID = 'AW-XXXXXXXXX/XXXXXXXXX';
```

## 🔒 セキュリティ機能

- XSS保護
- クリックジャッキング防止
- コンテンツタイプスニッフィング防止
- リファラーポリシー設定
- 権限ポリシー設定

## 📱 対応ブラウザ

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)
- モバイルブラウザ

## 📞 サポート

ご質問やご不明な点がございましたら、以下までお問い合わせください：

- Email: support@example.com
- 営業時間: 平日 9:00-18:00

## ⚠️ 免責事項

本プラットフォームは投資助言を提供するものではありません。投資判断は必ずご自身の責任で行い、必要に応じて専門家にご相談ください。投資にはリスクが伴います。

---

**株式AI分析プラットフォーム v1.0.1**  
© 2024 Stock Analysis Platform Team. All rights reserved.
