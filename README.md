HTML5勉強会 名古屋 #3 デモ用プロジェクト
========================================
デモで使用したプロジェクトは実際にインストールして動かしてみることができます。  
開発マシンにMacを使用していて手軽に試してみたい人はCodeKitを使って動かしてみてください。  
Windows, Linux, MacでRubyが動作する環境であればTerminalからコマンドラインで実行できます。

CodeKitを使う人へ
=================
CodeKitで手軽に動かしたい人向けです

1. 次のURLからファイルをダウンロード
  - <https://github.com/subak/html5_nagoya_3/archive/master.zip>
2. 適当な場所へファイルを解答
3. CodeKitを起動して解答してできたフォルダをドラッグアンドドロップ
4. 変換したいSCSSまたはSassファイルを選択
5. 右下の **Compile** ボタンをクリック
![CodeKit](http://subak.github.io/html5_nagoya_3/images/CodeKit.png)

Terminalを使う人へ
==================
Terminalから直接コマンドを叩く人向けです

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
