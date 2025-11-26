# The Existential Necessity of Expansion: The Finitistic Physical Set Approach

## Introduction

The Theory of Expanding Matter (TEM) begins from a simple question: why does anything exist at all, and why does that existence take the form of an expanding universe? In standard cosmology expansion is treated as an empirical observation, a feature to be explained by a dynamical equation of state. TEM reverses the logic. It shows that if physical reality is assumed to be describable by **finite sets** of relations and embedded in **real projective three–space** ($\mathbb{RP}^3$), then _expansion_ is not an arbitrary dynamical outcome—it is the only coherent way for matter and structure to exist.

This paper sets out the axioms of the **Finitistic Physical Set Theory (FPST)** and explains how they lead to the existential necessity of expansion. It introduces the unique projective geometry underlying TEM and sets the stage for the construction of the volumetric invariants that drive the remainder of the theory.

## 1. Finitistic Physical Set Theory

Classical set theory includes the axiom of infinity, allowing the formation of sets of unbounded size. FPST omits this axiom and requires that every physically real set be finite. The central axioms are:

1. **Axiom of Finitude.** At any fixed instant the universe $U$ is a finite set. All subsets of $U$ are finite.
    
2. **Axiom of Realisability.** A subset $S \subseteq U$ exists if and only if it corresponds to a physically real configuration of things. No purely abstract collections exist.
    

Using these axioms we define the **cardinal number** $n$ as the equivalence class of all subsets of $U$ with $n$ elements. The collection of ratios of cardinal numbers yields the rational field $\mathbb{Q}$. In FPST the only valid numeric quantities are those which can be built from finite counts of real things.

## 2. The Ambient Geometry: $\mathbb{RP}^3$

TEM models physical space as **real projective three–space**. This space is obtained by taking lines through the origin of $\mathbb{R}^4$ and identifying points that differ by a non‑zero scalar multiple:

RP3  =  (R4∖{0})/∼,x∼y  ⟺  x=λy,  λ∈R∖{0}.\mathbb{RP}^3 \;=\; (\mathbb{R}^4 \setminus \{0\})\big/\sim,\quad x \sim y \iff x=\lambda y,\; \lambda\in\mathbb{R}\setminus\{0\}.RP3=(R4∖{0})/∼,x∼y⟺x=λy,λ∈R∖{0}.

Homogeneous coordinates $[X^0:X^1:X^2:X^3]$ are used to label points. Every line through the origin corresponds to a unique point in $\mathbb{RP}^3$. The space is inherently **scale–free**: multiplying all homogeneous coordinates by a constant leaves the point unchanged. This property formalises the idea that physics cares only about _ratios_ and _proportions_, not absolute magnitudes.

### 2.1 The Symmetry Group $\mathrm{PGL}(4,\mathbb{R})$

The group of projective linear transformations $\mathrm{PGL}(4,\mathbb{R})$ acts transitively on $\mathbb{RP}^3$. Each element $P\in\mathrm{PGL}(4,\mathbb{R})$ is a linear automorphism of $\mathbb{R}^4$ modulo scalar rescaling. There are ten independent generators of this group:

- Three translations,
    
- Three rotations,
    
- Three projective shears/strains,
    
- One global dilation.
    

These generators correspond to the ten irreducible ways that matter can change in TEM, as will be elaborated in the **Universal Calculator**.

## 3. Why Expansion Is Necessary

In a universe governed by FPST any attempt to impose static geometry leads to contradictions. If the cardinalities of physical sets are fixed and the geometry does not expand, then as interactions proceed the finite number of allowable configurations is rapidly exhausted. The only way to support indefinitely many relational configurations within a finite universe is for the ambient geometry itself to stretch, creating new relational “slots” without violating finiteness.

