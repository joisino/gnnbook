<p align="center">
  <img src="cover.jpg" width=50%>
</p>

書籍『[グラフニューラルネットワーク](https://www.amazon.co.jp/d/4065347823)』のサポートページです。

# ノートブック

以下のノートブックは MIT ライセンスのもと配布されております。商用・非商用問わず自由に利用することができます。

### 環境構築

[Poetry](https://python-poetry.org/) をインストールした後、このディレクトリ上で

```
$ poetry install
$ poetry run jupyter notebook
```

を実行して Jupyter Notebook を起動してください。

Colab で実行する場合は Colab 上で [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/) をインストールしてください。

### 一覧

|図|アルゴリズム|説明|ファイル|Colab|
|:----|:----|:----|:----|:----:|
|図 2.4|アルゴリズム 2.1|ラベル伝播法|[algo2.1.ipynb](https://github.com/joisino/gnnbook/blob/main/notebooks/algo2.1.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joisino/gnnbook/blob/main/notebooks/algo2.1.ipynb)|
|図 2.8|アルゴリズム 2.2|隣接行列の行列分解|[algo2.2.ipynb](https://github.com/joisino/gnnbook/blob/main/notebooks/algo2.2.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joisino/gnnbook/blob/main/notebooks/algo2.2.ipynb)|
|例 3.1||グラフ畳み込みネットワーク|[ex3.1.ipynb](https://github.com/joisino/gnnbook/blob/main/notebooks/ex3.1.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joisino/gnnbook/blob/main/notebooks/ex3.1.ipynb)|
|||グラフ注意ネットワーク|[gat.ipynb](https://github.com/joisino/gnnbook/blob/main/notebooks/gat.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joisino/gnnbook/blob/main/notebooks/gat.ipynb)|
|例4.1||グラフ分類（グラフ同型ネットワーク）|[ex4.1.ipynb](https://github.com/joisino/gnnbook/blob/main/notebooks/ex4.1.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joisino/gnnbook/blob/main/notebooks/ex4.1.ipynb)|
|図5.1||GNN の受容野|[fig5.1.ipynb](https://github.com/joisino/gnnbook/blob/main/notebooks/fig5.1.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joisino/gnnbook/blob/main/notebooks/fig5.1.ipynb)|
||アルゴリズム 5.1|近傍サンプリング|[algo5.1.ipynb](https://github.com/joisino/gnnbook/blob/main/notebooks/algo5.1.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joisino/gnnbook/blob/main/notebooks/algo5.1.ipynb)|
|図 6.13, 6.17|アルゴリズム 6.1, 6.2|グラフフーリエ変換|[graphfourier.ipynb](https://github.com/joisino/gnnbook/blob/main/notebooks/graphfourier.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joisino/gnnbook/blob/main/notebooks/graphfourier.ipynb)|
|例6.8||スペクトルクラスタリング|[ex6.8.ipynb](https://github.com/joisino/gnnbook/blob/main/notebooks/ex6.8.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joisino/gnnbook/blob/main/notebooks/ex6.8.ipynb)|
|例7.1, 7.2||過平滑化現象|[oversmoothing.ipynb](https://github.com/joisino/gnnbook/blob/main/notebooks/oversmoothing.ipynb)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joisino/gnnbook/blob/main/notebooks/oversmoothing.ipynb)|


# 正誤表

本書の正誤情報は[正誤表](https://github.com/joisino/gnnbook/blob/main/errata.md)にて公開しています。