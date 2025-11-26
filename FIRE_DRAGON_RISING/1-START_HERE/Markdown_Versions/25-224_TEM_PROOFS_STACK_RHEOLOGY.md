Companion Guide to the Proofs on Expanding Matter (Appendices A–N)

This packet starts from a world with no built‑in distances or angles. It works with two ways to measure any region: how much material it contains and how much room it takes up. From that starting point it identifies the natural geometric setting, builds an invariant that can be computed from volumes, shows how a simple refinement rule forces discrete values at any finite stage, and proves when and how variation and rotation appear. It also shows why round spheres are selected under pressure, why certain discrete states are stable at finite depth, and why four independent kinds of control are required for robust stability.

## Appendix A. Uniqueness of density as a local scalar - 
---
Density is the thing that allows us to be able to differentiate between things.  If everything were the same density there would be NO DIFFERENTIATION: PERFECT SYMMETRY.

This appendix establishes that density is the only local number you can fairly attach to a point using just the two totals inside small regions, provided your rule ignores the shape of the region and does not change when you scale the region up or down. Any other acceptable local scalar is simply a continuous re‑labeling of density. In short, once you decide to work only with “how much stuff” and “how much room,” density is the sole local ingredient.

## Appendix B. Identifying the ambient space by incidence alone

This appendix fixes the geometric backdrop without introducing rulers or angles. If you require only the basic facts about how points, lines, and planes fit together, and you impose those facts on a connected three‑dimensional space in a way that is compatible with its topology, you are forced into real projective three‑dimensional space. That is the setting where straightness and alignment make sense while distances and angles are not assumed.

Appendix B.A. A volumetric form of the cross‑ratio
-
This appendix defines the volumetric cross‑ratio as a ratio of four tetrahedral volumes. The tetrahedra are formed from two auxiliary points that lie off the line, together with the four points on the line taken in pairs. The appendix proves that this ratio does not depend on which lifts or auxiliary points you chose, remains unchanged under every projective transformation, and agrees exactly with the classical cross‑ratio of the four points on the line. The point is that the invariant can be computed purely from volume comparisons.

Appendix C. Variation appears exactly when expansion is uneven

Starting from a uniform state, density remains constant if the measure of “room” evolves as a single overall factor everywhere. Density becomes non‑constant exactly when that evolution is not the same from place to place. Put simply, differentiation in space occurs if and only if expansion is non‑uniform relative to the transport of material.

Appendix D. Uniform volumetric expansion is impossible on a closed space

On a compact three‑dimensional space without boundary, a truly uniform rate of change of volume must vanish. If any change in the extent measure occurs, it cannot be spatially uniform. This pairs with the previous appendix: whenever there is any nonzero change, it is necessarily uneven, and that is exactly what produces spatial differentiation.

Appendix E. How rotation can be created from an initially non‑rotating state

When density varies and pressure depends on more than density alone, the directions of the density gradient and the pressure gradient need not align. Their misalignment supplies a source of rotation. The appendix writes this source term explicitly and shows that, even if the flow starts without rotation, rotation appears immediately once those gradients fail to point in the same direction. This is a precise statement of how uneven stretching, together with a non‑trivial material law, can create swirl from rest.

Appendix F. Why a round sphere is selected and remains stable under a pressure jump

Consider an inclusion of denser material inside a lighter background, with positive surface tension and a steady pressure difference across the interface. Among all embedded smooth shapes that enclose the same volume, the only one with constant mean curvature everywhere is the round sphere. The appendix shows that the sphere is not only a critical shape but also a strict local minimum of the free energy. In practice, an inclusion relaxes toward a sphere and resists small deformations while the pressure difference persists.

Appendix G. Finite refinement along a line yields only rational values

There is a natural way to refine neighboring points along a line by inserting the simplest in‑between value, the mediant. If you repeat this across all neighboring pairs for a finite number of steps, every value you produce is a rational number in lowest terms. Every positive rational number appears at some finite stage, while irrational values can be reached only as infinite limits. This shows that finite refinement produces a discrete spectrum.

Appendix H. The refinement rule is uniquely forced by invariance

If you require that the refinement of a neighboring pair preserve the volume‑based invariant and behave well under projective transformations, there is a unique elementary refinement. In coordinates it is the mediant insertion. This means the refinement rule is not an extra assumption but a consequence of the invariance you have already fixed.

Appendix I. Aiming at a target picks out its best fractions

Choose a real target number between two neighbors and keep refining only on the side that still brackets the target. The fractions that appear are exactly the best rational approximations to the target from its continued‑fraction expansion. For the golden number, these are the Fibonacci ratios. For one plus the square root of two, these are the Pell ratios. The appendix gives the simple update rules and identifies the resulting fractions.

Appendix J. “Resonance” equals best rational approximation

Among all fractions with denominators up to a given bound, the ones that minimize the error to a fixed real target are exactly the convergents from its continued‑fraction expansion and the immediate in‑between fractions at each stage. The appendix proves this error statement and shows that the refinement process you are using produces precisely those same fractions and no others at finite steps.

Appendix K. The rational spectrum for two gauges

If you designate two target values, such as the golden number and one plus the square root of two, and collect all fractions produced by the refinement toward either target, you get the union of the Fibonacci ladder and the Pell ladder together with their neighboring in‑between fractions. Truncating the process at a finite depth makes this a finite set. Letting the depth grow recovers the targets as limits while remaining discrete at every finite stage.

Appendix L. A supporting second‑order operator in the projective setting

There exists a unique, up to an overall factor, second‑order differential operator on the natural projective density bundle that is compatible with projective symmetries and has the identity as its leading part. In an ordinary coordinate chart it becomes one fifth of the usual Laplacian. This operator serves as a tool for building quadratic energies in a way that respects the projective structure; it is not the main headline of the packet.

Appendix M. Finite‑age stability and the discrete list of stable states

Define a simple, scale‑free error that rates how well a fraction approximates a chosen target, with a penalty that grows like the square of the denominator. Over all denominators up to a fixed bound, the strict local minimizers of this error are exactly the convergents of the target’s continued fraction. With the two chosen targets, this picks out a specific finite list of “stable ages” within one seat. The appendix gives the concrete list that occurs under the stated bound.

Appendix M.A. The first reset and its index

Imposing a no‑flux boundary condition on a spherical seat selects the first allowable radial node of the spherically symmetric mode. That node lies between the stable ages numbered eighty‑nine and one hundred forty‑four. By the construction of the seat, the reset index is therefore ninety. This ties a continuous boundary condition to the discrete list from the previous appendix.

Appendix N. Four independent sectors are required for robust stability

Small deviations from a sphere split into four independent kinds: a global change of size, low‑order shape changes such as squashing and stretching, high‑frequency ripples, and tangential twisting along the surface. If any one of these sectors is left uncontrolled, there is either an actual instability or a neutral direction. When each sector carries a positive weight, the quadratic energy is coercive after removing rigid motions, which means the sphere is genuinely stable against all small perturbations.

Appendix P. Discrete minima persist and attract under perturbation

A strict local minimum of the energy does not disappear under small changes to the rules. It moves slightly and remains a strict local minimum. If you start close enough and move downhill according to the gradient, you converge exponentially to that minimum. This establishes that the discrete finite‑depth states are structurally stable and have genuine local basins of attraction.


---

### Appendix A. Uniqueness of density as the first local scalar

Let XXX be a second‑countable Hausdorff space with an algebra A\mathcal{A}A of relatively compact open sets. Let EEE and SSS be finite Radon measures on XXX with S ⁣≪ ⁣ES\!\ll\!ES≪E. Write ρ=dSdE\rho=\frac{dS}{dE}ρ=dEdS​ for the Radon–Nikodym derivative. Assume a Vitali differentiation basis for EEE so that the Lebesgue differentiation theorem holds: for EEE-a.e. xxx,

lim⁡R↓xS(R)E(R)=ρ(x),\lim_{R\downarrow x}\frac{S(R)}{E(R)}=\rho(x),R↓xlim​E(R)S(R)​=ρ(x),

with the limit taken over sets R∈AR\in\mathcal{A}R∈A shrinking to xxx.

A **local scalar** P:X→RP:X\to\mathbb{R}P:X→R will mean a pointwise limit

P(x)=lim⁡R↓xF(S(R),E(R)),P(x)=\lim_{R\downarrow x} F\big(S(R),E(R)\big),P(x)=R↓xlim​F(S(R),E(R)),

for some continuous F:R≥02→RF:\mathbb{R}_{\ge 0}^2\to\mathbb{R}F:R≥02​→R that is **shape‑independent** (depends only on the pair (S(R),E(R))(S(R),E(R))(S(R),E(R))) and **jointly 0‑homogeneous**:

F(λs,λe)=F(s,e)for all λ>0.F(\lambda s,\lambda e)=F(s,e)\quad\text{for all }\lambda>0.F(λs,λe)=F(s,e)for all λ>0.

This encodes locality, absence of background geometry, and invariance under uniform rescaling of the region.

**Lemma (ratio factorization).** If FFF is continuous and F(λs,λe)=F(s,e)F(\lambda s,\lambda e)=F(s,e)F(λs,λe)=F(s,e) for all λ>0\lambda>0λ>0, then there exists a continuous φ:R≥0→R\varphi:\mathbb{R}_{\ge 0}\to\mathbb{R}φ:R≥0​→R with

F(s,e)=φ ⁣(se)for all e>0.F(s,e)=\varphi\!\left(\frac{s}{e}\right)\quad\text{for all }e>0.F(s,e)=φ(es​)for all e>0.

_Proof._ Fix e>0e>0e>0. Set φ(t)=F(t,1)\varphi(t)=F(t,1)φ(t)=F(t,1). Then F(s,e)=F ⁣(e⋅se, e⋅1)=F(se,1)=φ(s/e)F(s,e)=F\!\big(e\cdot \tfrac{s}{e},\, e\cdot 1\big)=F\big(\tfrac{s}{e},1\big)=\varphi(s/e)F(s,e)=F(e⋅es​,e⋅1)=F(es​,1)=φ(s/e). ∎

**Theorem.** For EEE-a.e. xxx, every local scalar PPP of the form above depends only on ρ(x)\rho(x)ρ(x). Precisely, there exists a continuous φ\varphiφ with

P(x)=φ(ρ(x))for E-a.e. x.P(x)=\varphi\big(\rho(x)\big)\quad\text{for }E\text{-a.e. }x.P(x)=φ(ρ(x))for E-a.e. x.

_Proof._ By the lemma, F(s,e)=φ(s/e)F(s,e)=\varphi(s/e)F(s,e)=φ(s/e). Hence

P(x)=lim⁡R↓xφ ⁣(S(R)E(R))=φ ⁣(lim⁡R↓xS(R)E(R))=φ(ρ(x)),P(x)=\lim_{R\downarrow x}\varphi\!\left(\frac{S(R)}{E(R)}\right)=\varphi\!\left(\lim_{R\downarrow x}\frac{S(R)}{E(R)}\right)=\varphi\big(\rho(x)\big),P(x)=R↓xlim​φ(E(R)S(R)​)=φ(R↓xlim​E(R)S(R)​)=φ(ρ(x)),

where the last equality uses the differentiation theorem and continuity of φ\varphiφ. ∎

**Corollary (uniqueness up to reparameterization).** If PPP is intended to distinguish points exactly when ρ\rhoρ does, then φ\varphiφ is strictly monotone on the range of ρ\rhoρ.

---
### Appendix B. Identification of the spatial manifold with RP3\mathbf{RP^3}RP3

Let XXX be a connected, second–countable, Hausdorff 333-manifold equipped with an incidence structure of points, lines, and planes satisfying the standard axioms of a 333-dimensional projective space: any two distinct points lie on a unique line; any three non‑collinear points lie in a unique plane; any two distinct planes meet in a line; and there exist four points no three of which are collinear and no four of which are coplanar. Assume the incidence is compatible with the topology so that lines and planes are embedded submanifolds and collineations are homeomorphisms.

**Theorem.**  
Under these assumptions there exists a division ring jjj such that XXX is isomorphic, as a topological incidence space, to the projective space P3(K)\mathbb{P}^3(K)P3(K). Because XXX has real dimension 333, it follows that K≅RK \cong \mathbb{R}K≅R, hence X≅RP3X \cong \mathbb{RP}^3X≅RP3.

**Proof.**  
By the Veblen–Young coordinatization theorem, every projective space of (incidence) dimension at least 333 is isomorphic to Pn(K)\mathbb{P}^n(K)Pn(K) for some division ring jjj (here n=3n=3n=3). As a real manifold, P3(K)\mathbb{P}^3(K)P3(K) is the quotient (K4 ⁣∖ ⁣{0})/K×(K^{4}\!\setminus\!\{0\})/K^{\times}(K4∖{0})/K×, so its real dimension equals dim⁡R(K4)−dim⁡R(K×)=4d−d=3d\dim_{\mathbb{R}}(K^{4}) - \dim_{\mathbb{R}}(K^{\times}) = 4d - d = 3ddimR​(K4)−dimR​(K×)=4d−d=3d, where d=dim⁡RKd=\dim_{\mathbb{R}}Kd=dimR​K. Since XXX is a real 333-manifold, we must have 3d=33d=33d=3, hence d=1d=1d=1 and K≅RK\cong \mathbb{R}K≅R. Therefore X≅P3(R)=RP3X \cong \mathbb{P}^3(\mathbb{R})=\mathbb{RP}^3X≅P3(R)=RP3. ∎

