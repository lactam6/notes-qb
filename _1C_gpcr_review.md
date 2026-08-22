# 1C GPCR・細胞間情報伝達レビュー

## 判定

- TARGET A (`1C_01.md` の指定2 subsectionのみ): DEFINITE ERRORS 0件、QUESTIONABLE / 教科書により揺れる点 4件。
  - G蛋白割り当ては、試験用の典型分類としては全体に妥当。
  - 5-HT3がセロトニン受容体で唯一のイオンチャネル型である点、V1=Gq、V2=Gs、AT1=主にGqは確認済み。
- TARGET B (`1C_02.md` 全体): DEFINITE ERRORS 0件、QUESTIONABLE / 教科書により揺れる点 4件、RECOMMENDED ADDITIONS 2件。
  - インスリンS-S結合、バソプレシン/オキシトシンの環状ノナペプチド、RLR/NLR、NO-sGC-cGMP-PKG、PDEの記載は修正不要。
  - Type I核内受容体からエストロゲン受容体を外している点は、CBT向け分類として妥当。

## DEFINITE ERRORS

なし。

## QUESTIONABLE / 教科書により揺れる points

### TARGET A: `1C_01.md`

1. Exact line:
   `- ニコチン性アセチルコリン受容体: Na+流入`

   問題点:
   試験用の脱分極機序としては許容されるが、厳密にはnAChRは非選択性陽イオンチャネルで、Na+流入だけでなくK+流出、一部Ca2+透過もある。特に神経型nAChRではCa2+透過性が意味を持つ。

   正しい記載:
   `ニコチン性ACh受容体: 非選択性陽イオンチャネル。主にNa+流入で脱分極(K+流出、一部Ca2+透過もある)。`

   根拠:
   NCBI Bookshelf, *Neuroscience*「Cholinergic Receptors」はnAChRを非選択性陽イオンチャネルと説明。NCBI Bookshelf, *Molecular Biology of the Cell* も通常電流は主にNa+とK+、一部Ca2+と説明。

2. Exact line:
   `- NMDA型受容体: Ca²⁺流入`

   問題点:
   NMDA受容体の高Ca2+透過性を覚える目的なら許容されるが、単独行だと「Ca2+選択性チャネル」「リガンドだけで常に開く」と誤読されうる。実際は非選択性陽イオンチャネルで、Na+/K+も通し、グルタミン酸に加えてグリシンまたはD-セリンが必要で、静止膜電位ではMg2+ブロックを受ける。

   正しい記載:
   `NMDA型受容体: 非選択性陽イオンチャネル(Ca2+透過性が高い; グルタミン酸+グリシン/D-セリン、脱分極によるMg2+ブロック解除が必要)。`

   根拠:
   NCBI Bookshelf, *Neuroscience*「Glutamate Receptors」はNMDA/AMPA/kainateを非選択性陽イオンチャネルとし、NMDAはCa2+透過、グリシン共作動薬、Mg2+電位依存性ブロックを持つと説明。IUPHARもNMDA受容体はグルタミン酸とグリシン結合を要し、Ca2+透過性とMg2+ブロックを持つと記載。

3. Exact lines:
   `- GABA_A受容体: 脳`
   `- グリシン受容体: 脊髄`

   問題点:
   「GABA_A=脳、グリシン=脊髄」は国試・CBTの大づかみとしてはよく使われるが、断定すると過剰。GABAは脳の主要抑制性伝達物質で脊髄にも存在し、グリシンは脊髄・脳幹で代表的だが脳にも受容体分布がある。

   正しい記載:
   `GABA_A受容体: 脳を中心にCNS全般(脊髄にも存在)`
   `グリシン受容体: 脊髄・脳幹で代表的(脳にも存在)`

   根拠:
   NCBI Bookshelf, *Neuroscience*「GABA and Glycine」はGABAを脳の主要な抑制性伝達、グリシンを脊髄でより局在する抑制性伝達として説明。StatPearls「Ligand Gated Chloride Channel」も成人脊髄ではグリシンが優位な抑制性シグナルと説明。

4. Exact line:
   `- TSH・ACTH・LH/FSH・PTH受容体`

   問題点:
   Gsの例としてPTHを置くのはCBTレベルでは許容される。ただしPTH1RはIUPHAR上、GsとGqの両方に共役するため、受容体分類の精度を上げるなら補足した方がよい。

   正しい記載:
   `TSH・ACTH・LH/FSH受容体`
   `PTH1受容体: 主にGs(cAMP/PKA); Gq/PLCにも共役`

   根拠:
   IUPHAR/BPS Guide to Pharmacology「Parathyroid hormone receptors」はPTH1RがGsおよびGqに共役すると記載。

### TARGET B: `1C_02.md`

