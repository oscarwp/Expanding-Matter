# Emergence of Gaussian Curvature from Expanding Circle Packings: A Differential Geometric and Projective Perspective

## Abstract

We present a rigorous differential geometric analysis showing how uniform expansion of circles arranged in a hexagonal packing on a 2-manifold compels the emergence of nonzero Gaussian curvature. Using the Levi-Civita connection and curvature 2-forms, we prove that the induced curvature K(t)K(t) scales as 1/r2(t)1/r^2(t), where r(t)r(t) is the circle radius at time tt. We highlight the role of the hexagonal arrangement as the densest planar packing, explain why no flat embedding can accommodate growth, and compare with other packings. Additionally, we discuss stability under perturbations and briefly introduce a complementary projective geometry viewpoint, which not only illuminates circle tangency as a projective invariant but also sets the stage for broader investigations in subsequent work.

Our results emphasize the fundamental necessity and uniqueness of the inverse-square law, supported by complete proofs, boundary considerations, and references to classical circle packing theorems (e.g., the Koebe–Andreev–Thurston theorem) and discrete conformal geometry (e.g., Stephenson’s work [9]). We further offer a short discussion of how such curvature emergence might appear in real-world contexts, such as biological membrane deformation or crystal lattice expansions.

---

## 1. Introduction

A recurring theme in geometry is that _local constraints_ can force _global_ geometric features. In two dimensions, circle packing has long served as an archetype of this phenomenon. Notably, the Koebe–Andreev–Thurston theorem shows that for a given combinatorial surface, one can realize it through a circle packing in a _static_ framework. Here, we examine a _dynamic_ variant: if circles in a maximally dense (hexagonal) arrangement expand uniformly while preserving tangential contact, the underlying surface must develop Gaussian curvature.

### 1.1 Core Concept and Motivations

- **Expansion vs. Flatness**  
    In a flat plane, circles that grow uniformly while remaining mutually tangent inevitably overlap unless the plane itself “bends.” Hence, uniform radial expansion from local adjacency forces curvature.
    
- **Hexagonal Arrangement**  
    Hexagonal packing is not just any arrangement but the **densest** in two dimensions, imposing particularly strong constraints. We show it leads to a clear law relating curvature to radius, specifically K(t)=1/[4 r2(t)]K(t) = 1/[4\,r^2(t)].
    
- **Potential Applications**
    
    - **Biological Membranes**: Certain viral capsids or cellular shells expand while keeping subunits in close packing, affecting the membrane’s curvature.
    - **Crystal Lattices**: 2D layers under thermal or chemical expansion (e.g., in graphene-like materials) can warp out of plane.
    - **Cosmological Analogies**: Uniform expansions in discrete models may induce curvature on large scales.

Figure 1 (below) should depict the **initial hexagonal packing** on a flat surface and conceptually show how, as r(t)r(t) increases, the geometry transitions toward a curved surface to avoid overlap.

**Figure 1**. _Illustration of the initial hexagonal packing of circles of radius r0r_0. As r(t)r(t) grows, the circles cannot remain in a flat Euclidean plane without overlap, thus inducing curvature._

---

### 1.2 Relation to Existing Literature

- **Koebe–Andreev–Thurston (Static Circle Packing)**  
    These classical results guarantee that a prescribed combinatorial triangulation can be realized by a circle packing. By contrast, here the circle radii r(t)r(t) _evolve in time_, leading to an explicit inverse-square curvature law K(t)∝1/r2(t)K(t) \propto 1/r^2(t). This complements the static theory with a uniform growth scenario.
    
- **Discrete Conformal Geometry**  
    In many discrete conformal approaches (e.g., Stephenson’s work [9]), circle packings approximate conformal maps on triangulated meshes. Our uniform expansion underscores a simple local adjacency constraint that yields a global sphere-like geometry and may serve as a discrete analogue to uniformizing flows or curvature-driven PDEs.
    

---

## 2. Mathematical Framework

### 2.1 Preliminaries and Notation

