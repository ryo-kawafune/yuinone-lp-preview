# YUINONE LP（LPOプロトタイプ v1）

企業スポンサー型ブライダル支援サービス YUINONE のLP改善プロトタイプ。

## 構成
- `index.html` … ページ本体（モバイルファースト / max-width 480px）
- `style.css` … スタイル（デザイントークンは :root に集約）
- `assets/` … 画像（WebP）・ロゴ

## 閲覧方法
1. このフォルダのまま `index.html` をブラウザで開く（ローカルで表示可）
2. もしくは任意の静的ホスティング（Netlify / Vercel / S3 等）にフォルダごと配置

## 技術メモ（開発者向け）
- 依存なしの素のHTML/CSS/JS（ビルド不要）
- フォント：Google Fonts（Shippori Mincho / Zen Kaku Gothic New / Cormorant Garamond）をCDN読込
- 画像はWebP（合計約1MB）。元データ（PNG/JPG）が必要な場合は別途共有可
- フォーム・Google/LINE登録・各リンクは**ダミー**（UI確認用）。本実装は別途
- キャンペーン条件・運営会社情報は現行LP（yuinone.net / 株式会社R-field）記載値を反映

## 主な改善点（LPO）
- FVに会員登録フォーム（メールのみ＋Google/LINE）を内包
- 訴求＝「最大100万円分プレゼント」キャンペーン主軸／スポンサーマッチングは特徴に
- 追従CTA・中間/最終の登録動線・三方よし図・横スクロールの声 等
