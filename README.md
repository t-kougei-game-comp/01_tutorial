# チュートリアル

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

## 出力例1
~~~
This is a pen.
~~~
