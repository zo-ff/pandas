# analysis 索引

データセット・手法から探すための一覧。ノートブックを追加/移動したらここも更新する。

| フォルダ | ファイル | データセット | 手法 | メモ |
|---|---|---|---|---|
| titanic/ | decision_tree.ipynb | Titanic (Kaggle) | 決定木(分類) | notes_decision_tree.md に学習メモ |
| titanic/ | random_forest.ipynb | Titanic (Kaggle) | ランダムフォレスト(分類) | |
| steel_industry/ | steel_industry.ipynb | Steel Industry Energy | EDA / STL・MSTL時系列分解 | Usage_kWhの欠損確認・季節性分解 |
| steel_industry/ | OLS_steelindustry.ipynb | Steel Industry Energy | OLS回帰 | Day_of_week+Load_Type+NSMをダミー化、R²=0.484(in-sample) |
| practice/ | corr_heatmap_practice.ipynb | (合成データ、非依存) | 相関行列/ヒートマップ | 手法確認用の練習 |

## フォルダ分けの方針
- フォルダはデータセット単位。手法別・ジャンル別には分けていない。
- ジャンル階層(例: 製造業/)は、同ジャンルのデータセットが3つ以上溜まったら検討する。