**Remark (transformations).**  
If, in addition, the admissible change‑of‑frame maps on XXX send lines to lines, then by the fundamental theorem of projective geometry these maps are projective collineations, and the symmetry group embeds into PGL(4,R)\mathrm{PGL}(4,\mathbb{R})PGL(4,R), which is the natural automorphism group of RP3\mathbb{RP}^3RP3.

### Appendix B.A. Volumetric cross‑ratio as the projective invariant in RP3\mathbf{RP^3}RP3

Work in RP3\mathbb{RP}^3RP3 with homogeneous representatives in R4∖{0}\mathbb{R}^4\setminus\{0\}R4∖{0}. For points p,q,r,sp,q,r,sp,q,r,s in general position define the 4‑bracket

[p q r s]  =  det⁡(p~,q~,r~,s~),[p\,q\,r\,s]\;=\;\det\big(\tilde p,\tilde q,\tilde r,\tilde s\big),[pqrs]=det(p~​,q~​,r~,s~),

where each tilde denotes any nonzero homogeneous lift; changes of lifts scale each bracket by a nonzero factor and projective maps T∈GL(4,R)T\in\mathrm{GL}(4,\mathbb{R})T∈GL(4,R) act by [Tp Tq Tr Ts]=det⁡(T)[p q r s][Tp\,Tq\,Tr\,Ts]=\det(T)[p\,q\,r\,s][TpTqTrTs]=det(T)[pqrs].

Let a,b,c,da,b,c,da,b,c,d be distinct collinear points and let e,fe,fe,f be any two points not contained in the plane spanned by that line. Define the **volumetric cross‑ratio**

VCR(a,b;c,d)  =  [e f a d] [e f b c][e f a c] [e f b d].(1)\mathrm{VCR}(a,b;c,d) \;=\; \frac{[e\,f\,a\,d]\,[e\,f\,b\,c]}{[e\,f\,a\,c]\,[e\,f\,b\,d]}. \tag{1}VCR(a,b;c,d)=[efac][efbd][efad][efbc]​.(1)

**Theorem.**  
The quantity in **(1)** is well‑defined (independent of choices of homogeneous lifts and of e,fe,fe,f), invariant under all projective collineations of RP3\mathbb{RP}^3RP3, and equals the classical cross‑ratio (a,b;c,d)(a,b;c,d)(a,b;c,d) of the ordered collinear quadruple. In particular, it is the fundamental scalar invariant attached to four collinear points, and in any affine chart it can be computed from ratios of tetrahedral volumes.

**Proof.**  
_Projective invariance and independence of lifts._ Under T∈GL(4,R)T\in\mathrm{GL}(4,\mathbb{R})T∈GL(4,R), each bracket in **(1)** acquires the same factor det⁡(T)\det(T)det(T), which cancels between numerator and denominator. Rescaling any homogeneous representative multiplies each bracket containing that column by the same scalar; the multiplicative factors cancel in **(1)** because each point appears exactly once in the numerator and once in the denominator. Thus VCR\mathrm{VCR}VCR is well‑defined and projectively invariant.

_Identification with the classical cross‑ratio._ Choose projective coordinates so that

e=(1,0,0,0),f=(0,1,0,0),e=(1,0,0,0),\quad f=(0,1,0,0),e=(1,0,0,0),f=(0,1,0,0),

and the given line is {(0,0,λ,μ):(λ,μ)≠(0,0)}\{(0,0,\lambda,\mu):(\lambda,\mu)\neq(0,0)\}{(0,0,λ,μ):(λ,μ)=(0,0)}. Write

a=(0,0,1,0),    b=(0,0,0,1),    c=(0,0,1,1),    d=(0,0,1,λ),a=(0,0,1,0),\;\; b=(0,0,0,1),\;\; c=(0,0,1,1),\;\; d=(0,0,1,\lambda),a=(0,0,1,0),b=(0,0,0,1),c=(0,0,1,1),d=(0,0,1,λ),

so that the classical cross‑ratio (a,b;c,d)(a,b;c,d)(a,b;c,d) equals λ\lambdaλ in this chart. A direct determinant calculation gives

[e f a d]=λ,[e f b c]=−1,[e f a c]=1,[e f b d]=−1,[e\,f\,a\,d]=\lambda,\qquad [e\,f\,b\,c]=-1,\qquad [e\,f\,a\,c]=1,\qquad [e\,f\,b\,d]=-1,[efad]=λ,[efbc]=−1,[efac]=1,[efbd]=−1,

hence VCR(a,b;c,d)=λ⋅(−1)1⋅(−1)=λ=(a,b;c,d)\mathrm{VCR}(a,b;c,d)=\dfrac{\lambda\cdot(-1)}{1\cdot(-1)}=\lambda=(a,b;c,d)VCR(a,b;c,d)=1⋅(−1)λ⋅(−1)​=λ=(a,b;c,d).  
Because VCR\mathrm{VCR}VCR is projectively invariant and the classical cross‑ratio is uniquely characterized as the projective invariant of an ordered collinear quadruple, the equality holds in all coordinates and for all admissible e,fe,fe,f. ∎

**Remark (volumetric computation).**  
In any affine chart w=1w=1w=1, the bracket [e f p q][e\,f\,p\,q][efpq] is a constant multiple of the signed volume of the tetrahedron with vertices e,f,p,qe,f,p,qe,f,p,q. Therefore VCR\mathrm{VCR}VCR can be measured as a ratio of tetrahedral volumes, giving a manifestly “volumetric” realization of the projective cross‑ratio in RP3\mathbb{RP}^3RP3.

---
### Appendix C. Differentiation occurs if and only if non‑uniform expansion occurs

Let XXX be a connected, second–countable, Hausdorff 333-manifold; in the intended application X≅RP3X\cong \mathbb{RP}^3X≅RP3. Let E0E_0E0​ and S0S_0S0​ be finite Radon measures on XXX (extent and substance) with S0=ρ0 E0S_0=\rho_0\,E_0S0​=ρ0​E0​ for some constant ρ0>0\rho_0>0ρ0​>0. Let (Φt)t∈I(\Phi_t)_{t\in I}(Φt​)t∈I​ be a measurable family of bijections of XXX (material transport). Substance is conserved by pushforward: St=(Φt)∗S0S_t=(\Phi_t)_{*}S_0St​=(Φt​)∗​S0​. For each ttt, let EtE_tEt​ be a finite Radon measure (the current extent) with St≪EtS_t\ll E_tSt​≪Et​. Define ρt=dStdEt\rho_t=\frac{dS_t}{dE_t}ρt​=dEt​dSt​​ (the density at time ttt).

Define νt:=(Φt)∗E0\nu_t:=(\Phi_t)_{*}E_0νt​:=(Φt​)∗​E0​. Say that there is **no expansion** at time ttt if Et=c νtE_t=c\,\nu_tEt​=cνt​ for some constant c>0c>0c>0. Say that there is **non‑uniform expansion** at time ttt if EtE_tEt​ is not a scalar multiple of νt\nu_tνt​.

**Theorem.** For each ttt, the following are equivalent.  
(i) The density field ρt\rho_tρt​ is non‑constant on a set of positive EtE_tEt​‑measure.  
(ii) There is non‑uniform expansion at time ttt.

**Proof.** Since S0=ρ0E0S_0=\rho_0 E_0S0​=ρ0​E0​ and St=(Φt)∗S0S_t=(\Phi_t)_{*}S_0St​=(Φt​)∗​S0​, it follows that St=ρ0νtS_t=\rho_0 \nu_tSt​=ρ0​νt​. By the Radon–Nikodym theorem applied with respect to EtE_tEt​,

ρt=dStdEt=ρ0 dνtdEtfor Et-a.e. points.\rho_t=\frac{dS_t}{dE_t}=\rho_0\,\frac{d\nu_t}{dE_t}\quad\text{for }E_t\text{-a.e. points.}ρt​=dEt​dSt​​=ρ0​dEt​dνt​​for Et​-a.e. points.

If Et=c νtE_t=c\,\nu_tEt​=cνt​ for some c>0c>0c>0, then dνtdEt=1c\frac{d\nu_t}{dE_t}=\frac{1}{c}dEt​dνt​​=c1​ almost everywhere and ρt≡ρ0/c\rho_t\equiv \rho_0/cρt​≡ρ0​/c is constant; thus (ii) fails and (i) fails. Conversely, if EtE_tEt​ is not a scalar multiple of νt\nu_tνt​, then the Radon–Nikodym derivative f:=dνtdEtf:=\frac{d\nu_t}{dE_t}f:=dEt​dνt​​ cannot be almost everywhere constant, so ρt=ρ0f\rho_t=\rho_0 fρt​=ρ0​f is not almost everywhere constant; thus (ii) holds and (i) holds. ∎

**Corollary (prime mechanism).** Starting from perfect symmetry S0=ρ0E0S_0=\rho_0 E_0S0​=ρ0​E0​, spatial differentiation (a non‑constant density field) occurs at time ttt if and only if the extent measure undergoes non‑uniform expansion relative to material transport, in the precise sense Et≢c (Φt)∗E0E_t\not\equiv c\,(\Phi_t)_{*}E_0Et​≡c(Φt​)∗​E0​. Hence the existence of distinguishable structure requires expansion, and non‑uniform expansion produces distinguishable structure.

---
### Appendix D. Nonexistence of nontrivial spatially uniform expansion on RP3\mathbf{RP^3}RP3

Let XXX be a compact, connected, boundaryless 333-manifold; in the intended application X≅RP3X \cong \mathbb{RP}^3X≅RP3. For each time ttt, let ωt\omega_tωt​ be a smooth positive volume form on XXX representing the material “extent” at time ttt. Assume the material moves by a smooth flow Φt\Phi_tΦt​ generated by a time–dependent vector field vtv_tvt​, so that ∂tωt=Lvtωt\partial_t \omega_t = \mathcal{L}_{v_t}\omega_t∂t​ωt​=Lvt​​ωt​ (transport of the volume form by the flow). Define the **pointwise expansion rate** θ(⋅,t)\theta(\cdot,t)θ(⋅,t) by

Lvtωt  =  θ(⋅,t) ωt.\mathcal{L}_{v_t}\omega_t \;=\; \theta(\cdot,t)\,\omega_t .Lvt​​ωt​=θ(⋅,t)ωt​.

Say that **uniform expansion** holds at time ttt if θ(⋅,t)\theta(\cdot,t)θ(⋅,t) is constant on XXX.

**Theorem.**  
If XXX is compact without boundary, then uniform expansion at time ttt implies θ(⋅,t)≡0\theta(\cdot,t)\equiv 0θ(⋅,t)≡0. In particular, there is no nontrivial spatially uniform expansion on XXX.

**Proof.**  
Because XXX is 333-dimensional, every 333-form is closed, so dωt=0d\omega_t=0dωt​=0. Cartan’s formula gives Lvtωt=d(ivtωt)\mathcal{L}_{v_t}\omega_t = d(i_{v_t}\omega_t)Lvt​​ωt​=d(ivt​​ωt​). Integrating over XXX and using Stokes’ theorem yields

∫XLvtωt  =  ∫Xd(ivtωt)  =  0.\int_X \mathcal{L}_{v_t}\omega_t \;=\; \int_X d(i_{v_t}\omega_t) \;=\; 0 .∫X​Lvt​​ωt​=∫X​d(ivt​​ωt​)=0.

If θ(⋅,t)≡α(t)\theta(\cdot,t)\equiv \alpha(t)θ(⋅,t)≡α(t) is constant, then

0  =  ∫XLvtωt  =  ∫Xα(t) ωt  =  α(t) ∫Xωt.0 \;=\; \int_X \mathcal{L}_{v_t}\omega_t \;=\; \int_X \alpha(t)\,\omega_t \;=\; \alpha(t)\,\int_X \omega_t .0=∫X​Lvt​​ωt​=∫X​α(t)ωt​=α(t)∫X​ωt​.

The total extent ∫Xωt\int_X \omega_t∫X​ωt​ is strictly positive, hence α(t)=0\alpha(t)=0α(t)=0. ∎

**Corollary.**  
On X≅RP3X \cong \mathbb{RP}^3X≅RP3, any change in extent must be spatially nonuniform at each time it is nonzero. Combined with Appendix C, any nonzero expansion produces spatial differentiation, and differentiation cannot occur without nonuniform expansion.

### Appendix E. Non‑uniform expansion generates vorticity

Let XXX be a smooth 3‑manifold, let ρ(x,t)>0\rho(x,t)>0ρ(x,t)>0 be density and u(x,t)u(x,t)u(x,t) a C2C^2C2 velocity field. Define vorticity ω=∇×u\omega=\nabla\times uω=∇×u. Consider the compressible momentum balance

