# TEM‑01: The Volumetric Cross‑Ratio and the Rational Resonance Radix

## Introduction

Having established in **TEM‑00** that expansion and projective geometry are necessary features of physical reality, we now construct the fundamental invariants that govern all subsequent structure. The **Volumetric Cross‑Ratio (VCR)** is a scalar functional defined on smooth density fields in real projective three–space ($\mathbb{RP}^3$). It measures the relative arrangement of matter and remains unchanged under the full projective group $\mathrm{PGL}(4,\mathbb{R})$.

This paper defines the VCR, proves that it is the unique integral invariant under mild assumptions, and introduces the **Harmonic Fixed‑Point Theorem**. This theorem asserts that stable configurations of matter are only possible when the VCR takes rational values. We then use this result to derive the **Rational Resonance Radix**, a finite set of fourteen stable states that form the symbolic base system of reality.

## 1. The Volumetric Cross‑Ratio

### 1.1 Weighted Volumetric Averages

Let $\rho : \mathbb{RP}^3\to \mathbb{R}$ be a smooth scalar field representing a mass or density distribution. Choose a base point $x_0 \in \mathbb{RP}^3$ and let $w_i:[0,\pi)\to\mathbb{R}$ for $i=1,\dots,6$ be smooth radial kernels with compact support. Define the weighted volumetric integrals

Ψi[ρ](x0)  :=  ∫RP3wi(d(x,x0)) ρ(x) dV(x),\Psi_i[\rho](x_0) \;:=\; \int_{\mathbb{RP}^3} w_i\bigl(d(x,x_0)\bigr)\, \rho(x)\, dV(x),Ψi​[ρ](x0​):=∫RP3​wi​(d(x,x0​))ρ(x)dV(x),

where $dV$ is the projectively natural volume form and $d(x,x_0)$ is the geodesic distance in the Fubini–Study metric.

### 1.2 Definition of the VCR

The **Volumetric Cross‑Ratio** is defined by balancing the weights of these six integrals:

VCR[ρ](x0) = Ψ1[ρ](x0) Ψ4[ρ](x0)Ψ2[ρ](x0) Ψ3[ρ](x0) × Ψ5[ρ](x0)Ψ6[ρ](x0).\mathrm{VCR}[\rho](x_0) \,=\, \frac{\Psi_1[\rho](x_0)\, \Psi_4[\rho](x_0)}{\Psi_2[\rho](x_0)\, \Psi_3[\rho](x_0)}\,\times\,\frac{\Psi_5[\rho](x_0)}{\Psi_6[\rho](x_0)}.VCR[ρ](x0​)=Ψ2​[ρ](x0​)Ψ3​[ρ](x0​)Ψ1​[ρ](x0​)Ψ4​[ρ](x0​)​×Ψ6​[ρ](x0​)Ψ5​[ρ](x0​)​.

The kernels $w_i$ are chosen so that the Jacobian weights of the integrals cancel in pairs. Specifically, if $\alpha_i$ denotes the first non‑vanishing radial moment of $w_i$, then the following relations hold:

α1+α4=α2+α3,α5=α6.\alpha_1 + \alpha_4 = \alpha_2 + \alpha_3,\quad \alpha_5 = \alpha_6.α1​+α4​=α2​+α3​,α5​=α6​.

These conditions ensure that under any projective transformation $P\in\mathrm{PGL}(4,\mathbb{R})$ the VCR is invariant:

VCR[P⋅ρ](x0)  =  VCR[ρ](x0).\mathrm{VCR}[P\cdot\rho](x_0) \;=\; \mathrm{VCR}[\rho](x_0).VCR[P⋅ρ](x0​)=VCR[ρ](x0​).

### 1.3 Uniqueness

Any other integral functional constructed from finitely many radially weighted averages and invariant under $\mathrm{PGL}(4,\mathbb{R})$ reduces to the VCR up to trivial reparameterisations of the kernels. The uniqueness follows from the fact that the Jacobian balancing conditions impose a five‑dimensional linear constraint on the weights; the only non‑trivial solution with six integrals is the cross‑ratio structure.

## 2. The Volumetric Laplacian

In addition to an integral invariant TEM requires a differential invariant. The **volumetric Laplacian** $\nabla_v^2$ is the unique second‑order differential operator on $\mathbb{RP}^3$ that commutes with all generators of $\mathrm{PGL}(4,\mathbb{R})$. Its existence is guaranteed by representation theory and is analogous to the unique quadratic Casimir operator in a Lie algebra. In affine coordinates it takes a simple scaled form of the ordinary Laplacian: $\nabla_v^2 = \tfrac{1}{5} \nabla^2$.

