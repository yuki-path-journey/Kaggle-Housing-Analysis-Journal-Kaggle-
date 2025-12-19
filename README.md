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
# House Prices Mystery: Investigation log 🕵️‍♂️
このプロジェクトでは、アイオワ州エイムズの住宅価格データを、単なる数字としてではなく「生活者の視点」と「刑事の推理」で分析します。

## 🤝 Acknowledgments / チーム
- **Gemini (AI Thought Partner)**: 
  住宅の専門知識（温度差・水捌け等）をデータサイエンスの仮説に変換するサポートを担当。

---

## 📊 Investigation Cases

### Case 01: Heating Quality (HeatingQC) - 暖房の品質
**[Investigation / 捜査の目的]**
アイオワ州の過酷な冬を想定。暖房設備の品質が住宅の「資産価値」にどう直結するかを検証。

**[Findings / 調査結果]**
- **Ex (Excellent)**: 平均約21.5万ドル
- **Po (Poor)**: 平均約8.7万ドル
品質が一段階下がるごとに、価格も明確に下落する「負の相関」を確認。

**[Insight / 刑事の勘]**
暖房品質「Ex」は単なる設備の良さだけでなく、家全体の気密性や断熱リフォームが行き届いている「優良物件」の証拠である。


### Case 02: Land Slope (LandSlope) - 水捌けと地形
**[Investigation / 捜査の目的]**
水捌けの良さがシロアリや湿気対策に重要であるという仮説に基づき、地形の傾斜を調査。

**[Findings / 調査結果]**
- 大半(1382件)は平坦な土地(Gtl)に位置する。
- 意外にも「急傾斜(Sev)」の物件の方が平均価格が高い傾向。

**[Insight / 刑事の勘]**
急傾斜地の物件は、水捌けのリスクよりも「眺望(View)」という付加価値が勝っている可能性がある。ただし、サンプル数が13件と極めて少ないため、特定の豪邸による「外れ値」の影響を考慮すべきである。
![Heating Analysis](slope_analysis.png)