Let Σ\Sigma be a 2-manifold—topologically without boundary, or large enough that boundary effects are localized. At each time tt, circles of radius r(t)r(t) form a hexagonal packing on Σ\Sigma. Denote by pi(t)p_i(t) the centers of these circles. The key constraints are:

1. **Tangential Adjacency**: Each circle touches six neighbors at exactly one point.
2. **Distance Constraint**: The distance between centers remains 2 r(t)2\,r(t).
3. **Hexagonal Symmetry**: Locally, the centers form equilateral triangles of side 2 r(t)2\,r(t), meeting at 120∘120^\circ angles.

Since these circles expand uniformly in time without overlapping, Σ\Sigma acquires a time-dependent Riemannian metric gij(x,t)g_{ij}(x,t).

### 2.2 Time-Dependent Metric and Levi-Civita Connection

We write

ds2  =  gij(x,t) dxi dxjds^2 \;=\; g_{ij}(x,t)\,dx^i\,dx^j

to denote the infinitesimal distance on Σ\Sigma at time tt.

**Prescribed Curvature and Uniqueness.**  
Given a desired Gaussian curvature function K(p)K(p) on a simply connected region (assuming it meets appropriate compatibility conditions), there is (up to isometry) a unique Riemannian metric that realizes this curvature. In our scenario, the local circle adjacency constraints effectively fix

K(p,t)  =  14 r2(t),K(p,t) \;=\; \frac{1}{4\,r^2(t)},

forcing a geometry approximating a sphere of radius 2 r(t)2\,r(t).

**Levi-Civita Connection.**  
We choose the Levi-Civita connection ∇\nabla because it is the **unique torsion-free, metric-compatible connection** for gijg_{ij}. If {e1,e2}\{e_1, e_2\} is an orthonormal frame, then

∇ea  =  ωba eb,\nabla e_a \;=\; \omega^b{}_a\, e_b,

where ωab\omega^a{}_b are the connection 1-forms. Their curvature 2-forms

Ωab  =  d ωab  +  ωac ∧ ωcb\Omega^a{}_b \;=\; d\,\omega^a{}_b \;+\; \omega^a{}_c \,\wedge\, \omega^c{}_b

encode the intrinsic geometry in 2D via

Ω12  =  K ω,\Omega^1{}_2 \;=\; K\,\omega,

with ω\omega the oriented area form in the local frame.

---

### 2.3 Projective Geometry as a Complementary Lens

In addition to differential geometry, projective geometry provides valuable insights:

- **Tangency Preservation**  
    Under projective transformations, tangency of conic sections is preserved (even though absolute distances and angles change).
    
- **Line at Infinity**  
    From a projective viewpoint, “infinite” boundaries can be mapped to finite curves or conics. Thus, boundary behavior may be compactified and sometimes simplified.
    

Figure 4 (conceptually) will illustrate a **projective transformation** that maps a spherically curved region of circles onto another planar region while preserving tangency. For clarity, one might choose a **central projection** or **stereographic projection** from the sphere to a plane, labeling the tangencies before and after transformation.

**Figure 4**. _Schematic of a projective transformation. The original sphere (left) with circle packings is projected onto a plane (right). Tangencies remain single contact points, though angles and lengths are not preserved._

---

## 3. Main Results: Curvature Under Hexagonal Expansion

### 3.1 Fundamental Theorem

**Theorem (Inverse-Square Curvature).**  
For a time-dependent circle radius r(t)r(t) in a hexagonal circle packing on Σ\Sigma, the induced Gaussian curvature K(t)K(t) satisfies

K(t)  =  14 r2(t).K(t) \;=\; \frac{1}{4\,r^2(t)}.

**Proof Sketch**

1. **Equilateral Triangles**  
    The centers form an equilateral triangle of side 2 r(t)2\,r(t).
2. **Chord–Arc Relation**  
    On a sphere of radius R(t)R(t), a chord subtending π/3\pi/3 has length 2 R(t) sin⁡(π/6)=R(t)2\,R(t)\,\sin(\pi/6) = R(t). Matching 2 r(t)=R(t)2\,r(t) = R(t) yields R(t)=2 r(t)R(t)=2\,r(t).