1. Exact lines:
   `- μ受容体: β-エンドルフィン、メチオニンエンケファリン`
   `- δ受容体: ロイシンエンケファリン`
   `- κ受容体: ダイノルフィン`

   問題点:
   「μ=エンドルフィン、δ=エンケファリン、κ=ダイノルフィン」という試験用対応なら概ねよいが、Met/Leuエンケファリンをμ/δに排他的に割り振るのは不正確。IUPHARではμの主要内因性作動薬にβ-endorphin、Met-enkephalin、Leu-enkephalinが入り、δにもβ-endorphin、Leu-enkephalin、Met-enkephalinが入る。κはdynorphin A/B、big dynorphinが代表。

   正しい記載:
   `μ受容体: β-エンドルフィン、エンドモルフィン、エンケファリン(非選択的)`
   `δ受容体: エンケファリン(Met/Leu)、β-エンドルフィン(非選択的)`
   `κ受容体: ダイノルフィンA/B、big dynorphin`

   根拠:
   IUPHAR/BPS Guide to Pharmacology「Opioid receptors」、IUPHAR Review 9、Goodman & Gilman's Manual の内因性オピオイド表。

2. Exact line:
   `- H1: 血管内皮、平滑筋、副腎髄質、神経細胞`

   問題点:
   副腎髄質クロム親和性細胞のH1作用は実験的には支持されるが、CBT/国試の「H1分布」としては中心的でない。代表分布として列挙すると、血管内皮・気管支/消化管平滑筋・感覚神経・CNSを優先した方が安全。

   正しい記載:
   `H1: 血管内皮、気管支・消化管などの平滑筋、感覚神経、CNS`

   根拠:
   StatPearls「Biochemistry, Histamine」はH1を神経、気道・血管平滑筋、内皮に広く発現し、アレルギー症状・血管透過性亢進・気管支収縮に関与と説明。副腎髄質H1作用は PubMed PMID:3342078、PMID:7509435 で支持されるが、標準的な試験用代表分布ではない。

3. Exact line:
   `- H2: 胃壁細胞、心臓、神経細胞`

   問題点:
   誤りではないが、直下に「気道・血管平滑筋の弛緩」「免疫細胞への作用」を置くなら、H2分布にも血管平滑筋・免疫細胞を含めた方が対応が明確。気道平滑筋弛緩は文献上支持されるが、臨床・試験上はH1による気管支収縮の方がはるかに高頻度。

   正しい記載:
   `H2: 胃壁細胞、心臓、血管平滑筋、免疫細胞、神経細胞`

   根拠:
   IUPHAR/BPS Guide to Pharmacology「Histamine receptors」はH2をGs共役、局在は主に胃・心臓・CNSとし、H2 receptor pageでは胃酸分泌、血管平滑筋H2による内皮非依存性血管拡張、免疫細胞作用を記載。StatPearls「Biochemistry, Histamine」もH2を胃壁細胞、平滑筋、心臓に記載。

4. Exact line:
   `- ソマトスタチン: 膵島δ細胞と視床下部から分泌`

   問題点:
   記載自体は正しいが、主要産生部位として消化管D細胞が抜けている。体内ソマトスタチンの大きなプールは消化管D細胞で、CBT/国試でも胃酸・消化管ホルモン抑制と結びつく。

   正しい記載:
   `ソマトスタチン: 膵島δ細胞、視床下部、消化管D細胞から分泌`

   根拠:
   StatPearls「Physiology, Somatostatin」はソマトスタチン産生部位をGI tract、膵、視床下部、CNSとし、消化管D細胞が体内ソマトスタチンの大きな割合を占めると説明。NCBI MeSH「Somatostatin-Secreting Cells」も消化管と膵島のD細胞を記載。

## RECOMMENDED ADDITIONS

1. `1C_02.md` アドレナリンβ1受容体:
   β1は心臓だけでなく腎傍糸球体細胞でレニン分泌を促進する点が高頻度。現行行は誤りではないが、国試薬理・生理では追加推奨。

2. `1C_01.md` GPCR:
   セロトニン受容体を出すなら、5-HT1=Gi、5-HT2=Gq、5-HT4/6/7=Gs、5-HT3=イオンチャネル、という対応は高頻度。現行の5-HT4と5-HT3だけでも誤りではないが、受容体分類の表としては追加価値が高い。

## 修正パッチ案

### `1C_01.md`

```diff
-  - ニコチン性アセチルコリン受容体: Na+流入
+  - ニコチン性アセチルコリン受容体: 非選択性陽イオンチャネル(主にNa+流入で脱分極。K+流出、一部Ca2+透過もある)

-    - NMDA型受容体: Ca²⁺流入
+    - NMDA型受容体: 非選択性陽イオンチャネル(Ca2+透過性が高い。グルタミン酸+グリシン/D-セリン、脱分極によるMg2+ブロック解除が必要)

-  - GABA_A受容体: 脳
-  - グリシン受容体: 脊髄
+  - GABA_A受容体: 脳を中心にCNS全般(脊髄にも存在)
+  - グリシン受容体: 脊髄・脳幹で代表的(脳にも存在)

-  - セロトニン5-HT4受容体
+  - セロトニン5-HT4・5-HT6・5-HT7受容体

-  - TSH・ACTH・LH/FSH・PTH受容体
+  - TSH・ACTH・LH/FSH受容体
+  - PTH1受容体: 主にGs(cAMP/PKA)。Gq/PLCにも共役

 - Gi: ACを抑制 → cAMP減少
+  - セロトニン5-HT1受容体

 - Gq: ホスホリパーゼC(PLC)を活性化 → PIP2をIP3とDAGに分解
+  - セロトニン5-HT2受容体
```

