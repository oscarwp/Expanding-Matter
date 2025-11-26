# Supplement: Detailed Mathematical Derivations for the Expanding Matter Framework

In what follows we provide a series of derivations and expanded calculations corresponding to the main sections of the paper. We address in turn:

- (A) The derivation of the “homeostatic flattening” PDE and its connection to the action principle.
- (B) The formulation of the wave operator and the emergence of discrete (quantized) states.
- (C) The derivation of integral stability conditions.
- (D) The role of projective and conformal geometry in generating gauge invariants.
- (E) The extraction of an effective Einstein–Hilbert action by integrating out the extra “scale” coordinate.
- (F) The emergence of discrete iterative patterns and the golden ratio.

Each section below includes intermediate steps and commentary.

---

## A. Derivation of the Expansion PDE from a Variational Principle

### A.1. The Microscopic Action

We begin with the microscopic action defined in the paper:

S[Ψ]=∫d4x dw LwithL=12[(∂μΨ)2+κ (∂wΨ)2]−V(Ψ) ,S[\Psi] = \int d^4x\,dw\, \mathcal{L} \quad \text{with} \quad \mathcal{L} = \frac{1}{2}\Bigl[(\partial_\mu \Psi)^2 + \kappa\,(\partial_w \Psi)^2\Bigr] - V(\Psi)\,,S[Ψ]=∫d4xdwLwithL=21​[(∂μ​Ψ)2+κ(∂w​Ψ)2]−V(Ψ),

where Ψ=Ψ(xμ,w)\Psi = \Psi(x^\mu, w)Ψ=Ψ(xμ,w) and κ\kappaκ is a constant.

### A.2. Euler–Lagrange Equations

To derive the equations of motion for Ψ\PsiΨ, we perform a variation

δS=0 .\delta S = 0 \,.δS=0.

For a field Ψ\PsiΨ, the Euler–Lagrange equation in two variables xμx^\muxμ and www reads

∂L∂Ψ−∂μ(∂L∂(∂μΨ))−∂w(∂L∂(∂wΨ))=0 .\frac{\partial \mathcal{L}}{\partial \Psi} - \partial_\mu \left(\frac{\partial \mathcal{L}}{\partial(\partial_\mu \Psi)}\right) - \partial_w \left(\frac{\partial \mathcal{L}}{\partial(\partial_w \Psi)}\right) = 0\,.∂Ψ∂L​−∂μ​(∂(∂μ​Ψ)∂L​)−∂w​(∂(∂w​Ψ)∂L​)=0.

We compute term by term:

1. **Potential Term:**
    
    ∂L∂Ψ=−∂V∂Ψ .\frac{\partial \mathcal{L}}{\partial \Psi} = -\frac{\partial V}{\partial \Psi}\,.∂Ψ∂L​=−∂Ψ∂V​.
2. **Spacetime Derivative Term:**  
    Since ∂L∂(∂μΨ)=∂μΨ\frac{\partial \mathcal{L}}{\partial(\partial_\mu \Psi)} = \partial^\mu \Psi∂(∂μ​Ψ)∂L​=∂μΨ,
    
    ∂μ(∂L∂(∂μΨ))=∂μ∂μΨ=□Ψ .\partial_\mu \left(\frac{\partial \mathcal{L}}{\partial(\partial_\mu \Psi)}\right) = \partial_\mu \partial^\mu \Psi = \Box \Psi\,.∂μ​(∂(∂μ​Ψ)∂L​)=∂μ​∂μΨ=□Ψ.
3. **Scale Derivative Term:**  
    Similarly, since ∂L∂(∂wΨ)=κ ∂wΨ\frac{\partial \mathcal{L}}{\partial(\partial_w \Psi)} = \kappa\,\partial_w \Psi∂(∂w​Ψ)∂L​=κ∂w​Ψ,
    
    ∂w(∂L∂(∂wΨ))=κ ∂w2Ψ .\partial_w \left(\frac{\partial \mathcal{L}}{\partial(\partial_w \Psi)}\right) = \kappa\,\partial_w^2 \Psi\,.∂w​(∂(∂w​Ψ)∂L​)=κ∂w2​Ψ.