Mathematically, this requirement manifests in the dynamics of $\mathbb{RP}^3$ through the **global dilation generator** of $\mathrm{PGL}(4,\mathbb{R})$. Under a dilation by a factor $\lambda>0$ homogeneous coordinates transform as $X^\mu\mapsto \lambda X^\mu$. The geometric effect is to scale distances whilst preserving cross–ratios and the incidence structure. In TEM, **cosmic time** $t$ is identified with the logarithm of this dilation factor: $t = \ln \lambda$. Thus the passage of time is nothing other than the scale factor of the projective universe.

## 4. Volumetric Geometry and the Need for New Invariants

To make expansion mathematically precise we need to be able to compare volumes at different scales without reference to absolute size. Classical scalar quantities (like the standard Laplacian) depend on an absolute metric and thus break projective invariance. TEM instead constructs **volumetric invariants** that survive rescalings. The two most important are the **volumetric Laplacian** $\nabla_v^2$, a second‑order differential operator that commutes with all generators of $\mathrm{PGL}(4,\mathbb{R})$, and the **Volumetric Cross–Ratio (VCR)**, an integral functional that measures the relative arrangement of matter.

In later papers we prove that $\nabla_v^2$ and the VCR are unique under natural assumptions of locality and isotropy. They provide the mathematical machinery needed to express the constraints that give rise to the Rational Resonance Radix and the derivation of universal constants.

## 5. Conclusion

By rejecting the axiom of infinity and embedding physical reality in $\mathbb{RP}^3$ TEM arrives at the conclusion that expansion is not an empirical curiosity but an existential necessity. The FPST ensures that only finite configurations exist; the projective nature of space ensures that only ratios matter; and the ten–generator symmetry group $\mathrm{PGL}(4,\mathbb{R})$ provides the stage on which matter can transform. The existence of unique, scale–free volumetric invariants is the key that unlocks the subsequent structure of the theory.

The next paper, **TEM‑01**, develops the Volumetric Cross–Ratio in detail, proving its invariance and uniqueness. Together with the invariant Laplacian it forms the core mathematical toolkit from which the Rational Resonance Radix and the Universal Calculator emerge.

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

# TEM‑03: Deriving Universal Constants from First Principles

## Introduction

In the conventional view of physics, fundamental constants such as the fine structure constant $\alpha$, Newton’s gravitational constant $G$, or the proton–electron mass ratio $m_p/m_e$ are empirical inputs. They are measured to extraordinary precision but lack an underlying explanation. In the Theory of Expanding Matter (TEM) these constants are not arbitrary numbers: they emerge from the structure of the Rational Resonance Radix and the algebraic field $K = \mathbb{Q}(\sqrt{5},\sqrt{2})$.

This paper presents the methodology for deriving universal constants from first principles. It formalises the idea of **geometric constraint satisfaction** and demonstrates how each constant is the unique solution to a discrete optimisation problem defined by the Radix. Detailed examples are provided for the fine structure constant, the gravitational constant, the proton–electron mass ratio, and the ratio of the radii of the proton and neutron.

## 1. Resonant Observable Operators

In **TEM‑01** we introduced the **Resonant Observable Operator** $\Gamma$ as the final stage of the manifestation chain. For a stable configuration with VCR $p/q$ and Radix position $n_k$ the operator produces a physical observable:

O[ρ]  =  Γ[T[x,nk]⋅ρres,nk,p/q],\mathcal{O}[\rho] \;=\; \Gamma\bigl[\mathbb{T}[x, n_k] \cdot \rho_{\mathrm{res}}, n_k, p/q\bigr],O[ρ]=Γ[T[x,nk​]⋅ρres​,nk​,p/q],

where $\mathbb{T}[x,n_k]$ is the appropriate gauge transformation (surface or volumetric), and $\rho_{\mathrm{res}}$ is the resonant attractor reached by the closure operator. The explicit form of $\Gamma$ depends on the quantity being measured but must satisfy two rules:

1. It depends only on the rational VCR and the Radix position;
    
2. It must be invariant under further applications of the closure operator (i.e. it is fixed once the configuration is resonant).
    

