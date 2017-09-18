# アプリを動かした際の環境設定

## python環境
* python version
	3.6.1
* 必要なモジュール( ()内はデフォルトで入っているはず)
	numpy pandas scipy (itertools copy sets os sys glob)

## R環境
* R version
	3.4.1
* 必要なパッケージ 
	shiny，shinydashboard，plotly，ggplot2，jpeg，igraph，visnetwork, markdown, doMC, rlist, lpSolve, clue


## c++環境
* 下記コマンドをあらかじめ行う
	1. `cd ***/my_app/WLK/graph-kernels/src/cc`
	2. `make`
	`/usr/local/include/eigen3`でエラーの場合`brew install eigen`で`make`は通るようになる



