# Ruby スクレイピング ハンズオン
## 概要 📝
- Qiita、Zenの記事タイトルをスクレイピングしCSVで出力する

## 環境構築 💻
- こちらのリポジトリをクローンする
- nokogiriをインストール (既にある人はそのままでOK)
  - `$ gem install nokogiri`

## 動作確認 🔍
- cloneしたディレクトリに移動し`$ ruby ruby_scraping.rb`を実行
- ディレクトリを確認して`target.csv`が出力されていればOK 
  - 確認コマンドはこちら→ `$ ls`
  - target.csvはQuipでも開ます！

## ブランチの説明
- main
  - Qittaのホームページの記事タイトルをスクレイピング
- scraping-01
  - Qittaの質問トレンドページの記事タイトルをスクレイピング
- scraping-02
  - Zennのホームページの記事タイトルをスクレイピング  
