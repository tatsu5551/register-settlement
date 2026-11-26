レジ精算アプリ 第2版（ホーム画面アイコン対応）

GitHub Pagesへの公開手順
1. GitHubにログインし、New repositoryを選ぶ。
2. Repository nameを register-settlement と入力する。
3. Publicを選び、Create repositoryを押す。
4. Add file → Upload filesを選ぶ。
5. ZIPを解凍し、中の5ファイルをすべてアップロードする。
   index.html / manifest.json / sw.js / icon-192.png / icon-512.png
6. Commit changesを押す。
7. Settings → Pages → Build and deploymentでDeploy from a branchを選ぶ。
8. Branchをmain、フォルダを/(root)にしてSave。
9. 公開URL https://ユーザー名.github.io/register-settlement/ をAndroidのChromeで開く。
10. Chrome右上の︙から「アプリをインストール」または「ホーム画面に追加」を選ぶ。

注意：精算記録は端末内ブラウザに保存されます。公開版とは保存場所が別なので、移行前に現在の記録をCSV出力してください。
