# 分野の地図：この一連の話題は何の学問か

L&S 読書〜依存型理論〜基礎づけの議論が、どの分野に属するかの見取り図。

> 一語なら **「圏論的論理 (categorical logic)」＋「型理論 (type theory)」**。実際は複数分野の交差点。

---

## 大きな傘

- **数理論理学 (Mathematical Logic)** — 最上位。古典的に4分野（証明論・モデル理論・集合論・再帰理論）。型理論/圏論的論理は主に **証明論 (Proof Theory)** の系譜。
- **数学の基礎論 / 基礎づけ (Foundations of Mathematics)** — 「何を土台に数学を建てるか」（`foundations-of-math-today.md`）。

## 中核（ここまでの主役）

| 分野 | 何を扱うか | 対話での登場 |
|---|---|---|
| **型理論 (Type Theory)** | 型・項・証明の体系 | 𝓛₀、依存型理論、NNO |
| **圏論的論理 (Categorical Logic)** | 論理・型理論を圏論で意味づけ | トポス＝型理論、L&S 全体 |
| **トポス理論 (Topos Theory)** | 「集合の圏の一般化」での論理 | Ω、自由トポス |
| **構成的数学 (Constructive Math)** | 直観主義・証明＝構成 | disjunction/existence property |

## 隣接する橋

- **理論計算機科学 (Theoretical CS) / プログラミング言語理論 (PL theory)** — 型理論＝型システムの理論。Lean/Coq、Curry–Howard（証明＝プログラム）で直結。
- **数学の哲学 (Philosophy of Mathematics)** — 「自由トポスは中立な基礎か」等（読書ノート §6）。

## 全部を束ねる呼び名

```
論理（証明論） ⟷ 型理論 ⟷ 圏論
```

- **Curry–Howard–Lambek 対応** — 三者の同一視（L&S の "Lambek" 部分、読書ノート §1）。
- **computational trinitarianism（計算論的三位一体）** — Bob Harper の造語。「証明論・型理論・圏論は同じ一つのものの三つの顔」。

> まとめ：核＝型理論＋圏論的論理（トポス理論）／傘＝数理論理学・数学の基礎論／橋＝理論計算機科学（PL理論）・数学の哲学。束ねる標語が Curry–Howard–Lambek 対応 / computational trinitarianism。
