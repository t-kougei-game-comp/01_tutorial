# チュートリアル
-------------------

# 進め方
## はじめてのとき
* [GitHub](https://github.com/)のアカウントを作成してください
* [Travis CI](https://travis-ci.org/) のアカウントを作成してください
* GitHubのアカウントを[こちらのフォーム](https://goo.gl/forms/anAdoxqPKVt8sJGZ2)から教えてください。
## 毎回の進め方
* このリポジトリをforkしてください
* Travis CI を設定して、自動ビルドが通るようにしてください
   * Travis CI のGitHubアカウントでの登録とforkしたリポジトリをTravisCI側で許可する
   * 参考サイト：[Travis CI入門 Travis CIとGitHubでCIを実現する方法(Change the World!)](http://changesworlds.com/2014/09/introduction-to-travis-ci-and-github-001/)
* forkしたリポジトリの README.md ファイルの「t-kougei-game-comp」の部分を自分のGitHubアカウント名に差し替えてください(2箇所)
* 問題を解いて、テストを通るようにしてください。
* fork 元の master ブランチにプルリクエストを投げてください

# テスト結果

[![Build Status](https://travis-ci.org/t-kougei-game-comp/tutorial.svg?branch=master)](https://travis-ci.org/t-kougei-game-comp/tutorial)

# 今回の問題

環境に慣れるための課題です。

入力される文字列を出力してください。

Travis CI では、プロジェクトにある　input?.txt ファイルを標準入力として読み込んで、標準出力の結果を output?.txt ファイルと一致するか比較するテストをします。

main.c ファイルだけを書き換えて下さい。

## 入力される値
入力は以下のフォーマットで与えられます。
~~~
str
~~~
* str: 入力される文字列

## 期待する出力

入力された文字列を出力します。

最後は改行し、余計な文字、空行を含んではいけません。

## 条件

* 入力される文字列は一行
* 入力される文字数は改行を含めて256文字以内

## 入力例1
~~~
Hello world!
~~~

## 出力例1
~~~
Hello world!
~~~

## 入力例2
~~~
This is a pen.
~~~

## 出力例2
~~~
This is a pen.
~~~
