This repository contains the source of the **Fermionic Matter Presentation Note** of the Cosmochrony programme
*The Fermionic Matter Sub-Programme (Presentation Note 6)*.

This note is the synthesis paper of the **fermionic matter sub-programme**. It shows that fermions, chirality and the three-generation structure need not be added to the Cosmochrony framework as external fields, once a Heisenberg carrier is supplied: on that carrier they are the spinorial face of the Weil module $V_\rho$, revealed through the Lorentzian complexification of its metaplectic structure. The carrier is supplied rather than selected by the admissibility axioms, and every result below inherits that condition.

## Central Question

> The bosonic spectral stratification (gravity at $a_2$, Yang–Mills at $a_4$) derives the bosonic sector of the Standard Model from the admissible spectral functional. Do fermions, chirality, hypercharge, and three generations also arise as forced consequences of the admissible Weil fibre, or must they be introduced as additional postulates?

The sub-programme answers: **stratified, and conditional**. On a supplied Heisenberg carrier, spinoriality and the $V-A$ chiral selection follow with no further hypothesis. The rigidity of the hypercharge weights carries in addition a supplied three-dimensional colour module; selecting the Standard Model pattern among them carries, beyond that module, the minimal integral normalisation of the determinant line $L_Y$, holds only up to an overall sign and rescaling, and rests on a connection Q14 leaves open. The generation factor carries a supplied rank-three carrier.

## Structural Chain

Read on the supplied Heisenberg carrier, not derived from the axioms: the admissibility axioms force irreducibility and non-commutation, but neither make the commutator central nor select a finite Heisenberg group (an explicit $\mathfrak{S}_3$ countermodel satisfies the extracted carrier contract).

$$
\Pi \Rightarrow F_n \simeq V_\rho \Rightarrow \mathrm{Mp}(2,\mathbb{R}) \Rightarrow \mathrm{mp}(2,\mathbb{R})_\mathbb{C} \simeq \mathfrak{sl}_2(\mathbb{C}) \rightsquigarrow \mathrm{Spin}(3,1) \simeq \mathrm{SL}(2,\mathbb{C}) \Rightarrow \mathcal{S}_\Pi.
$$

Then:

- $\mathrm{Sym}^2(\mathcal{S}_\Pi) \Rightarrow \mathrm{ad}_\mathbb{C}(P_\Pi)$ -- the $\mathrm{SU}(2)_L$ sector.
- $\wedge^2(\mathcal{S}_\Pi) = L_Y$ -- the $\mathrm{U}(1)_Y$ sector.
- $E_\Pi$ left-admissible -- the $V-A$ chiral structure (established via the spinorial BI lift theorem of Q14).
- $\sigma_c(n_3) = 3 \to C^3_{\mathrm{gen}}$ -- three generations as a gauge-singlet factor,
  conditional on the supplied rank-three selection rule of O23 (Theorem 3.1 proves the
  three-dimensionality of the neutral sector of a supplied spinor carrier; carrier selection
  and observable identification are open).

## Three Structural Results (Q14)

| Result | Central output | Status |
|---|---|---|
| **Theorem A** (Spinorial electroweak bundle) | $\mathcal{S}_\Pi$; $\mathrm{Sym}^2(\mathcal{S}_\Pi) \simeq \mathrm{ad}_\mathbb{C}(P_\Pi)$ and $\wedge^2(\mathcal{S}_\Pi) = L_Y$ from tensor functors | structural; no hypothesis beyond the supplied carrier |
| **Theorem B** ($V-A$) | $P_R E_\Pi P_R = 0$; $V-A$ chiral structure | structural; no hypothesis beyond the supplied carrier |
| **Theorem B** (weight rigidity) | $Y_R$ constrained by the anomaly-cancellation trace $\mathrm{Tr}_{\mathcal{S}_\Pi}(\gamma_5 Y A_\Pi(x)) = 0$ | structural; conditional on a supplied three-dimensional colour module |
| **Theorem B** (Standard Model pattern) | that pattern selected among the allowed weights, up to an overall sign and rescaling; the cubic constraint vanishes on it at colour multiplicity three | structural; conditional on the same module **and** on the minimal integral normalisation of $L_Y$, whose connection to the pattern Q14 lists as an open direction |
| **Theorem C** (3 generations) | $C^3_{\mathrm{gen}} \subset \ker(\mathrm{ad}_{\mathrm{SU}(2)} \oplus Y)$; gauge-singlet generation space | structural, conditional on the supplied rank-three carrier (O23) |
| **Dynamic generation lifting** (Q14 §6) | Static $J_\Pi$-protected degeneracy of $C^3_{\mathrm{gen}}$ is statically obstructed; admissible lifts form a 2D $J_\Pi$-odd sector; the oriented cascade generator carries a non-zero $J_3$ projection ($\alpha \neq 0$) | qualitative mechanism; amplitude deferred to cascade normalisation |
| Colour sector | $\mathcal{S}_\Pi \otimes V_{\mathrm{color}}$ (quark bundle) | structural; conditional on the same supplied colour module. O31 is a withdrawal notice: $[H\text{-color}]_{\mathrm{pointwise}}$, the uniqueness of $\mathrm{SU}(3)$ and every derivation of a gauge factor are withdrawn |