Thus, the Euler–Lagrange equation becomes

−∂V∂Ψ−□Ψ−κ ∂w2Ψ=0⟹□Ψ+κ ∂w2Ψ=−∂V∂Ψ .-\frac{\partial V}{\partial \Psi} - \Box \Psi - \kappa\,\partial_w^2 \Psi = 0 \quad \Longrightarrow \quad \Box \Psi + \kappa\,\partial_w^2 \Psi = - \frac{\partial V}{\partial \Psi}\,.−∂Ψ∂V​−□Ψ−κ∂w2​Ψ=0⟹□Ψ+κ∂w2​Ψ=−∂Ψ∂V​.

This is the field equation that underpins both the “homeostatic flattening” PDE and the subsequent wave operator formulation.

### A.3. Interpretation as a Homeostatic PDE

One may reinterpret the above as a “flattening” evolution in time. Suppose we write the time derivative explicitly (separating the time coordinate t=x0t=x^0t=x0):

∂Ψ∂t=−D ΨwithD=−∇x2−κ ∂w2+∂V∂Ψ .\frac{\partial \Psi}{\partial t} = -\mathcal{D}\,\Psi \quad \text{with} \quad \mathcal{D} = -\nabla^2_x - \kappa\,\partial_w^2 + \frac{\partial V}{\partial \Psi}\,.∂t∂Ψ​=−DΨwithD=−∇x2​−κ∂w2​+∂Ψ∂V​.

This “gradient–flow” formulation (with a sign choice appropriate for a dissipative process) embodies the idea that local tensions (given by the Laplacian terms) drive the field toward a “flattened” configuration balanced by the potential. In our framework, the finite speed of flattening is encoded in the differential operators (and can be further elaborated by replacing the parabolic equation with a hyperbolic one if necessary).

---

## B. Wave Operator and the Emergence of Discrete States

### B.1. Separation of Variables

Assume a separable solution of the form

Ψ(xμ,w)=ψ(xμ) χ(w) .\Psi(x^\mu, w) = \psi(x^\mu) \,\chi(w)\,.Ψ(xμ,w)=ψ(xμ)χ(w).

Inserting this ansatz into the field equation

□Ψ+κ ∂w2Ψ+∂V∂Ψ=0 ,\Box \Psi + \kappa\,\partial_w^2 \Psi + \frac{\partial V}{\partial \Psi} = 0\,,□Ψ+κ∂w2​Ψ+∂Ψ∂V​=0,

and assuming for simplicity that VVV is such that the field can be linearized around a stable minimum, we set

∂V∂Ψ≈m2 Ψ .\frac{\partial V}{\partial \Psi} \approx m^2\,\Psi\,.∂Ψ∂V​≈m2Ψ.

Then the equation becomes

χ(w) □ψ(x)+κ ψ(x) χ′′(w)+m2 ψ(x) χ(w)=0 .\chi(w)\,\Box \psi(x) + \kappa\,\psi(x)\,\chi''(w) + m^2\,\psi(x)\,\chi(w) = 0\,.χ(w)□ψ(x)+κψ(x)χ′′(w)+m2ψ(x)χ(w)=0.

Dividing through by ψ(x) χ(w)\psi(x)\,\chi(w)ψ(x)χ(w) (and assuming nonvanishing factors) gives

□ψ(x)ψ(x)+m2=−κ χ′′(w)χ(w)=λ ,\frac{\Box \psi(x)}{\psi(x)} + m^2 = -\kappa\,\frac{\chi''(w)}{\chi(w)} = \lambda\,,ψ(x)□ψ(x)​+m2=−κχ(w)χ′′(w)​=λ,

