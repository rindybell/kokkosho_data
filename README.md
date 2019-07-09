# 車両不具合情報に関するデータセット


## 概要
車両の不具合情報について、ユーザからの申告内容の要約（テキスト）と、  
不具合装置（クラスラベル）が対となったデータセットです。  
研究目的に限り利用することが可能です。文書分類の検証等にご利用ください。  

## 提供するデータについて

### データフォーマット

2列のtsvファイルであり、  
1列目は不具合装置（クラスラベル）、2列目は申告内容の要約（テキスト）を意味します。  
データの具体例については、`sample.tsv`をご確認ください。  


### データ統計量

学習データ、検証データ、評価データに関する、データ量を以下に示します。  

|ファイル名|用途|データ量|
|-|-|-:|
|kokkousho_train.tsv|学習データ|37664|
|kokkousho_dev.tsv|検証データ|4708|
|kokkousho_test.tsv|評価データ|4708|


### データ構築方法

2017年5月頃に、下記URLからクローリングして構築しました。
[http://carinf.mlit.go.jp/jidosha/carinf/opn/index.html](http://carinf.mlit.go.jp/jidosha/carinf/opn/index.html)




## ファイルの解凍

gunzipコマンド等をご利用ください。


## 利用上の注意

- 研究目的でのみ利用可能です。
- 本データの利用において発生したあらゆる不利益について、
  国土交通省さま及び@rindybellは、責任を負いません。


## 公開者

[@rindybell](https://twitter.com/rindybell)


## 謝辞

本データの公開につきまして、
快く承諾していただいた国土交通省さまに感謝します。
