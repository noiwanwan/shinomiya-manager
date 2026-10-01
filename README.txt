四宮 管理アプリ v1.3

今回の修正:
- .xlsm（マクロ有効Excel）を直接読み込み
- Uber総合_更新版_給油反映_v2.xlsm に対応
- タイトル/集計欄が上にあっても、先頭30行から見出し行を自動探索
- 「週別売上」シートを優先
- 週開始日 / 売上（円） / 件数 / オンライン時間 / 走行距離(km) / ガソリン代(円) を自動判定
- Google Driveの通常共有リンクをURL欄へ入れた場合は、直接同期できないことを明示
- Service Workerの旧キャッシュを自動削除

重要:
今回のDriveファイルはGoogleスプレッドシートではなく
Uber総合_更新版_給油反映_v2.xlsm
です。
Drive共有URLをブラウザから直接読み込む方式ではなく、
端末にダウンロードしてExcelファイル欄から選択してください。

GitHub更新:
index.html / sw.js / manifest.webmanifest / README.txt を差し替えてCommit。
