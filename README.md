# アルファベットカウンタ

Pythonでアルファベットをカウント

## 概要

- このプロジェクトでは、入力ファイルにある英文で出現した各アルファベットの個数をカウントします。 
- このプロジェクトは数値解析の自然言語の確率的生成の調査として、任意の英文を読み込みます。また、GITHUBへプッシュするまでの過程やGITHUB Actionsの実施、README.mdの整備練習を兼ねています。
- input.txtレポジトリに入力されている英文をtask1レポジトリが読み込み、文中の各アルファベットと空白、その他記号をそれぞれカウントします。また、全アルファベットの出現回数を総和したtotalから、各アルファベットの出現率を計算しています。なお、input.txtレポジトリ内の空白や記号を含めたすべての数はtotal space othersの和でもとめられます。

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

```input.txt```に以下を入力

```Thanks for applying !!```

上記を行った場合の```task1```の実行結果

```
```



- このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されています。
- 2024　Goto　Shingo
