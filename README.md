# sunagw.github.io

砂川祐介 (Yusuke Sunagawa) の公式プロフィールサイト。

- 公開URL: https://sunagw.github.io/
- 静的 HTML 1ファイル構成（ビルド不要・依存なし）
- SEO: JSON-LD (schema.org Person) / OGP / canonical 設定済み

## 公開手順

GitHub のユーザーページとして公開するため、リポジトリ名は `sunagw.github.io` にする必要がある。

```bash
gh repo create sunagw/sunagw.github.io --public --source . --push
```

その後、リポジトリの Settings → Pages で `main` ブランチの `/ (root)` が
ソースになっていることを確認する（ユーザーページは通常自動で有効になる）。

## 編集方針

- 所属企業名・顧客名は記載しない（本人の方針）
- 登壇・メディア掲載は一次ソースの URL を必ず添える
