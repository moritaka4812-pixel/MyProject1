プロジェクト概要:<br>
このプロジェクトファイルは様々な機械学習の手法について実際に自分で試して検証することを目的として作成しています。今回は機械学習のテーマとして英文のフェイクニュースの分類を選びました。また、機械学習の手法による精度や処理速度の差についても興味があったため、その比較検証も行っています。<br>
使用言語: python 3.14.5 <br>
環境: Windows11, VSCode <br>
使用ライブラリ: pandas, scikit-learn, matplotlib, nltk<br>
インストール方法: 次のコマンドをコマンドラインで実行 <br>
'pip install pandas scikit-learn matplotlib nltk'<br>
データセット: https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets?resource=download <br>
各ファイルの説明:<br>
Figures/ :機械学習の学習の処理結果のグラフを格納したファイル
Notebooks/FakeNewsMachineLearning.ipynb: すべての比較のベースとなる機械学習
Notebooks/FakeNewsMLCompare/01_Preprocessing.ipynb: 比較において共通の処理をまとめたもの
Notebooks/FakeNewsMLCompare/02_TF-IDF_And_LogisticRegression: TF-IDFとロジスティック回帰を使った学習