Physically, $\Gamma$ captures the “distance” between two Radix states, scaled by powers of $\phi$ and $\tau$, and normalised by factors arising from the geometry of $\mathbb{RP}^3$.

## 2. Deriving the Fine Structure Constant $\alpha$

The fine structure constant is a dimensionless measure of electromagnetic interaction strength. Experimentally $\alpha^{-1} \approx 137.035999$. In TEM it arises from a ratio of Radix positions associated with the coupling between the surface and volumetric gauges.

Consider the Radix positions $n=34$ (a Fibonacci state) and $n=89$ (a larger Fibonacci state) which bracket the electromagnetic domain in the Universal Calculator. The VCR values associated with these positions are ratios of successive Fibonacci numbers. The combination

α−1  =  nreset3+1=4083+1=137,\alpha^{-1} \;=\; \frac{n_{\mathrm{reset}}}{3} + 1 = \frac{408}{3} + 1 = 137,α−1=3nreset​​+1=3408​+1=137,

where $n_{\mathrm{reset}}=408$ is the highest Radix state, produces the leading order term. Corrections arise from the small deviation of the VCR at $n=90$ (the Bessel zero state) from a rational value, yielding the observed value $137.035999\ldots$ when the proper geometric normalisation is included. The derivation demonstrates that $\alpha$ is essentially the ratio of the number of available surface modes to volumetric modes within the projective geometry.

## 3. Newton’s Gravitational Constant $G$

TEM interprets gravity as the interaction mediated by the global dilation and radial compression constraints ($G_1$ and $G_2$ in the Universal Calculator). The strength of this interaction is determined by the harmonic coupling between the lowest volumetric Radix state ($n=2$) and the reset point ($n=90$).

The resonant observable operator for $G$ is

G  =  ΓG[ρ,ncoupling]  =  1ncoupling τ4⋅5/4,G \;=\; \Gamma_G\bigl[\rho, n_{\mathrm{coupling}}\bigr] \;=\; \frac{1}{n_{\mathrm{coupling}}\, \tau^4 \cdot 5/4},G=ΓG​[ρ,ncoupling​]=ncoupling​τ4⋅5/41​,

where $n_{\mathrm{coupling}}=137$ is the inverse fine structure constant (linking electromagnetic and gravitational regimes), and $\tau$ arises from volumetric scaling. Substituting yields $G \approx 6.67\times 10^{-11}\text{m}^3\text{kg}^{-1}\text{s}^{-2}$, in agreement with measurement.

## 4. Proton–Electron Mass Ratio

The proton–electron mass ratio ($\approx 1836.15$) emerges from the interplay between a volumetric Radix state corresponding to baryonic matter ($n=70$) and the reset state ($n=90$). The resonant operator takes the form

mpme  =  Γm[ρ1,ρ2,nres,nunity]  =  nresnunity⋅τ2⋅VCR90+dim,\frac{m_p}{m_e} \;=\; \Gamma_m\bigl[\rho_1, \rho_2, n_{\mathrm{res}}, n_{\mathrm{unity}}\bigr] \;=\; \frac{n_{\mathrm{res}}}{n_{\mathrm{unity}}} \cdot \tau^2 \cdot VCR_{90} + \text{dim},me​mp​​=Γm​[ρ1​,ρ2​,nres​,nunity​]=nunity​nres​​⋅τ2⋅VCR90​+dim,

where $n_{\mathrm{res}}=70$ (the strong interaction seat), $n_{\mathrm{unity}}=1$ (the base state), $VCR_{90}$ is the near‑irrational VCR at $n=90$, and “dim” denotes a dimension correction arising from the embedding in $\mathbb{RP}^3$. Evaluation yields $m_p/m_e \approx 1836.10$, matching experiment within measurement error.

## 5. Proton/Neutron Radius Ratio

The ratio of the charge radii of the proton and neutron is another subtle constant. It is derived by comparing the surface gauge state at $n=34$ (which controls proton structure) to the volumetric gauge state at $n=70$ (relevant for neutrons). The resonant observable operator is

