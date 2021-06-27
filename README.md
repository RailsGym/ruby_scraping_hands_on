# Ruby スクレイピング ハンズオン
## 概要 📝
- Qiita、Zenの記事タイトルをスクレイピングしCSVで出力する

## 環境構築 💻
- こちらのリポジトリをクローンする
- nokogiriをインストール (既にある人はそのままでOK)
  - `$ gem install nokogiri`

## 動作確認 🔍 (rubyバージョン2.5.0 ~ 2.70で動作確認済み)
- cloneしたディレクトリに移動する
- rubyのバージョンが2.5.0以上であることを確認する
- `$ ruby ruby_scraping.rb`を実行する
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