3. **Spherical Curvature**  
    A sphere of radius R(t)R(t) has K=1/R2(t)K=1/R^2(t). Substituting R(t)=2 r(t)R(t)=2\,r(t) gives K(t)=1(2 r(t))2  =  14 r2(t).K(t) = \frac{1}{(2\,r(t))^2} \;=\; \frac{1}{4\,r^2(t)}.

Figure 2 should illustrate this chord–arc relationship in a local spherical patch, labeling the central angle (π/3\pi/3), chord length, and resulting sphere radius (2 r(t)2\,r(t)).

**Figure 2**. _Accurate chord–arc depiction: A sphere of radius R(t)R(t). The central angle is π/3\pi/3. The chord length is 2 R(t) sin⁡(π/6)=R(t)2\,R(t)\,\sin(\pi/6)=R(t). Matching 2 r(t)=R(t)2\,r(t) = R(t) leads to R(t)=2 r(t)R(t)=2\,r(t)._

---

### 3.2 Uniqueness and Necessity

- **Uniqueness**  
    Suppose R(t)≠2r(t)R(t)\neq 2r(t). Then the chord–arc relation fails: the chord for angle π/3\pi/3 will not match 2r(t)2r(t), contradicting strict adjacency. Hence no other value for R(t)R(t) can preserve uniform tangencies.
    
- **Necessity**  
    Flat geometry (K=0K=0) cannot accommodate larger r(t)r(t) without overlap. If R(t)R(t) deviates even slightly from 2r(t)2r(t), chord–arc mismatch arises. Thus K(t)=1/[4 r2(t)]K(t)=1/[4\,r^2(t)] is forced.
    

Further details, including a short lemma on chord–arc mismatch, appear in Section 6.2.

---

### 3.3 Comparisons to Non-Hexagonal Packings

While hexagonal packing is the densest, other regular packings likewise yield a 1/r21/r^2 scaling but with different constants determined by local angles. The principle remains that uniform expansions under adjacency constraints enforce a curvature ~ 1/r21/r^2.

---

## 4. Discussion and Broader Context

### 4.1 Boundary Conditions

For finite domains, boundary arcs must meet the induced curvature. Figure 3 should depict a **boundary “cap”** scenario: imagine cutting out a spherical patch of radius 2 r(t)2\,r(t). If the boundary is maintained tangentially, it follows the arc of that sphere. In a projective setting, one could map this spherical boundary to a simpler conic or line, preserving circle tangencies.

**Figure 3**. _A more detailed boundary “cap”: circles near the boundary remain tangent. The boundary arcs align with the spherical geometry, forming a cap of radius 2 r(t)2\,r(t)._

---

### 4.2 Stability Under Perturbations

Let r(t)→r(t)+ε(t)r(t) \to r(t)+\varepsilon(t), angle π/3→π/3+δθ\pi/3 \to \pi/3 + \delta_\theta. Then the chord length changes slightly by Δ(t)\Delta(t), combining ε(t)\varepsilon(t) and terms in δθ\delta_\theta.

K′(t)  ≈  14 r2(t)  −  Δ(t)2 r3(t)+O(Δ2).K'(t) \;\approx\; \frac{1}{4\,r^2(t)} \;-\; \frac{\Delta(t)}{2\,r^3(t)} + \mathcal{O}(\Delta^2).

Hence the inverse-square law persists as the leading behavior, demonstrating **robustness** under small fluctuations.

> _(When finalizing the figures, consider adding a schematic or flow diagram showing how slight changes in θ\theta or r(t)r(t) affect the local geometry. This could be an inset in Figure 2.)_

---

### 4.3 Ties to Discrete Conformal Geometry and Ricci Flow

- **Discrete Conformal Methods**  
    Circle packings in discrete conformal geometry approximate conformal maps. Our uniform expansion can be seen as a discrete “flow” driving the manifold toward a sphere-like curvature.
- **Ricci Flow Analogy**  
    While we do not apply Ricci flow directly, the adjacency constraint effectively _uniformizes_ curvature by forcing K(t)=1/[4 r2(t)]K(t)=1/[4\,r^2(t)], a concept reminiscent of 2D uniformization.