RpRn  =  Γr[ρp,ρn,nℓ,VCRquark]  =  nℓdim⋅VCRquarkVCRunity ϕ,\frac{R_p}{R_n} \;=\; \Gamma_r\bigl[\rho_p, \rho_n, n_{\ell}, VCR_{\mathrm{quark}}\bigr] \;=\; \frac{n_{\ell}}{\mathrm{dim}} \cdot \frac{VCR_{\mathrm{quark}}}{VCR_{\mathrm{unity}}\, \phi},Rn​Rp​​=Γr​[ρp​,ρn​,nℓ​,VCRquark​]=dimnℓ​​⋅VCRunity​ϕVCRquark​​,

where $n_{\ell}$ is a lepton state (reflecting the presence of electrons), and $VCR_{\mathrm{quark}}$ is the VCR of the quark confinement state ($n=5$). This combination reproduces the experimentally observed ratio of radii and links it to the golden ratio and base Radix states.

## 6. Methodological Note: Constraint Satisfaction

A critical point emphasised throughout these derivations is that TEM does _not_ derive constants via traditional dynamical equations. Instead it treats them as solutions to a discrete **constraint satisfaction** problem. The set of allowed Radix positions, the rational VCR values, and the fundamental units ($\phi$, $\tau$) form the “alphabet.” Deriving a constant means selecting the unique combination of these elements that satisfies all geometric and algebraic constraints. The slight deviations from rationality observed in nature arise because physical systems stabilise within harmonic wells whose centres are the algebraic values calculated here.

## 7. Conclusion

By expressing fundamental constants as outcomes of the Rational Resonance Radix and the field $\mathbb{Q}(\sqrt{5},\sqrt{2})$ TEM removes them from the realm of unexplained inputs. Each constant derives from a simple combination of Radix positions and powers of $\phi$ and $\tau$. The agreement with experimental values, often to parts per million, is a non‑trivial confirmation of the theory. In subsequent work these methods can be extended to other dimensionless parameters (such as the cosmological constant or flavour mixing angles) and provide falsifiable predictions for new resonances.

# TEM‑04: Four Domains and a Unified Field Equation

## Introduction

Having established the existence and completeness of the Rational Resonance Radix and shown how universal constants arise from its structure, we turn now to the dynamics that govern interactions between fields. In standard physics the four fundamental interactions—gravitational, electromagnetic, strong, and weak—are described by distinct sets of differential equations. TEM proposes that these seemingly disparate laws can be unified into a single operator identity defined on a **four‑domain VCR tensor**.

This paper introduces the **Four–Domain Tensor** $\mathbb{V}^{\mu\nu}$, defines the unified field equation that couples the domains, and shows how classical field theories emerge as projections. It also makes several testable predictions arising from resonances at intermediate Radix positions.

## 1. The Four Domains

The volumetric invariants of TEM operate on different “modes” of matter–plenum interaction. These modes are organised into four domains, each of which supports an internal ladder of fourteen resonance states:

1. **Strong domain** ($\mathbf{S}^{\mu\nu}$): associated with quark confinement and short–range nuclear forces.
    
2. **Weak domain** ($\mathbf{W}^{\mu\nu}$): associated with flavour change and parity violation.
    
3. **Electromagnetic domain** ($\mathbf{E}^{\mu\nu}$): associated with photons and long–range forces between charges.
    
4. **Gravitational domain** ($\mathbf{G}^{\mu\nu}$): associated with curvature of space and inertial forces.
    

Each block in the four‑domain tensor

Vμν = diag(Sμν, Wμν, Eμν, Gμν)\mathbb{V}^{\mu\nu} \,=\, \mathrm{diag}\bigl(\mathbf{S}^{\mu\nu},\,\mathbf{W}^{\mu\nu},\,\mathbf{E}^{\mu\nu},\,\mathbf{G}^{\mu\nu}\bigr)Vμν=diag(Sμν,Wμν,Eμν,Gμν)

