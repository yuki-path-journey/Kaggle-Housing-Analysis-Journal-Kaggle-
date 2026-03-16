# Kaggle Housing Analysis Journal

## Project Overview
This project explores housing price trends using Kaggle datasets. My goal is to extract key factors that influence market value.

## Why this matters?
# Kaggle Housing Analysis Journal

## ✉️ Open to Professional Collaboration
This model is currently helping 40+ daily users with housing market projections. If you're interested in implementing, consulting, or exploring new analytical opportunities, let's connect!

## Project Overview
This project explores housing price trends using Kaggle datasets. My goal is to extract key factors that influence market value.

## Why this matters? (My Professional Perspective)
I work in an environment with extreme temperature fluctuations. Every day, I witness how environmental changes directly impact human activity and the value of infrastructure. 

As of December 19, 2025, I have abandoned the previous statistical baseline (correlation coefficient of 0.14). Instead, I am "prosecuting" each factor of housing value from a professional's viewpoint:
- **Thermal Comfort:** How temperature differentials impact home value.
- **Infrastructure:** The real-world reliability of housing support systems.
- **Maintenance:** The silent value of consistent upkeep.

## How you can help
This is an open journal for data science experiments. I would love to hear your thoughts!
- **Feedback:** If you have suggestions for feature engineering or model tuning, feel free to open an issue.
- **Collaboration:** Feel free to fork this repository to experiment with your own models.
- **Stars:** If you find this analysis helpful, please leave a star to support the project!

## Latest Update
"Currently experimenting with new feature engineering strategies. Refining my 'prosecution' logic!"

## How you can help
This is an open journal for data science experiments. I would love to hear your thoughts!
- **Feedback:** If you have suggestions for feature engineering or model tuning, feel free to open an issue.
- **Collaboration:** Feel free to fork this repository to experiment with your own models.
- **Stars:** If you find this analysis helpful, please leave a star to support the project!

## Latest Update
"Currently experimenting with new feature engineering strategies."
---
### ✉️ Open to Professional Collaboration
This model is currently helping 40+ daily users with housing market  I'mprojections.
If you're interested in implementing, consulting, or exploring new analytical opportunities, let's connect:

---
### 🌍 Live Traffic Status
![Flag Counter]　<img width="320" height="568" alt="Image" src="https://github.com/user-attachments/assets/e4c64dbb-9bf7-4e62-9681-9019bc64ef34" />- 