## Constituent Papers

- **Q14** -- *Fermionic matter and chirality from projective Dirac admissibility*. The sole constituent paper of the sub-programme: spinor bundle from metaplectic lift + Lorentzian complexification, projected Dirac operator and the projective endomorphism $E_\Pi$, anomaly-cancellation trace constraining the hypercharge weights, Standard Model pattern selection under the minimal integral normalisation of $L_Y$, three-generation factor from $\sigma_c(n_3)=3$.

## Position in the Programme

The fermionic matter sub-programme sits at the **apex of Branch III**. It is the first paper of the Q-series that depends simultaneously on all four upstream layers:

- the admissible Weil fibre structure on the supplied carrier (Notes 1 and 5);
- the closed Lorentzian geometry (Note 2);
- the gauge bundle for a supplied compact structure group (Note 3), which singles out no particular group;
- the conditional gauge-gravity system (Q13, summarised in Presentation Note 8).

## Scope Statement

This sub-programme addresses the **identification** of the fermionic sector: spinor bundle, chirality, hypercharge quantum numbers, and generation factor. The spinor bundle and the chiral selection are settled on the supplied Heisenberg carrier; the hypercharge weight rigidity and the generation factor remain conditional on a supplied colour module and a supplied rank-three carrier respectively, and the Standard Model hypercharge pattern carries the further minimal-integral-normalisation premise. It does **not** derive the mass spectrum, the Yukawa couplings, or the CKM/PMNS mixing matrices.

## Open Deliverables

- **Explicit $E_\Pi$, splitting amplitude and the Yukawa sector.** The structural form of $E_\Pi$ is fixed as the Schur complement of the eliminated spinorial block; the open part is its explicit Lorentzian block along the $J_\Pi$-odd modulus. The amplitude mechanism is the derived Born-Infeld saturation, and the split value $|u|$ is dictionary-bound through the chiral-frontier normalisation $\mathcal{N}_A$. Its first-principles front is upstream and structural: the ADE case selection and the level-to-generation map, the projective-resolution growth $\Lambda_{\mathrm{proj}}(n)$ and the cascade exponent $\beta$ (no structural bound on $\beta$ is available), and the transfer constant $N_{\mathrm{casc}}$. The integral normalisation of $\mathcal{L}_Y$ and generation mixing via the complex metaplectic phase remain open.
- **An admissible colour sector.** No colour module is derived, so the quark bundle and the rigidity of the hypercharge weights both rest on a supplied one, and the Standard Model pattern rests on it too. O31 withdraws the co-admissibility of the individual capacity profiles, the uniqueness of $\mathrm{SU}(3)$, the arithmetic criterion for colour triplets, and every derivation of a gauge factor, with no weaker positive statement in their place; the gauge structure sub-programme singles out no particular group either, keeping a structural $\mathrm{U}(1)$ sector and an $\mathrm{SU}(2)$ sector conditional on the supplied spinor carrier, without assembling them into a group. The open problem is the construction of an admissible colour sector itself.
- **Full matter content in Lorentzian signature.** $S^{\mathrm{matter}}_\Pi = (\mathcal{S}_\Pi \oplus (\mathcal{S}_\Pi \otimes V_{\mathrm{color}})) \otimes C^3_{\mathrm{gen}}$ with explicit gauge couplings and three-generation Yukawa structure.

## Build

```bash
bash compile.sh
```

This runs `pdflatex -> bibtex -> pdflatex -> pdflatex -> pdflatex` on `tex/FermionicMatterNote.tex` and produces `out/FermionicMatterNote.pdf`. The fourth LaTeX pass settles the cross-references, so a build from a clean tree ends with no outstanding rerun warning.
