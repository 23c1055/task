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

- Ubuntu 20.04以降

## 概要

- このプロジェクトでは、実行環境に入力された文で出現した各アルファベットの個数をカウントします。 

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
echo Thanks for using. ありがとう!! | ./task1
```
以降が、その時の```task1```の実行結果です。

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
others:7
total:14
```

## ライセンス

- このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されています。

©2024 Goto Shingo
