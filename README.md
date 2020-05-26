# 本プログラムについて
- PytorchでMNISTを解くサンプルプログラム。  
- 特にkaggleに特化しており、csv入力のデータを対象として作成。
- 動作確認に用いたデータは、kaggleで開催されているDigit Recognizerコンペにて提供されるtrain.csv, test.csv

# 動作環境
- Python 3.7系
- Pytorch 1.5
- その他Numpy, Pandasなどは入れておいてください。

# フォルダ
- 01_input：教師データ(train.csv)、テスト用データ(test.csv)を格納する。kaggleのDigit Recognizerのファイルを配置すること。  
- 02_output：学習済みのモデル、テスト用データに対する予測結果を格納する。

# 使い方
1. 本リポジトリをcloneする。
2. 自身でinputフォルダに学習用データ、テスト用データをそれぞれ格納する。
3. notebookのセルを上から順に実行する。ただし、Datasetの内容は自身のデータ量に合わせて書き換える必要があるため、注意されたい。
