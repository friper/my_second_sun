﻿Deep Learning in Python
===

期待の地平

## base of Eco system Deep Learning

### 教師あり学習

利点

* 大量のデータ、一定の規則性がある→高確率
* 未知の情報に対するエラーが少ない

欠点

* データのラベル付けが必要
* データ加工のコストが高い
* 学習していないもの→誤検知を起こす

用途

　主に実用段階で利用する。→分類の精度が高いため　

### 教師なし学習

利点
* 少量のデータ、不規則性がある→教師あり学習に比べれば、高精度
* どんなものでも大まかに分類できる
* データのラベル付けがいらない

欠点
* 正確に分類することは難しい

用途

　主にテスト段階で利用する。→低コストで分類が実現できるため、精度が低いため

### 機械学習の問題

* 大量のデータがない、あってもそのラベリングが苦行
* 過剰適合・・・どんなデータも無理やり分類→エラーを見つけ辛い
* 次元の呪い・・・入力項目が多いと処理が鈍化→10M LANのような速度
* 特徴量エンジニアリング・・・教師なし学習を使おう！
* 学習データの加工・・・ゴミデータはエラーのもと
* データドリフト・・・都度最適化しないとね

### 教師あり学習

線形モデル：　線引いて、上か下か

例）身長から体重予測

* 線形回帰・・・単純明快すばらしい
* ロジスティック回帰・・・ちょっと賢くなったね

近傍ベースモデル：　近いか遠いか

例）推薦システム、ユーザーへのおすすめ

* ｋ近傍法・・・k-means clusteringのお友達

決定木ベースモデル：　分類、分類、最後に残ったのが正

例）汎用的に使われてるから特にこれってない

* 単独の決定木
* バギング・・・複数の単独決定木で判断、決定木の並列回路
* ランダムフォレスト・・・バギングの上位版
* ブースティング・・・複数の結合決定木で判断、決定木の直列回路

サポートベクタマシン：　境界線からの距離で判断

ニューラルネットワーク

### 教師なし学習

次元削減：　特徴値の抽出

* 線形斜影
* 多様体学習
* 独立成分分析
* LDA

クラスタリング：　グルーピング

* k-means clustering
* 階層クラスタリング
* DBSCAN

特徴量抽出

* オートエンコーダ
* 順伝播ニューラルネットワークを用意た特徴量抽出

教師なし深層学習

* 教師なし事前学習
* RBM：制限付きボルツマシン
* DBN：深層信念ネットワーク
* GAN：敵対的生成ネットワーク

教師なし学習を用いた逐次データ分析


## Start up Deep Learning

### Requirement

<PC>

* Github
* Anaconda

<Python Labrary>

* tensorFlow
* Keras
* pandas
* numpy
* matplotlib
* sklearn
* XGBoost
* LightGBM
* fastcluster
* hdbscan
* tslearn

### Program

線形モデル

* [線形回帰]()
* [ロジスティック回帰]()

近傍ベースモデル

* [ｋ近傍法]()

決定木ベースモデル

* [単独の決定木]()
* [バギング]()
* [ランダムフォレスト]()
* [ブースティング]()


## Dimension reduction


## Anomaly detection


## Clustering


## Grouping



