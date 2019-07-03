# Ruby on Rails チュートリアルのサンプルアプリケーション

これは次の教材で作られたサンプルアプリケーションです。<br>
[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)<br>
[Michael Hartl](http://www.michaelhartl.com/) 著

## ライセンス

[Ruby on Rails チュートリアル](https://railstutorial.jp/)内にあるソースコードはMITライセンスとBeerwareライセンスのもとで公開されています。<br>
詳細は[LICENSE.md](LICENSE.md)を御覧ください。

## 使い方
このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。<br>
その後、次のコマンドで必要になるRubyGemsをインストールします。

```
$ bundle install --without production
```

その後、データベースへのマイグレーションを実行します。

```
$ rails db:migrate
```

最後に、テストを実行してうまく動いているかどうか確認してください。

```
$ rails test
```

テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っているはずです。

```
$ rails server
````

詳しくは、[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
を参考にしてください。