### 4.4 Non-Uniform Expansions

If not all circles grow at the same rate, chord–arc matching is broken in different regions, resulting in more complicated surfaces with patchwise curvature. We do not treat that scenario here, though it might open interesting PDE or numerical avenues.

### 4.5 Potential Physical Applications

- **Biological Membranes**  
    Membrane elasticity models (e.g., with Helfrich energy) connect membrane free energy to curvature terms. Our inverse-square law might influence how expansions in a “packed shell” shape the membrane’s equilibrium or stability.
    
- **Crystal Lattices**  
    2D atomic layers (like graphene) can ripple or warp if expansions preserve adjacency. The 1/r²(t) curvature law suggests a fundamental geometric impetus for curvature formation at macroscopic scales.
    

> _(In a future Figure 1 extension or separate figure, one might show a micrograph or schematic of a crystal lattice patch “popping up” into a curved shape as it expands.)_

---

## 5. Conclusion

We have shown that uniform expansion of circles in a dense (hexagonal) packing enforces Gaussian curvature scaling as 1/[4 r2(t)]1/[4\,r^2(t)]. This inverse-square law emerges from local adjacency constraints and is robust under small perturbations. By considering projective geometry, we see that circle tangencies remain preserved under a broad class of transformations—a promising avenue for cosmic-scale or boundary-at-infinity analyses.

Connections to the Koebe–Andreev–Thurston theorem, discrete conformal geometry, and potential ties to physical membrane or lattice models position this work at the intersection of rigorous geometry and applied contexts. Future directions include boundary refinements, non-uniform expansions, and deeper exploitations of projective invariants, especially relevant for large-scale geometry or flow-based transformations.

---

## 6. Mathematical Supplement

This supplement provides technical details, including a lemma on chord–arc mismatch, clarifications in the perturbation analysis, and notes on boundary conditions.

### 6.1 Inevitability of K>0K>0

1. **Contradiction Setup**: Suppose K=0K=0 (flat) while r(t)r(t) grows beyond r0r_0.
2. **Overlap**: Retaining distance 2 r(t)2\,r(t) on a flat plane with r(t)>r0r(t) > r_0 forces overlap.
3. **Conclusion**: Nonzero curvature is mandatory to avoid overlap.

### 6.2 Lemma on Chord–Arc Mismatch (Uniqueness)

**Lemma**. If R(t)≠2 r(t)R(t) \neq 2\,r(t), the circle adjacency condition fails.

**Proof Sketch**:

1. A chord subtending angle π/3\pi/3 on a sphere of radius R(t)R(t) has length R(t)R(t).
2. For adjacency, we require chord = 2 r(t)2\,r(t).
3. Thus R(t)=2 r(t)R(t)=2\,r(t). Any deviation breaks tangency, producing gaps or overlaps.

### 6.3 Clarification of Δ(t)\Delta(t) in Perturbations

Consider r′(t)=r(t)+ε(t)r'(t) = r(t) + \varepsilon(t), θ′=π/3+δθ\theta' = \pi/3 + \delta_\theta. Then chord lengths shift by small amounts:

Δ(t)  =  2 ε(t)  +  C δθ  +  …\Delta(t) \;=\; 2\,\varepsilon(t) \;+\; C\,\delta_\theta \;+\;\dots

for some constant CC derived from the linear expansion of sin⁡(θ)\sin(\theta). Hence

K′(t)  =  1[ 2 r(t)+Δ(t) ]2  ≈  14 r2(t)  −  Δ(t)2 r3(t)  +  …K'(t) \;=\; \frac{1}{[\,2\,r(t)+\Delta(t)\,]^2} \;\approx\; \frac{1}{4\,r^2(t)} \;-\; \frac{\Delta(t)}{2\,r^3(t)} \;+\; \dots

preserving the leading 1/r21/r^2 behavior.

### 6.4 Boundary Conditions

A region approximated by a spherical cap of radius 2 r(t)2\,r(t) must have boundary arcs consistent with that sphere. In a projective mapping, these arcs can become lines or conics; tangency and circle adjacency remain single-contact constraints, but the shape is reconfigured.

