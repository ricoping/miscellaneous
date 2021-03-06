## 自己紹介
- 実務未経験
- 希望職種:
  - データサイエンティスト、データ分析、機械学習に関わるエンジニア
  - Webプログラマー
  
## 大学での制作物
寄付制を用いた漫画投稿サイト（2014, PHP, MySQL, Apache, VirtualBox)
  
## 大学での研究（B4)
ユーザの内的コンテキストに応じた推薦に関する研究
http://gospel.aid.design.kyushu-u.ac.jp/~ushiama/
  
## 作成したもの

### 機械学習

- <strong>ポケモン図鑑に関する考察</strong>
  - ポケモンの種族値について統計的に調べました
  - python, scikit learn, scipy, numpy, pandas
  - 詳細はこちら→https://github.com/ricoping/pokemon/blob/master/pokemon_description.ipynb
  - データ前処理→https://github.com/ricoping/pokemon/blob/master/pokemon.py

- <strong>LSTM(ディープラーニング)による文章自動生成</strong>
  - 寺田寅彦氏の文章の特徴を学習し、特徴を真似た文章を自動で生成
  - python, keras
  - 動画はこちら→https://twitter.com/rcpn_9/status/1106959593165340672
  - コード→https://github.com/ricoping/keras/blob/master/deepNiche.py
  - モデルの学習経過→https://github.com/ricoping/keras/blob/master/terada_results.txt
  
- <strong>ディープラーニングによるニュース記事分類</strong>
  - Livedoor newsコーパスを用いて、ジャンルごとに分類する分類器を作成
  - python
  - 教師データ1600,テストデータは800で正解率は95.5%、隠れ層２つ(ニューロン100と50)、学習率0.01、特徴量は単語10336語
  - コード→https://github.com/ricoping/deep-learning/blob/master/deep_train.py
  - データ前処理→https://github.com/ricoping/deep-learning/blob/master/deep_prepare.py
  - 結果→https://raw.githubusercontent.com/ricoping/deep-learning/master/deep_output.txt
  
- <strong>バズったツイートを決定木(CART)分析</strong>
  - 「バズったツイート」を「いいねを１００００以上得たツイート」と定義する
  - ツイートの特徴量を「文章に占めるひらがな・カタカナの割合」「画像の有無」とする
  - 「ひらがなの割合が5割以上で画像はなし」のツイートがよりいいねを得ているという結果になった
  - python
  - コード→https://github.com/ricoping/ricoping-ML/blob/master/tweet_tree.py
  - 決定木の画像→https://pbs.twimg.com/media/D1BOPwEVYAA2Zwa.jpg
  
- <strong>単純ベイズ分類器によるニュース記事分類</strong>
  - Livedoor newsコーパスを用いて、ジャンルごとに分類する分類器を作成
  - python
  - コード→https://github.com/ricoping/ricoping-ML/blob/master/news_classify.py  
  
- <strong>遺伝アルゴリズムによるマッチングシステム</strong>
  - ジョジョのスタンドのステータス（パワー、スピード、防御力、耐久力、技、応用力）のデータをもとに、同レベルかつ全体のレベルが高めになるような５体のスタンドグループをつくる
  - 「全体のレベルが均一」とはプレイヤー間の各ステータスのばらつき（分散）が小さいこととする
  - また全体のレベルはプレイヤーごとの平均の総和とする。以上を考慮して損失関数を作成。
  - 結果は「スティッキーフィンガーズ 、ストーンフリー 、メタリカ、ハーヴェスト 、クラフトワーク」の五体となった（変動あり）
  - python
  - コード→https://github.com/ricoping/ricoping-ML/blob/master/melone.py
  - 結果→https://github.com/ricoping/ricoping-ML/blob/master/melone_result.txt

- <strong>階層クラスタリングによるニュース記事分類</strong>
  - 類似するニュースを階層的にクラスタリングする
  - python
  - 結果→https://github.com/ricoping/miscellaneous/blob/master/categorize_output.txt
  - コード→https://github.com/ricoping/ricoping-ML/blob/master/news_clustering.py
  - 行が近いほど類似するニュース
  
