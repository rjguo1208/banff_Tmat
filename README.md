# banff_Tmat — Explicit Electron–Defect T-matrix (MoS₂ S-vacancy)

**Live site:** https://rjguo1208.github.io/banff_Tmat/

Explicit (no-Sternheimer) electron–defect *T*-matrix spectral function for the
MoS₂ sulfur vacancy: all matrix elements ⟨ψ_nk|ΔV|ψ_mk'⟩ from **EDI direct-mode**,
full-order rest-space downfolding by a direct 8496×8496 inverse, active-space
resummation T_PP=[1−Ṽ G^A]⁻¹Ṽ, validated against direct supercell DFT
diagonalization. Computed on **Banff** (UT Austin) with a from-source QE 7.5 + EDI.

The published payload is `docs/` (GitHub Pages, `main`/`docs`). Raw data — the
16 GB matrix-element files, cube potentials, and QE `*.save/` — are **not** committed.

Companion to the Sternheimer downfolding site:
https://rjguo1208.github.io/claude-sternheimer/
