# Companion Terminology and Notational Guide

This companion document records terminology, notation, and any neologisms introduced in the TEM papers. Its purpose is to ensure clarity and consistency for readers encountering TEM for the first time. When a new term or unconventional usage appears in the main papers, it is explained here.

## General Terms

- **Finitistic Physical Set Theory (FPST):**  
    A version of set theory used in TEM in which the axiom of infinity is omitted. All physically real sets are finite, and subsets exist only if they correspond to actual physical configurations. Cardinal numbers are defined as equivalence classes of finite subsets.
    
- **Real Projective Three–Space ($\mathbb{RP}^3$):**  
    The set of lines through the origin in $\mathbb{R}^4$. Points are represented by homogeneous coordinates $[X^0:X^1:X^2:X^3]$, where rescaling by a non‑zero factor leaves the point unchanged. This space captures the scale–free nature of physical geometry.
    
- **Projective General Linear Group ($\mathrm{PGL}(4,\mathbb{R})$):**  
    The group of invertible $4\times4$ real matrices modulo scalar rescaling. It represents the symmetries of $\mathbb{RP}^3$. It has ten independent generators corresponding to translations, rotations, shears/strains, and a global dilation.
    
- **Radix (Rational Resonance Radix):**  
    The finite set of fourteen stable states labelled by integers $n\in{1,2,5,12,29,34,55,70,89,90,144,169,233,408}$. These states arise from the Harmonic Fixed‑Point Theorem and the geometric necessity of the Golden and Silver ratios. They form the symbolic base of all physical manifestations.
    
- **Radix Position / System Age ($n$):**  
    An integer labelling a stable configuration in the Radix. It measures the number of recursive layers (the “system age”) in the configuration. Radix positions are grouped into volumetric (Pell), surface (Fibonacci), and reset families.
    
- **Volumetric Cross‑Ratio (VCR):**  
    A scalar functional defined on smooth density fields in $\mathbb{RP}^3$. It is constructed from six radially weighted volumetric integrals whose Jacobian weights cancel. The VCR is invariant under $\mathrm{PGL}(4,\mathbb{R})$ and unique under natural locality and isotropy assumptions. It generalises the classical one‑dimensional cross‑ratio to volumetric fields.
    
- **Volumetric Laplacian ($\nabla_v^2$):**  
    The unique second‑order differential operator on $\mathbb{RP}^3$ that commutes with all generators of $\mathrm{PGL}(4,\mathbb{R})$. It appears in the recursive constraint operators and defines the propagation of density fields in a scale‑free manner.
    
- **Closure Operator ($\Phi$):**  
    An operator acting on density fields that combines the Volumetric Laplacian and VCR-based corrections. Iterating $\Phi$ drives fields towards resonant attractors—fixed points corresponding to stable Radix states.
    
- **Harmonic Fixed‑Point Theorem (HFPT):**  
    A theorem stating that a configuration is a fixed point of the closure operator if and only if its VCR is a positive rational number. It implies that only rational VCR values lead to stability.
    
- **Geometric Constraint Satisfaction:**  
    The paradigm underlying TEM in which the universe selects configurations by solving a discrete optimisation problem. Rather than solving continuous equations of motion, reality “fits” itself into patterns that satisfy all geometric and algebraic constraints (Radix positions, VCR rationality, and fundamental units).
    
- **Stabilisation Well:**  
    A conceptual illustration of how measured values of constants fluctuate around algebraic centres. The algebraic value derived from TEM (e.g. 137 for $\alpha^{-1}$) is the centre of a stabilisation well. Physical systems settle into these wells and exhibit small deviations due to environmental factors.
    
- **Cut–and–Project Method:**  
    A mathematical technique used to model quasicrystals. A periodic lattice in a higher dimension is projected into a lower dimension at an irrational angle, producing an aperiodic but ordered structure. In TEM this mechanism mirrors the projection from the full algebraic field $\mathbb{Q}(\sqrt{5},\sqrt{2})$ into observable reality.
    

## Symbols and Notation

- $U$ – The finite set representing the universe at a fixed instant in FPST.
    
- $\rho$ – A smooth density field on $\mathbb{RP}^3$.
    
- $dV$ – The projectively natural volume form on $\mathbb{RP}^3$.
    
- $\Psi_i[\rho]$ – Weighted volumetric integrals used to construct the VCR.
    
- $\mathrm{VCR}[\rho]$ – The volumetric cross‑ratio of $\rho$.
    
- $\nabla_v^2$ – The volumetric Laplacian.
    
- $\partial_k[\rho]$ – Recursive constraint operators defined by $\nabla_v^{2(k-1)}$.
    
- $\Phi$ – The closure operator.
    
- $\Gamma$ – The resonant observable operator mapping stable configurations to physical observables.
    
- $\phi$ – Golden Ratio, $(1+\sqrt{5})/2$.
    
- $\tau$ – Silver Ratio, $1+\sqrt{2}$.
    
- $K$ – The biquadratic field $\mathbb{Q}(\sqrt{5},\sqrt{2})$.
    
- $U_K$ – The unit group of $K$.
    
- $\mathbb{V}^{\mu\nu}$ – The four–domain VCR tensor.
    
- $G_i$ – The $i$‑th fundamental constraint/operator in the Universal Calculator (Ring One).
    
- $n_k$ – The $k$‑th Radix position.
    

## Changes in Presentation

- The paper series introduces the **Universal Calculator** as a visual and organisational tool. Although inspired by earlier drafts, the presentation here explicitly ties the ten positions of Ring One to the ten generators of $\mathrm{PGL}(4,\mathbb{R})$.
    
- The **Constraint Satisfaction** paradigm is emphasised more strongly than in some previous writings, providing a conceptual bridge between algebraic derivations and observable variability.
    
- Terminology such as “Stabilisation Well” is introduced to aid intuition. These terms are not present in earlier drafts but are explained here to ensure clarity.
    

## Usage

Readers are encouraged to refer back to this guide whenever they encounter an unfamiliar term or symbol in the main TEM papers. The goal is to make the exposition self‑contained and accessible without diluting the mathematical precision of the results.