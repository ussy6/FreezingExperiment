# Freezing experiment data viewer

## Overview

実験データ解析用のpythonスクリプトです．ロガーから回収したCSV形式の温度データの整形し，グラフ化することができます．スクリプトはjupyter notebook形式で記述しています．

A python script for analyzing experimental data. Temperature data in CSV format collected from the logger can be formatted and graphed. The script is written in jupyter notebook format.

## Requirement
- Python
- 

pipenvが使える環境であれば下記のコマンドでPipfileから仮想環境が構築されます．

If you can use pipenv, the virtual environment will be built from the Pipfile with the following command.

## Usage

- お使いの環境に合わせて必要ライブラリをインストールしてください．Pythonの環境がない場合はこちら(  )を使ってください．使い方はリンク先に書いています．

- input, output, graphというフォルダが存在することを確認してください．なければ作成してください．

- ロガーから回収したcsvファイルをinputフォルダに入れます．この状態でmake_tempfile.ipynbを開いて実行するとinput内のcsvファイルが全て結合されたtemp.csvがoutputフォルダ内に生成されます．このとき，以前に作られたtemp.csvは上書きされる点に注意してください．

- temp_viewer.ipynb実行するとgraphフォルダ内にグラフの画像ファイルが生成されます．PNG形式とSVG形式のファイルが利用可能です．
 




