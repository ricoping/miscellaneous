## 自己紹介

福岡市在住

## 作成したもの

### 機械学習

- ポケモン図鑑に関する考察
  - ポケモンの種族値について統計的に調べました
  - python, scikit learn, scipy, numpy, pandas
  - 詳細はこちら→https://github.com/ricoping/pokemon/blob/master/pokemon_description.ipynb
  - データ前処理→https://github.com/ricoping/pokemon/blob/master/pokemon.py

- LSTM(ディープラーニング)による文章自動生成
  - 寺田寅彦氏の文章の特徴を学習し、特徴を真似た文章を自動で生成
  - python, keras
  - 動画はこちら→https://twitter.com/rcpn_9/status/1106959593165340672
  - コード→https://github.com/ricoping/keras/blob/master/deepNiche.py
  - モデルの学習経過→https://github.com/ricoping/keras/blob/master/terada_results.txt
  
- ディープラーニングによるニュース記事分類
  - Livedoor newsコーパスを用いて、ジャンルごとに分類する分類器を作成
  - python
  - 教師データ1600,テストデータは800で正解率は95.5%、隠れ層２つ(ニューロン100と50)、学習率0.01、特徴量は単語10336語
  - コード→https://github.com/ricoping/deep-learning/blob/master/deep_train.py
  - データ前処理→https://github.com/ricoping/deep-learning/blob/master/deep_prepare.py
  - 結果→https://raw.githubusercontent.com/ricoping/deep-learning/master/deep_output.txt
  
- バズったツイートを決定木(CART)分析
  - 「バズったツイート」を「いいねを１００００以上得たツイート」と定義する
  - ツイートの特徴量を「文章に占めるひらがな・カタカナの割合」「画像の有無」とする
  - 「ひらがなの割合が5割以上で画像はなし」のツイートがよりいいねを得ているという結果になった
  - python
  - コード→https://github.com/ricoping/ricoping-ML/blob/master/tweet_tree.py
  - 決定木の画像→https://pbs.twimg.com/media/D1BOPwEVYAA2Zwa.jpg
  
- 単純ベイズ分類器によるニュース記事分類
  - Livedoor newsコーパスを用いて、ジャンルごとに分類する分類器を作成
  - python
  - コード→https://github.com/ricoping/ricoping-ML/blob/master/news_classify.py  
  
- 遺伝アルゴリズムによるマッチングシステム
  - ジョジョのスタンドのステータス（パワー、スピード、防御力、耐久力、技、応用力）のデータをもとに、同レベルかつ全体のレベルが高めになるような５体のスタンドグループをつくる
  - 「全体のレベルが均一」とはプレイヤー間の各ステータスのばらつき（分散）が小さいこととする
  - また全体のレベルはプレイヤーごとの平均の総和とする。以上を考慮して損失関数を作成。
  - 結果は「スティッキーフィンガーズ 、ストーンフリー 、メタリカ、ハーヴェスト 、クラフトワーク」の五体となった（変動あり）
  - python
  - コード→https://github.com/ricoping/ricoping-ML/blob/master/melone.py
  - 結果→https://github.com/ricoping/ricoping-ML/blob/master/melone_result.txt

- 階層クラスタリングによるニュース記事分類
  - 類似するニュースを階層的にクラスタリングする
  - python
  - 結果→https://github.com/ricoping/miscellaneous/blob/master/categorize_output.txt
  - コード→https://github.com/ricoping/ricoping-ML/blob/master/news_clustering.py
  - 行が近いほど類似するニュース
  
- k近傍法
  - ジョジョのスタンドのステータス（パワー、スピード、防御力、耐久力、技、応用力）のデータを使って、スタンドをk近傍法（k=3）で分類
  - python
  - 結果→https://raw.githubusercontent.com/ricoping/ricoping-ML/master/jojo_clustering_output.txt
  - コード→https://github.com/ricoping/ricoping-ML/blob/master/jojo_clustering.py
   
### Web系
- Django, Vue.jsを用いたモダンなウェブデザインサイト
  - ポートフォリオサイトです
  - http://140.227.227.5/learn/hello
  
- Djangoを用いた英語学習SNSサイト
  - Bootstrap
  - データ処理など: Python, Bash
  - Twitter APIを用いて自動で英語のニュースを収集します
  - みんなで英語のニュースを翻訳しながら英語を学習することが目的です
  - 気に入ったユーザはフォローできます
  - 翻訳してほしい記事はリクエストできます
  - Twitter認証で登録できます
  - URL→http://140.227.227.5/learn/
  - 紹介動画→https://twitter.com/rcpn_9/status/1099919186753507328
  - 2. →https://twitter.com/rcpn_9/status/1099920097458569216
  
- Twilyco
  - Django, CSS, Javascript
  - バズったツイートをクローリングして収集し、紹介するサイト
  - LINE画面を参考にしたデザインで使いやすくしました
  - クローラーにはアニーリング法の考え方を採用
  - http://140.227.224.71/tw/politics/1
  
- Django, Ajaxを用いたチャット
  - http://140.227.227.5/todo/chat


### ユーティリティ

- Googleで画像検索を行い、顔の部分だけ切り出して保存するツール「face-images」
  - https://github.com/ricoping/face-images

- まとめサイト記事作成自動化ツール（5ch）
  - 紹介動画→https://twitter.com/rcpn_9/status/1100625622953484288
  - 2.→https://twitter.com/rcpn_9/status/1100626117877088256
  
- まとめサイト記事作成自動化ツール(Twitterまとめ)
  - 紹介動画→https://twitter.com/rcpn_9/status/1099704181265289216
  
