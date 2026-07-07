# ktteacher.net 搭載ファイル配置図（v2・会社情報ページ追加）

このフォルダの中身を、リポジトリに同じパスのままコピー（上書き）してください。
GitHubのWeb画面なら「ファイルを追加→アップロード」に tools フォルダ・company フォルダ・sitemap.xml をドラッグ＆ドロップ。

| パス | 役割 |
|---|---|
| sitemap.xml | 上書き（company含む全新ページ追加済み） |
| company/index.html | 会社情報・特商法表記・プライバシーポリシー（新規） |
| tools/utamie/index.html | うたミエ無料デモ（上書き） |
| tools/utamie/full/index.html | うたミエ販売LP（新規） |
| tools/utamie/school/index.html | スクールライセンス（新規） |
| tools/utamie/terms/index.html | 利用規約（新規） |
| tools/yubimie/index.html | ゆびミエ無料版（上書き） |
| tools/yubimie/full/index.html | ゆびミエ販売LP（新規） |

## push前に【 】を編集するファイル
1. company/index.html : 住所・メール・電話・インボイス登録番号・日付
2. tools/utamie/full/index.html と tools/yubimie/full/index.html : PURCHASE_URL・SET_URL（note公開後）
3. tools/utamie/school/index.html : CONTACT・INVOICE（・SCHOOL_PRICE任意）
4. tools/utamie/terms/index.html : 制定日