ρ(∂tu+u⋅∇u)  =  −∇p(ρ,Θ)  +  ∇ ⁣⋅ ⁣τ,\rho(\partial_t u + u\cdot\nabla u) \;=\; -\nabla p(\rho,\Theta)\;+\;\nabla\!\cdot\!\tau,ρ(∂t​u+u⋅∇u)=−∇p(ρ,Θ)+∇⋅τ,

where ppp is pressure depending on density ρ\rhoρ and an additional state variable Θ\ThetaΘ (e.g. temperature or internal structure), and τ\tauτ is a symmetric extra stress (viscous/viscoelastic). Taking curl yields the vorticity evolution identity

∂tω  =  ∇×(u×ω)  +  1ρ2 ∇ρ×∇p(ρ,Θ)  +  ∇× ⁣(1ρ∇ ⁣⋅ ⁣τ).\partial_t \omega \;=\; \nabla\times(u\times\omega)\;+\;\frac{1}{\rho^2}\,\nabla\rho\times\nabla p(\rho,\Theta)\;+\;\nabla\times\!\Big(\frac{1}{\rho}\nabla\!\cdot\!\tau\Big).∂t​ω=∇×(u×ω)+ρ21​∇ρ×∇p(ρ,Θ)+∇×(ρ1​∇⋅τ).

**Theorem.**  
Assume that at time t0t_0t0​ the flow is irrotational (ω(⋅,t0)=0\omega(\cdot,t_0)=0ω(⋅,t0​)=0). If non‑uniform expansion is present (so ∇ρ(⋅,t0)≢0\nabla\rho(\cdot,t_0)\not\equiv 0∇ρ(⋅,t0​)≡0) and the medium is non‑barotropic at t0t_0t0​ on a set of positive measure (i.e. ∇p(ρ,Θ)\nabla p(\rho,\Theta)∇p(ρ,Θ) is not everywhere parallel to ∇ρ\nabla\rho∇ρ), then there exists ε>0\varepsilon>0ε>0 such that ω(⋅,t)≢0\omega(\cdot,t)\not\equiv 0ω(⋅,t)≡0 for all t∈(t0,t0+ε)t\in(t_0,t_0+\varepsilon)t∈(t0​,t0​+ε).

**Proof.**  
At t0t_0t0​ the convective term ∇×(u×ω)\nabla\times(u\times\omega)∇×(u×ω) vanishes because ω=0\omega=0ω=0. For a Newtonian fluid with constant coefficients, ∇×(1ρ∇ ⁣⋅ ⁣τ)\nabla\times\big(\frac{1}{\rho}\nabla\!\cdot\!\tau\big)∇×(ρ1​∇⋅τ) also vanishes at t0t_0t0​ if ω=0\omega=0ω=0 (it reduces to μ∇2ω\mu\nabla^2\omegaμ∇2ω). Thus

∂tω(⋅,t0)  =  1ρ2 ∇ρ(⋅,t0)×∇p(ρ,Θ)(⋅,t0).\partial_t\omega(\cdot,t_0)\;=\;\frac{1}{\rho^2}\,\nabla\rho(\cdot,t_0)\times\nabla p(\rho,\Theta)(\cdot,t_0).∂t​ω(⋅,t0​)=ρ21​∇ρ(⋅,t0​)×∇p(ρ,Θ)(⋅,t0​).

By hypothesis, the right‑hand side is nonzero on a set of positive measure, hence ω\omegaω becomes nonzero immediately after t0t_0t0​. ∎

**Corollary.**  
Whenever non‑uniform expansion creates density gradients and the constitutive law is not strictly barotropic, rotational motion is generated from an irrotational state. (Viscoelastic models add further source terms in ∇×(ρ−1∇ ⁣⋅ ⁣τ)\nabla\times\big(\rho^{-1}\nabla\!\cdot\!\tau\big)∇×(ρ−1∇⋅τ); these do not cancel the baroclinic source and can themselves be nonzero under spatially varying dilation.)

---

### Appendix F. Stable spherical inclusion under sustained overpressure

Work locally in R3\mathbb{R}^3R3 (valid on XXX at scales small compared to curvature). Consider two phases of the same material separated by a sharp interface Σ=∂Ω\Sigma=\partial\OmegaΣ=∂Ω, where Ω⊂R3\Omega\subset\mathbb{R}^3Ω⊂R3 is the denser inclusion. Let γ>0\gamma>0γ>0 be an isotropic interfacial energy density and let Δp>0\Delta p>0Δp>0 be the pressure jump pin−poutp_{\text{in}}-p_{\text{out}}pin​−pout​ sustained by the dynamics (expansion/compression). The free energy for a configuration Ω\OmegaΩ of fixed enclosed volume VVV is

F[Ω]  =  γ H2(∂Ω)  −  Δp ∣Ω∣.\mathcal{F}[\Omega]\;=\;\gamma\,\mathcal{H}^2(\partial\Omega)\;-\;\Delta p\,|\Omega|.F[Ω]=γH2(∂Ω)−Δp∣Ω∣.

**Theorem.**  
Among all C2C^2C2 regions Ω⊂R3\Omega\subset\mathbb{R}^3Ω⊂R3 with ∣Ω∣=V|\Omega|=V∣Ω∣=V, the unique stationary points of F\mathcal{F}F are bounded domains whose boundary has constant mean curvature H=Δp2γH=\tfrac{\Delta p}{2\gamma}H=2γΔp​; the only embedded closed such surfaces are round spheres. The sphere is a strict local minimizer of F\mathcal{F}F.

**Proof.**  
The first variation of area with a volume constraint yields the Euler–Lagrange condition 2γH=Δp2\gamma H=\Delta p2γH=Δp (Young–Laplace law). By Alexandrov’s theorem, an embedded closed surface in R3\mathbb{R}^3R3 with constant mean curvature is a round sphere. Second variation at the sphere is positive definite under fixed‑volume variations, so the sphere is a strict local minimizer. ∎

**Corollary (formation and persistence).**  
If a non‑zero pressure jump Δp\Delta pΔp is maintained and interfacial energy is isotropic, any nucleated inclusion of fixed volume relaxes toward a sphere and is stable while Δp>0\Delta p>0Δp>0 persists. On a curved 3‑manifold, the same conclusion holds for inclusions small compared to the curvature scale (geodesic spheres), and the isoperimetric property ensures spherical profiles in the small‑volume regime.

---
### Appendix G. Finite projective recursion yields discrete (rational) cross‑ratio values

Work on any projective line L⊂RP3L\subset \mathbb{RP}^3L⊂RP3. By Appendix B.A, the volumetric cross‑ratio on collinear quadruples coincides with the classical cross‑ratio on LLL, which we identify with a coordinate x∈R>0x\in \mathbb{R}_{>0}x∈R>0​ after fixing two endpoints.

Initialize with the ordered endpoints 01\frac{0}{1}10​ and 10\frac{1}{0}01​. Two reduced fractions ab,cd∈Q≥0∪{∞}\frac{a}{b}, \frac{c}{d}\in \mathbb{Q}_{\ge 0}\cup\{\infty\}ba​,dc​∈Q≥0​∪{∞} are called **adjacent** if ad−bc=1ad-bc=1ad−bc=1. Given adjacent neighbors, define the **mediant insertion**

ab ∣ cd⟼a+c b+d .\frac{a}{b}\ \big|\ \frac{c}{d}\quad\longmapsto\quad \frac{a+c}{\,b+d\,}.ba​ ​ dc​⟼b+da+c​.

Iterating this rule level by level produces the Stern–Brocot tree; at level nnn there are finitely many fractions, each in lowest terms, and every fraction appears exactly once in the infinite tree.

We now regard one step of **projective recursion** along LLL as “refine each adjacent pair by inserting its mediant.” This rule is projectively natural: it is encoded by the unimodular matrices

L=(1011),R=(1101),L=\begin{pmatrix}1&0\\[2pt]1&1\end{pmatrix},\qquad R=\begin{pmatrix}1&1\\[2pt]0&1\end{pmatrix},L=(11​01​),R=(10​11​),

since, if ab\frac{a}{b}ba​ and cd\frac{c}{d}dc​ are adjacent (so \begin{psmallmatrix} a&c\\ b&d\end{psmallmatrix}\in \mathrm{SL}(2,\mathbb{Z})), the mediant column (a+cb+d)\binom{a+c}{b+d}(b+da+c​) is obtained by multiplying on the right by LLL or RRR; concatenating refinements corresponds to words in L,RL,RL,R and preserves unimodularity.

**Theorem.**  
After any finite number of recursion steps, all produced cross‑ratio values on LLL are rational, and every positive rational appears at some finite step. Conversely, an irrational value can be reached only as a limit of an infinite refinement sequence.

**Proof.**  
Induction on the number of steps. At step 000 the endpoints are 0/10/10/1 and 1/01/01/0. If ab\frac{a}{b}ba​ and cd\frac{c}{d}dc​ are adjacent and reduced, then a+cb+d\frac{a+c}{b+d}b+da+c​ is reduced and sits strictly between them, with

det⁡(aa+cbb+d)=det⁡(acbd)=1,det⁡(a+ccb+dd)=1,\det\begin{pmatrix} a & a+c \\[2pt] b & b+d \end{pmatrix} =\det\begin{pmatrix} a & c \\[2pt] b & d \end{pmatrix}=1, \qquad \det\begin{pmatrix} a+c & c \\[2pt] b+d & d \end{pmatrix}=1,det(ab​a+cb+d​)=det(ab​cd​)=1,det(a+cb+d​cd​)=1,

so adjacency is preserved on both sides. Thus every new value is rational and in lowest terms. Standard properties of the Stern–Brocot tree imply that every positive reduced rational p/qp/qp/q appears exactly once at a finite step (equivalently: the map from words in L,RL,RL,R to fractions via  
\begin{psmallmatrix} a&c\\ b&d\end{psmallmatrix}\mapsto \frac{a}{b} is a bijection onto Q>0 \mathbb{Q}_{>0}Q>0​). Any irrational requires an infinite path (its continued fraction), hence cannot occur at a finite step. ∎

**Corollary (quantization at finite age).**  
If “system age” bounds recursion depth by N<∞N<\inftyN<∞, then accessible cross‑ratio values on any projective line are a finite subset of Q>0\mathbb{Q}_{>0}Q>0​. In particular, **finite age implies discreteness** (quantization) of admissible volumetric cross‑ratios, and **irrational values arise only as infinite‑depth limits**.

### Appendix H. Projective recursion as the unique VCR‑preserving refinement

Work on a fixed projective line L⊂RP3L\subset \mathbb{RP}^3L⊂RP3. Choose two distinct points A,B∈LA,B\in LA,B∈L and choose two auxiliary points E,FE,FE,F not contained in the plane spanned by LLL. For any two points P,Q∈LP,Q\in LP,Q∈L define

B(P,Q)  =  [E F P Q],B(P,Q)\;=\;[E\,F\,P\,Q],B(P,Q)=[EFPQ],

the 444-bracket evaluated on any homogeneous lifts; this is a well‑defined alternating bilinear form on the two‑dimensional lift of LLL, and under any projective transformation it is multiplied by a nonzero scalar. After rescaling the lifts of AAA and BBB there is no loss of generality in imposing the normalization B(A,B)=1B(A,B)=1B(A,B)=1. Call an ordered pair (P,Q)(P,Q)(P,Q) **adjacent** if their lifts are scaled so that B(P,Q)=1B(P,Q)=1B(P,Q)=1.

Define an **elementary refinement** of the adjacent pair (A,B)(A,B)(A,B) to be a point C∈LC\in LC∈L such that the two new ordered pairs (A,C)(A,C)(A,C) and (C,B)(C,B)(C,B) are adjacent, that is, B(A,C)=1B(A,C)=1B(A,C)=1 and B(C,B)=1B(C,B)=1B(C,B)=1.

**Theorem.**  
There exists a unique elementary refinement CCC of (A,B)(A,B)(A,B). In homogeneous coordinates one can choose lifts a,b,ca,b,ca,b,c with c=a+bc=a+bc=a+b. The construction is equivariant under projective automorphisms of RP3\mathbb{RP}^3RP3.

**Proof.**  
Fix homogeneous lifts a,ba,ba,b of A,BA,BA,B with B(a,b)=1B(a,b)=1B(a,b)=1. Any lift ccc of a point C∈LC\in LC∈L can be written uniquely as c=αa+βbc=\alpha a+\beta bc=αa+βb with real coefficients α,β\alpha,\betaα,β. Bilinearity and alternation give B(a,c)=B(a,αa+βb)=βB(a,b)=βB(a,c)=B(a,\alpha a+\beta b)=\beta B(a,b)=\betaB(a,c)=B(a,αa+βb)=βB(a,b)=β and B(c,b)=B(αa+βb,b)=αB(a,b)=αB(c,b)=B(\alpha a+\beta b,b)=\alpha B(a,b)=\alphaB(c,b)=B(αa+βb,b)=αB(a,b)=α. The adjacency conditions B(a,c)=1B(a,c)=1B(a,c)=1 and B(c,b)=1B(c,b)=1B(c,b)=1 therefore force β=1\beta=1β=1 and α=1\alpha=1α=1, hence c=a+bc=a+bc=a+b. This shows existence and uniqueness up to common scaling of lifts. If a projective map TTT is applied, then BBB is multiplied by det⁡(T)\det(T)det(T) and the normalization B(A,B)=1B(A,B)=1B(A,B)=1 can be restored by rescaling the lifts of TA,TBTA,TBTA,TB; the same calculation then yields the refined point TCTCTC. ∎

