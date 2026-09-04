# yasashiihoushu-legal

Androidアプリ「誰でもできる報酬計算と請求書作成」（`jp.kkuramochi.yasashiihoushu` / リポジトリ
`KKuramochi/invoice_master`）の法的情報を GitHub Pages で公開するための静的サイト。

## 公開URL

- プライバシーポリシー: https://kkuramochi.github.io/yasashiihoushu-legal/privacy-policy.html

このURLを次の2か所に設定すること:

1. アプリ内「設定」→「プライバシーポリシー」（`lib/settings/settings_page.dart` の `privacyPolicyUrl`）
2. Google Play Console → アプリのコンテンツ → プライバシーポリシー

## app-ads.txt について

`_app-ads.txt.template` 参照。GitHub Pages のプロジェクトページ（サブパス配信）は
`app-ads.txt` の要件（ドメイン直下）を満たせないため、本番広告IDの取得後に
カスタムドメインか Cloudflare Pages 等で対応する。

## 更新

内容を変えたら `privacy-policy.html` の「最終更新日」を更新して push（`main` ブランチが Pages のソース）。
