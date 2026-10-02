This repository contains the source of the **Fermionic Matter Presentation Note** of the Cosmochrony programme
*The Fermionic Matter Sub-Programme (Presentation Note 6)*.

This note is the synthesis paper of the **fermionic matter sub-programme**. It states what the fermionic sector requires when fermions are sought in the admissible Weil fibre rather than added to the Cosmochrony framework as external fields. On a supplied Heisenberg carrier, given a real metaplectic model and a supplied doublet, the algebra is proved and needs no metric; its Lorentz reading and its electroweak reading are two distinct hypotheses, supplied by no source. The carrier is supplied rather than selected by the admissibility axioms, and every result below inherits that condition.

## Central Question

> The bosonic spectral stratification (gravity at $a_2$, Yang–Mills at $a_4$) derives the bosonic sector of the Standard Model from the admissible spectral functional. Do fermions, chirality, hypercharge, and three generations also arise as forced consequences of the admissible Weil fibre, or must they be introduced as additional postulates?

The sub-programme answers: **stratified, and conditional**. On a supplied Heisenberg carrier and supplied model data, the algebra $\mathrm{mp}(2,\mathbb{R})_\mathbb{C} \simeq \mathfrak{sl}_2(\mathbb{C})$, $\mathrm{Sym}^2 = $ adjoint, $\wedge^2 = $ determinant line, is proved. The Lorentz reading is the hypothesis [H-Spin] (a Lorentzian spin solder); the electroweak reading, including the $V-A$ structure, is the distinct hypothesis [H-Weak] (a rank-two weak factor $E_{\mathrm{weak}}$ with structure group $\mathrm{U}(2)$). Lorentz chirality (left-admissibility of $E_\Pi$) and the weak chiral selection are different statements, and the second is not derived from the first. The rigidity of the hypercharge weights carries in addition a supplied three-dimensional colour module; selecting the Standard Model pattern among them carries, beyond that module, the minimal integral normalisation of the determinant line $L_Y = \wedge^2(E_{\mathrm{weak}})$, holds only up to an overall sign, rescaling and the exchange of $u_R$ and $d_R$, and rests on a connection Q14 leaves open. The generation factor carries a supplied rank-three carrier.

## Structural Chain

Read on the supplied Heisenberg carrier, not derived from the axioms: the admissibility axioms force irreducibility and non-commutation, but neither make the commutator central nor select a finite Heisenberg group (an explicit $\mathfrak{S}_3$ countermodel satisfies the extracted carrier contract).

$$
\Pi \Rightarrow F_n \simeq V_\rho \overset{\text{model}}{\rightsquigarrow} \mathrm{Mp}(2,\mathbb{R}) \Rightarrow \mathrm{mp}(2,\mathbb{R})_\mathbb{C} \simeq \mathfrak{sl}_2(\mathbb{C}) \overset{[\text{H-Spin}]}{\rightsquigarrow} \mathrm{Spin}(3,1) \simeq \mathrm{SL}(2,\mathbb{C}) \Rightarrow \mathcal{S}_\Pi.
$$

The arrow marked [H-Spin] is not an implication. Then:

- $\mathrm{Sym}^2(S_L) \simeq \mathrm{ad}(P_\Pi)$ and $\wedge^2(S_L)$ trivial -- the Lorentz sector, under [H-Spin].
- $\mathrm{Sym}^2(E_{\mathrm{weak}}) \supset \mathrm{ad}_\mathbb{C}(\mathfrak{su}(2)_L)$ -- the $\mathrm{SU}(2)_L$ sector, under [H-Weak].
- $L_Y := \wedge^2(E_{\mathrm{weak}})$ -- the $\mathrm{U}(1)_Y$ sector, under [H-Weak].
- $E_\Pi$ left-admissible -- Lorentz chirality, under [H-Spin], the Born--Infeld datum of O30; left-admissibility is the definition of the orientation-compatible branch (an input).
- The $V-A$ chiral structure -- the representation content of [H-Weak], not derived from left-admissibility.
- $\sigma_c(n_3) = 3 \to C^3_{\mathrm{gen}}$ -- three generations as a gauge-singlet factor,
  conditional on the supplied rank-three selection rule of O23 (Theorem 3.1 proves the
  three-dimensionality of the neutral sector of a supplied spinor carrier; carrier selection
  and observable identification are open).

## Three Structural Results (Q14)