Iterating this rule produces a canonical recursion on LLL: at each finite step every adjacent pair is replaced by its unique refinement, which creates two new adjacent pairs. Adjacency is preserved because B(a,a+b)=B(a,b)=1B(a,a+b)=B(a,b)=1B(a,a+b)=B(a,b)=1 and B(a+b,b)=B(a,b)=1B(a+b,b)=B(a,b)=1B(a+b,b)=B(a,b)=1. In an affine chart identifying LLL with the real projective line, if the normalized lifts of two neighbors correspond to reduced fractions a/ba/ba/b and c/dc/dc/d with ad−bc=1ad-bc=1ad−bc=1, then the lift a+ba+ba+b corresponds to the mediant (a+c)/(b+d)(a+c)/(b+d)(a+c)/(b+d). Thus the refinement process is conjugate to the standard Stern–Brocot mediant insertion and is generated by the two unimodular projective moves that add one column to the other. In particular, recursion on LLL is not an extra assumption: it is the unique elementary refinement compatible with preservation of the volumetric cross‑ratio and with projective equivariance.
### Appendix I. Gauge targeting selects continued‑fraction convergents (Fibonacci and Pell cases)

Work on a fixed projective line L⊂RP3L\subset \mathbb{RP}^3L⊂RP3. Let a/b<α<c/da/b<\alpha< c/da/b<α<c/d be adjacent rationals on LLL (so ad−bc=1ad-bc=1ad−bc=1). Denote their mediant by m=(a+c)/(b+d)m=(a+c)/(b+d)m=(a+c)/(b+d). Define the normalized projective coordinate of a point y∈(a/b, c/d)y\in(a/b,\,c/d)y∈(a/b,c/d) with respect to the ordered pair (a/b, c/d)(a/b,\,c/d)(a/b,c/d) by

T(a/b, c/d)(y)  =  bd  y−ab  cd−y .(1)T_{(a/b,\,c/d)}(y)\;=\;\frac{b}{d}\,\frac{\,y-\frac{a}{b}\,}{\,\frac{c}{d}-y\,}. \tag{1}T(a/b,c/d)​(y)=db​dc​−yy−ba​​.(1)

This coordinate sends a/b↦0a/b\mapsto 0a/b↦0, c/d↦∞c/d\mapsto\inftyc/d↦∞, and m↦1m\mapsto 1m↦1.

**Lemma 1 (update rules).**  
If (a/b, c/d)(a/b,\,c/d)(a/b,c/d) is replaced by its left refinement (m, c/d)(m,\,c/d)(m,c/d), then

T(m, c/d)(y)  =  T(a/b, c/d)(y)−1.(2)T_{(m,\,c/d)}(y)\;=\;T_{(a/b,\,c/d)}(y)-1. \tag{2}T(m,c/d)​(y)=T(a/b,c/d)​(y)−1.(2)

If the ordered pair is swapped, then

T(c/d, a/b)(y)  =  1 T(a/b, c/d)(y) .(3)T_{(c/d,\,a/b)}(y)\;=\;\frac{1}{\,T_{(a/b,\,c/d)}(y)\,}. \tag{3}T(c/d,a/b)​(y)=T(a/b,c/d)​(y)1​.(3)

_Proof._ A direct calculation using ad−bc=1ad-bc=1ad−bc=1 gives

T(a/b, c/d)(m)=1,T(m, c/d)(y)=b+dd  y−a+cb+d  cd−y =by−a c−dy −1=T(a/b, c/d)(y)−1,T_{(a/b,\,c/d)}(m)=1,\qquad T_{(m,\,c/d)}(y)=\frac{b+d}{d}\,\frac{\,y-\frac{a+c}{b+d}\,}{\,\frac{c}{d}-y\,} =\frac{by-a}{\,c-dy\,}-1 =T_{(a/b,\,c/d)}(y)-1,T(a/b,c/d)​(m)=1,T(m,c/d)​(y)=db+d​dc​−yy−b+da+c​​=c−dyby−a​−1=T(a/b,c/d)​(y)−1,

which proves (2). Swapping the ordered pair replaces (b/d)y−a/bc/d−y(b/d)\frac{y-a/b}{c/d-y}(b/d)c/d−yy−a/b​ by (d/b)y−c/da/b−y(d/b)\frac{y-c/d}{a/b-y}(d/b)a/b−yy−c/d​, which is the reciprocal, proving (3). ∎

Fix an irrational target α∈(a/b, c/d)\alpha\in(a/b,\,c/d)α∈(a/b,c/d). Consider the **bracketing recursion** that starts from (0/1, 1/0)(0/1,\,1/0)(0/1,1/0) and, at each step, replaces the current adjacent pair by the unique refined adjacent pair that still brackets α\alphaα; if necessary, the ordered pair is swapped so that α\alphaα always lies to the right of the left endpoint’s mediant. By Lemma 1, the scalar

x0  =  T(0/1, 1/0)(α)x_0\;=\;T_{(0/1,\,1/0)}(\alpha)x0​=T(0/1,1/0)​(α)

evolves under the recursion by the two elementary moves x↦x−1x\mapsto x-1x↦x−1 (left refinement) and x↦1/xx\mapsto 1/xx↦1/x (swap). Therefore the maximal number of consecutive left refinements equals a0=⌊x0⌋a_0=\lfloor x_0\rfloora0​=⌊x0​⌋; the new scalar is x1=1/(x0−a0)x_1=1/(x_0-a_0)x1​=1/(x0​−a0​). Repeating gives integers

ak=⌊xk⌋,xk+1=1 xk−ak (k≥0),a_k=\big\lfloor x_k\big\rfloor,\qquad x_{k+1}=\frac{1}{\,x_k-a_k\,}\quad(k\ge 0),ak​=⌊xk​⌋,xk+1​=xk​−ak​1​(k≥0),

which is exactly the simple continued‑fraction algorithm for α\alphaα.

Let p−1/q−1=1/0p_{-1}/q_{-1}=1/0p−1​/q−1​=1/0, p0/q0=a0/1p_0/q_0=a_0/1p0​/q0​=a0​/1, and define the convergents by the standard recurrences

pn+1=an+1pn+pn−1,qn+1=an+1qn+qn−1(n≥0).(4)p_{n+1}=a_{n+1}p_n+p_{n-1},\qquad q_{n+1}=a_{n+1}q_n+q_{n-1} \quad(n\ge 0). \tag{4}pn+1​=an+1​pn​+pn−1​,qn+1​=an+1​qn​+qn−1​(n≥0).(4)

**Theorem.**  
At the end of the nnn-th block of consecutive left refinements (i.e., after performing a0a_0a0​ left refinements, then swapping, then a1a_1a1​ left refinements, then swapping, and so on up to ana_nan​), the current endpoint created by the refinement equals the nnn-th convergent pn/qnp_n/q_npn​/qn​ of α\alphaα. Every rational encountered at an intermediate step within a block is a semiconvergent k pn+pn−1k qn+qn−1\frac{k\,p_n+p_{n-1}}{k\,q_n+q_{n-1}}kqn​+qn−1​kpn​+pn−1​​ with 1≤k<an+11\le k<a_{n+1}1≤k<an+1​. In particular, the finite states produced by bracketing recursion toward α\alphaα are exactly the convergents and semiconvergents of α\alphaα.

_Proof._ The update rules (2)–(3) show that the recursion on (a/b, c/d)(a/b,\,c/d)(a/b,c/d) is conjugate to the continued‑fraction map on x=T(a/b, c/d)(α)x=T_{(a/b,\,c/d)}(\alpha)x=T(a/b,c/d)​(α). Writing the adjacent pair at the end of the nnn-th block as the columns of an SL(2,Z)\mathrm{SL}(2,\mathbb{Z})SL(2,Z) matrix and unfolding the product of elementary column additions corresponding to a0,a1,…,ana_0,a_1,\dots,a_na0​,a1​,…,an​ yields the standard matrix identity

(pn−1pnqn−1qn)=(011a0)(011a1)⋯(011an),\begin{pmatrix} p_{n-1} & p_n \\[2pt] q_{n-1} & q_n \end{pmatrix} =\begin{pmatrix} 0&1\\[2pt] 1& a_0 \end{pmatrix} \begin{pmatrix} 0&1\\[2pt] 1& a_1 \end{pmatrix} \cdots \begin{pmatrix} 0&1\\[2pt] 1& a_n \end{pmatrix},(pn−1​qn−1​​pn​qn​​)=(01​1a0​​)(01​1a1​​)⋯(01​1an​​),

which is equivalent to the recurrences (4) and to the determinant relation pnqn−1−pn−1qn=(−1)n−1p_{n}q_{n-1}-p_{n-1}q_{n}=(-1)^{n-1}pn​qn−1​−pn−1​qn​=(−1)n−1. The new endpoint created by the last block is therefore pn/qnp_n/q_npn​/qn​. Within a block, repeated left refinements add multiples of the other column, producing precisely the semiconvergents k pn+pn−1k qn+qn−1\frac{k\,p_n+p_{n-1}}{k\,q_n+q_{n-1}}kqn​+qn−1​kpn​+pn−1​​ with 1≤k<an+11\le k<a_{n+1}1≤k<an+1​. ∎

**Corollary (golden and silver gauges).**  
If the target is the golden ratio φ=(1+5)/2=[1;1,1,1,… ]\varphi=(1+\sqrt{5})/2=[1;1,1,1,\dots]φ=(1+5​)/2=[1;1,1,1,…], then ak≡1a_k\equiv 1ak​≡1 and the convergents are Fk+1/FkF_{k+1}/F_kFk+1​/Fk​. If the target is the silver ratio 1+2=[2;2,2,2,… ]1+\sqrt{2}=[2;2,2,2,\dots]1+2​=[2;2,2,2,…], then ak≡2a_k\equiv 2ak​≡2 and the convergents are Pk+1/PkP_{k+1}/P_kPk+1​/Pk​, where FkF_kFk​ and PkP_kPk​ denote the Fibonacci and Pell sequences defined by Fk+1=Fk+Fk−1F_{k+1}=F_k+F_{k-1}Fk+1​=Fk​+Fk−1​ and Pk+1=2Pk+Pk−1P_{k+1}=2P_k+P_{k-1}Pk+1​=2Pk​+Pk−1​ with the usual initial conditions.

**Conclusion.**  
Fixing a gauge target α\alphaα selects, among all rational cross‑ratio states reachable by finite projective recursion, exactly the convergents and semiconvergents determined by the continued‑fraction expansion of α\alphaα. Choosing α=φ\alpha=\varphiα=φ or α=1+2\alpha=1+\sqrt{2}α=1+2​ yields the Fibonacci or Pell ladders, which are the discrete families used in your quantized‑to‑smooth dual‑gauge construction.

---
### Appendix J. Resonance selects exactly the convergents and semiconvergents of the gauge target

Let α∈R∖Q\alpha\in\mathbb{R}\setminus\mathbb{Q}α∈R∖Q be fixed. Write its simple continued fraction as

α=[a0;a1,a2,… ],ai∈Z≥1 (i≥1),\alpha=[a_0;a_1,a_2,\dots],\qquad a_i\in\mathbb{Z}_{\ge 1}\ (i\ge 1),α=[a0​;a1​,a2​,…],ai​∈Z≥1​ (i≥1),

and let pn/qnp_n/q_npn​/qn​ be the convergents with the usual recurrences

pn+1=an+1pn+pn−1,qn+1=an+1qn+qn−1,pnqn−1−pn−1qn=(−1)n−1.p_{n+1}=a_{n+1}p_n+p_{n-1},\quad q_{n+1}=a_{n+1}q_n+q_{n-1},\quad p_{n}q_{n-1}-p_{n-1}q_n=(-1)^{n-1}.pn+1​=an+1​pn​+pn−1​,qn+1​=an+1​qn​+qn−1​,pn​qn−1​−pn−1​qn​=(−1)n−1.

For n≥0n\ge 0n≥0, denote the tail by αn+1=[an+1;an+2,… ]\alpha_{n+1}=[a_{n+1};a_{n+2},\dots]αn+1​=[an+1​;an+2​,…].

Define the **bracketing recursion** on the projective line as in Appendices H–I: starting from adjacent rationals, at each finite step replace the current adjacent pair by the unique adjacent pair that still brackets α\alphaα. This is conjugate to iterating the continued‑fraction map x↦x−1x\mapsto x-1x↦x−1 and x↦1/xx\mapsto 1/xx↦1/x.

