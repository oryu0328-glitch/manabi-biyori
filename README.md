# まなび日和 v1.2

PCサイドメニュー・ホーム画面・スマホ下部タブが表示されない問題を修正しました。

原因：設定画面でのみ存在するファイル入力欄へ起動時にイベント登録しようとしてJavaScriptが停止していました。イベント委譲に変更し、初期描画を妨げないようにしました。

青色アイコン・既存デザイン・学習データ保存キーは維持。HTML、manifest、Service Workerのバージョンを更新しました。

## GitHub Pages更新

解凍後のファイル一式をリポジトリのルートへアップロードし、mainにコミットします。

Commit message: `Fix Manabi Biyori v1.2 navigation and dashboard`

反映後にCtrl+Shift+Rで強制再読み込みしてください。
