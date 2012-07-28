Shellfish でコマンドを覚えよう
==============================

色々なコマンドを駆使して問題を解決しよう。

遊び方
------

GitHub からダウンロードできます。  
インストールして実行するには Ruby 及び Bundler が必要です。

```
$ git clone https://github.com/yuya-takeyama/learn-shell-commands-with-shellfish.git
$ cd learn-shell-commands-with-shellfish
$ bundle install --path=vendor/bundle
$ bundle exec shellfish problems/*
```

以上のコマンドで `shellfish` のシェルが立ち上がります。  
通常のシェルと同様にコマンドが実行できます。  
コマンドを駆使して、出力が期待結果に一致すると正解で、次の問題に進みます。

スペシャルサンクス
------------------

問題ははてなダイアリーの [id:Yamashiro0217](http://d.hatena.ne.jp/Yamashiro0217/) さんの記事をほぼそのまま利用させていただきました。  
問題ありましたら [@yuya_takeyama](http://twitter.com/yuya_takeyama) までご連絡ください。

- [シェル操作課題 (cut, sort, uniq などで集計を行う) 設問編](http://d.hatena.ne.jp/Yamashiro0217/20120727/1343371036)

なお、問題文中の「このファイル」という表現は「log.csv」として置き換えています。  
また、想定期待結果のうち間違いと思われるものはこちらで修正しています。

この README.md を書いた人
-------------------------

Yuya Takeyama