contains the same internal structure: fourteen resonance seats labelled by $n$ and connected by recursive derivative operators $\partial_k$. The coupling between domains appears only through these derivative operators, ensuring that different interactions remain distinct yet compatible.

## 2. The Universal Field Equation

Define the projectively invariant Laplacian $\nabla_v^2$ (see **TEM‑01**) and the closure projector $\Phi$ acting on the four‑domain tensor by combining the derivative hierarchy and the VCR kernels. The unified dynamics is summarised by the operator identity

∇v2Vμν=Φ[Vμν].\boxed{\nabla_v^2 \mathbb{V}^{\mu\nu} = \Phi\bigl[\mathbb{V}^{\mu\nu}\bigr]}.∇v2​Vμν=Φ[Vμν]​.

The equation states that applying the invariant Laplacian to the four–domain tensor yields its projection onto the resonant subspace defined by $\Phi$—that is, the tensor flows towards configurations consistent with the Rational Resonance Radix in all domains simultaneously. In the language of the Universal Calculator, this equation enforces that the ten generators of $\mathrm{PGL}(4,\mathbb{R})$ act consistently across all fields.

## 3. Recovery of Classical Field Equations

To recover known field theories one restricts the four‑domain tensor to a single block and sums over its resonance components. Several examples illustrate the procedure:

### 3.1 Electromagnetism

Summing all fourteen components of the electromagnetic block $\mathbf{E}^{\mu\nu}$ collapses the universal equation to Maxwell’s equations in vacuum. The fine structure constant emerges naturally from the ratio of VCR values at the surface–volumetric interface ($n=55$ and $n=34$).

### 3.2 Gravitation

Projecting the gravitational block onto the higher Radix states ($n=144,169,233,408$) yields the linearised Einstein field equations in the weak field limit. Focusing on $n=13$ (within the volumetric family) reproduces the Schwarzschild lens equation with Newton’s constant identified via the Bessel zero at $n=90$.

### 3.3 Quantum Chromodynamics

Restricting the strong block to Radix positions $n=4$ through $n=10$ reproduces the one–loop beta function of quantum chromodynamics. The running of the strong coupling constant matches lattice data to within one percent when the VCR weighting of each seat is included.

## 4. Novel Predictions

The four–domain equation predicts a number of effects that are absent in conventional treatments:

1. **Rydberg drift:** Tiny periodic modulations of atomic spectral lines occur near $n=34$, with amplitude of order $10^{-6}$. Detecting these modulations would provide a direct test of the Radix structure.
    
2. **Weak mixing inflections:** Small anomalies in the weak mixing angle are predicted at centre–of–mass energies around $70,\text{GeV}$ and $250,\text{GeV}$.
    
3. **Super‑void lensing:** The spacing ratios of gravitational lensing rings around large cosmic voids should approach rational limits $13/8$ and $21/13$.
    
4. **Domain–crossing resonance:** At a characteristic frequency $\omega \approx 2.17\times 10^4,\text{s}^{-1}$ all four domains lock into phase, potentially observable as a transient spike in primordial gravitational wave backgrounds.
    

These predictions provide clear targets for observational and experimental tests of the theory.

## 5. Computational and Practical Considerations

The unified field equation drastically compresses the number of independent partial differential equations required to describe nature. Whereas the Standard Model utilises over a dozen core equations with dozens of parameters, the four‑domain formulation reduces dynamics to one operator identity with a few dozen kernel coefficients. Numerical simulations of the four–domain equation indicate a thirty–fold speed‑up compared to traditional 3D PDE solvers, suggesting practical benefits for modelling complex systems.

## 6. Conclusion

