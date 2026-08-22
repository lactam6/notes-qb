# 1C_01 fact-check review

## 判定

確定的な誤り: 1件。Questionable / 教科書により揺れる点: 4件。

## DEFINITE ERRORS

| 該当行 | 何が問題か | 正しい記述 | 根拠 |
|---|---|---|---|
| `### 酵素内蔵型(チロシンキナーゼ型) — 成長・増殖・同化` 配下の `- サイトカイン受容体(JAK-STAT系)` | サイトカイン受容体を「酵素内蔵型(チロシンキナーゼ型)」に入れると、受容体自体がチロシンキナーゼ活性を持つように読める。これは不正確。 | サイトカイン受容体は多くが受容体関連型チロシンキナーゼ、特にJAK、を介する。受容体自体には内在性酵素活性がない。インスリン受容体やEGF/FGFなどの成長因子受容体は代表的な受容体型チロシンキナーゼ。 | NCBI Bookshelf, *The Cell: A Molecular Approach*, "Cytokine Receptors and Nonreceptor Protein-Tyrosine Kinases": cytokine receptors lack intrinsic catalytic activity and act with associated nonreceptor tyrosine kinases. https://www.ncbi.nlm.nih.gov/books/NBK9866/ ; NCBI Bookshelf, *Molecular Biology of the Cell*, "Cytokine Receptors Activate the Jak-STAT Signaling Pathway": cytokine receptors are associated with JAKs. https://www.ncbi.nlm.nih.gov/books/NBK26822/ |

## QUESTIONABLE / 教科書により揺れる points

| 該当行 | 評価 | コメント / 試験上の安全な表現 | 根拠 |
|---|---|---|---|
| `- コレステロール: 流動性・透過性を低下させる` | 要修正寄りの曖昧さ | 透過性低下は正しい。流動性は「低下」とだけ覚えると危険。コレステロールは脂質二重層を秩序化して小分子透過性を下げる一方、低温では脂肪酸鎖の結晶化を防ぎ、相転移を抑える。試験用には「膜流動性を調節し、透過性を低下」とするのが安全。 | NCBI Bookshelf, *Molecular Biology of the Cell*, "The Lipid Bilayer": cholesterol enhances barrier properties, decreases mobility near head groups and permeability, but also prevents crystallization/phase transitions at high concentrations. https://www.ncbi.nlm.nih.gov/books/NBK26871/ |
| `- 脂肪酸・エイコサノイド` | 過度に一般化 | PPARなど核内受容体の内因性リガンドとして脂肪酸・一部エイコサノイドは正しい。ただしプロスタグランジン/ロイコトリエンなど多くのエイコサノイド受容体は細胞膜上GPCR。単に「エイコサノイド=核内受容体」と覚えると誤答になりうる。 | PPARの脂肪酸・エイコサノイドリガンド: https://pmc.ncbi.nlm.nih.gov/articles/PMC20719/ ; PPARリガンドの総説: https://pmc.ncbi.nlm.nih.gov/articles/PMC3437919/ |
| `- 高いほど水を引き込む` （晶質浸透圧の項） | 文脈依存で危険 | 血漿浸透圧の計算には尿素/BUNを含めるが、細胞膜を介した水移動を決める「有効浸透圧/張度」では尿素は基本的に無効浸透圧物質。`Na+、グルコース、尿素` の直後にこの文があるため、尿素も持続的な細胞内外水移動を起こすように読める。 | Serum osmolality formula: AMBOSS snippet https://www.amboss.com/us/snippet/Serum_osmolality ; tonicityでは尿素は無効: https://pmc.ncbi.nlm.nih.gov/articles/PMC6161575/ ; osmolalityとtonicityの区別: https://pmc.ncbi.nlm.nih.gov/articles/PMC2784783/ |
| `- グリシン / ...` と `- メチオニン / プロリン / ...` （疎水性分類） | 教科書差あり。ただし現行記述は国試・CBT向けには許容 | グリシンとプロリンは分類が揺れる。Lehninger系ではグリシンは非極性に置くが、側鎖がHのみで疎水性相互作用への寄与は小さいと説明する。日本語の大学系教材ではグリシン・プロリンを疎水性/非極性に含めるものがあり、CBT対策上は現行分類で大きな誤りではない。ただし「Glyは小さく特殊、Proはイミノ酸で屈曲を作る」と補うと安全。 | NCBI Bookshelf, *The Cell*, amino acids: glycine/prolineをnonpolar側鎖に分類。https://www.ncbi.nlm.nih.gov/books/NBK9879/ ; 東京大学Web連携テキスト: 疎水性アミノ酸にGly/Proを含める。https://www.iu.a.u-tokyo.ac.jp/textbook/chapter3.html ; Lehninger 6e資料: glycine is most easily grouped with nonpolar, but small side chain contributes little to hydrophobic interactions. https://studylib.net/doc/27934686/lehninger-principles-of-biochemistry--6th-edition---pdfdr... |