| Result | Central output | Status |
|---|---|---|
| **Theorem A(a)** (algebra) | $\mathrm{Sym}^2 = \mathfrak{sl}_2(\mathbb{C})$ adjoint and $\wedge^2 = $ determinant line on the supplied doublet | proved on the supplied model data, independent of any metric |
| **Theorem A(b)** (Lorentz reading) | $\mathcal{S}_\Pi$; $\mathrm{Sym}^2(S_L) \simeq \mathrm{ad}(P_\Pi)$ and $\wedge^2(S_L)$ trivial | conditional on [H-Spin] |
| **Theorem A(c)** (electroweak reading) | $\mathfrak{su}(2)_L \subset \mathrm{Sym}^2(E_{\mathrm{weak}})$ and $L_Y = \wedge^2(E_{\mathrm{weak}})$ | conditional on [H-Weak]; $E_{\mathrm{weak}}$ is not constructed |
| **Theorem B** (Lorentz chirality) | $P_R E_\Pi P_R = 0$ | conditional on [H-Spin], the Born--Infeld datum of O30; left-admissibility is the definition of the orientation-compatible branch (an input) |
| **Theorem B** ($V-A$) | weak chiral selection | conditional on [H-Weak]; not derived from left-admissibility |
| **Theorem B** (weight rigidity) | $Y_R$ constrained by the anomaly-cancellation trace $\mathrm{Tr}_{\mathcal{S}_\Pi}(\gamma_5 Y A_\Pi(x)) = 0$ | conditional on [H-Spin], [H-Weak], a supplied three-dimensional colour module and the admissible matter decomposition (Q14 Prop. 4.4) |
| **Theorem B** (Standard Model pattern) | that pattern selected among the allowed weights, up to an overall sign, rescaling and the exchange of $u_R$ and $d_R$; the cubic constraint vanishes on it at colour multiplicity three | conditional on the same hypotheses and module **and** on the minimal integral normalisation of $L_Y$, whose connection to the pattern Q14 lists as an open direction |
| **Theorem C** (3 generations) | $C^3_{\mathrm{gen}} \subset \ker(\mathrm{ad}_{\mathrm{SU}(2)} \oplus Y)$; gauge-singlet generation space | conditional on the supplied rank-three carrier (O23), and on [H-Spin] and [H-Weak] through the bundle it multiplies |
| **Dynamic generation lifting** (Q14 §6) | On model operators on a distinct supplied doublet $V_{\mathrm{gen}}$: the static degeneracy of $C^3_{\mathrm{gen}}$ is obstructed; admissible lifts form a 2D $J_\Pi$-odd sector; the oriented cascade generator carries a non-zero $J_3$ projection ($\alpha \neq 0$) | qualitative mechanism; Q14 does not supply the reading of the model operators as restrictions of $E_\Pi^2$ (named [H-Res] for $\mathrm{diag}(1,\tfrac12+u,\tfrac12-u)$), the level-to-generation map is not established, $\varepsilon = 1/10$ is a matching value; amplitude deferred to cascade normalisation |
| Colour sector | $\mathcal{S}_\Pi \otimes V_{\mathrm{color}}$ (quark bundle) | conditional on the same supplied colour module, [H-Spin] and [H-Weak]. O31 is a withdrawal notice: the co-admissibility of the individual profiles (which Q14 identifies with $[H\text{-color}]_{\mathrm{pointwise}}$), the uniqueness of $\mathrm{SU}(3)$ and every derivation of a gauge factor are withdrawn |

## Constituent Papers

- **Q14** -- *Toward Fermionic Matter from Projective Dirac Admissibility: Chirality and Electroweak Structure Rest on a Lorentzian Spin Solder and a Distinct Weak Factor*. The sole constituent paper of the sub-programme: the $\mathfrak{sl}_2(\mathbb{C})$ tensor algebra on supplied model data with its Lorentz reading [H-Spin] and its electroweak reading [H-Weak], projected Dirac operator and the projective endomorphism $E_\Pi$, anomaly-cancellation trace constraining the hypercharge weights, Standard Model pattern selection under the minimal integral normalisation of $L_Y$, three-generation factor from $\sigma_c(n_3)=3$.

## Position in the Programme

The fermionic matter sub-programme sits at the **apex of Branch III**. It is the first paper of the Q-series that depends simultaneously on all four upstream layers:

- the admissible Weil fibre structure on the supplied carrier (Notes 1 and 5);
- the conditional Lorentzian geometry (Note 2);
- the gauge bundle for a supplied compact structure group (Note 3), which singles out no particular group;
- the conditional gauge-gravity system (Q13, summarised in Presentation Note 8).

## Scope Statement