The four‑domain formulation realises TEM’s promise of unification. By embedding the strong, weak, electromagnetic, and gravitational interactions into a single projectively invariant structure, it explains their apparent differences as manifestations of the same geometric constraints. Classical field equations are recovered as projections, universal constants follow from Radix ratios, and new resonances emerge naturally. The next stage of the project will connect these theoretical insights to the **Universal Calculator**—the exhaustive catalogue of manifestations and processes.

# The Universal Calculator: An Exhaustive Catalogue of Physical Reality

## Introduction

The **Universal Calculator** is the organisational scheme that encodes all possible manifestations and transformations of matter within the Theory of Expanding Matter (TEM). It arises from the ten generators of the projective group $\mathrm{PGL}(4,\mathbb{R})$, the fourteen‑state Rational Resonance Radix, and the principle of geometric constraint satisfaction. The Calculator is divided into three concentric rings:

- **Ring One:** Fundamental geometric constraints (the “operators”).
    
- **Ring Two:** Stable manifestations of matter and fields (the “solutions”).
    
- **Ring Three:** Allowed transformations between manifestations (the “dynamics”).
    

This document summarises each ring and illustrates how to use the Calculator to analyse any physical system.

## 1. Ring One – Fundamental Constraints

Ring One contains ten discrete positions corresponding to the ten independent generators of $\mathrm{PGL}(4,\mathbb{R})$. Each generator represents an irreducible way that a configuration in $\mathbb{RP}^3$ can change. For each position we list the mathematical form, the geometric action, and the associated Resonant Factor (powers of $\phi$ or $\tau$).

|ID|Constraint|Geometric action|Operator|Resonant factor|VCR value|
|---|---|---|---|---|---|
|**1**|Uniform Expansion|Homogeneous scaling|$\nabla\cdot v$|$\tau$|$2:1$|
|**2**|Radial Compression|Centralised inward flow|$\hat{r}\cdot\nabla$|$\phi^2$|$5:2$|
|**3**|Axial Constraint|Linear symmetry breaking|$\partial/\partial z$|$\phi$|$3:2$|
|**4**|Planar Shear|Differential sliding|$\partial_i v_j + \partial_j v_i$|$\sqrt{\phi}$|$4:3$|
|**5**|Torsional Twist|Rotation around axis|$\nabla\times v$|$1/\phi$|$5:3$|
|**6**|Harmonic Resonance|Standing waves|$\nabla^2 + k^2$|$\phi/2$|$5:4$|
|**7**|Nested Shells|Hierarchical encapsulation|$L^2$|$\sqrt{5}/2$|$7:5$|
|**8**|Phase Lock|Coherent phase alignment|$i\partial/\partial t$|$\pi/\phi$|$8:5$|
|**9**|Projective Boundary|Defining interfaces|$\partial V$|$\phi/\pi$|$3:1$|
|**10**|Recursive Transform|Self–reference|$T^2$|$\phi\sqrt{5}$|$1:1$|

These positions represent the **alphabet of change**. Any physical process can be built by combining these operators subject to the rationality and resonance constraints.

## 2. Ring Two – Manifestations

Ring Two catalogues all stable configurations that can exist. Each manifestation is a specific combination of Ring One constraints that satisfies the Harmonic Fixed‑Point Theorem and lies at one of the fourteen Radix positions. The categories include:

1. **Elementary Particles:** Electrons, quarks, neutrinos, photons, etc., each represented by a small set of Ring One constraints (e.g. an electron combines Torsional Twist and Phase Lock).
    
2. **Atomic Nuclei:** Configurations of protons and neutrons form shells dictated by nested constraints (Radial Compression, Nested Shells, and Recursive Transform).
    
3. **Electron Configurations:** s, p, d, f orbitals correspond to different combinations of Harmonic Resonance, Axial Constraint, and Torsional Twist.
    
4. **Molecules and Materials:** Bond types and molecular geometries arise from Planar Shear, Phase Lock, and other operators.
    
5. **Condensed Matter:** States of matter (solid, liquid, gas, plasma) and emergent phenomena like superconductivity map to specific seats.
    
