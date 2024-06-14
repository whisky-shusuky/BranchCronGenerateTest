# BranchCronGenerateTest
- Github Actionsを使ってリリースbranchを定期作成するサンプルコード

- UTCの金曜日の8:30（JSTの17:30に対応）に1週間後の日付のbranchが作成される
  - 2024 6/14に実行すれば以下のようになる。
<img width="341" alt="スクリーンショット 2024-06-14 17 52 11" src="https://github.com/whisky-shusuky/BranchCronGenerateTest/assets/20264602/e4f1a9e4-1319-4ce0-bfcf-5c2bf3a09561">

- Github Actionsに対する権限設定が必要
  - リポジトリの設定ページ（https://github.com/whisky-shusuky/BranchCronGenerateTest/settings）に移動する。
  - 左側のメニューから「Actions」を選択し、「General」タブをクリックする。
  - スクロールダウンして、「Workflow permissions」セクションを見つける。
  - 「Read and write permissions」オプションを選択し、「Save」をクリックして変更を保存。
