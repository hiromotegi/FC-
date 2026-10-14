# もみほぐしや フランチャイズ募集サイト

静的HTMLサイトです。GitHub PagesのGitHub Actions経由で公開できます。

## 初回公開

1. Gitをインストールし、GitHubで空のリポジトリを作成します。リポジトリ名の例は `fc-recruitment-site` です。
2. このフォルダーで次のコマンドを実行します。

```powershell
git init -b main
git add index.html README.md .github/workflows/pages.yml
git commit -m "Create franchise recruitment site"
git remote add origin https://github.com/OWNER/REPOSITORY.git
git push -u origin main
```

`OWNER` と `REPOSITORY` は、作成したGitHubリポジトリの値に置き換えてください。

3. GitHubリポジトリの **Settings → Pages → Build and deployment** で、Sourceを **GitHub Actions** にします。
4. **Actions** タブでデプロイ完了を確認します。公開URLは通常 `https://OWNER.github.io/REPOSITORY/` です。

以降は変更を `main` ブランチへpushすると、自動で再デプロイされます。

## 公開前に設定すること

- `index.html` の加盟条件・支援内容・代表者紹介・都内店舗展開に関する説明が、実際の事業情報と一致しているか確認する
- 相談フォームに送信先を接続する（現在はプレビュー表示のみで、入力内容は送信・保存されません）
- プライバシーポリシー、運営会社情報、問い合わせ先を追加する
- 外部配信の写真・Webフォントを利用し続けるか確認する

## ローカル表示

`index.html` をブラウザーで開いて確認できます。ビルドツールやパッケージのインストールは不要です。