This sub-programme addresses the **identification** of the fermionic sector: spinor bundle, chirality, hypercharge quantum numbers, and generation factor. The algebra of the spinor doublet is proved on the supplied model data, its Lorentz reading rests on [H-Spin] and the weak chiral selection on [H-Weak], neither of which is supplied; the hypercharge weight rigidity and the generation factor remain conditional on a supplied colour module and a supplied rank-three carrier respectively, and the Standard Model hypercharge pattern carries the further minimal-integral-normalisation premise. It does **not** derive the mass spectrum, the Yukawa couplings, or the CKM/PMNS mixing matrices.

## Open Deliverables

- **Explicit $E_\Pi$, splitting amplitude and the Yukawa sector.** The structural form of $E_\Pi$ is fixed as the Schur complement of the eliminated spinorial block; the open part is its explicit Lorentzian block along the $J_\Pi$-odd modulus. The amplitude mechanism is Born-Infeld saturation on the real cascade of the model, and the split value $|u|$ is dictionary-bound through the chiral-frontier normalisation $\mathcal{N}_A$. Its first-principles front is upstream and structural: the ADE case selection and the level-to-generation map, the projective-resolution growth $\Lambda_{\mathrm{proj}}(n)$ and the cascade exponent $\beta$ (no structural bound on $\beta$ is available), and the transfer constant $N_{\mathrm{casc}}$. The integral normalisation of $\mathcal{L}_{\mathrm{Yuk}}$ and generation mixing remain open; Q14 excludes a complex metaplectic phase as a source of $R_{\mathrm{mix}}$ within its metaplectic step model, where $R_{\mathrm{mix}}$ is not reached by the image of $\mathfrak{sl}_2(\mathbb{C})$ (Remark 6.4). $A_\Pi$, the anti-Hermitian part of the $J_\Pi$-odd part of the $\mathfrak{sl}_2$ lift of the step generator, vanishes identically for all complex coefficients, because with Q14's antilinear $J_\Pi$ the $J_\Pi$-odd part of the lift is its Hermitian part; this is a statement about $A_\Pi$ as defined in the companion PYO, a generator that is not the anomaly density $A_\Pi(x)$ of Q14. The $J_\Pi$-even anti-Hermitian part of the lift has a non-zero internal entry, non-zero for real $p \neq q$, so the image of $\mathfrak{sl}_2$ does reach the internal block $e_0 \leftrightarrow e_\pm$ through that part (Q14 excludes the internal block by hypothesis only, Proposition 6.3(i)-(ii)). No physical exclusion of the internal block is claimed: whether $A_\Pi$, rather than the $J_\Pi$-even part, is the right object is a modelling choice of PYO that no source justifies. The operators on the generation factor are model operators on a distinct supplied doublet, and Q14 does not supply their reading as restrictions of $E_\Pi^2$; [H-Res] names that reading for the model operator $\mathrm{diag}(1,\tfrac12+u,\tfrac12-u)$, and it is not supplied.
- **The two hypotheses [H-Spin] and [H-Weak].** Constructing the Lorentzian spin solder from the metaplectic action, and a distinct rank-two weak factor $E_{\mathrm{weak}}$ with structure group $\mathrm{U}(2)$ (or showing that the admissible fibre supplies neither); reading the residual reflection $R_b = W(-I)$ as central in the spin group needs a group-level map from the finite Weil group to the $\mathrm{SL}(2,\mathbb{C})$ of [H-Spin], which is not supplied.
- **An admissible colour sector.** No colour module is derived, so the quark bundle and the rigidity of the hypercharge weights both rest on a supplied one, and the Standard Model pattern rests on it too. O31 withdraws the co-admissibility of the individual capacity profiles, the uniqueness of $\mathrm{SU}(3)$, the arithmetic criterion for colour triplets, and every derivation of a gauge factor, with no weaker positive statement in their place; the gauge structure sub-programme singles out no particular group either, keeping a structural $\mathrm{U}(1)$ sector and an $\mathrm{SU}(2)$ sector conditional on the supplied spinor carrier, without assembling them into a group. The open problem is the construction of an admissible colour sector itself.
- **Full matter content in Lorentzian signature.** $S^{\mathrm{matter}}_\Pi = (\mathcal{S}_\Pi \oplus (\mathcal{S}_\Pi \otimes V_{\mathrm{color}})) \otimes C^3_{\mathrm{gen}}$ with explicit gauge couplings and three-generation Yukawa structure.

## Build

```bash
bash compile.sh
```

This runs `pdflatex -> bibtex -> pdflatex -> pdflatex -> pdflatex` on `tex/FermionicMatterNote.tex` and produces `out/FermionicMatterNote.pdf`. The fourth LaTeX pass settles the cross-references, so a build from a clean tree ends with no outstanding rerun warning.