## RECOMMENDED ADDITIONS

| 追加したい点 | 理由 | 根拠 |
|---|---|---|
| SGLT1は小腸刷子縁だけでなく、腎近位尿細管S3部の管腔側にもある。SGLT2は近位尿細管S1/S2部の管腔側が中心。 | SGLT2阻害薬、Fanconi症候群、腎糖再吸収の整理で高頻度。現行の `SGLT1: 小腸の刷子縁` は誤りではないが分布表としては不足。 | Endotext, insulin/glucose transport: SGLT1 in small intestinal epithelium, SGLT2 in renal proximal tubule. https://www.ncbi.nlm.nih.gov/books/NBK279029/ ; renal localization SGLT2 S1/S2, SGLT1 S3: https://pmc.ncbi.nlm.nih.gov/articles/PMC6133168/ |
| GLUT4に心筋を加える。運動でも膜移行が増えることを一言補う。 | GLUT4は骨格筋・心筋・脂肪細胞でインスリン応答性。運動時の骨格筋取り込みはインスリン非依存的にも増えるため、糖尿病・運動療法で高 yield。 | StatPearls, GLUT4: skeletal muscle, adipose tissue, cardiomyocytes; insulin/exerciseで膜移行。https://www.ncbi.nlm.nih.gov/books/NBK537322/ |
| GLUT5: 小腸刷子縁の果糖輸送体を追加。 | GLUT/SGLT表でGLUT5は国試・CBTの周辺知識としてよく問われる。 | PubMed review: GLUT5 is a fructose transporter abundant in apical intestinal cells. https://pubmed.ncbi.nlm.nih.gov/8112322/ |
| 血漿浸透圧と有効浸透圧/張度を分ける: 血漿浸透圧は `2Na + Glu/18 + BUN/2.8`、有効浸透圧は概ね `2Na + Glu/18`。 | 低Na血症、高血糖、尿毒症で誤答を防ぐ。 | https://pmc.ncbi.nlm.nih.gov/articles/PMC2784783/ ; https://pmc.ncbi.nlm.nih.gov/articles/PMC6161575/ |
| 洞房結節4相にIf、T型Ca2+、0相にL型Ca2+を補う。 | 現行記述は正しいが、ペースメーカー電位の機序としてIfとCaチャネルの区別は高 yield。 | StatPearls, cardiac muscle/pacemaker action potential: phase 4 If slow Na+ influx, threshold opens Ca2+ channels for phase 0. https://www.ncbi.nlm.nih.gov/books/NBK572070/ ; https://www.ncbi.nlm.nih.gov/books/NBK537194/ |

## 修正パッチ案

機械的に置換するなら、以下の差し替えが安全。

```diff
- コレステロール: 流動性・透過性を低下させる
+ コレステロール: 膜流動性を調節し、低分子水溶性物質への透過性を低下させる
```

```diff
-### 酵素内蔵型(チロシンキナーゼ型) — 成長・増殖・同化
+### 酵素連結型 — 成長・増殖・同化
 - インスリン受容体
 - 成長因子受容体
- サイトカイン受容体(JAK-STAT系)
+- サイトカイン受容体: 受容体関連JAKを介する(JAK-STAT系)
```

```diff
- 脂肪酸・エイコサノイド
+ 脂肪酸・一部のエイコサノイド(PPARなど)
```

```diff
- GLUT4: 骨格筋、脂肪細胞(インスリン依存で膜へ移行)
+ GLUT4: 骨格筋、心筋、脂肪細胞(インスリン依存で膜へ移行。骨格筋では運動でも移行)
+- GLUT5: 小腸刷子縁(果糖輸送)
```

```diff
- SGLT1: 小腸の刷子縁
- SGLT2: 腎近位尿細管
+ SGLT1: 小腸刷子縁、腎近位尿細管S3部管腔側
+ SGLT2: 腎近位尿細管S1/S2部管腔側
```

```diff
 - Na+、グルコース、尿素で規定される
- 高いほど水を引き込む
+- 血漿浸透圧はNa+、グルコース、尿素で規定される
+- 有効浸透圧/張度は主にNa+とグルコースで規定される(尿素は細胞膜を通過しやすく無効浸透圧物質)
 - 計算式: 2 × Na(mEq/L) + 血糖(mg/dL)/18 + BUN(mg/dL)/2.8
   - 例: 2×140 + 100/18 + 14/2.8 ≒ 290 mOsm/L
   - K を加える式(2×(Na+K)+…)を使う教科書もある
```

```diff
- 洞房結節: 静止電位が不安定。4相で緩徐脱分極し、0相はCa²⁺チャネルによる
+ 洞房結節: 静止電位が不安定。4相でIfなどにより緩徐脱分極し、0相は主にL型Ca²⁺チャネルによる
```
