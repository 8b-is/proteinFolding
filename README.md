# proteinFolding — the sovereign protein lane

> Fold structures, design binders, on hardware you **own**. The evolution of
> [`protein-q-fold-bind`](https://github.com/8b-is/protein-q-fold-bind) from a
> Modal-hosted surface toward a **sovereign** one: same science, no cloud tax,
> data never leaves the room.
>
> `8b.is · the constellation · 2026.10.08`

## why this repo exists

`protein-q-fold-bind` proved the science: **Boltz-2** folds, **ESMFold2/ESMC**
designs, `Gradio + Molstar` shows it — all live, all working. But it runs on
**Modal** (someone else's cloud). That is fine for research and wrong for the
people who need it most: regulated labs and pharma businesses, where sending a
target or a sequence off-site is a legal and trust wall.

This lane is the next step: **the same folding and design, on owned silicon.**

| | `protein-q-fold-bind` (today) | `proteinFolding` (this lane) |
|---|---|---|
| compute | Modal (cloud) | **owned GPU box** |
| data | leaves the building | **never leaves the room** |
| cost | per-run cloud | **capital, not rent** |
| for | research | **regulated labs, pharma, pilots** |

## what it is

- **fold** — run Boltz-2-class structure prediction locally (sequence → structure, Molstar view).
- **bind** — design binders with ESMFold2/ESMC-class models on a local box.
- **own it** — the box is yours; the pipeline is portable; walking away keeps everything.

## the shelf it sits on

- [`protein-q-fold-bind`](https://github.com/8b-is/protein-q-fold-bind) — the proven fold/design surface (Modal).
- [`qbit-protein-studio`](https://github.com/8b-is/qbit-protein-studio) — the studio lane.
- [`kompress-ultra`](https://github.com/peterlodri-sec/kompress-ultra) — context compression (keeps the expensive context small).
- [`knowledge-worker`](https://github.com/rahulmranga/knowledge-worker) — private, provenance-backed memory: *which target, which run, which model, why.*
- [`project-zero`](https://github.com/shifulegend/project-zero) — the sovereign inference engine.

## the bridge — Nate (standardgalactic) and the clinic

This lane is built **with** [`standardgalactic`](https://github.com/standardgalactic)
(Nate), already a member of the protein lane. His
[`biomechanical_DLIR`](https://github.com/standardgalactic/biomechanical_DLIR)
is the clinical sibling: physically-constrained deformable registration for
medical imaging — *the same sovereignty question, applied to anatomy instead of
molecules.* Folding and registration are two faces of one platform: **model the
structure, own the compute, keep the data.**

## the pilot it powers

The [`sovereign-pilot`](https://pilot.vaked.dev) proposal offers a private
4–6 week pharma pilot: **one owned GPU box, one open protein model, one dataset
that never leaves the room.** This repo is the machinery behind that promise —
the fold/design lane, running sovereign.

## status & honesty

- **proven:** fold + design work today (`protein-q-fold-bind`).
- **in progress:** the sovereign port — folding/design models on owned silicon.
- **honest:** open protein models do not replace lab validation; results on any
  target are not guaranteed. This lane measures whether owned compute meaningfully
  helps real work, cheaply and privately.

## the line

```
∅R ⟶ᴸ R₁ ⟶ᴸ R₂ ⟶ᴸ ⋯ ⟶ᴸ Rₙ ⟶ᴸ ⌂
│ μ(Rᵢ, you) ≠ 0 ∀i ∴ μ(⌂, you) ≠ 0
```

For Rahul, my brother — and for his father. <3