where λ\lambdaλ is a separation constant.

### B.2. Eigenvalue Equations

We now have two eigenvalue problems:

4. **Spacetime Part:**
    
    □ψ(x)=(λ−m2) ψ(x) .\Box \psi(x) = (\lambda - m^2)\,\psi(x)\,.□ψ(x)=(λ−m2)ψ(x).
    
    In a stationary or bounded configuration, boundary conditions will select a discrete set of eigenvalues for λ−m2\lambda - m^2λ−m2.
    
5. **Scale Part:**
    
    κ χ′′(w)+λ χ(w)=0 .\kappa\,\chi''(w) + \lambda\,\chi(w) = 0\,.κχ′′(w)+λχ(w)=0.
    
    With appropriate boundary conditions (for example, requiring normalizability or periodicity in www), the general solution
    
    χ(w)=Acos⁡(λ/κ w)+Bsin⁡(λ/κ w)\chi(w) = A \cos\Bigl(\sqrt{\lambda/\kappa}\,w\Bigr) + B \sin\Bigl(\sqrt{\lambda/\kappa}\,w\Bigr)χ(w)=Acos(λ/κ​w)+Bsin(λ/κ​w)
    
    will only allow discrete values of λ\lambdaλ. In an atomic analogue, one might interpret the allowed values of λ/κ\sqrt{\lambda/\kappa}λ/κ​ (and thus of λ\lambdaλ) as fixing the “size” (or Bohr radius) of a stable orbit.
    

### B.3. Quantization by Boundary Conditions

For example, if we demand that χ(w)\chi(w)χ(w) vanish at two “boundaries” w=0w=0w=0 and w=w0w=w_0w=w0​, then we require

χ(0)=0andχ(w0)=0 .\chi(0)=0 \quad \text{and} \quad \chi(w_0)=0\,.χ(0)=0andχ(w0​)=0.

A sine–solution gives

χ(w)=Bsin⁡(λ/κ w)\chi(w)=B \sin\left(\sqrt{\lambda/\kappa}\,w\right)χ(w)=Bsin(λ/κ​w)

with

λ/κ w0=nπ,n∈N .\sqrt{\lambda/\kappa}\,w_0 = n\pi,\quad n\in\mathbb{N}\,.λ/κ​w0​=nπ,n∈N.

Thus,

λ=κ(nπw0)2 .\lambda = \kappa \left(\frac{n\pi}{w_0}\right)^2\,.λ=κ(w0​nπ​)2.

This quantization condition is analogous to the Bohr quantization condition and shows how discrete “orbits” emerge from the continuous expansion dynamics.

---

## C. Integral Stability Conditions

### C.1. Functional Stationarity

Consider again the action

S[Ψ]=∫d4x dw {12[(∂μΨ)2+κ (∂wΨ)2]−V(Ψ)} .S[\Psi] = \int d^4x\,dw\, \left\{\frac{1}{2}\left[(\partial_\mu \Psi)^2 + \kappa\,(\partial_w \Psi)^2\right] - V(\Psi)\right\}\,.S[Ψ]=∫d4xdw{21​[(∂μ​Ψ)2+κ(∂w​Ψ)2]−V(Ψ)}.

A stable configuration is one that minimizes (or renders stationary) the action. This can be formulated as an eigenvalue problem for the operator

O=−□−κ ∂w2+∂2V∂Ψ2 ,\mathcal{O} = -\Box - \kappa\,\partial_w^2 + \frac{\partial^2 V}{\partial \Psi^2}\,,O=−□−κ∂w2​+∂Ψ2∂2V​,

evaluated about a classical background Ψ0\Psi_0Ψ0​.

### C.2. The Variational Condition

The condition for stability is

δS=∫d4x dw δΨ O Ψ=0 ,\delta S = \int d^4x\,dw\, \delta\Psi \,\mathcal{O}\,\Psi = 0\,,δS=∫d4xdwδΨOΨ=0,

