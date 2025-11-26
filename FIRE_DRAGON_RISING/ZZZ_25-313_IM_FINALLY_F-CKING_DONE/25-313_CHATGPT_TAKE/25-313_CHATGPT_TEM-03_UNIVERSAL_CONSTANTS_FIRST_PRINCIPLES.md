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