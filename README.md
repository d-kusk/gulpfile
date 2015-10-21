# my-gulpfiles

よく使う gulp のタスクファイル

## 出来る事
* Slimのコンパイル
* Jadeのコンパイル
* Sassのコンパイル
* CoffeeScriptのコンパイル
* ベンダープレフィックスの自動付与
* エラーが起きてもwatchタスクを止めない
* CSSの圧縮(別ファイルの作成)
* Javascriptファイルの圧縮(別ファイルの作成)
* ブラウザーのオートリロード

## 使い方
1. ファイルをダウンロード
2. `npm install`  
  でプラグインをインストールする。  
  package.jsonに書かれたNodeのモジュールがインストールされる。
3. `gulp watch`  
  でwatchタスクを走らせる
4. 作業を開始する