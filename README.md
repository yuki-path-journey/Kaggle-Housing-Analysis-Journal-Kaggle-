"Kaggle House Prices Analysis: Identifying Value through Environmental Factors"# Kaggle-Housing-Analysis-Journal-Kaggle-
「実務での環境（気温）意識をデータ分析に活用するプロジェクト」
# Kaggle House Prices Analysis 🏠🌡️

### 📝 Project Overview
このプロジェクトでは、単なる統計モデルの構築だけでなく、実務経験に基づいた「環境・気温要因」が不動産価格に与える影響を分析しています。

### 💡 Key Insights (My Personal Hypothesis)
現在、私は気温の変化が激しい環境で働いており、環境の変化が人間の活動や設備の価値に直結することを日々実感しています。
この視点を住宅データに適用し、以下の項目に注目しました。

- **CentralAir (エアコン)**: アイオワ州の気候において、エアコンの有無は平均価格で約 **$80,923 (約1,200万円)** もの差を生むことが判明。
- **MoSold (売却月)**: 気温が上がる6月〜7月に取引が集中し、冬場の約5倍の取引量になる市場の季節性を特定。

### 📊 Results
- **First Submission Score**: 0.71890
- **Approach**: Linear Regression using Quality, Area, House Age, and CentralAir.
Case 01: Heating Quality (HeatingQC)
[Investigation / 捜査の目的] アイオワ州の厳しい冬を想定。暖房設備(HeatingQC)の品質が住宅価格に与える影響をプロファイリングする。

[Findings / 調査結果] 「Ex (Excellent)」評価の物件が、他のランクと比較して圧倒的に高値で取引されていることが判明。

[Insight / 刑事の勘] 「Ex」評価は単なる暖房機の性能だけでなく、建物全体の気密性や断熱リフォームが完了していることを示唆している。冬の光熱費という「ランニングコスト」を抑えられる物件が、市場では高い資産価値として認められている。
