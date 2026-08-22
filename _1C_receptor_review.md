# 1C_01 受容体分類 focused re-check

対象範囲: `1C_01.md` の `## アミノ酸` 内「リン酸化を受けるアミノ酸(OH基を持つ)」および `## 膜受容体` 内「酵素連結型 — 成長・増殖・同化」のみ。

## 判定

確定的な誤り: 1件。  
Questionable / 教科書により揺れる点: 2件。

## DEFINITE ERRORS

| 該当行 | 何が問題か | 正しい記述 | 根拠 |
|---|---|---|---|
| `- グアニル酸シクラーゼ内蔵型: ANP/BNP受容体(NPR-A、NPR-B)` | NPR-A と NPR-B はどちらも膜型/受容体型グアニル酸シクラーゼである点は正しいが、リガンド対応が不正確。NPR-B を ANP/BNP 受容体として並べると誤り。 | ANP/BNP の主な生理活性受容体は NPR-A(GC-A)。CNP の主な受容体は NPR-B(GC-B)。NPR-C はグアニル酸シクラーゼドメインを欠くクリアランス受容体として補足すると安全。 | NCBI Bookshelf, *Molecular Biology of the Cell*, receptor guanylyl cyclases: https://www.ncbi.nlm.nih.gov/books/NBK26822/ 。医書.jp/生体の科学「ナトリウム利尿ペプチド受容体」: NPR-A/NPR-B は GC ドメインをもち、NPR-C は GC ドメインを欠きクリアランスに関与: https://webview.isho.jp/journal/detail/abs/10.11477/mf.2425901619 。Kuhn, *Natriuretic Peptides*: NPR-A は ANP/BNP の principal receptor、NPR-B は CNP、NPR-C は clearance: https://pmc.ncbi.nlm.nih.gov/articles/PMC4855512/ |

## QUESTIONABLE / 教科書により揺れる points

| 該当行 | 評価 | コメント / 試験上の安全な表現 | 根拠 |
|---|---|---|---|
| `### リン酸化を受けるアミノ酸(OH基を持つ)` 配下の `- セリン・トレオニン: TGF-βファミリーの受容体...` / `- チロシン: EGFR...` | 要修正寄りの曖昧さ | 「受容体キナーゼの代表例」としてなら正しい。ただし、この見出しのままだと「Ser/Thr リン酸化は主に TGF-β 受容体、Tyr リン酸化は RTK」と一般化して読める。実際には細胞内の Ser/Thr リン酸化は PKA、PKC、CaMK、MAPK など下流キナーゼでも広く起こる。 | NCBI Bookshelf, *Molecular Biology of the Cell*, TGF-β family receptors are receptor Ser/Thr kinases: https://www.ncbi.nlm.nih.gov/books/NBK26822/ 。同書 GPCR 章: PKA/PKC/CaM-kinases phosphorylate Ser/Thr targets downstream of second messengers: https://www.ncbi.nlm.nih.gov/books/NBK26912/ |
| `### 酵素連結型 — 成長・増殖・同化` と分類語 `内蔵型` | 用語の揺れ | 内容上は大きな問題なし。ただし CBT/国試向けには、見出しは「酵素連結型受容体」または「酵素共役型受容体」が通じやすく、各サブタイプは「受容体型チロシンキナーゼ」「受容体型セリン/トレオニンキナーゼ」「受容体型グアニル酸シクラーゼ」「受容体型/受容体様チロシンホスファターゼ」とするのが標準的。「内蔵型」は意味は通るが、医学書院系では「酵素活性内蔵型受容体」という上位語として使われることが多く、個々の型には「受容体型」を使うほうが自然。 | 医学書院 UNITAS「酵素活性内蔵型受容体」: 受容体型チロシンキナーゼ、受容体型チロシンホスファターゼ、受容体型セリン/スレオニンキナーゼ、受容体型グアニルシクラーゼ、会合型を列挙: https://imis.igaku-shoin.co.jp/contents/journal/03709531/48/5/2425901257/ 。NCBI Bookshelf, *Molecular Biology of the Cell*, enzyme-linked receptor classes: https://www.ncbi.nlm.nih.gov/books/NBK26822/ |

## RECOMMENDED ADDITIONS