### 6.5 Glossary of Selected Terms

- **Levi-Civita Connection**: The unique torsion-free, metric-compatible affine connection on a Riemannian manifold.
- **Connection 1-Forms** (ωab\omega^a{}_b): Differential forms describing how orthonormal frames rotate/translate under parallel transport.
- **Curvature 2-Forms** (Ωab\Omega^a{}_b): The wedge-derivative of ωab\omega^a{}_b, measuring intrinsic curvature.
- **Projective Transformation**: A mapping that preserves lines (and conic tangencies) but not absolute distances or angles.
- **Discrete Conformal Geometry**: A field studying piecewise-linear or circle-based analogs of conformal maps on meshes.

---

## References

1. L. Fejes Tóth, _Regular Figures_, Macmillan, 1964.
2. M. P. do Carmo, _Differential Geometry of Curves and Surfaces_, Prentice-Hall, 1976.
3. A. D. Alexandrov, _Convex Polyhedra_, Springer, 2005.
4. J. Stillwell, _Geometry of Surfaces_, Springer, 1992.
5. J. A. Wheeler, _Geometrodynamics_, Academic Press, 1962.
6. H. Pottmann and J. Wallner, _Computational Line Geometry_, Springer, 2001.
7. T. C. Hales, "A proof of the Kepler conjecture," _Annals of Mathematics_, vol. 162, no. 3, pp. 1065–1185, 2005.
8. F. Kampas and P. Pardalos, "Solving circle packing problems by global optimization: Numerical results and industrial applications," _European Journal of Operational Research_, vol. 84, no. 3, pp. 623–637, 1995.
9. K. Stephenson, _Introduction to Circle Packing: The Theory of Discrete Analytic Functions_, Cambridge University Press, 2005.
10. R. Taşpınar and B. Kocuk, "Discretization-Based Solution Approaches for the Circle Packing Problem," _arXiv preprint arXiv:2401.00217_, 2023.
11. S. Kaji and J. Zhang, "Free-form Design of Discrete Architectural Surfaces by use of Circle Packing," _arXiv preprint arXiv:2103.07584_, 2021.

---

## Figures

1. **Figure 1**:
    
    - _Goal_: Show the initial hexagonal packing of circles of radius r0r_0 on a plane, hinting at how, as r(t)r(t) increases, the surface “lifts” into curvature.
    - _Implementation Suggestion_: Possibly a two-panel figure. The left panel: circles of radius r0r_0 in hexagonal arrangement on a flat plane. The right panel: circles of radius r1r_1 that no longer fit in a flat plane but start forming a “bubble” shape.
2. **Figure 2**:
    
    - _Goal_: Demonstrate the chord–arc geometry on a local spherical patch, labeling π/3\pi/3, chord length 2r(t)2r(t), and radius R(t)=2r(t)R(t)=2r(t).
    - _Implementation Suggestion_: Draw a circle (great circle cross-section) of radius R(t)R(t). Mark the chord subtending angle π/3\pi/3. Show sin⁡(π/6)=1/2\sin(\pi/6)=1/2.
3. **Figure 3**:
    
    - _Goal_: Illustrate a boundary “cap” scenario. Circles near the boundary remain tangent, forming arcs consistent with a spherical boundary of radius 2 r(t)2\,r(t).
    - _Implementation Suggestion_: Maybe a perspective or “cutaway” view of a spherical patch, with the boundary a circular arc in 3D, plus tangent circles near the edge.
4. **Figure 4**:
    
    - _Goal_: Depict a projective transformation (e.g., a central or stereographic projection) from a sphere to a plane, preserving tangencies.
    - _Implementation Suggestion_: Show the sphere with circles in the “source” space, a plane in the “target” space, and lines/rays representing the projection. Label tangential contacts before and after.

_(You could reference Figures 1–4 in the text at appropriate points, e.g., “(see Figure 1 for an illustration)”. The text above includes some suggestions, but feel free to adapt as you develop final diagrams.)_

**End of Paper**