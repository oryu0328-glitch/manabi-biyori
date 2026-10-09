# まなび日和 v1.0

学習・集中管理用のPWAです。HTML/CSS/JavaScriptだけで動作し、データは各端末のブラウザのlocalStorageに保存されます。

## GitHub Pagesで公開
1. GitHubで `manabi-biyori` というPublicリポジトリを作成。
2. このフォルダの**中身**（index.html、script.js、style.css、manifest.webmanifest、service-worker.js、icon-192.png、icon-512.png、README.md）をリポジトリ直下へアップロード。
3. Commit changes欄に `Launch まなび日和 v1.0` と入力し、**Commit directly to the main branch** を選択して **Commit changes** をクリック。
4. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/(root)` → Save。
5. 公開後のURLは `https://ユーザー名.github.io/manabi-biyori/` です。数分後に開いてください。
6. スマホで公開URLを開き、iPhoneはSafariの共有→ホーム画面に追加、AndroidはChromeのメニュー→アプリをインストール／ホーム画面に追加。

## 更新時のコミット
- Commit message: `Update まなび日和 v1.0`
- Extended description: `Improve study tracking, focus timer, calendar, goals, analytics, and PWA assets.`
- Branch: `main` を選び、**Commit changes** をクリック。

## 注意
- ブラウザのデータ消去や端末変更で記録は消えます。設定からJSONバックアップを定期的に保存してください。
- スマホとPCは自動同期しません。JSONで手動移行できます。
- 終了音はブラウザの制限により、アプリを閉じている間には鳴らない場合があります。
- GitHub PagesはHTTPSのためPWAが利用できます。ファイルを直接開く場合はPWAは有効になりません。
