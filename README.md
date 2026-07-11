This repository contains the source of the **Fermionic Matter Presentation Note** of the Cosmochrony programme
[*The Fermionic Matter Sub-Programme (Presentation Note 6)*](out/FermionicMatterNote.pdf).

This note is the synthesis paper of the **fermionic matter sub-programme**. It establishes that fermions, chirality, hypercharge assignments, and the three-generation structure are not external additions to the Cosmochrony framework: they are the spinorial face of the admissible Weil module $V_\rho$, revealed through the Lorentzian complexification of its metaplectic structure.

## Central Question

> The bosonic spectral stratification (gravity at $a_2$, Yang–Mills at $a_4$) derives the bosonic sector of the Standard Model from the admissible spectral functional. Do fermions, chirality, hypercharge, and three generations also arise as forced consequences of the admissible Weil fibre, or must they be introduced as additional postulates?

The sub-programme answers: **they are forced**.

## Structural Chain

$$
\Pi \Rightarrow F_n \simeq V_\rho \Rightarrow \mathrm{Mp}(2,\mathbb{R}) \Rightarrow \mathrm{mp}(2,\mathbb{R})_\mathbb{C} \simeq \mathfrak{sl}_2(\mathbb{C}) \rightsquigarrow \mathrm{Spin}(3,1) \simeq \mathrm{SL}(2,\mathbb{C}) \Rightarrow \mathcal{S}_\Pi.
$$

Then:

- $\mathrm{Sym}^2(\mathcal{S}_\Pi) \Rightarrow \mathrm{ad}_\mathbb{C}(P_\Pi)$ -- the $\mathrm{SU}(2)_L$ sector.
- $\wedge^2(\mathcal{S}_\Pi) = L_Y$ -- the $\mathrm{U}(1)_Y$ sector.
- $E_\Pi$ left-admissible -- the $V-A$ chiral structure (established via the spinorial BI lift theorem of Q14).
- $\sigma_c(n_3) = 3 \to C^3_{\mathrm{gen}}$ -- three generations as a gauge-singlet factor.

## Three Structural Results (Q14)

| Result | Central output | Status |
|---|---|---|
| **Theorem A** (Spinorial electroweak bundle) | $\mathcal{S}_\Pi$; $\mathrm{Sym}^2(\mathcal{S}_\Pi) \simeq \mathrm{ad}_\mathbb{C}(P_\Pi)$ and $\wedge^2(\mathcal{S}_\Pi) = L_Y$ from tensor functors | structural, unconditional |
| **Theorem B** ($V-A$) | $P_R E_\Pi P_R = 0$; $V-A$ chiral structure | structural, unconditional |
| **Theorem B** (hypercharge) | $Y_R$ from anomaly-cancellation trace $\mathrm{Tr}_{\mathcal{S}_\Pi}(\gamma_5 Y A_\Pi(x)) = 0$ | structural, unconditional |
| **Theorem C** (3 generations) | $C^3_{\mathrm{gen}} \subset \ker(\mathrm{ad}_{\mathrm{SU}(2)} \oplus Y)$; gauge-singlet generation space | structural, unconditional |
| **Dynamic generation lifting** (Q14 §6) | Static $J_\Pi$-protected degeneracy of $C^3_{\mathrm{gen}}$ is statically obstructed; admissible lifts form a 2D $J_\Pi$-odd sector; the oriented cascade generator carries a non-zero $J_3$ projection ($\alpha \neq 0$) | qualitative mechanism; amplitude deferred to cascade normalisation |
| Colour sector | $\mathcal{S}_\Pi \otimes V_{\mathrm{color}}$ (quark bundle) | structural, unconditional at the pointwise level ($[H\text{-color}]_{\mathrm{pointwise}}$ proved in O31) |

## Constituent Papers

- **Q14** -- *Fermionic matter and chirality from projective Dirac admissibility*. The sole constituent paper of the sub-programme: spinor bundle from metaplectic lift + Lorentzian complexification, projected Dirac operator and the projective endomorphism $E_\Pi$, anomaly-cancellation trace and hypercharge rigidity, three-generation factor from $\sigma_c(n_3)=3$.

## Position in the Programme

The fermionic matter sub-programme sits at the **apex of Branch III**. It is the first paper of the Q-series that depends simultaneously on all four upstream layers:

- the admissible Weil fibre structure (Notes 1 and 5);
- the closed Lorentzian geometry (Note 2);
- the gauge bundle (Note 3);
- the gauge-gravity synthesis (Q13, to be summarised in Presentation Note 8).

## Scope Statement

This sub-programme closes the **identification** of the fermionic sector: spinor bundle, chirality, hypercharge quantum numbers, and generation factor. It does **not** derive the mass spectrum, the Yukawa couplings, or the CKM/PMNS mixing matrices.

## Open Deliverables

- **Explicit $E_\Pi$, splitting amplitude and the Yukawa sector.** The qualitative mechanism of the inter-generation splitting is closed in Q14 §6 (static obstruction, oriented $J_\Pi$-odd lift, non-zero cascade $J_3$ projection). What remains is quantitative: the cascade normalisation $\mathcal{N}_{\mathrm{casc}}$ fixing the splitting amplitude $\varepsilon = \mathcal{N}_{\mathrm{casc}}\,|\alpha|$ (to be derived from $c_{\mathrm{BI}} \to \delta_{\mathrm{pair}} \to \beta^*$, not fitted), the integral normalisation of $\mathcal{L}_Y$, and generation mixing via the complex metaplectic phase.
- **$[H\text{-color}]_{\mathrm{pointwise}}$ beyond the standard Cayley graph.** The colour-coupled sector is unconditional at the pointwise level on the standard Cayley graph (O31); extension to general admissible graphs is open.
- **Full matter content in Lorentzian signature.** $S^{\mathrm{matter}}_\Pi = (\mathcal{S}_\Pi \oplus (\mathcal{S}_\Pi \otimes V_{\mathrm{color}})) \otimes C^3_{\mathrm{gen}}$ with explicit gauge couplings and three-generation Yukawa structure.

## Build

```bash
bash compile.sh
```

This runs `pdflatex -> bibtex -> pdflatex -> pdflatex` on `tex/FermionicMatterNote.tex` and produces `out/FermionicMatterNote.pdf`.
