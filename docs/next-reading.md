# 次に読む本：依存型理論・型理論的基礎づけ

L&S（圏論的論理・基礎論）の次に進むための読書ガイド。`foundations-of-math-today.md` で見た「型理論＝基礎」の現代的後継（HoTT/UF・依存型理論）を追うための地図。

> 一冊で全員が認める「決定版」はない。(a) 基礎論、(b) 圏論的意味論、(c) 証明支援系での実践、で標準書が分かれる。L&S の延長としては圏論的意味論・基礎論の軸が相性◯。

---

## 角度別の定番

### 基礎論 / Univalent Foundations（L&S の現代的後継に最も近い）

| 書名 | 著者・年 | メモ |
|---|---|---|
| **《HoTT Book》*Homotopy Type Theory: Univalent Foundations of Mathematics*** | 集団執筆, 2013（無料） | HoTT/UF の事実上の標準リファレンス。「型理論＝基礎」の現代版の本丸 |
| **《Rijke》*Introduction to Homotopy Type Theory*** | E. Rijke, 2022（arXiv/書籍） | HoTT Book より教科書的・体系的。独学/講義向き。いまの「入門の標準」 |

### 型理論そのものをきれいに学ぶ

| 書名 | 著者・年 | メモ |
|---|---|---|
| **《Nederpelt–Geuvers》*Type Theory and Formal Proof: An Introduction*** | 2014 | λキューブ→依存型→PTS まで丁寧。理論を腰を据えて学ぶ決定版候補・読みやすい |
| ***Intuitionistic Type Theory*** | P. Martin-Löf, 1984 | 原典（講義録）。短く古いが一次資料 |
| ***Programming in Martin-Löf's Type Theory*** | Nordström–Petersson–Smith, 1990（無料） | MLTT の古典 |

### 圏論的意味論（L&S の延長として相性◎）

| 書名 | 著者・年 | メモ |
|---|---|---|
| **《Jacobs》*Categorical Logic and Type Theory*** | B. Jacobs, 1999 | 依存型理論の圏論的意味論（fibration / 表示意味論）の重量級リファレンス。L&S の「型理論↔圏」を依存型まで押し進める決定版。難度高 |

### やさしい入門 / 証明支援系で手を動かす

| 書名 | 著者・年 | メモ |
|---|---|---|
| ***The Little Typer*** | Friedman & Christiansen, 2018 | 対話形式で依存型を体感。最もやさしい入口 |
| ***Theorem Proving in Lean 4*** | Avigad et al. | Lean。mathlib の現実を体験 |
| ***Certified Programming with Dependent Types*** (CPDT) | A. Chlipala | Coq。依存型を実装で |

---

## L&S 文脈でのおすすめ順

L&S → 依存型 → 現代基礎論の流れなら：

1. **Rijke** — 型理論＋univalence を体系的に（理論の足場）
2. **HoTT Book** — 参照書として併用（基礎論的主張の本丸）
3. **Jacobs** — 圏論側を深める（L&S の自然な続き）
4. **Lean**（Avigad）— 手を動かして mathlib の現実を体験

> 素直な線：**Rijke → Jacobs**。基礎論なら HoTT Book＋Rijke、圏論的意味論なら Jacobs、理論入門なら Nederpelt–Geuvers、体感なら Little Typer / Lean。