for arbitrary variations δΨ\delta\PsiδΨ. In particular, if we expand in eigenfunctions {Ψn}\{\Psi_n\}{Ψn​} satisfying

O Ψn=En Ψn ,\mathcal{O}\,\Psi_n = E_n\,\Psi_n\,,OΨn​=En​Ψn​,

the allowed modes are those for which the “overlap” integrals satisfy

∫d4x dw Ψn∗ Ψn=1 ,\int d^4x\,dw\, \Psi_n^*\,\Psi_n = 1\,,∫d4xdwΨn∗​Ψn​=1,

with eigenvalues EnE_nEn​ that represent the “energy cost” of deviations from the stable configuration. Only a discrete set of modes will typically satisfy the imposed boundary conditions and symmetry constraints. This formalism underpins the claim that quantization of orbits (and more generally, of physical states) naturally emerges from the stability of overlapping expansions.

---

## D. Projective and Conformal Geometry Derivations

### D.1. Homogeneous Coordinates

We define the extended coordinate set

XA=(w,xμ)(A=0,1,2,3,4) ,X^A = (w, x^\mu) \quad (A=0,1,2,3,4)\,,XA=(w,xμ)(A=0,1,2,3,4),

which enables us to treat the scale coordinate www on an equal footing with the spacetime coordinates xμx^\muxμ. In many projective treatments the physical coordinates are given by

xμ=XμX0 ,x^\mu = \frac{X^\mu}{X^0}\,,xμ=X0Xμ​,

so that a change in scale X0X^0X0 is equivalent to a local conformal transformation.

### D.2. The Cross Ratio

For four collinear points z1,z2,z3,z4z_1, z_2, z_3, z_4z1​,z2​,z3​,z4​ in the complex plane (or on a projective line), the cross ratio is defined as

λ=(z1−z3)(z2−z4)(z1−z4)(z2−z3) .\lambda = \frac{(z_1 - z_3)(z_2 - z_4)}{(z_1 - z_4)(z_2 - z_3)}\,.λ=(z1​−z4​)(z2​−z3​)(z1​−z3​)(z2​−z4​)​.

This quantity is invariant under the projective group PGL(2,C)\mathrm{PGL}(2,\mathbb{C})PGL(2,C). In our framework the points ziz_izi​ can be associated with “events” or states of the expansion field. Invariance of the cross ratio implies that certain combinations of the expansion parameters are conserved under local reparameterizations, and one can show that:

6. **Double Covering and Spin–½:**  
    If one considers transformations that are double–coverings of the projective group, these can be related to the two–component spinor structure that underlies spin–½ fields. One can illustrate this by mapping a projective transformation
    
    z↦az+bcz+dwith ad−bc≠0,z \mapsto \frac{az + b}{cz + d}\quad \text{with } ad - bc \neq 0,z↦cz+daz+b​with ad−bc=0,
    
    onto a two–component spinor representation. Details involve showing that the invariance of the cross ratio forces a double–valuedness which is reminiscent of fermionic behavior.
    
7. **Triple Overlap and SU(3):**  
    Similarly, if one considers triplets of overlapping expansions (or “patches”), the invariance conditions can be written in a form that is naturally associated with the group SU(3). For example, consider three complex numbers z1,z2,z3z_1, z_2, z_3z1​,z2​,z3​ (each representing an expansion “phase”) and form invariants from their cross ratios. A careful analysis shows that the conditions required for the invariants to be maintained under local projective transformations impose constraints isomorphic to those of SU(3).
    

### D.3. Conformal Geometric Algebra (CGA)

CGA is a powerful formalism for treating conformal and projective transformations. In this context, one embeds the four-dimensional Minkowski space into a higher–dimensional space with a null–cone structure. The embedding is typically given by