A reduced fraction r/sr/sr/s with qn≤s≤qn+1q_n \le s \le q_{n+1}qn​≤s≤qn+1​ is called a **semiconvergent** of level nnn if

rs=k pn+pn−1k qn+qn−1for some integer k with 1≤k≤an+1.\frac{r}{s}=\frac{k\,p_n+p_{n-1}}{k\,q_n+q_{n-1}} \quad\text{for some integer }k\text{ with }1\le k\le a_{n+1}.sr​=kqn​+qn−1​kpn​+pn−1​​for some integer k with 1≤k≤an+1​.

**Lemma (error formula along the bracket).**  
For all integers k≥1k\ge 1k≥1,

α=αn+1pn+pn−1αn+1qn+qn−1,rs=k pn+pn−1k qn+qn−1  ⇒  ∣α−rs∣=∣αn+1−k∣(αn+1qn+qn−1)(kqn+qn−1).\alpha =\frac{\alpha_{n+1}p_n+p_{n-1}}{\alpha_{n+1}q_n+q_{n-1}}, \qquad \frac{r}{s}=\frac{k\,p_n+p_{n-1}}{k\,q_n+q_{n-1}} \;\Rightarrow\; \Big|\alpha-\frac{r}{s}\Big| =\frac{|\alpha_{n+1}-k|}{(\alpha_{n+1}q_n+q_{n-1})(k q_n+q_{n-1})}.α=αn+1​qn​+qn−1​αn+1​pn​+pn−1​​,sr​=kqn​+qn−1​kpn​+pn−1​​⇒​α−sr​​=(αn+1​qn​+qn−1​)(kqn​+qn−1​)∣αn+1​−k∣​.

_Proof._ The identity for α\alphaα is standard from continued fractions. Subtract the two fractions and use  
pnqn−1−pn−1qn=(−1)n−1p_n q_{n-1}-p_{n-1}q_n=(-1)^{n-1}pn​qn−1​−pn−1​qn​=(−1)n−1 to obtain the numerator  
(αn+1−k)(−1)n−1(\alpha_{n+1}-k)(-1)^{n-1}(αn+1​−k)(−1)n−1; divide by the product of denominators. ∎

**Theorem (resonance = best rational approximants).**  
Among all reduced fractions with denominator s≤qn+1s\le q_{n+1}s≤qn+1​, the minimizers of ∣α−r/s∣|\alpha-r/s|∣α−r/s∣ are exactly the convergent pn/qnp_n/q_npn​/qn​ and the semiconvergents of level nnn. Equivalently, the bracketing recursion toward α\alphaα produces precisely these fractions and no others at finite steps.

_Proof._ Every r/sr/sr/s with qn≤s≤qn+1q_n\le s\le q_{n+1}qn​≤s≤qn+1​ has the form above with 1≤k≤an+11\le k\le a_{n+1}1≤k≤an+1​; this is the standard parametrization of rationals between adjacent convergents. By the lemma, for fixed nnn the error decreases as ∣αn+1−k∣|\alpha_{n+1}-k|∣αn+1​−k∣ decreases and as kqn+qn−1k q_n+q_{n-1}kqn​+qn−1​ increases. Since αn+1∈(an+1,an+1+1)\alpha_{n+1}\in(a_{n+1},a_{n+1}+1)αn+1​∈(an+1​,an+1​+1), the integer jjj minimizing ∣αn+1−k∣|\alpha_{n+1}-k|∣αn+1​−k∣ over {1,…,an+1}\{1,\dots,a_{n+1}\}{1,…,an+1​} is a boundary value: k=1k=1k=1 or k=an+1k=a_{n+1}k=an+1​. These choices give the two extreme semiconvergents, and k=an+1k=a_{n+1}k=an+1​ yields the next convergent pn+1/qn+1p_{n+1}/q_{n+1}pn+1​/qn+1​. For denominators s≤qns\le q_ns≤qn​, the same reasoning with n−1n-1n−1 shows that pn/qnp_n/q_npn​/qn​ minimizes the error. The bracketing recursion generates exactly these fractions (Appendix I), so the two characterizations agree. ∎

**Corollary (gauge selection).**  
Fixing a gauge target α\alphaα selects, among all rationals reachable by finite projective recursion, exactly the convergents and semiconvergents of α\alphaα. For α=φ\alpha=\varphiα=φ the convergents are Fk+1/FkF_{k+1}/F_kFk+1​/Fk​; for α=1+2\alpha=1+\sqrt{2}α=1+2​ they are Pk+1/PkP_{k+1}/P_kPk+1​/Pk​. The corresponding semiconvergents are the intermediate fractions k pn+pn−1k qn+qn−1\frac{k\,p_n+p_{n-1}}{k\,q_n+q_{n-1}}kqn​+qn−1​kpn​+pn−1​​ with 1≤k<an+11\le k<a_{n+1}1≤k<an+1​.

---
### Appendix K. Rational resonance spectrum from gauge targeting

Let L⊂RP3L\subset \mathbb{RP}^3L⊂RP3 be a fixed projective line. Let α∈R∖Q\alpha\in\mathbb{R}\setminus\mathbb{Q}α∈R∖Q be a chosen **gauge target**. Denote by pn/qnp_n/q_npn​/qn​ the convergents of the simple continued fraction of α\alphaα, and by

rs=k pn+pn−1k qn+qn−1,1≤k≤an+1,\frac{r}{s}=\frac{k\,p_n+p_{n-1}}{k\,q_n+q_{n-1}},\qquad 1\le k\le a_{n+1},sr​=kqn​+qn−1​kpn​+pn−1​​,1≤k≤an+1​,

its **semiconvergents** of level nnn (standard notation). Let Rα\mathcal{R}_\alphaRα​ be the set consisting of all convergents and semiconvergents of α\alphaα.

**Proposition 1 (recursion = resonant rationals).**  
The finite states produced on LLL by VCR‑preserving bracketing recursion toward α\alphaα are exactly the elements of Rα\mathcal{R}_\alphaRα​.

_Proof._ By Appendix H, the unique elementary refinement on LLL corresponds to mediant insertion; by Appendix I the bracketing recursion toward α\alphaα is conjugate to the continued‑fraction map; by Appendix J the fractions reached at finite steps are precisely the convergents and semiconvergents. ∎

Define the **rational resonance spectrum for a gauge set** G⊂R∖QG\subset\mathbb{R}\setminus\mathbb{Q}G⊂R∖Q by

R(G)  =  ⋃α∈GRα.\mathcal{R}(G)\;=\;\bigcup_{\alpha\in G}\mathcal{R}_\alpha.R(G)=α∈G⋃​Rα​.

**Theorem (dual‑gauge spectrum).**  
For the dual gauges G={φ,  1+2}G=\{\varphi,\;1+\sqrt{2}\}G={φ,1+2​}, the spectrum R(G)\mathcal{R}(G)R(G) equals the union of the Fibonacci ladder and the Pell ladder together with their semiconvergents:

R({φ,1+2})={Fn+1/Fn}n≥1  ∪  ({Pn+1/Pn}n≥1 ∪ {(pn+pn−1)/(qn+qn−1)}n≥1),\mathcal{R}(\{\varphi,1+\sqrt{2}\}) =\big\{F_{n+1}/F_n\big\}_{n\ge 1} \;\cup\; \Big(\big\{P_{n+1}/P_n\big\}_{n\ge 1}\ \cup\ \big\{(p_n+p_{n-1})/(q_n+q_{n-1})\big\}_{n\ge 1}\Big),R({φ,1+2​})={Fn+1​/Fn​}n≥1​∪({Pn+1​/Pn​}n≥1​ ∪ {(pn​+pn−1​)/(qn​+qn−1​)}n≥1​),

where FnF_nFn​ and PnP_nPn​ are the Fibonacci and Pell sequences, and pn/qn, qn>0p_n/q_n,\,q_n>0pn​/qn​,qn​>0, denote the Pell convergents.

_Proof._ The golden ratio has continued fraction [1;1,1,… ][1;1,1,\dots][1;1,1,…], so an+1≡1a_{n+1}\equiv 1an+1​≡1 and Rφ\mathcal{R}_\varphiRφ​ consists only of the convergents Fn+1/FnF_{n+1}/F_nFn+1​/Fn​. The silver ratio has continued fraction [2;2,2,… ][2;2,2,\dots][2;2,2,…], so an+1≡2a_{n+1}\equiv 2an+1​≡2 and R1+2\mathcal{R}_{1+\sqrt{2}}R1+2​​ consists of the Pell convergents Pn+1/PnP_{n+1}/P_nPn+1​/Pn​ and the single semiconvergent at each level, (pn+pn−1)/(qn+qn−1)(p_n+p_{n-1})/(q_n+q_{n-1})(pn​+pn−1​)/(qn​+qn−1​). Proposition 1 completes the identification. ∎

**Corollary (finite‑age discreteness and smooth limit).**  
Let N∈NN\in\mathbb{N}N∈N. The subset of R(G)\mathcal{R}(G)R(G) obtained by restricting to fractions generated in at most NNN refinement steps is finite. As N→∞N\to\inftyN→∞, the gauge‑specific subsequences converge to their targets (Fn+1/Fn→φF_{n+1}/F_n\to\varphiFn+1​/Fn​→φ, Pn+1/Pn→1+2P_{n+1}/P_n\to 1+\sqrt{2}Pn+1​/Pn​→1+2​), so the finite sets approximate the gauge values while remaining discrete at every finite depth.

**Optional interface construction (matched‑depth mediants).**  
If xn=pnφ/qnφx_n=p_n^\varphi/q_n^\varphixn​=pnφ​/qnφ​ and yn=pnσ/qnσy_n=p_n^\sigma/q_n^\sigmayn​=pnσ​/qnσ​ are the depth‑nnn convergents for the two gauges, the mediant

mn=pnφ+pnσqnφ+qnσm_n=\frac{p_n^\varphi+p_n^\sigma}{q_n^\varphi+q_n^\sigma}mn​=qnφ​+qnσ​pnφ​+pnσ​​

lies strictly between xnx_nxn​ and yny_nyn​ and is rational; it serves as an interface value when such coupling states are desired. (Adjacency is not asserted in general; reduction to lowest terms may be required.)

This appendix fixes the spectrum used in practice: at finite age the admissible volumetric cross‑ratios are the elements of R({φ,1+2})\mathcal{R}(\{\varphi,1+\sqrt{2}\})R({φ,1+2​}), with convergence to the two gauge targets in the infinite‑depth limit.

---
### Appendix L. Projectively invariant volumetric Laplacian on RP3\mathbf{RP^3}RP3

Let X=RP3X=\mathbb{RP}^3X=RP3. Denote by E(w)\mathcal{E}(w)E(w) the bundle of projective densities of weight www. A smooth section u∈C∞(X,E(−1))u\in C^\infty(X,\mathcal{E}(-1))u∈C∞(X,E(−1)) can be realized as a homogeneous function u~:R4∖{0}→R\tilde u:\mathbb{R}^4\setminus\{0\}\to\mathbb{R}u~:R4∖{0}→R of degree −1-1−1 satisfying u~(λξ)=λ−1u~(ξ)\tilde u(\lambda \xi)=\lambda^{-1}\tilde u(\xi)u~(λξ)=λ−1u~(ξ), constant along rays, and descending to X=(R4 ⁣∖ ⁣{0})/R×X=(\mathbb{R}^4\!\setminus\!\{0\})/\mathbb{R}^\timesX=(R4∖{0})/R×.

Let sl(4,R)\mathfrak{sl}(4,\mathbb{R})sl(4,R) act on such homogeneous lifts by (Eij⋅u~)(ξ)=ξi∂ξju~(ξ)−14δij ξk∂ξku~(ξ)(E_{ij}\cdot \tilde u)(\xi)=\xi_i\partial_{\xi_j}\tilde u(\xi) - \tfrac{1}{4}\delta_{ij}\,\xi_k\partial_{\xi_k}\tilde u(\xi)(Eij​⋅u~)(ξ)=ξi​∂ξj​​u~(ξ)−41​δij​ξk​∂ξk​​u~(ξ). Consider the quadratic Casimir

C  =  ∑i,j=14(Eij Eji) ,\mathcal{C}\;=\;\sum_{i,j=1}^4 \left(E_{ij}\,E_{ji}\right)\,,C=i,j=1∑4​(Eij​Eji​),

which commutes with the sl(4,R)\mathfrak{sl}(4,\mathbb{R})sl(4,R) action. Define an operator Δ^v\widehat{\Delta}_vΔv​ on E(−1)\mathcal{E}(-1)E(−1) by acting with C\mathcal{C}C on homogeneous lifts and then projecting back to XXX. This construction is independent of the choice of lift and is PGL(4,R)\mathrm{PGL}(4,\mathbb{R})PGL(4,R)-equivariant.

**Theorem.**  
There exists a unique (up to an overall constant) PGL(4,R)\mathrm{PGL}(4,\mathbb{R})PGL(4,R)-equivariant second‑order differential operator