### `1C_02.md`

```diff
- - β1: 心臓(洞房結節・心筋)。心拍数と収縮力の増加
+ - β1: 心臓(洞房結節・心筋)、腎傍糸球体細胞。心拍数・収縮力の増加、レニン分泌促進

- - H1: 血管内皮、平滑筋、副腎髄質、神経細胞
+ - H1: 血管内皮、気管支・消化管などの平滑筋、感覚神経、CNS

- - H2: 胃壁細胞、心臓、神経細胞
+ - H2: 胃壁細胞、心臓、血管平滑筋、免疫細胞、神経細胞

- - μ受容体: β-エンドルフィン、メチオニンエンケファリン
- - δ受容体: ロイシンエンケファリン
- - κ受容体: ダイノルフィン
+ - μ受容体: β-エンドルフィン、エンドモルフィン、エンケファリン(非選択的)
+ - δ受容体: エンケファリン(Met/Leu)、β-エンドルフィン(非選択的)
+ - κ受容体: ダイノルフィンA/B、big dynorphin

- - ソマトスタチン: 膵島δ細胞と視床下部から分泌
+ - ソマトスタチン: 膵島δ細胞、視床下部、消化管D細胞から分泌
```

## 使用した主な情報源

- IUPHAR/BPS Guide to Pharmacology: Parathyroid hormone receptors. https://www.guidetopharmacology.org/GRAC/FamilyDisplayForward?familyId=53
- IUPHAR/BPS Guide to Pharmacology: Vasopressin and oxytocin receptors. https://www.guidetopharmacology.org/GRAC/FamilyDisplayForward?familyId=66
- IUPHAR/BPS Guide to Pharmacology: Angiotensin AT1 receptor. https://www.guidetopharmacology.org/GRAC/ObjectDisplayForward?objectId=34
- IUPHAR/BPS Guide to Pharmacology: H1 receptor. https://www.guidetopharmacology.org/GRAC/ObjectDisplayForward?familyType=GPCR&objectId=262
- IUPHAR/BPS Guide to Pharmacology: H2 receptor. https://www.guidetopharmacology.org/GRAC/ObjectDisplayForward?objectId=263
- IUPHAR/BPS Guide to Pharmacology: Opioid receptors. https://www.guidetopharmacology.org/GRAC/FamilyDisplayForward?familyId=50
- IUPHAR/BPS Guide to Pharmacology: 5-Hydroxytryptamine receptors. https://www.guidetopharmacology.org/GRAC/FamilyDisplayForward?familyId=1
- NCBI Bookshelf, *Neuroscience*, Cholinergic Receptors. https://www.ncbi.nlm.nih.gov/books/NBK10834/
- NCBI Bookshelf, *Neuroscience*, Glutamate Receptors. https://www.ncbi.nlm.nih.gov/books/NBK10802/
- NCBI Bookshelf, *Neuroscience*, Serotonin Receptors. https://www.ncbi.nlm.nih.gov/books/NBK11124/
- NCBI Bookshelf, *Neuroscience*, GABA and Glycine / GABA and Glycine Receptors. https://www.ncbi.nlm.nih.gov/books/NBK11084/ ; https://www.ncbi.nlm.nih.gov/books/NBK10977/
- NCBI Bookshelf, *Endotext*, The Neurohypophysis: Endocrinology of Vasopressin and Oxytocin. https://www.ncbi.nlm.nih.gov/books/NBK279157/
- NCBI Bookshelf, The Genetic Landscape of Diabetes, Insulin Structure. https://www.ncbi.nlm.nih.gov/books/NBK1671/
- NCBI Bookshelf, *Basic Neurochemistry*, Biochemistry of Steroid and Thyroid Hormone Actions. https://www.ncbi.nlm.nih.gov/books/NBK28144/
- NCBI Bookshelf, *Endocrinology*, Principles of endocrinology. https://www.ncbi.nlm.nih.gov/books/NBK20/
- NCBI Bookshelf, *Basic Neurochemistry*, Guanylyl Cyclase. https://www.ncbi.nlm.nih.gov/books/NBK28167/
- NCBI Bookshelf, Autoimmunity, Innate immune system. https://www.ncbi.nlm.nih.gov/books/NBK459455/
- StatPearls, Biochemistry, Histamine. https://www.ncbi.nlm.nih.gov/books/NBK557790/
- StatPearls, Physiology, Somatostatin. https://www.ncbi.nlm.nih.gov/books/NBK538327/
- PubMed PMID:3342078, PMID:7509435: adrenal medulla/chromaffin cell H1 histamine receptor作用。
- Goodman & Gilman's Manual of Pharmacology and Therapeutics, 2e: endogenous opioid peptide receptor table.