| 追加したい点 | 理由 | 根拠 |
|---|---|---|
| NPR-C を「クリアランス受容体」として 1語補足 | ANP/BNP/CNP の受容体整理で NPR-A/B/C の対比が高 yield。NPR-C は GC 活性をもたない点も誤解防止になる。 | 医書.jp/生体の科学「ナトリウム利尿ペプチド受容体」: https://webview.isho.jp/journal/detail/abs/10.11477/mf.2425901619 |
| リン酸化節に「受容体キナーゼの代表例」と明記 | Ser/Thr リン酸化全体の説明ではなく、受容体キナーゼ分類の補助情報であることを明確にするため。 | NCBI Bookshelf, GPCR 章 summary: PKA/PKC/CaM-kinases が Ser/Thr をリン酸化: https://www.ncbi.nlm.nih.gov/books/NBK26912/ |

## 修正パッチ案

```diff
-### リン酸化を受けるアミノ酸(OH基を持つ)
-- セリン・トレオニン: TGF-βファミリーの受容体(TGF-β受容体、アクチビン受容体、BMP受容体=骨形成タンパク質受容体)
-- チロシン: EGFR(上皮成長因子受容体)、FGFR(線維芽細胞増殖因子受容体)、PDGFR(血小板由来成長因子受容体)、インスリン受容体
+### リン酸化を受けるアミノ酸(OH基を持つ): 受容体キナーゼの代表例
+- セリン・トレオニン: TGF-βファミリーの受容体(TGF-β受容体、アクチビン受容体、BMP受容体=骨形成タンパク質受容体)
+- チロシン: EGFR(上皮成長因子受容体)、FGFR(線維芽細胞増殖因子受容体)、PDGFR(血小板由来成長因子受容体)、インスリン受容体
```

```diff
-- グアニル酸シクラーゼ内蔵型: ANP/BNP受容体(NPR-A、NPR-B)
+- 受容体型グアニル酸シクラーゼ: ANP/BNP受容体(NPR-A/GC-A)、CNP受容体(NPR-B/GC-B)、NPR-Cはクリアランス受容体(GC活性なし)
```

```diff
-- セリン/トレオニンキナーゼ内蔵型: TGF-β受容体、アクチビン受容体、BMP受容体
-- チロシンホスファターゼ内蔵型: CD45
+- 受容体型セリン/トレオニンキナーゼ: TGF-β受容体、アクチビン受容体、BMP受容体
+- 受容体型/受容体様チロシンホスファターゼ: CD45
```

## 照合メモ

標準分類では「セリン/トレオニンキナーゼ会合型/共役型」という哺乳類の主要クラスは確認できなかった。Alberts の分類では「tyrosine-kinase-associated receptors」はあるが、Ser/Thr は「receptor serine/threonine kinases」として扱われ、TGF-β/activin/BMP 受容体は細胞質側 Ser/Thr kinase domain をもつ。したがって、以前あった「セリン/トレオニンキナーゼ会合型」を削除した判断は正しい。

成長ホルモン受容体、プロラクチン受容体、エリスロポエチン受容体、IL-2/IL-3 受容体は、いずれも cytokine receptor superfamily/JAK 関連受容体として扱うのが正しい。受容体自身に内在性キナーゼ活性がある受容体型チロシンキナーゼではない。根拠: NCBI Bookshelf *The Cell*, cytokine receptors lack intrinsic enzymatic activity and include IL-2, erythropoietin, growth hormone: https://www.ncbi.nlm.nih.gov/books/NBK9866/ 。MBoC は cytokine receptors are associated with one or more JAKs とし、EPO receptor は JAK2 associated と記載: https://www.ncbi.nlm.nih.gov/books/NBK26822/ 。GH/PRL は NCBI Bookshelf *Endocrinology* でも JAK/STAT、inherent tyrosine kinase activity なし: https://www.ncbi.nlm.nih.gov/sites/books/NBK27/?report=reader 。

CD45 は代表的な receptor-like protein tyrosine phosphatase として妥当。膜貫通型で細胞質側に phosphatase domains を持つため「内蔵型」は意味としては正しい。ただし教科書語としては「受容体型」または Alberts に寄せて「受容体様」のほうが自然。根拠: MBoC, CD45 is an important example of transmembrane receptorlike tyrosine phosphatases: https://www.ncbi.nlm.nih.gov/books/NBK26822/ 。Immunobiology/NCBI Bookshelf: CD45 is a transmembrane protein tyrosine phosphatase: https://www.ncbi.nlm.nih.gov/books/NBK27130/ 。

ヒスチジンキナーゼ会合型は、二成分制御系として細菌・酵母・植物で重要だが、動物では apparent not used とされる。ヒト生理・CBT/国試の中心事項ではないため、現行の「主に細菌・植物」は許容。より厳密には「細菌・酵母・植物」としてもよい。根拠: MBoC, bacterial chemotaxis/two-component signaling and same type used by yeasts and plants, apparently not by animals: https://www.ncbi.nlm.nih.gov/books/NBK26822/ 。
