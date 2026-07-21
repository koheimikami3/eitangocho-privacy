# eitangocho-privacy

macOS アプリ「シンプル英単語帳」のプライバシーポリシー・サポートページ。
GitHub Pages で静的ホスティングする。

## 構成

| ファイル | 役割 | 公開後の用途 |
|---|---|---|
| `index.html` | トップ（両ページへのリンク） | ランディング |
| `privacy.html` | プライバシーポリシー | App Store Connect の「プライバシーポリシー URL」 |
| `support.html` | サポート・FAQ | App Store Connect の「サポート URL」 |
| `style.css` | 共通スタイル（ライト/ダーク対応） | — |

## 公開前にやること

- `privacy.html` と `support.html` の「お問い合わせ先」プレースホルダを実際の連絡先
  （メールアドレスまたは問い合わせフォーム URL）に置き換える。

## GitHub Pages で公開する手順

1. このディレクトリを public リポジトリ `eitangocho-privacy` として GitHub に push する。
2. リポジトリの Settings → Pages を開く。
3. Source を `Deploy from a branch` にし、Branch を `main` / `(root)` に設定して Save。
4. 数分後、以下の URL で公開される（`<user>` は GitHub ユーザー名）:
   - トップ: `https://<user>.github.io/eitangocho-privacy/`
   - プライバシーポリシー: `https://<user>.github.io/eitangocho-privacy/privacy.html`
   - サポート: `https://<user>.github.io/eitangocho-privacy/support.html`
5. App Store Connect に上記 URL を登録する。