- <strong>k平均法</strong>
  - ジョジョのスタンドのステータス（パワー、スピード、防御力、耐久力、技、応用力）のデータを使って、スタンドをk平均法（k=3）で分類
  - python
  - 結果→https://raw.githubusercontent.com/ricoping/ricoping-ML/master/jojo_clustering_output.txt
  - コード→https://github.com/ricoping/ricoping-ML/blob/master/jojo_clustering.py
   
### Web系
- <strong>Django, Vue.jsを用いたモダンなウェブデザインサイト</strong>
  - ポートフォリオサイトです
  - http://140.227.227.5/learn/hello(停止中)
  
- <strong>Djangoを用いた英語学習SNSサイト</strong>
  - Bootstrap
  - データ処理など: Python, Bash
  - Twitter APIを用いて自動で英語のニュースを収集します
  - みんなで英語のニュースを翻訳しながら英語を学習することが目的です
  - 気に入ったユーザはフォローできます
  - 翻訳してほしい記事はリクエストできます
  - Twitter認証で登録できます
  - URL→http://140.227.227.5/learn/(停止中)
  - 紹介動画→https://twitter.com/rcpn_9/status/1099919186753507328
  - 2.→https://twitter.com/rcpn_9/status/1099920097458569216
  
- <strong>Twilyco</strong>
  - Django, CSS, Javascript
  - バズったツイートをクローリングして収集し、紹介するサイト
  - LINE画面を参考にしたデザインで使いやすくしました
  - クローラーにはアニーリング法の考え方を採用
  - http://140.227.224.71/tw/politics/1(停止中)
  
- <strong>Django, Vue.js, Ajaxを用いたチャット</strong>
  - http://140.227.227.5/todo/chat(停止中)

- <strong>SPA(シングルページアプリケーション)を用いたコメント機能付きニュース記事表示サイト</strong>
  - Vue.js, Bootstrap, JSON server
  - Yahoo newsをXML（RSS）で取得し、JSON形式で保存
  - JSONサーバーを立ち上げ、fetchAPIで取得したニュース記事を表示
  - コメント機能つき
  - https://twitter.com/rcpn_9/status/1117465909814337538
  
- <strong>シンプルなブログサイト</strong>
  - PHP, HTML, CSS
  - セッションを用いた登録・ログイン機能
  - バリデーション機能
  - ブログ投稿機能
  - https://twitter.com/rcpn_9/status/1115972762558844930
  
- <strong>パララックスを用いたデザインサイト</strong>
  - PHP, jQuery, HTML
  - セッションを用いた登録・ログイン機能
  - jQueryプラグイン多数
  - http://tomatocake.php.xdomain.jp/index.php

### ユーティリティ

- <strong>Googleで画像検索を行い、顔の部分だけ切り出して保存するツール「face-images」</strong>
  - https://github.com/ricoping/face-images

- <strong>まとめサイト記事作成自動化ツール（5ch）</strong>
  - 紹介動画→https://twitter.com/rcpn_9/status/1100625622953484288
  - 2.→https://twitter.com/rcpn_9/status/1100626117877088256
  
- <strong>まとめサイト記事作成自動化ツール(Twitterまとめ)</strong>
  - 紹介動画→https://twitter.com/rcpn_9/status/1099704181265289216
  
  
## 最近読んだ本
 - Hands-On Machine Learning with Scikit-Learn and TensorFlow
 - 集合知プログラミング
 - PythonとKerasによるディープラーニング
 - ゼロから作るDeep Learning ―Pythonで学ぶディープラーニングの理論と実装
 
 
## 経験したフルタイムの仕事
### コールセンター
  - 携帯電話の料金コンサル
    - 料金プランを全て把握し、お客様と喋りながら過去の利用履歴を参照し、かつ電卓を叩く必要があったので、マルチタスク能力が養われました
    
  - 太陽光発電の出力制御に関するお問い合わせ対応
    - 専門的な知識だけでなく電力会社と国との間の法律なども案内する必要があったので、視野が広まりました
    
  - クレジットカード関連
   
  - 日本年金機構
   
### ゲームのデバッグ
 - エクセルやSlack, G suiteを利用して、チームで協力しながらゲームのバグを探すお仕事で、チームワークを学びました
    
