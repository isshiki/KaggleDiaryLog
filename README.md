KaggleDiaryLog： Kaggle日記のログ
=================================

Kaggleで作業した日々の内容を書きつづった日誌のうち、コンペが終わるなどしたため、記録保存用に回したものです。

目次
----------------------------------

### :house:[［トップページ］](https://github.com/isshiki/KaggleDiaryLog)

### :runner:[［competitions］フォルダー](https://github.com/isshiki/KaggleDiaryLog/tree/main/competitions): コンペ

- [Kaggle日記： Kaggle機能や分類問題の:lab_coat:**実験場**](https://github.com/isshiki/KaggleDiaryLog/blob/main/competitions/titanic/Diary.md)
- [Kaggle日記： 回帰問題の:lab_coat:**実験場**](https://github.com/isshiki/KaggleDiaryLog/blob/main/competitions/house-prices-advanced-regression-techniques/Diary.md)
- [Kaggle日記（2021年8月13日～18日、おまけ：20日）： コンペ「Housing Prices Competition for Kaggle Learn Users」](https://github.com/isshiki/KaggleDiaryLog/blob/main/competitions/home-data-for-ml-course/Diary.md)
- [Kaggle日記（2021年8月18日、24日～31日）： コンペ「30 Days of ML」](https://github.com/isshiki/KaggleDiaryLog/blob/main/competitions/30-days-of-ml/Diary.md)

### :bar_chart:[［datasets］フォルダー](https://github.com/isshiki/KaggleDiaryLog/tree/main/datasets): データセット

### :computer:[［code］フォルダー](https://github.com/isshiki/KaggleDiaryLog/tree/main/code): 上記以外

- [ノートブック： Kaggle APIの使い方](https://github.com/isshiki/KaggleDiaryLog/blob/main/code/kaggle-api/notebooks/KaggleAPI.ipynb)

### :busts_in_silhouette:[［courses］フォルダー](https://github.com/isshiki/KaggleDiaryLog/tree/main/courses): Kaggle公式講座

- [Kaggle日記（2021年8月3日～9日）： Kaggle公式講座「Python」の履修](https://github.com/isshiki/KaggleDiaryLog/blob/main/courses/python/Diary.md)
- [Kaggle日記（2021年8月10日～13日）： Kaggle公式講座「Intro to Machine Learning」の履修](https://github.com/isshiki/KaggleDiaryLog/blob/main/courses/intro-to-machine-learning/Diary.md)
- [Kaggle日記（2021年8月14日～18日）： Kaggle公式講座「Intermediate Machine Learning」の履修](https://github.com/isshiki/KaggleDiaryLog/blob/main/courses/intermediate-machine-learning/Diary.md)

フォルダー名とファイル名のルール
----------------------------------

- フォルダー名：Kaggleサイト上の各コンペ／講座のURLで使われている文字列をそのまま使う。
  例えば「[Learn Intro to Machine Learning Tutorials | Kaggle](https://www.kaggle.com/learn/intro-to-machine-learning)」講座のURLは「intro-to-machine-learning」にする。
- ファイル名：日記は「Diary.md」に統一する。検索しやすくするため。

日記の書き方と心構え
----------------------------------

- できるだけフラットに書く。
- フォーマットや見た目にはこだわらない。
- 凝ったりするムダな時間は使わない。手が動くままに自由に書く。
- 自分だけが分かればいいが、チームならチーム内で説明するときに使える資料にもなった方がいいね。
- コンペ参加時のアイデア管理／実験計画には、GitHubのプロジェクトボードを使う。
- 参考：「[Kaggle日記という戦い方](https://zenn.dev/fkubota/articles/3d8afb0e919b555ef068)」

コンペ提出ログの書き方フォーマット
----------------------------------

- `:+1: :-1: :point_right: [バージョン番号：Baseline／Improved／NotChanged／Worsened]【Public Score】（順位：Top ？％）簡易説明`
- :+1: :-1: :point_right: [バージョン番号：Baseline／Improved／NotChanged／Worsened]【Public Score】（順位：Top ？％）簡易説明
- [🎁 絵文字を探す](https://www.webfx.com/tools/emoji-cheat-sheet/)

コンペ提出時の説明欄の書き方フォーマット
----------------------------------

- 例：Notebook \<NotebookName> | Model v3
- 例：Azure AutoML - LightGBM | Model v5
- バージョン部分は、コミットバージョンと区別するため、「Model v＜バージョン番号＞」という書き方にする

コンペのチーム戦について
----------------------------------

- チーム作業では、**個人で進めて競争**し、途中で**技術内容の共有と評価**を行ったうえで、最後に**アンサンブル**する。
- ただし、EDA（探索的データ分析）など情報共有が他のチームメンバーに役立つ部分では役割分担するのもあり。
- 参考：[この記事で書かれている「チームでの動き方」](https://amalog.hateblo.jp/entry/kaggle-home-credit#%E3%83%81%E3%83%BC%E3%83%A0%E3%81%A7%E3%81%AE%E5%8B%95%E3%81%8D%E6%96%B9)

ライセンス
--------------------------------

- Apache License 2.0
- [ライセンスページ](https://github.com/isshiki/KaggleDiaryLog/blob/main/LICENSE)