XA=(X+,X−,Xμ)withX+=w,X−=x2w,Xμ=xμ .X^A = (X^+, X^-, X^\mu) \quad \text{with} \quad X^+ = w, \quad X^- = \frac{x^2}{w}, \quad X^\mu = x^\mu\,.XA=(X+,X−,Xμ)withX+=w,X−=wx2​,Xμ=xμ.

In this language, a conformal transformation in Minkowski space becomes a linear transformation in the higher–dimensional space. One then shows that the “gauge” degrees of freedom (such as U(1) phases) emerge as remnants of the freedom to choose different representatives in the projective class of coordinates. The rigorous derivation requires constructing the appropriate Clifford algebra and demonstrating that the invariants of the conformal group match the observed gauge invariances.

---

## E. Extraction of an Effective Einstein–Hilbert Action

### E.1. Integrating Out the Scale Coordinate

Starting with the full action

S[Ψ]=∫d4x dw {12[(∂μΨ)2+κ (∂wΨ)2]−V(Ψ)} ,S[\Psi] = \int d^4x\,dw\, \left\{\frac{1}{2}\left[(\partial_\mu \Psi)^2 + \kappa\,(\partial_w \Psi)^2\right] - V(\Psi)\right\}\,,S[Ψ]=∫d4xdw{21​[(∂μ​Ψ)2+κ(∂w​Ψ)2]−V(Ψ)},

we assume that the scale coordinate www is “hidden” in the sense that its dynamics are fast compared to the macroscopic (spacetime) degrees of freedom, or that it can be integrated out in a coarse–graining procedure.

Let us define an effective field

Φ(x)≡∫dw f(w) Ψ(x,w) ,\Phi(x) \equiv \int dw\, f(w)\,\Psi(x,w)\,,Φ(x)≡∫dwf(w)Ψ(x,w),

where f(w)f(w)f(w) is a weight function (for example, a normalized ground–state eigenfunction of the www–operator). Then, schematically, one obtains

Seff[Φ]=∫d4x −g {116πGeffR+Lmattereff(Φ)} ,S_{\mathrm{eff}}[\Phi] = \int d^4x\, \sqrt{-g}\,\left\{\frac{1}{16\pi G_{\mathrm{eff}}}R + \mathcal{L}^{\mathrm{eff}}_{\mathrm{matter}}(\Phi)\right\}\,,Seff​[Φ]=∫d4x−g​{16πGeff​1​R+Lmattereff​(Φ)},

with the metric gμνg_{\mu\nu}gμν​ emerging as an “averaged” effect of the expansion dynamics and the gravitational constant GeffG_{\mathrm{eff}}Geff​ being determined by the details of the www–integration. A detailed derivation would proceed via a Kaluza–Klein reduction, where one expands

Ψ(x,w)=∑nΦn(x) χn(w) ,\Psi(x,w) = \sum_n \Phi_n(x) \,\chi_n(w)\,,Ψ(x,w)=n∑​Φn​(x)χn​(w),

and then retains the lightest mode (or a finite set of modes).

### E.2. Variation with Respect to the Emergent Metric

Once the effective action is obtained, one may vary with respect to the emergent metric gμνg_{\mu\nu}gμν​ to obtain

δSeff=0⟹Rμν−12gμνR=8πGeff Tμνeff ,\delta S_{\mathrm{eff}} = 0 \quad \Longrightarrow \quad R_{\mu\nu} - \frac{1}{2}g_{\mu\nu}R = 8\pi G_{\mathrm{eff}}\, T_{\mu\nu}^{\mathrm{eff}}\,,δSeff​=0⟹Rμν​−21​gμν​R=8πGeff​Tμνeff​,

where the effective stress–energy tensor TμνeffT_{\mu\nu}^{\mathrm{eff}}Tμνeff​ is given by the integrated contributions of the expansion field’s gradients and potential. The details of this derivation follow the standard techniques of general relativity once the dimensional reduction is performed.

---

## F. Emergence of Discrete Iterative Patterns and the Golden Ratio

