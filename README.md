
Terminalを使う人へ
==================
Terminalから直接コマンドを叩くひと向けです

動作環境
--------
下記のソフトウェアがインストールされていること
- git
- ruby
- rake
- bundler


Sass・Compassのインストール
---------------------------
```bash
$ git clone git://github.com/subak/html5_nagoya_3.git
$ cd html5_nagoya_3
$ bundle install --path vendor/bundle
```

使い方
------
```bash
# SCSSまたはSassファイルをCSSに変換
$ rake sass:compile

# キャッシュおよび生成ファイルの削除
$ rake sass:clean

# 更に詳しい使い方など
$ bundle exec sass --help
```
