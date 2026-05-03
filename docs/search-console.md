# Google Search Console

`rubykaja` で `https://kaja.rubyist.net/` が見つかりやすくなるように、デプロイ後に Google Search Console で次を実行する。

## 手順

1. Google Search Console を開く。
   https://search.google.com/search-console/
2. `https://kaja.rubyist.net/` の URL プレフィックス プロパティを選択する。未登録なら追加する。
3. サイトマップに次の URL を送信する。
   `https://kaja.rubyist.net/sitemap.xml`
4. URL 検査で次の URL を検査し、インデックス登録をリクエストする。
   `https://kaja.rubyist.net/`
5. 数日後に検索パフォーマンスで `rubykaja` の表示回数と掲載順位を確認する。

## 確認 URL

- `https://kaja.rubyist.net/robots.txt`
- `https://kaja.rubyist.net/sitemap.xml`

サイトマップ送信やインデックス登録リクエストはクロールのきっかけになるが、検索順位や即時反映は保証されない。