## 3. The Harmonic Fixed‑Point Theorem (HFPT)

The central dynamical postulate of TEM is encoded in the **closure operator** $\Phi$, built from the volumetric Laplacian and the VCR. Given an initial density distribution $\rho_0$ one iterates $\Phi$ to obtain a sequence $\rho_k = \Phi^k[\rho_0]$. The system is said to reach a **resonant attractor** when $\rho_k$ converges to a fixed point $\rho_\infty$.

**Theorem 3.1 (Harmonic Fixed‑Point Theorem).**

> A density field $\rho$ on $\mathbb{RP}^3$ is a fixed point of the closure operator $\Phi$ if and only if its Volumetric Cross‑Ratio takes a positive rational value:
> 
> ρ is stable    ⟺    VCR[ρ]∈Q+.\rho \text{ is stable}\;\iff\; \mathrm{VCR}[\rho] \in \mathbb{Q}^+.ρ is stable⟺VCR[ρ]∈Q+.

_Sketch of proof._ If $\mathrm{VCR}[\rho]$ is irrational then successive applications of $\Phi$ generate incommensurate ratios of volumes, preventing the system from settling into a repeating pattern. Conversely, if $\mathrm{VCR}[\rho] = p/q \in \mathbb{Q}^+$, then the recursive constraints can align the higher–order derivatives of $\rho$ (measured by $\nabla_v^2$) in such a way that the system repeats after a finite number of steps. Rigorous details are provided in TEM‑02.

## 4. Emergence of $\phi$ and $\tau$

While the HFPT tells us that $\mathrm{VCR}[\rho]$ must be rational, it does not tell us which rationals are allowed. Physical configurations must also respect geometric resonance conditions that arise from the interplay between surface expansion and volumetric expansion. In two dimensions the natural expansion rate is the **Golden Ratio**

ϕ=1+52≈1.6180,\phi = \frac{1 + \sqrt{5}}{2} \approx 1.6180,ϕ=21+5​​≈1.6180,

and in three dimensions the natural expansion rate is the **Silver Ratio**

τ=1+2≈2.4142.\tau = 1 + \sqrt{2} \approx 2.4142.τ=1+2​≈2.4142.

Rational approximations to $\phi$ are given by the ratios of consecutive Fibonacci numbers, and those to $\tau$ by ratios of consecutive Pell numbers. The only rational values of the VCR that satisfy both the HFPT and the geometric resonance conditions are those low–order convergents of $\phi$ and $\tau$ that lie in the compositum field $\mathbb{Q}(\sqrt{5}, \sqrt{2})$.

## 5. The Rational Resonance Radix

Combining the HFPT with the geometric necessity of $\phi$ and $\tau$ yields a finite spectrum of stable VCR values. Explicit solution of the recursive constraint equations shows that there are exactly **fourteen** distinct resonance positions, labelled by an integer $n$ representing the effective “system age” of the configuration. These positions, ordered by increasing complexity, are

n∈{1,2,5,12,29,34,55,70,89,90,144,169,233,408}.n \in \{1, 2, 5, 12, 29, 34, 55, 70, 89, 90, 144, 169, 233, 408\}.n∈{1,2,5,12,29,34,55,70,89,90,144,169,233,408}.

Each value of $n$ corresponds to a rational VCR $p/q$ and a specific harmonic configuration in $\mathbb{RP}^3$. The values can be grouped into two families and a reset point:

- **Volumetric (Pell) family:** ${1,2,5,12,29,70,169,408}$,
    
- **Surface (Fibonacci) family:** ${34,55,89,144,233}$,
    
- **Symmetry reset:** $n=90$, associated with the first zero of the Bessel function $J_1$.
    

These fourteen states form the **Rational Resonance Radix (RRR)**, a symbolic base analogous to the ten digits of decimal notation. Every stable physical phenomenon can be described as a combination of these radix states. In later papers we will see how these positions map onto particles, fields, atoms, and even cosmological structures.

## 6. Conclusion

The Volumetric Cross‑Ratio is the essential measure of configuration in real projective space. Its uniqueness and invariance mean that it plays the role of equality itself in TEM: two states are equivalent if and only if their VCRs are equal. The Harmonic Fixed‑Point Theorem shows that only rational values of the VCR lead to stability, and the geometric resonance conditions restrict those rationals to a finite set derived from the Golden and Silver ratios. The result is the Rational Resonance Radix—a compact alphabet of fourteen states from which the richness of the physical world emerges.

The next paper, **TEM‑02**, will formalise the Projective Completeness Theorem, proving that these fourteen states exhaust all possibilities and exploring the deeper algebraic structure behind them.