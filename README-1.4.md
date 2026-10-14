# GAME VAULT 1.4 / BEYOND VAULT

## 更新方法
1. 既存アプリで**最新のJSONバックアップ**を書き出す。
2. `index.html`、`manifest.webmanifest`、`sw.js`、`icon-192.png`、`icon-512.png` をGitHub `game-vault` リポジトリのルートへ同名アップロードしてコミットする。既存の個人JSONをGitHubにアップロードしない。
3. 公開後、iPhoneでアプリを再起動。旧画面が残るときはSafariでサイトを再読み込みし、PWAを閉じて開き直す。アプリを削除しない。
4. [RAWG](https://rawg.io/apidocs) で無料の個人用APIキーを取得（RAWG側でアカウント登録が必要）。
5. BEYOND VAULT画面でAPIキーを保存し、テーマを選んで検索する。
6. ウォッチするとGAME RADARに追加される。ユーザーゲーム276作品は既存ストレージのまま保持。

## 注意
- RAWGのキーは端末のlocalStorageにのみ別保存し、バックアップJSONに含めません。キーをGitHubにアップロードしないでください。
- RAWGの仕様やブラウザのCORS制限により、ブラウザから直接APIが利用できない場合があります。実API・iPhone実機接続はユーザー側で要確認です。
- 作品の照合は正規化タイトルによる一致で、別言語のタイトル・リマスター版などの見逃しがあります。
- 取得結果はRAWG収録データに基づくもので、Xboxストアでの販売やGame Passを保証しません。
- 検索テーマはAPIでのメタデータ検索。好みの一致率や個人評価を自動的に計算・保証しません。