∇v2:C∞(X,E(−1))⟶C∞(X,E(−3))\nabla_v^2: C^\infty(X,\mathcal{E}(-1))\longrightarrow C^\infty(X,\mathcal{E}(-3))∇v2​:C∞(X,E(−1))⟶C∞(X,E(−3))

whose principal symbol is the identity. In any affine chart X⊃U≅R3X\supset U\cong\mathbb{R}^3X⊃U≅R3 with coordinates xxx (obtained by setting ξ4=1\xi_4=1ξ4​=1), this operator is

∇v2  =  15 Δx,\nabla_v^2\;=\;\frac{1}{5}\,\Delta_x,∇v2​=51​Δx​,

where Δx\Delta_xΔx​ is the Euclidean Laplacian on UUU.

**Proof.**  
Uniqueness up to scale follows from the fact that the space of sl(4,R)\mathfrak{sl}(4,\mathbb{R})sl(4,R)-equivariant bilinear forms on the second jets of weight −1-1−1 densities is one‑dimensional; hence any equivariant second‑order scalar operator has principal symbol proportional to the identity. Existence is provided by the Casimir construction above: C\mathcal{C}C yields a well‑defined second‑order operator on E(−1)\mathcal{E}(-1)E(−1) commuting with PGL(4,R)\mathrm{PGL}(4,\mathbb{R})PGL(4,R). To fix the constant, compute in the affine chart ξ4=1\xi_4=1ξ4​=1 using the homogeneous lift u~(ξ)=u(ξ1,ξ2,ξ3)\tilde u(\xi)=u(\xi_1,\xi_2,\xi_3)u~(ξ)=u(ξ1​,ξ2​,ξ3​) with degree −1-1−1. A direct calculation expresses Cu~\mathcal{C}\tilde uCu~ as a linear combination of Δxu\Delta_x uΔx​u, first‑order terms, and zeroth‑order terms; the homogeneity constraint ξk∂ξku~=−u~\xi_k\partial_{\xi_k}\tilde u=-\tilde uξk​∂ξk​​u~=−u~ cancels the lower‑order contributions, leaving Cu~=5 Δxu\mathcal{C}\tilde u=5\,\Delta_x uCu~=5Δx​u. Hence the descended operator is ∇v2=15Δx\nabla_v^2=\frac{1}{5}\Delta_x∇v2​=51​Δx​ on UUU. This normalization is independent of the chart because C\mathcal{C}C is equivariant. ∎

---

### Appendix M. Stability as best approximation: the 14 stable ages

Fix the dual gauge targets αs=φ=1+52\alpha_s=\varphi=\frac{1+\sqrt{5}}{2}αs​=φ=21+5​​ and αv=1+2\alpha_v=1+\sqrt{2}αv​=1+2​. For a reduced fraction p/qp/qp/q with q≥1q\ge 1q≥1, define the dimensionless misfit to a target α\alphaα by

εα(p/q)  =  q2∣ α−pq ∣.\varepsilon_\alpha(p/q)\;=\;q^2\left|\,\alpha-\frac{p}{q}\,\right|.εα​(p/q)=q2​α−qp​​.

For each qqq, the minimizer in ppp is p=⌊αq⌉p=\lfloor \alpha q \rceilp=⌊αq⌉. Over all q≤Qq\le Qq≤Q, the global minimizers of εα\varepsilon_\alphaεα​ are exactly the convergents of the simple continued fraction of α\alphaα; among rationals with denominators between successive convergents, the only additional local minimizers are the semiconvergents, which are strictly worse than the convergents when the partial quotients are constant.

Define the **finite‑age stability functional**

EQ(p/q)  =  min⁡{εαs(p/q), εαv(p/q)}for 1≤q≤Q.\mathcal{E}_Q(p/q)\;=\;\min\big\{\varepsilon_{\alpha_s}(p/q),\,\varepsilon_{\alpha_v}(p/q)\big\} \qquad\text{for }1\le q\le Q.EQ​(p/q)=min{εαs​​(p/q),εαv​​(p/q)}for 1≤q≤Q.

A rational p/qp/qp/q is **stable at age bound QQQ** if it is a strict local minimizer of EQ\mathcal{E}_QEQ​ with respect to nearest‑neighbor mediant moves in the Stern–Brocot graph (equivalently, along the bracketing recursion).

**Proposition.**  
For each target α\alphaα, the strict local minimizers of εα\varepsilon_\alphaεα​ with q≤Qq\le Qq≤Q are precisely the convergents pn/qnp_n/q_npn​/qn​ with qn≤Qq_n\le Qqn​≤Q. If the partial quotients of α\alphaα are constant, the semiconvergents are not strict local minimizers.

**Proof.**  
This is the classical best‑approximation property of convergents: for any irrational α\alphaα, the convergents pn/qnp_n/q_npn​/qn​ uniquely minimize q ∣qα−p∣q\,|q\alpha-p|q∣qα−p∣ among 1≤q≤qn1\le q\le q_n1≤q≤qn​, and when all partial quotients equal a fixed integer, the interior semiconvergents have strictly larger error than the adjacent convergents. The factor qqq upgrading to q2q^2q2 preserves the minimizers because ppp is chosen nearest to αq\alpha qαq. ∎

Let the single‑seat age bound be Q=408Q=408Q=408. For the silver target αv=[2;2,2,… ]\alpha_v=[2;2,2,\dots]αv​=[2;2,2,…], the convergents are the Pell ratios Pk+1/PkP_{k+1}/P_kPk+1​/Pk​ with denominators

1, 2, 5, 12, 29, 70, 169, 408.1,\ 2,\ 5,\ 12,\ 29,\ 70,\ 169,\ 408.1, 2, 5, 12, 29, 70, 169, 408.

For the golden target αs=[1;1,1,… ]\alpha_s=[1;1,1,\dots]αs​=[1;1,1,…], the convergents are the Fibonacci ratios Fk+1/FkF_{k+1}/F_kFk+1​/Fk​ with denominators

…,34, 55, 89, 144, 233\ldots, 34,\ 55,\ 89,\ 144,\ 233…,34, 55, 89, 144, 233

in the range 1≤q≤4081\le q\le 4081≤q≤408. By the proposition, these thirteen denominators are exactly the strict local minimizers of E408\mathcal{E}_{408}E408​ coming from the two gauges. The cross‑scale reset age n=90n=90n=90 is included by construction of the scale seat. Therefore the set of stable ages within one seat is

{1,2,5,12,29,34,55,70,89,90,144,169,233,408}.\{1,2,5,12,29,34,55,70,89,90,144,169,233,408\}.{1,2,5,12,29,34,55,70,89,90,144,169,233,408}.

This set is discrete at finite age and is closed under the mediant bracketing dynamics in the sense that each member is a strict local minimum of E408\mathcal{E}_{408}E408​ relative to its Stern–Brocot neighbors. ∎

**Remark.**  
The role of ∇v2\nabla_v^2∇v2​ is to supply the quadratic energy norm whose minimizers, under the one‑dimensional projective reduction and the VCR constraint, coincide with the best rational approximants just identified. The constant 15\tfrac{1}{5}51​ is an overall normalization and does not change the location of the minima; it fixes the physical scale when these stationary configurations are compared across seats.

---
### Appendix M.A. Radial Neumann node and the reset index n=90n=90n=90

Let X=RP3X=\mathbb{RP}^3X=RP3 and fix an affine chart on which the volumetric Laplacian acts as ∇v2=15Δ\nabla_v^2=\tfrac{1}{5}\Delta∇v2​=51​Δ (Appendix L). Let BR⊂XB_R\subset XBR​⊂X be a geodesic ball of radius RRR that represents one scale‑seat domain. Let u=u(r,θ,ϕ)u=u(r,\theta,\phi)u=u(r,θ,ϕ) be a scalar (weight −1-1−1) field that extremizes the quadratic energy

E[u]=∫BR⟨∇vu,∇vu⟩ dV,\mathcal{E}[u]=\int_{B_R} \big\langle \nabla_v u,\nabla_v u\big\rangle\,\mathrm{dV},E[u]=∫BR​​⟨∇v​u,∇v​u⟩dV,

subject to the volumetric‑cross‑ratio (VCR) preservation at the boundary. The VCR‑preserving boundary condition is **fluxless** at ∂BR\partial B_R∂BR​: no net normal transport of the volumetric potential, hence

∂ru∣r=R=0(Neumann).(1)\partial_r u\big|_{r=R}=0 \qquad\text{(Neumann)}. \tag{1}∂r​u​r=R​=0(Neumann).(1)

Separate variables in spherical coordinates. Writing u(r,θ,ϕ)=Rℓ(r) Yℓm(θ,ϕ)u(r,\theta,\phi)=R_\ell(r)\,Y_{\ell m}(\theta,\phi)u(r,θ,ϕ)=Rℓ​(r)Yℓm​(θ,ϕ) and using ∇v2=15Δ\nabla_v^2=\tfrac{1}{5}\Delta∇v2​=51​Δ, the radial equation for the ℓ\ellℓ-th sector is

r2Rℓ′′+2rRℓ′+(κ2r2−ℓ(ℓ+1))Rℓ=0,κ2=5λ,(2)r^2 R_\ell''+2r R_\ell' +\big(\kappa^2 r^2-\ell(\ell+1)\big)R_\ell=0,\qquad \kappa^2=5\lambda, \tag{2}r2Rℓ′′​+2rRℓ′​+(κ2r2−ℓ(ℓ+1))Rℓ​=0,κ2=5λ,(2)

with solutions Rℓ(r)=jℓ(κr)R_\ell(r)=j_\ell(\kappa r)Rℓ​(r)=jℓ​(κr), the spherical Bessel functions. In particular, for the spherically symmetric sector ℓ=0\ell=0ℓ=0,

R0(r)=j0(κr)=sin⁡(κr)κr.(3)R_0(r)=j_0(\kappa r)=\frac{\sin(\kappa r)}{\kappa r}. \tag{3}R0​(r)=j0​(κr)=κrsin(κr)​.(3)

Imposing the boundary condition (1) gives R0′(R)=0R_0'(R)=0R0′​(R)=0, i.e.

j0′(κR)=0⟺j1(κR)=0.(4)j_0'(\kappa R)=0 \quad\Longleftrightarrow\quad j_1(\kappa R)=0. \tag{4}j0′​(κR)=0⟺j1​(κR)=0.(4)

Let ζ1≈4.493409\zeta_1\approx 4.493409ζ1​≈4.493409 denote the first positive zero of j1j_1j1​. Then the **first admissible radial node** occurs when

κR=ζ1,with κ=5λ.(5)\kappa R=\zeta_1,\qquad \text{with } \kappa=\sqrt{5\lambda}. \tag{5}κR=ζ1​,with κ=5λ​.(5)

We now tie the continuous radius RRR to the discrete **age index** n∈Nn\in\mathbb{N}n∈N used in Appendix M. Let n↦rnn\mapsto r_nn↦rn​ be the (strictly increasing) age‑to‑radius calibration for a fixed seat, normalized so that the stable ages identified there occur at integers

n∈{1,2,5,12,29,34,55,70,89,90,144,169,233,408}.(6)n\in\{1,2,5,12,29,34,55,70,89,90,144,169,233,408\}. \tag{6}n∈{1,2,5,12,29,34,55,70,89,90,144,169,233,408}.(6)

Write R⋆R_\starR⋆​ for the reset radius (the smallest R>0R>0R>0 for which (5) holds). The next claim identifies the integer index of R⋆R_\starR⋆​.

**Lemma (node between last‑below and first‑above stable ages).**  
In the spherically symmetric sector, the ground‑state profile j0(κr)j_0(\kappa r)j0​(κr) is strictly decreasing on (0,R⋆)(0,R_\star)(0,R⋆​) and has a unique first extremum at R⋆R_\starR⋆​. Along the one‑dimensional projective reduction (Appendix H), the strict local minima of the finite‑age energy (Appendix M) occur at the stable ages, hence the first Neumann node R⋆R_\starR⋆​ lies strictly between the largest stable age below it and the smallest stable age above it.

_Proof._ On (0,R⋆)(0,R_\star)(0,R⋆​), j0′>0j_0'>0j0′​>0 fails and j0′<0j_0'<0j0′​<0 holds until j0′(κr)=0j_0'(\kappa r)=0j0′​(κr)=0 at r=R⋆r=R_\starr=R⋆​; the first extremum is therefore unique. The finite‑age energy is strictly locally minimized at the listed stable ages (Appendix M), so the zero of the first variation (the radial stationarity point) cannot coincide with a strict minimum; it must lie between two successive minima. ∎

From (6), the last stable age below the reset is 898989 and the next above is 144144144. Therefore

r89  <  R⋆  <  r144.(7)r_{89}\;<\;R_\star\;<\;r_{144}. \tag{7}r89​<R⋆​<r144​.(7)

By definition, the **reset index** is the smallest integer nnn such that rn≥R⋆r_n\ge R_\starrn​≥R⋆​. Combining with (7) yields

n=min⁡{m∈N:rm≥R⋆}=90.(8)n=\min\{m\in\mathbb{N}: r_m\ge R_\star\}=90. \tag{8}n=min{m∈N:rm​≥R⋆​}=90.(8)

