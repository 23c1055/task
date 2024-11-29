# アルファベットカウンタ

![status](https://github.com/23c1055/task/actions/workflows/test.yml/badge.svg)
<img src="https://img.shields.io/badge/-Python-F9DC3E.svg?logo=python">
![Python version](https://img.shields.io/badge/Needed_Python_version-3_or_more-blue)
![Downloads](https://img.shields.io/badge/Downloads-1-green)


Pythonでアルファベットをカウント

## 必要なソフトウェア

- Python 

    - テスト済み: 3.7 ~ 3.11

## テスト環境

- Ubuntu 20.04 on Windows

## 概要

- このプロジェクトでは、実行環境に入力された文で出現した各アルファベットの個数をカウントします。 

- 実行環境に入力されている英文をtask1ファイルが読み込み、文中の小文字に変換された各アルファベットと空白、その他記号をそれぞれカウントしアルファベットは出現回数の降順で表示します。また、全アルファベットの出現回数を総和したtotalから、各アルファベットの出現率を計算しています。なお、文中の空白や記号を含めたすべての数はtotal space othersの和でもとめられます。

## 使用方法

  以下の手順でプロジェクトをローカルレポジトリにインストールしてください。

```bash
リポジトリをクローン
git clone https://github.com/23c1055/task.git

ディレクトリに移動
cd task

権限の付与
chmod +x task1

```


実行方法の例

```bash

実行ファイルの実行
./task1
```

サンプルコード

実行環境に以下の文章を入力します。

```
Thanks for using. ありがとう!!
```
以降が、その時の```task```の実行結果です。

```
n: 2    :14.29%
s: 2    :14.29%
t: 1    :7.14%
h: 1    :7.14%
a: 1    :7.14%
k: 1    :7.14%
f: 1    :7.14%
o: 1    :7.14%
r: 1    :7.14%
u: 1    :7.14%
i: 1    :7.14%
g: 1    :7.14%
space:3
others:8
total:14
```

## 現状で想定される不具合とその回避

- 変数otherのカウントが多い。
- Enterを押しても実行結果が表示されない
    - otherには改行を含むEnterを押された回数も含みます。終了の際は、それら変数の過剰カウントを避けるために以下の動作を連続で２回おこなってください。
   
        ```Ctrl```を押しながら```D```を押す。
- ```test```ファイルにて、いかなる文字列でも変数othersが1つ多くカウントされている。
    - この不具合は現在解明中です。今のところ、```test内の変数others```のカウントを一つ多くして対処しています。なお、```task1```にそれら不具合はなく、正常にカウントできています。

 
## ライセンス

- このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されています。

©2024 Goto Shingo