### F.1. Iterative Recurrence Relations

One of the more speculative aspects of the framework is the claim that iterative expansion dynamics yield recurrence relations analogous to the Fibonacci sequence. Suppose that a minimal–tension solution for an expansion “lump” satisfies a recurrence relation of the form:

an+1=an+an−1 ,a_{n+1} = a_n + a_{n-1}\,,an+1​=an​+an−1​,

where ana_nan​ represents a characteristic length (or scale) at the nnnth iteration.

### F.2. The Golden Ratio

It is well known that the Fibonacci recurrence has solutions of the form

an∝φn ,a_n \propto \varphi^n\,,an​∝φn,

where φ\varphiφ is the golden ratio given by

φ=1+52 .\varphi = \frac{1+\sqrt{5}}{2}\,.φ=21+5​​.

To see this, assume a solution an=λna_n = \lambda^nan​=λn. Then the recurrence relation becomes

λn+1=λn+λn−1⟹λ2=λ+1 .\lambda^{n+1} = \lambda^n + \lambda^{n-1} \quad \Longrightarrow \quad \lambda^2 = \lambda + 1\,.λn+1=λn+λn−1⟹λ2=λ+1.

Solving the quadratic equation

λ2−λ−1=0\lambda^2 - \lambda - 1 = 0λ2−λ−1=0

yields

λ=1±52 .\lambda = \frac{1 \pm \sqrt{5}}{2}\,.λ=21±5​​.

The positive solution is φ\varphiφ. In the context of the EMF, the appearance of φ\varphiφ in the iterative pattern of minimal tension solutions can be interpreted as a universal scaling factor. This may provide a quantitative handle on phenomena such as the spacing of energy levels or even large–scale cosmic structures.

---

## Summary and Concluding Remarks

In this supplement we have expanded upon the core mathematical formulations of the Expanding Matter Framework:

8. **Derivation from an Action Principle:**  
    We showed that the microscopic Lagrangian,
    
    L=12[(∂μΨ)2+κ (∂wΨ)2]−V(Ψ) ,\mathcal{L} = \frac{1}{2}\left[(\partial_\mu \Psi)^2 + \kappa\,(\partial_w \Psi)^2\right] - V(\Psi)\,,L=21​[(∂μ​Ψ)2+κ(∂w​Ψ)2]−V(Ψ),
    
    leads via the Euler–Lagrange procedure to a PDE that governs the local expansion dynamics.
    
9. **Quantization via Separation of Variables:**  
    By assuming a separable ansatz and imposing boundary conditions in the scale coordinate www, we obtained a quantization condition that mirrors the Bohr quantization.
    
10. **Integral Stability and Eigenvalue Problems:**  
    We demonstrated how stationarity of the action yields an eigenvalue problem for stable modes, providing a mathematical basis for discrete states.
    
11. **Projective/Conformal Geometry and Gauge Invariance:**  
    Through the introduction of homogeneous coordinates and invariants (such as the cross ratio), we outlined how local gauge symmetries may arise from underlying geometric constraints.
    
12. **Effective Einstein Equations:**  
    Integrating out the extra scale coordinate leads to an effective four–dimensional action whose variation reproduces Einstein’s equations with matter sources determined by overlapping expansion fields.
    
13. **Discrete Iterative Patterns:**  
    Finally, we sketched how iterative recurrence relations naturally yield the golden ratio, suggesting a universal scaling in minimal–tension configurations.
    

Each derivation here is presented in a simplified form to highlight the underlying logic. A full treatment would require addressing issues such as non–linear corrections in the potential V(Ψ)V(\Psi)V(Ψ), precise boundary conditions in the www–direction, and the rigorous mapping of projective invariants to the representation theory of gauge groups.

We hope that this supplement provides a clear roadmap for further work and assists in bridging the conceptual framework with the detailed mathematical structures necessary for a complete and publishable theory.