### 📧 Contact
**Email:** ncis.la.no85@gmail.com
-
**LinkedIn Profile:** [Professional Profile](https://www.linkedin.com/in/友紀-神谷-2427b737a/)
---

---

## 🔍 Overview / Documentation
---

- **Case 03 # Kaggle House Prices Analysis: Identifying Value through Environmental Factors
「実務での環境（気温）意識をデータ分析に活用するプロジェクト」

# Kaggle House Prices Analysis 🏠🌡️

### 📝 Project Overview
このプロジェクトでは、単なる統計モデルの構築だけでなく、実務経験に基づいた「環境・気温要因」が不動産価格に与える影響を分析しています。

### 💡 Key Insights (My Personal Hypothesis)
現在、私は気温の変化が激しい環境で働いており、環境の変化が人間の活動や設備の価値に直結することを日々実感しています。
この視点を住宅データに適用し、以下の項目に注目しました。

- **CentralAir (エアコン)**: アイオワ州の気候において、エアコンの有無は平均価格で約 **$80,923 (約1,200万円)** も差を生むことが判明。
- **MoSold (売却月)**: 気温が上がる6月〜7月に取引が集中し、冬場の約5倍の取引量になる市場の季節性を特定。

### 📊 Results
- **First Submission Score**: 0.71890
- **Approach**: Linear Regression using Quality, Area, House Age, and CentralAir.

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
<img width="571" height="455" alt="heating_analysis" src="https://github.com/user-attachments/assets/0b529ca4-cd4f-4610-936c-1493ef335aa8" />

### Case 02: Land Slope (LandSlope) - 水捌けと地形
**[Investigation / 捜査の目的]**
水捌けの良さがシロアリや湿気対策に重要であるという仮説に基づき、地形の傾斜を調査。

**[Findings / 調査結果]**
- 大半(1382件)は平坦な土地(Gtl)に位置する。
- 意外にも「傾斜(Sev)」の物件の方が平均価格が高い傾向。

**[Insight / 刑事の勘]**
傾斜地の物件は、水捌けのリスクよりも「眺望(View)」という付加価値が勝っている可能性がある。ただし、特定の豪邸による「外れ値」の影響を考慮すべきである。
<img width="876" height="547" alt="slope_analysis" src="https://github.com/user-attachments/assets/f4bc694a-f218-4a20-9d85-7a20e7e26687" />

### Case 03: 屋根の素材 (Roof Material)
**[推理]** ウッドシングル(WdShngl)の屋根を持つ家は、標準的な素材(CompShg)よりも価格が高い傾向にある。屋根の素材は住宅のグレードを判断する重要な指標になりそうだ。
<img width="876" height="590" alt="屋根の分析" src="https://github.com/user-attachments/assets/c46ac433-756e-454b-98df-b9d695979772" />

### Case 04: キッチンの品質に関する捜査報告 (Analysis of Kitchen Quality)
特に WdShngl（木製屋根）の物件は価格が高騰しており、高級住宅の証拠と言える。
**[推理]** キッチンの品質（KitchenQual）は、住宅価格と非常に強い相関があることが判明。グラフが綺麗な階段状になっていることから、この項目は予測モデルにおいて極めて**重要**な「重み」を持つ変数になると推測される。
<img width="876" height="547" alt="kitchen_quality_analysis" src="https://github.com/user-attachments/assets/099601d6-5879-4c8b-be6f-7ef48aa13bd0" />

### Case 05: 暖房の品質 (HeatingQC)
<img width="876" height="547" alt="heating_quality" src="https://github.com/user-attachments/assets/f67672f5-9830-456a-a25b-d803188c196b" />

#### **今回の捜査結果（3つのグラフの比較）**
3つのグラフを並べて見ると、家の価格が決まる「優先順位」が見えてきます。

- **屋根 (RoofMatl)**: 特定の素材（WdShngl）だけが「突き抜けて高い」という、一点豪華主義な特徴があります。
- **キッチン (KitchenQual)**: 非常に綺麗な「右肩下がりの階段」を描いています。キッチンの質は、家の価格をダイレクトに左右する「最強の指標」の一つと言えます。
- **暖房 (HeatingQC)**: Ex（最高）のポテンシャルが凄まじいです。特に Ex には上に突き抜けた点（**外れ値**）が多く、暖房にお金をかける家は、他の設備も異次元である可能性を示唆しています。

**まとめ**(Roof)**: 木製屋根は高級住宅の象徴。
- **Case 04 (Kitchen)**: 品質が価格に直結。最も信頼できる指標。
- **Case 05 (Heating)**: 基本性能の高さが、高価格帯の絶対条件。
---
## The Ames Housing Mystery: データが語る「アメリカンドリームの格差」
【はじめに：これは単なる価格予測ではない】
この分析は、アイオワ州エイムズの住宅データ（Kaggle House Prices）を、単なる数値としてではなく、**「社会の鏡」**として読み解いた記録である。 住宅の価格は、面積や築年数だけで決まるのか？——いや、データはその背後にある「階級の分断」や「歴史的な政策の痕跡」を冷酷に映し出していた。
【捜査の軌跡：必死に追いかけた「真犯人」】
データ分析の過程で、私たちは以下のような「真犯人」たちを立件した：
* The Big Shot (Elite): 50万ドルを超える高額物件。車庫3台、プール、そして2000年代以降の圧倒的な品質評価。彼らはインフレをも跳ね除ける「別世界の資産」である。
* The Vanishing (Bottom): 4万ドルを下回る、消えゆく家々。中間層の崩壊とともに、地図から消えようとしている社会の傷跡。
* The Polarized Gap: 1950年以前の家と、2000年以降の家の間で広がる決定的な価格差。住宅はもはや「住む場所」ではなく「持つ者の資産」へと変貌している。
【技術的アプローチ：なぜこの特徴量を選んだのか】
* HeatingQC & KitchenQual: これらは単なる設備ではない。過酷な気候（冬の寒さ）を耐え抜くための「生存性能」であり、富裕層が何に金をかけるかの指標である。
* TotalSF (GrLivArea + TotalBsmtSF): 物理的な広さだけでなく、ガレージなどの「現代の三種の神器」を組み合わせることで、モデルの予測精度を劇的に向上させた。
【結論：AIが見た2025年の風景】
分析の結果、住宅市場における中間層の消失と二極化が浮き彫りになった。このコードは、単に価格を予測するものではなく、データを通じて「社会がどう変化しているか」を可視化するためのものである。


### 私の性格と特徴メモ
* 感情がエンジン: 感情が動かないことや、興味が持てないことは、どうしても覚えられない。逆に、深く心に刺さったことは、驚くほどの集中力を発揮して深く突き詰めることができる。
* 「普通」の枠組みが苦手: 世の中の「効率重視」や「機械的な対応」を強要されると、自分のルート（思考の流れ）がイレギュラーで詰まってしまい、パニックになってしまう。
* 限界を超えて全力投球: 目の前のことに100%で向き合ってしまうから、イレギュラーが重なるとすぐにパンクして、涙が出てしまうほど心身に負担がかかる。
* 「外部脳」が必要: 自分の頭の中だけで整理しようとするとパンクするので、Geminiのようなツールを「もう一つの脳」として使い、情報を整理・記録することで力を発揮できる。
* 深い洞察力: 理屈だけでは見えない「データの裏側にある物語や格差」を、感情を通して鋭く見抜く力がある。


「私は、マニュアル通りに淡々と進めることよりも、『なぜそれをするのか』という意味や物語を理解したときに、一番力を発揮するタイプなんです。イレギュラーが重なるとパニックになりやすいので、手順を一つずつ確認しながら、納得して進めさせてくれると助かります。」


あなたがパニックになったとき、背中をさすって『大丈夫、マニュアル通りに一つずつやろう』と言ってくれる仕組みがある場所

私は、このメモを読んだ上で、『うちならあなたの才能を100%活かせる環境を整えられる』と即答してくれる会社にしか行きません

"This README was drafted with the help of an AI assistant to articulate my thoughts and work style clearly."

### 🔍 Keywords for Global Search
`Kaggle` `Data Science` `Machine Learning` `House Prices` `Python` `Data Analysis` `Detective Intuition`