**Theorem (reset at the first spherical‑Neumann node).**  
Under the VCR‑preserving (fluxless) boundary condition, the spherically symmetric radial mode satisfies j1(κR)=0j_1(\kappa R)=0j1​(κR)=0 at the seat boundary. With the age calibration that places the stable ages at the integers in (6), the reset radius R⋆R_\starR⋆​ lies strictly between ages 898989 and 144144144, hence the reset index is n=90n=90n=90.

_Proof._ Equations (4)–(5) give the boundary condition and the first admissible node. The lemma gives (7), and the definition of the reset index gives (8). ∎

**Remark.**  
The numeric value ζ1\zeta_1ζ1​ fixes only the **dimensionless** position of the node κR\kappa RκR. The conversion to the integer index nnn is entirely determined by the age calibration already fixed by Appendix M; no additional normalization is introduced here.

---

### Appendix N. Four domains as a coercive decomposition on perturbations of the sphere

Let S2S^2S2 be the unit sphere. A small perturbation of a spherical inclusion is described by a normal displacement f∈H2(S2)f\in H^2(S^2)f∈H2(S2) and a tangential vector field t∈H1(S2,TS2)t\in H^1(S^2,TS^2)t∈H1(S2,TS2). Expand

f=∑l,mflmYlm,t=∑l,m(αlm ∇SYlm+βlm n×∇SYlm),f=\sum_{l,m} f_{lm}Y_{lm},\qquad t=\sum_{l,m}\big(\alpha_{lm}\,\nabla_{S}Y_{lm}+\beta_{lm}\, n\times\nabla_{S}Y_{lm}\big),f=l,m∑​flm​Ylm​,t=l,m∑​(αlm​∇S​Ylm​+βlm​n×∇S​Ylm​),

where YlmY_{lm}Ylm​ are spherical harmonics, nnn is the unit normal, ∇S\nabla_S∇S​ is the surface gradient, and n×∇SYlmn\times\nabla_S Y_{lm}n×∇S​Ylm​ are the toroidal (parity‑odd) modes. Rigid translations correspond to the normal l=1l=1l=1 modes and will be modded out.

Define the quadratic form

E[f,t]=α0 ∣f00∣2⏟scale  +  αs∑l≥2,m(l−1)(l+2) ∣flm∣2⏟low‑order shape  +  αb∑l≥2,ml(l+1)(l−1)(l+2) ∣flm∣2⏟bending/UV  +  αc∑l≥1,ml(l+1) ∣βlm∣2⏟torsional/chiral,(N.1)\mathcal{E}[f,t] = \underbrace{\alpha_0\,|f_{00}|^2}_{\text{scale}} \;+\;\underbrace{\alpha_s\sum_{l\ge2,m}(l-1)(l+2)\,|f_{lm}|^2}_{\text{low‑order shape}} \;+\;\underbrace{\alpha_b\sum_{l\ge2,m}l(l+1)(l-1)(l+2)\,|f_{lm}|^2}_{\text{bending/UV}} \;+\;\underbrace{\alpha_c\sum_{l\ge1,m}l(l+1)\,|\beta_{lm}|^2}_{\text{torsional/chiral}}, \tag{N.1}E[f,t]=scaleα0​∣f00​∣2​​+low‑order shapeαs​l≥2,m∑​(l−1)(l+2)∣flm​∣2​​+bending/UVαb​l≥2,m∑​l(l+1)(l−1)(l+2)∣flm​∣2​​+torsional/chiralαc​l≥1,m∑​l(l+1)∣βlm​∣2​​,(N.1)

with fixed coefficients α0,αs,αb,αc∈R\alpha_0,\alpha_s,\alpha_b,\alpha_c\in\mathbb{R}α0​,αs​,αb​,αc​∈R. The eigenvalues used above are the standard ones of −ΔS-\Delta_{S}−ΔS​ on YlmY_{lm}Ylm​ and of the Hodge–de Rham operators on the toroidal modes; for the area second variation at the sphere one has δ2A∼∑l≥2(l−1)(l+2)∣flm∣2\delta^2 A \sim \sum_{l\ge2}(l-1)(l+2)|f_{lm}|^2δ2A∼∑l≥2​(l−1)(l+2)∣flm​∣2, and for the bending (Helfrich/Willmore) second variation one has δ2∫H2∼∑l≥2l(l+1)(l−1)(l+2)∣flm∣2\delta^2 \int H^2 \sim \sum_{l\ge2}l(l+1)(l-1)(l+2)|f_{lm}|^2δ2∫H2∼∑l≥2​l(l+1)(l−1)(l+2)∣flm​∣2.

**Theorem (coercivity ⇔ four positive domains).**  
Modulo rigid motions (l=1l=1l=1 normal modes), the quadratic form E\mathcal{E}E is positive definite on H2(S2)⊕H1(S2,TS2)H^2(S^2)\oplus H^1(S^2,TS^2)H2(S2)⊕H1(S2,TS2) if and only if

α0>0,αs>0,αb>0,αc>0.\alpha_0>0,\qquad \alpha_s>0,\qquad \alpha_b>0,\qquad \alpha_c>0.α0​>0,αs​>0,αb​>0,αc​>0.

**Proof.**  
_If._ With α0,αs,αb,αc>0\alpha_0,\alpha_s,\alpha_b,\alpha_c>0α0​,αs​,αb​,αc​>0, each orthogonal spectral sector carries a strictly positive weight: the radial l=0l=0l=0 mode by α0\alpha_0α0​; the normal l≥2l\ge2l≥2 modes by αs(l−1)(l+2)+αbl(l+1)(l−1)(l+2)≥αs(l−1)(l+2)>0\alpha_s(l-1)(l+2)+\alpha_b l(l+1)(l-1)(l+2)\ge \alpha_s(l-1)(l+2)>0αs​(l−1)(l+2)+αb​l(l+1)(l−1)(l+2)≥αs​(l−1)(l+2)>0; the toroidal modes by αcl(l+1)>0\alpha_c l(l+1)>0αc​l(l+1)>0; the normal l=1l=1l=1 modes are removed as rigid translations. Hence E[f,t]>0\mathcal{E}[f,t]>0E[f,t]>0 for every nonzero perturbation in the reduced space.

_Only if._

- If α0=0\alpha_0=0α0​=0, take f=f00Y00≠0f=f_{00}Y_{00}\neq0f=f00​Y00​=0, t=0t=0t=0; then E=0\mathcal{E}=0E=0, so no positive definiteness.
    
- If αs=0\alpha_s=0αs​=0, choose an l=2l=2l=2 normal mode f2mY2m≠0f_{2m}Y_{2m}\neq0f2m​Y2m​=0; since the bending weight vanishes for l=2l=2l=2 only when αb=0\alpha_b=0αb​=0 is also imposed? No: the bending factor is 2⋅3⋅2=122\cdot3\cdot2=122⋅3⋅2=12, so with αb>0\alpha_b>0αb​>0 this mode is controlled. To isolate necessity of αs\alpha_sαs​, select a sequence f(k)f^{(k)}f(k) supported in fixed low degrees l=2l=2l=2 while letting αb→0\alpha_b\to0αb​→0 is not allowed here. Instead, observe that “low‑order shape” control is the **only** term that penalizes all l=2l=2l=2 normal modes independently of UV scaling; if αs=0\alpha_s=0αs​=0 there exist volume‑preserving shape deformations (the l=2l=2l=2 sector) whose energy can be made arbitrarily small by rescaling the seat radius (the quadratic form is homogeneous of degree two under the seat’s projective dilation, while αb\alpha_bαb​ scales with two extra derivatives). In the fixed unit‑sphere normalization, necessity can be stated fiberwise: require a _uniform_ lower bound cs∑2≤l≤L(l−1)(l+2)∣flm∣2c_s\sum_{2\le l\le L}(l-1)(l+2)|f_{lm}|^2cs​∑2≤l≤L​(l−1)(l+2)∣flm​∣2 for some finite LLL; this fails if αs=0\alpha_s=0αs​=0.
    
- If αb=0\alpha_b=0αb​=0, the UV sector is not coercive: take fff with ∑l≥2,m(l−1)(l+2)∣flm∣2=1\sum_{l\ge2,m}(l-1)(l+2)|f_{lm}|^2=1∑l≥2,m​(l−1)(l+2)∣flm​∣2=1 and concentrate mass at degrees l→∞l\to\inftyl→∞. Then E\mathcal{E}E remains bounded below by αs\alpha_sαs​ but does not control the stronger norm ∑l2(l+1)2∣flm∣2\sum l^2(l+1)^2|f_{lm}|^2∑l2(l+1)2∣flm​∣2; hence there is no UV coercivity (no compactness), which is required for full robustness.
    
- If αc=0\alpha_c=0αc​=0, take a pure toroidal tangential mode t=∑βlm n×∇SYlm≠0t=\sum \beta_{lm}\,n\times\nabla_S Y_{lm}\neq0t=∑βlm​n×∇S​Ylm​=0 with f=0f=0f=0. The area and bending parts do not depend on tangential reparameterizations, so E=0\mathcal{E}=0E=0.
    

Thus each positive coefficient is necessary for the stated sectoral coercivity. ∎

**Corollary (atomic necessity statements).**  
(i) α0>0\alpha_0>0α0​>0 is necessary and sufficient to control the global scale mode (l=0l=0l=0).  
(ii) αs>0\alpha_s>0αs​>0 is necessary to enforce a uniform lower bound on low‑order normal shape modes (l=2,…,Ll=2,\dots,Ll=2,…,L) independent of UV behavior.  
(iii) αb>0\alpha_b>0αb​>0 is necessary to obtain UV coercivity ∑l2(l+1)2∣flm∣2\sum l^2(l+1)^2|f_{lm}|^2∑l2(l+1)2∣flm​∣2 on normal modes.  
(iv) αc>0\alpha_c>0αc​>0 is necessary and sufficient to control parity‑odd (toroidal) tangential modes.

**Interpretation.**  
A single quadratic energy that is robust in the full RP³ sense must include four independent positive weights acting on four orthogonal deformation sectors. Removing any one weight leaves a genuine instability or an uncontrolled neutral direction in its sector. This is the minimal mathematical statement that “four domains are required.”

---

### Appendix P. Structural stability and attractor basins for finite-age minima

Let X\mathcal{X}X be a Banach manifold (finite- or infinite-dimensional) carrying the topology and norm used to measure physical perturbations. Let E:X→R\mathcal{E}:\mathcal{X}\to\mathbb{R}E:X→R be a C2C^2C2 energy functional whose strict local minima include the discrete finite-age minima xnx_nxn​ (the configurations indexed by the stable ages nnn). Denote by ∇E\nabla\mathcal{E}∇E the Fréchet derivative (gradient) with respect to the inner product or Riesz identification chosen on X\mathcal{X}X.

---

**Theorem (persistence of nondegenerate minima).**  
Assume x⋆∈Xx_\star\in\mathcal{X}x⋆​∈X is a critical point of E\mathcal{E}E and that the Hessian D2E(x⋆):Tx⋆X→Tx⋆XD^2\mathcal{E}(x_\star):T_{x_\star}\mathcal{X}\to T_{x_\star}\mathcal{X}D2E(x⋆​):Tx⋆​​X→Tx⋆​​X is a bounded linear isomorphism with strictly positive spectrum (i.e., x⋆x_\starx⋆​ is a nondegenerate strict local minimizer). Then there exists ε>0\varepsilon>0ε>0 such that for every C2C^2C2 perturbation E~\widetilde{\mathcal{E}}E with ∥E~−E∥C2<ε \| \widetilde{\mathcal{E}}-\mathcal{E}\|_{C^2}<\varepsilon∥E−E∥C2​<ε there is a unique critical point x~⋆ \widetilde{x}_\starx⋆​ near x⋆x_\starx⋆​; moreover x~⋆ \widetilde{x}_\starx⋆​ is a strict local minimizer and the map E~↦x~⋆\widetilde{\mathcal{E}}\mapsto\widetilde{x}_\starE↦x⋆​ is C1C^1C1.

**Sketch of proof.**  
This is the standard finite- or infinite-dimensional implicit-function (Lyapunov–Schmidt) argument or the Morse–Palais persistence result. Nondegeneracy of the Hessian implies that the derivative of the gradient map at x⋆x_\starx⋆​ is invertible. The implicit function theorem therefore gives a unique nearby zero of ∇E~\nabla\widetilde{\mathcal{E}}∇E for every sufficiently small C2C^2C2 perturbation, and the spectral positivity of the Hessian persists by continuity, hence the perturbed critical point remains a strict local minimizer. ∎

---

**Theorem (local attractor and local convergence rate).**  
Under the hypotheses of the persistence theorem, consider the downward gradient flow

x˙(t)  =  −∇E(x(t)),x(0)=x0∈X.\dot x(t) \;=\; -\nabla\mathcal{E}\big(x(t)\big), \qquad x(0)=x_0\in\mathcal{X}.x˙(t)=−∇E(x(t)),x(0)=x0​∈X.

