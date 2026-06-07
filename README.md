# プロジェクト概要  
このプロジェクトファイルは様々な機械学習の手法について実際に自分で試して検証することを目的として作成しています。今回は機械学習のテーマとして英文のフェイクニュースの分類を選びました。また、機械学習の手法による精度や処理速度の差についても興味があったため、その比較検証も行っています。  
使用言語:  
- python 3.11 (64bit)  Word2Vec実行用
- python 3.14.5  その他モデル比較用  
仮想環境の作成方法: python 3.14.5は以下を実行  
```
py -3.14 -m venv .venv314
```
python 3.11は以下を実行  
```
py -3.11 -m venv .venv311
```
環境: Windows11, VSCode  
使用ライブラリ: pandas, scikit-learn, matplotlib, nltk  
python3.11では追加でgensimも使用  
インストール方法: 次のコマンドを仮想環境内コマンドラインで実行  

```
pip install pandas scikit-learn matplotlib nltk  
```
上のコマンドでうまくいかない場合は以下のコマンド  
```
python -m pip install pandas scikit-learn matplotlib nltk
```
# データセット 
https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets?resource=download  
# 各ファイルの説明:  

- Figures/ :機械学習の学習の処理結果のグラフを格納したファイル  
- Notebooks/FakeNewsMachineLearning.ipynb: すべての比較のベースとなる機械学習  
- Notebooks/FakeNewsMLCompare/01_Preprocessing.ipynb: 比較において共通の処理をまとめたもの  
- Notebooks/FakeNewsMLCompare/02_TF-IDF_And_LogisticRegression: TF-IDFとロジスティック回帰を使った学習  