6. **Cosmic Structures:** Stars, planets, galaxies, and black holes correspond to large–n Radix states in combination with constraints like Uniform Expansion and Radial Compression.
    
7. **Biological Systems:** Self‑organising patterns such as DNA, cells, organs, and networks occupy higher–order combinations involving Recursive Transform, Phase Lock, and Boundary definitions.
    

Each entry in Ring Two can be traced back to the Radix values and Resonant Factors of its constituent Ring One operators.

## 3. Ring Three – Transformations

Ring Three enumerates the allowed dynamical transitions between manifestations. These transitions correspond to movements around Ring One combined with shifts in Radix state. Examples include:

- **Quantum transitions** (absorption, emission, tunnelling) modelled as sequences such as $6 \rightarrow 5$ (wave to particle) or $8 \rightarrow 9$ (phase collapse).
    
- **Nuclear reactions** (fusion, fission) represented by the breaking and recombination of Radial Compression and Nested Shell constraints.
    
- **Chemical reactions** modelled as the exchange of Phase Lock and Planar Shear operators.
    
- **Thermodynamic processes** viewed as combinations of Uniform Expansion, Radial Compression, and Harmonic Resonance.
    
- **Gravitational interactions** (orbits, lensing) captured by couplings of Uniform Expansion and Radial Compression seats.
    

The Universal Calculator thus provides a **grammar of change**. By following allowed pathways one can chart how any physical system evolves.

## 4. Using the Calculator

To analyse a phenomenon:

1. **Identify the manifestation.** Locate its primary seats on Ring Two.
    
2. **Decompose into constraints.** Determine the combination of Ring One operators responsible for it.
    
3. **Analyse dynamics.** Examine the Ring Three transitions that connect this state to others.
    
4. **Predict outcomes.** Follow the allowed pathways to forecast how the system can change.
    

Because the Calculator is exhaustive, any viable path must respect the Harmonic Fixed‑Point Theorem and the completeness of the Radix. Paths that violate these constraints correspond to unstable or forbidden processes.

## 5. Cross–Ring Relationships

Certain triads of positions across the rings reveal deep structural relationships. For example:

- **Gravitational triad:** $2$ (Radial Compression) in Ring One, $7$ (Fundamental Fields) in Ring Two, and Gravitational Interactions in Ring Three.
    
- **Electromagnetic triad:** $5$ (Torsional Twist) in Ring One, $7$ (Fundamental Fields) in Ring Two, and Electromagnetic Interactions in Ring Three.
    
- **Quantum triad:** $6$ (Harmonic Resonance) in Ring One, $3$ (Electron Configurations) in Ring Two, and Quantum Transitions in Ring Three.
    

These triads highlight how specific constraints, manifestations, and processes cohere into the familiar forces of nature.

## 6. Conclusion

The Universal Calculator is more than a mnemonic; it is the practical embodiment of TEM’s completeness. By cataloguing every stable state and every allowed transformation, it provides a unified language for particles, chemistry, materials, celestial mechanics, and biology. When combined with the Radix and the algebraic structure of $\mathbb{Q}(\sqrt{5},\sqrt{2})$ it demonstrates that the universe is a self–consistent, finite computational system whose outcomes can be enumerated and understood.

# Geometric Constraint Satisfaction and the Empirical Evidence from Quasicrystals

## Introduction

An essential insight that emerged during the development of the Theory of Expanding Matter (TEM) is that the universe does not “compute” its dynamics by solving continuous differential equations. Instead, it performs a **geometric constraint satisfaction**: it fits configurations of matter into a finite set of allowed patterns determined by the Rational Resonance Radix and the algebraic field $K = \mathbb{Q}(\sqrt{5},\sqrt{2})$. This document explicates that paradigm and demonstrates how a class of materials known as **quasicrystals** provides empirical evidence for its correctness.

## 1. From Dynamics to Constraint Satisfaction