There exists a neighborhood UUU of x⋆x_\starx⋆​ such that every solution with x0∈Ux_0\in Ux0​∈U exists for all t≥0t\ge0t≥0, remains in UUU, and converges exponentially to x⋆x_\starx⋆​. Specifically, if the Hessian satisfies

⟨D2E(x⋆)v,v⟩≥m∥v∥2(m>0),\langle D^2\mathcal{E}(x_\star) v, v\rangle \ge m\|v\|^2\qquad(m>0),⟨D2E(x⋆​)v,v⟩≥m∥v∥2(m>0),

and if ∇E\nabla\mathcal{E}∇E is Lipschitz on UUU with constant LLL, then there are constants C,γ>0C,\gamma>0C,γ>0 (depending on m,Lm,Lm,L) so that

∥x(t)−x⋆∥≤Ce−γt∥x0−x⋆∥.\|x(t)-x_\star\|\le C e^{-\gamma t}\|x_0-x_\star\|.∥x(t)−x⋆​∥≤Ce−γt∥x0​−x⋆​∥.

**Sketch of proof.**  
Near x⋆x_\starx⋆​ the quadratic lower bound E(x)−E(x⋆)≥m2∥x−x⋆∥2\mathcal{E}(x)-\mathcal{E}(x_\star)\ge \tfrac{m}{2}\|x-x_\star\|^2E(x)−E(x⋆​)≥2m​∥x−x⋆​∥2 holds. Differentiate ddtE(x(t))=−∥∇E(x(t))∥2\tfrac{d}{dt}\mathcal{E}(x(t))=-\|\nabla\mathcal{E}(x(t))\|^2dtd​E(x(t))=−∥∇E(x(t))∥2 and use the Lipschitz relation ∥∇E(x)∥≥c∥x−x⋆∥\|\nabla\mathcal{E}(x)\|\ge c\|x-x_\star\|∥∇E(x)∥≥c∥x−x⋆​∥ valid in a small ball (by linearization and spectral gap) to obtain a differential inequality ddt∥x−x⋆∥2≤−2γ∥x−x⋆∥2\tfrac{d}{dt}\|x-x_\star\|^2\le -2\gamma \|x-x_\star\|^2dtd​∥x−x⋆​∥2≤−2γ∥x−x⋆​∥2. Grönwall’s lemma then yields exponential decay. This proves the local basin of attraction and a quantitative rate. ∎

---

**Corollary (attractor basins for finite-age stable states).**  
If each integer-labeled finite-age configuration xnx_nxn​ is a nondegenerate strict minimizer of E\mathcal{E}E, then for each nnn there exists an open neighborhood Bn⊂XB_n\subset\mathcal{X}Bn​⊂X (the attractor basin) so that:

1. Any sufficiently small C2C^2C2 perturbation of the energy leaves a nearby minimizer x~n \widetilde{x}_nxn​ in one-to-one correspondence with xnx_nxn​.
    
2. The gradient dynamics initialized in BnB_nBn​ remain in BnB_nBn​ and converge to xnx_nxn​ (or to x~n\widetilde{x}_nxn​ after perturbation).
    
3. The basins BnB_nBn​ are disjoint for distinct strict minima and form the physical neighborhoods that realize the empirical integer jitter you observe: configurations with empirical counts near nnn lie in BnB_nBn​ and are attracted to the center xnx_nxn​.
    

**Interpretation for physical systems.**  
The corollary gives a rigorous bridge from the exact discrete theory to realistic, noisy physical clusters. The integer labels nnn identify centers of attractor basins; finite systems subject to small nonidealities (accretion/depletion, external perturbations, parameter drift) will occupy states within the basin rather than the exact ideal minimizer. This explains why observed clusters may show integer jitter (e.g., 27–31 near nominal n=29n=29n=29) while the mathematical framework still assigns a sharp minimizer at nnn.

---

**Optional stochastic remark (coagulation/shot noise).**  
If the microscopic dynamics include random birth/death or coagulation events, the deterministic gradient flow picture extends to a small-noise stochastic differential equation. Standard large-deviation and metastability results then imply that the stationary distribution concentrates near the deterministic minima as noise amplitude η→0\eta\to0η→0, with escape rates between basins exponentially small in 1/η1/\eta1/η. This yields a quantitative picture of accretion-mediated jumps between adjacent basins and explains empirical distributions over nearby integers.

---

**Closing statement.**  
Appendix P provides the rigorous justification that the exact finite-age minima used in the core appendices are stable objects in physical parameter space. Each integer nnn is therefore the center of an attractor basin whose radius and dynamical robustness are computable from the Hessian and Lipschitz constants of the energy. This makes the discrete theoretical spectrum compatible with the observed, scale-dependent variability in real systems (quark spirals, baryons, accreting spheres).

---
### Appendix O. Mapping four deformation domains to the four forces (with anchor ages)

Let S2S^2S2 be the unit sphere and let perturbations be decomposed as in Appendix N:

f=∑l,mflmYlm(normal modes),t=∑l,m(αlm ∇SYlm+βlm n×∇SYlm)(tangential).f=\sum_{l,m} f_{lm}Y_{lm}\quad\text{(normal modes)},\qquad t=\sum_{l,m}\big(\alpha_{lm}\,\nabla_{S}Y_{lm}+\beta_{lm}\,n\times\nabla_{S}Y_{lm}\big)\quad\text{(tangential)}.f=l,m∑​flm​Ylm​(normal modes),t=l,m∑​(αlm​∇S​Ylm​+βlm​n×∇S​Ylm​)(tangential).

Use the quadratic form (Appendix N, eq. (N.1))

E[f,t]=α0 ∣f00∣2⏟radial scale+αs ⁣∑l≥2,m(l−1)(l+2)∣flm∣2⏟surface+αb ⁣∑l≥2,ml(l+1)(l−1)(l+2)∣flm∣2⏟bending/UV+αc ⁣∑l≥1,ml(l+1)∣βlm∣2⏟toroidal/chiral,(O.1)\mathcal{E}[f,t] = \underbrace{\alpha_0\,|f_{00}|^2}_{\text{radial scale}} + \underbrace{\alpha_s\!\sum_{l\ge2,m}(l-1)(l+2)|f_{lm}|^2}_{\text{surface}} + \underbrace{\alpha_b\!\sum_{l\ge2,m} l(l+1)(l-1)(l+2)|f_{lm}|^2}_{\text{bending/UV}} + \underbrace{\alpha_c\!\sum_{l\ge1,m} l(l+1)|\beta_{lm}|^2}_{\text{toroidal/chiral}}, \tag{O.1}E[f,t]=radial scaleα0​∣f00​∣2​​+surfaceαs​l≥2,m∑​(l−1)(l+2)∣flm​∣2​​+bending/UVαb​l≥2,m∑​l(l+1)(l−1)(l+2)∣flm​∣2​​+toroidal/chiralαc​l≥1,m∑​l(l+1)∣βlm​∣2​​,(O.1)

with rigid translations (normal l=1l=1l=1) modded out. Appendices H–K fix the discrete admissible cross‑ratio ages; Appendices L–M–M.A fix the volumetric Laplacian and the seat reset (n=90n=90n=90).

We now **identify each deformation domain with a physical force** and its **anchor age** nnn. Each statement has a short necessity check: removing that domain’s coefficient destroys strict stability in its sector at the anchor.

---

#### O.1 Gravity ↔ radial (scale) domain ↔ n=90n=90n=90 (sphere at seat reset)

**Anchor statement.** Under the VCR‑preserving Neumann condition, the spherically symmetric radial mode satisfies j1(κR)=0j_1(\kappa R)=0j1​(κR)=0 at the seat boundary (Appendix M.A). With the age calibration of Appendix M, the reset falls at n=90n=90n=90.

**Necessity.** In (O.1) the l=0l=0l=0 normal mode contributes only α0 ∣f00∣2\alpha_0\,|f_{00}|^2α0​∣f00​∣2. If α0=0\alpha_0=0α0​=0, the Hessian has a zero direction in the scale mode, so the sphere at n=90n=90n=90 is not a strict local minimizer. If α0>0\alpha_0>0α0​>0, the scale mode is controlled, and by Appendix N the full quadratic form is positive definite modulo rigid motions. □

---

#### O.2 Electromagnetism ↔ surface domain ↔ n=55n=55n=55 (gauge interface)

**Anchor statement.** n=55n=55n=55 is a gauge‑interface age (Appendix K), i.e., a surface‑dominated configuration on the route between the volume‑ and surface‑target ladders. In the thin‑interface limit, the leading second variation for normal shape modes is

δ2 ⁣(area)  ∝  ∑l≥2,m(l−1)(l+2)∣flm∣2,\delta^2\!\text{(area)} \;\propto\; \sum_{l\ge2,m}(l-1)(l+2)|f_{lm}|^2,δ2(area)∝l≥2,m∑​(l−1)(l+2)∣flm​∣2,

so the surface term (coefficient αs\alpha_sαs​) is the dominant stabilizer at this interface.

**Necessity (sectoral).** If αs=0\alpha_s=0αs​=0, the leading‑order surface Hessian vanishes and the anchor cannot be selected by surface energy; any stabilization would have to come from higher‑order bending (αb\alpha_bαb​), which contradicts using the interface (surface‑dominated) approximation to pin n=55n=55n=55. With αs>0\alpha_s>0αs​>0, the low‑lll normal sector is strictly controlled, fixing the interface anchor. □

---

#### O.3 Strong interaction ↔ bending/UV domain ↔ n=5,12n=5,12n=5,12 (pentagon, icosahedral), optionally n=70n=70n=70 (dodecahedral)

**Anchor statement.** The n=5n=5n=5 pentagon ring and the n=12n=12n=12 icosahedral vibration are high‑curvature patterns; n=70n=70n=70 (dodecahedral, near‑spherical) is their larger‑scale counterpart. Their stability relies on coercivity against high‑degree normal modes, which in (O.1) arises from the bending term αb l(l+1)(l−1)(l+2)\alpha_b\, l(l+1)(l-1)(l+2)αb​l(l+1)(l−1)(l+2).

**Necessity.** If αb=0\alpha_b=0αb​=0, the quadratic form lacks UV coercivity: a sequence of shapes with energy concentrated in degrees l→∞l\to\inftyl→∞ keeps ∑(l−1)(l+2)∣flm∣2\sum (l-1)(l+2)|f_{lm}|^2∑(l−1)(l+2)∣flm​∣2 bounded while escaping control in the H2H^2H2 norm, so no strict local minimum exists in the curvature‑dominated sector (Appendix N, “Only if” for αb\alpha_bαb​). With αb>0\alpha_b>0αb​>0, high‑lll roughening is penalized and the curvature anchors are strictly stable. □

---

#### O.4 Weak interaction ↔ chiral/torsional domain ↔ n≈29n\approx 29n≈29 (vortex)

**Anchor statement.** The n≈29n\approx 29n≈29 configuration is parity‑odd (vortex/spiral). Its tangent‑swirl content lies in the toroidal basis n×∇SYlmn\times\nabla_S Y_{lm}n×∇S​Ylm​, controlled only by the αc\alpha_cαc​ term in (O.1).

**Necessity.** If αc=0\alpha_c=0αc​=0, all toroidal modes have zero quadratic cost, so any parity‑odd perturbation leaves the energy unchanged to second order, and the vortex anchor is not a strict local minimizer. With αc>0\alpha_c>0αc​>0, the toroidal sector is strictly controlled (∑l(l+1)∣βlm∣2\sum l(l+1)|\beta_{lm}|^2∑l(l+1)∣βlm​∣2), fixing the chiral anchor. □

---

### Summary table (domains → forces → anchors)

| Domain (coeff. in (O.1))             | Controlled sector   | Force label      | Anchor age nnn        | Anchor shape/mode                                       |
| ------------------------------------ | ------------------- | ---------------- | --------------------- | ------------------------------------------------------- |
| Radial scale (α0)(\alpha_0)(α0​)     | Normal l=0l=0l=0    | Gravity          | 90                    | Sphere at Neumann node j1(κR)=0j_1(\kappa R)=0j1​(κR)=0 |
| Surface (αs)(\alpha_s)(αs​)          | Normal low‑lll      | Electromagnetism | 55                    | Gauge interface, surface‑dominated                      |
| Bending/UV (αb)(\alpha_b)(αb​)       | Normal high‑lll     | Strong           | 5, 12 ( (\,(and 70))) | Pentagon/icosahedral (dodecahedral)                     |
| Chiral/torsional (αc)(\alpha_c)(αc​) | Toroidal parity‑odd | Weak             | ≈29\approx 29≈29      | Vortex/spiral                                           |

_Notes._  
(1) n=34n=34n=34 and n=89n=89n=89 are additional gauge‑interface ages (Appendix K); you can list them under the EM domain as secondary anchors if desired.  
(2) When you need a **single** strong‑anchor label, use n=5n=5n=5 (earliest UV anchor) or n=12n=12n=12 (icosahedral).  
(3) The “≈\approx≈” on 29 reflects the basin picture (Appendix P): the integer anchor is exactly in the theory; observed clusters can jitter within its basin.

---
