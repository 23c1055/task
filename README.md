# アルファベットカウンタ

![Build Status](https://github.com/23c1055/task/actions/workflows/test.yml/badge.svg)
<img src="https://img.shields.io/badge/-Python-F9DC3E.svg?logo=python">
![Needed Python version](https://img.shields.io/badge/Needed_Python_version-3_or_more-blue)
![Downloads](https://img.shields.io/badge/Downloads-1-green)


Pythonでアルファベットをカウント

## 概要

- このプロジェクトでは、入力ファイルにある英文で出現した各アルファベットの個数をカウントします。 

- このプロジェクトは数値解析における自然言語の確率的生成の調査として、任意の英文を読み込みます。また、GITHUBへプッシュするまでの過程やGITHUB Actionsの実施、README.mdの整備練習を兼ねています。

- input.txtファイルに入力されている英文をtask1ファイルが読み込み、文中の小文字に変換された各アルファベットと空白、その他記号をそれぞれカウントしアルファベットは出現回数の降順で表示します。また、全アルファベットの出現回数を総和したtotalから、各アルファベットの出現率を計算しています。なお、input.txtレポジトリ内の空白や記号を含めたすべての数はtotal space othersの和でもとめられます。

## インストール方法

  以下の手順でプロジェクトをローカルレポジトリにインストールしてください。

```bash
リポジトリをクローン
git clone https://github.com/23c1055/task.git

ディレクトリに移動
cd task

依存関係をインストール
pip install -r requirements.txt
```
## 使い方

実行方法の例

```bash
入力ファイルを開く。
nano input.txt
適当な英文を打ち込み、ファイル内にあるショートカットキーの案内に従い保存して終了する。

実行ファイルの実行
./task1
```

サンプルコード

```input.txt```に以下を入力します。

```
Thanks for using. ありがとう!!
```
以下はその時の```task```の実行結果です。

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

## 貢献

貢献方法は以下の通りです。

1.フォークする。

2.新しいブランチを作成する。(```bash git checkout -b feature/YourFeature```)

3.コードをコミットする。(```bash git commit -m "Add some feature"```)

4.プッシュする。(```bash git push origin feature/Yourfeature```)

5.プルリクエストを作成する。

## ライセンス

- このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されています。
- 2024　Goto　Shingo