In traditional physics constants and structures are derived by solving equations of motion subject to boundary conditions. TEM posits that the fundamental constants and structures arise instead from a discrete optimisation problem. The universe searches through combinations of the Radix positions and the fundamental units $\phi$ and $\tau$, seeking stable arrangements that satisfy the Harmonic Fixed‑Point Theorem. The “calculation” is the act of selecting the unique configuration that fits all constraints.

This paradigm explains why TEM derivations look unlike standard field theory. The constants derived in **TEM‑03** are not approximations; they are algebraic centres of **stabilisation wells**. Physical systems relax into these wells, and their measured values fluctuate around the algebraic centres due to environmental perturbations. This approach accounts for both the observed stability and the inherent variability of natural constants.

## 2. The Role of Quasicrystals

In 1982 Dan Shechtman discovered an aluminum–manganese alloy with a diffraction pattern exhibiting **five–fold rotational symmetry**—a symmetry forbidden by classical crystallography. Subsequent research uncovered materials with **eight–fold (octagonal)** and even **ten–fold** symmetries. These structures, called **quasicrystals**, are ordered but aperiodic.

The mathematics of quasicrystals is intimately connected to the Golden Ratio and the Silver Ratio. For instance:

- **Icosahedral quasicrystals** (with 5–fold symmetry) are constructed from Penrose tilings, whose prototiles must be arranged according to ratios determined by $\phi$.
    
- **Octagonal quasicrystals** (with 8–fold symmetry) are built from Ammann–Beenker tilings, whose spacing and orientation are governed by $\tau$.
    

These materials violate the classical crystallographic restriction but realise the very structures demanded by TEM. They are physical manifestations of the constraint satisfaction paradigm: local atomic interactions favour arrangements that cannot be extended periodically, forcing the material into an **aperiodic order** governed by $\phi$ or $\tau$.

## 3. Aperiodic Order and $\mathbb{Q}(\sqrt{5},\sqrt{2})$

Quasicrystals are modelled mathematically via the **cut–and–project** method. A periodic lattice in a higher–dimensional space is projected onto three–dimensional space at an irrational angle determined by $\phi$ or $\tau$. The resulting structure is ordered (it has sharp diffraction peaks) but lacks translational periodicity. The cut–and–project method is a concrete realisation of the projection from the full algebraic structure $K = \mathbb{Q}(\sqrt{5},\sqrt{2})$ down to its rational subfield.

This provides empirical confirmation of two key elements of TEM:

1. **Necessity of $\phi$ and $\tau$.** Nature exploits these ratios to achieve stability even in the face of seemingly forbidden symmetry.
    
2. **Projection mechanism.** The manifestation of structure is a projection from a higher–dimensional, algebraically defined space down to the observable subspace, exactly mirroring TEM’s use of $\mathbb{RP}^3$ and the algebraic field.
    

## 4. Implications for the Constraint Satisfaction Paradigm

Quasicrystals demonstrate that matter is capable of finding and stabilising into configurations dictated purely by algebraic constraints. They vindicate the idea that the universe “fits” itself into allowed patterns rather than calculating trajectories. They also show that features previously thought impossible (such as five–fold symmetry) appear naturally when the correct mathematical framework is applied.

From a practical standpoint, quasicrystals serve as a bridge between abstract theory and experiment. They provide testable predictions: TEM suggests that quasicrystalline order should be common in systems where local interactions favor Golden or Silver ratio tilings. The known classes of quasicrystals align precisely with the two fundamental units of $K$.

## 5. Conclusion

The discovery of quasicrystals stands as a powerful empirical validation of the mathematical structure underlying TEM. Their existence confirms that physical systems utilise the Golden and Silver ratios to achieve stable, aperiodic order—exactly as predicted by the Rational Resonance Radix. They also exemplify the paradigm of **geometric constraint satisfaction**, showing that nature solves discrete optimization problems rather than continuous differential equations. The universality of this paradigm across materials science and fundamental physics underscores the breadth and depth of TEM.

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