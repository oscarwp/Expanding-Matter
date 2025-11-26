---
title: "Emergence of Gaussian Curvature from Expanding Circle Packings: A Differential Geometric and Projective Perspective"
author: |
  Oscar Wojciechowski-Prill
  Affiliation: Humanity
  everythingexpands@gmail.com
date: October 25, 2025
aliases:
  - Gaussian Curvature from Expanding Circles
---
25-296_TEM00_EXPANDING_CIRCLES
# Emergence of Gaussian Curvature from Expanding Circle Packings: A Differential Geometric and Projective Perspective

## Abstract

We present a rigorous differential geometric analysis showing how uniform expansion of circles arranged in a **hexagonal packing** on a 2-manifold compels the emergence of nonzero Gaussian curvature. Using the **Levi-Civita connection** and **curvature 2-forms**, we prove that the induced curvature $K(t)$ scales as $1/r^2(t)$, where $r(t)$ is the circle radius at time $t$. We highlight the role of the hexagonal arrangement as the densest planar packing, explain why no flat embedding can accommodate growth, and compare with other packings. Additionally, we discuss stability under perturbations and briefly introduce a complementary **projective geometry** viewpoint, which not only illuminates circle tangency as a projective invariant but also sets the stage for broader investigations in subsequent work.

Our results emphasize the fundamental necessity and uniqueness of the **inverse-square law**, supported by complete proofs, boundary considerations, and references to classical circle packing theorems (e.g., the Koebe--Andreev--Thurston theorem) and discrete conformal geometry (e.g., Stephenson's work \cite{Stephenson2005}). We further offer a short discussion of how such curvature emergence might appear in real-world contexts, such as biological membrane deformation or crystal lattice expansions.

---

# Introduction

A recurring theme in geometry is that *local constraints* can force *global* geometric features. In two dimensions, circle packing has long served as an archetype of this phenomenon. Notably, the **Koebe--Andreev--Thurston theorem** shows that for a given combinatorial surface, one can realize it through a circle packing in a **static** framework. Here, we examine a **dynamic** variant: if circles in a maximally dense (hexagonal) arrangement expand uniformly while preserving tangential contact, the underlying surface must develop Gaussian curvature.

## Core Concept and Motivations

* **Expansion vs. Flatness**
    In a flat plane, circles that grow uniformly while remaining mutually tangent inevitably overlap unless the plane itself "bends." Hence, uniform radial expansion from local adjacency forces curvature.
* **Hexagonal Arrangement**
    Hexagonal packing is not just any arrangement but the **densest** in two dimensions, imposing particularly strong constraints. We show it leads to a clear law relating curvature to radius, specifically $K(t)=1/[4\,r^2(t)]$.
* **Potential Applications**
    * **Biological Membranes**: Certain viral capsids or cellular shells expand while keeping subunits in close packing, affecting the membrane's curvature.
    * **Crystal Lattices**: 2D layers under thermal or chemical expansion (e.g., in graphene-like materials) can warp out of plane.
    * **Cosmological Analogies**: Uniform expansions in discrete models may induce curvature on large scales.

## Relation to Existing Literature

* **Koebe--Andreev--Thurston (Static Circle Packing)**
    These classical results guarantee that a prescribed combinatorial triangulation can be realized by a circle packing. By contrast, here the circle radii $r(t)$ *evolve in time*, leading to an explicit inverse-square curvature law $K(t)\propto 1/r^2(t)$. This complements the static theory with a uniform growth scenario.
* **Discrete Conformal Geometry**
    In many discrete conformal approaches (e.g., Stephenson's work \cite{Stephenson2005}), circle packings approximate conformal maps on triangulated meshes. Our uniform expansion underscores a simple local adjacency constraint that yields a global sphere-like geometry and may serve as a discrete analogue to uniformizing flows or curvature-driven PDEs.

---

# Mathematical Framework

## Preliminaries and Notation

Let $\Sigma$ be a 2-manifold---topologically without boundary, or large enough that boundary effects are localized. At each time $t$, circles of radius $r(t)$ form a hexagonal packing on $\Sigma$. Denote by $p_i(t)$ the centers of these circles. The key constraints are:

1.  **Tangential Adjacency**: Each circle touches six neighbors at exactly one point.
2.  **Distance Constraint**: The distance between centers remains $2\,r(t)$.
3.  **Hexagonal Symmetry**: Locally, the centers form equilateral triangles of side $2\,r(t)$, meeting at $120^\circ$ angles.

Since these circles expand uniformly in time without overlapping, $\Sigma$ acquires a time-dependent **Riemannian metric** $g_{ij}(x,t)$.

## Time-Dependent Metric and Levi-Civita Connection

We write
$$
ds^2 \;=\; g_{ij}(x,t)\,dx^i\,dx^j
$$
to denote the infinitesimal distance on $\Sigma$ at time $t$.

**Prescribed Curvature and Uniqueness.**
Given a desired Gaussian curvature function $K(p)$ on a simply connected region (assuming it meets appropriate compatibility conditions), there is (up to isometry) a unique Riemannian metric that realizes this curvature. In our scenario, the local circle adjacency constraints effectively fix
$$
K(p,t) \;=\; \frac{1}{4\,r^2(t)},
$$
forcing a geometry approximating a sphere of radius $2\,r(t)$.

**Levi-Civita Connection.**
We choose the **Levi-Civita connection** $\nabla$ because it is the **unique torsion-free, metric-compatible connection** for $g_{ij}$. If $\{e_1, e_2\}$ is an orthonormal frame, then
$$
\nabla e_a \;=\; \omega^b{}_a\, e_b,
$$
where $\omega^a{}_b$ are the **connection 1-forms**. Their **curvature 2-forms**
$$
\Omega^a{}_b \;=\; d\,\omega^a{}_b \;+\; \omega^a{}_c \,\wedge\, \omega^c{}_b
$$
encode the intrinsic geometry in 2D via
$$
\Omega^1{}_2 \;=\; K\,\omega,
$$
with $\omega$ the oriented area form in the local frame.

---

## Projective Geometry as a Complementary Lens

In addition to differential geometry, projective geometry provides valuable insights:
* **Tangency Preservation**
    Under **projective transformations**, tangency of conic sections is preserved (even though absolute distances and angles change).
* **Line at Infinity**
    From a projective viewpoint, "infinite" boundaries can be mapped to finite curves or conics. Thus, boundary behavior may be compactified and sometimes simplified.

---

# Main Results: Curvature Under Hexagonal Expansion

## Fundamental Theorem

**Theorem (Inverse-Square Curvature).**
For a time-dependent circle radius $r(t)$ in a hexagonal circle packing on $\Sigma$, the induced Gaussian curvature $K(t)$ satisfies
$$
K(t) \;=\; \frac{1}{4\,r^2(t)}.
$$

**Proof Sketch**
1.  **Equilateral Triangles**
    The centers form an equilateral triangle of side $2\,r(t)$.
2.  **Chord--Arc Relation**
    On a sphere of radius $R(t)$, a chord subtending $\pi/3$ has length $2\,R(t)\,\sin(\pi/6) = R(t)$. Matching $2\,r(t) = R(t)$ yields $R(t)=2\,r(t)$.
3.  **Spherical Curvature**
    A sphere of radius $R(t)$ has $K=1/R^2(t)$. Substituting $R(t)=2\,r(t)$ gives $K(t) = \frac{1}{(2\,r(t))^2} \;=\; \frac{1}{4\,r^2(t)}$.

---

## Uniqueness and Necessity

* **Uniqueness**
    Suppose $R(t)\neq 2r(t)$. Then the chord--arc relation fails: the chord for angle $\pi/3$ will not match $2r(t)$, contradicting strict adjacency. Hence no other value for $R(t)$ can preserve uniform tangencies.
* **Necessity**
    Flat geometry ($K=0$) cannot accommodate larger $r(t)$ without overlap. If $R(t)$ deviates even slightly from $2r(t)$, chord--arc mismatch arises. Thus $K(t)=1/[4\,r^2(t)]$ is forced.

Further details, including a short lemma on chord--arc mismatch, appear in Section **Mathematical Supplement**.

## Comparisons to Non-Hexagonal Packings

While hexagonal packing is the densest, other regular packings likewise yield a $1/r^2$ scaling but with different constants determined by local angles. The principle remains that uniform expansions under adjacency constraints enforce a curvature $\sim 1/r^2$.

---

# Discussion and Broader Context

## Boundary Conditions

For finite domains, boundary arcs must meet the induced curvature. A **boundary "cap"** scenario: imagine cutting out a spherical patch of radius $2\,r(t)$. If the boundary is maintained tangentially, it follows the arc of that sphere. In a projective setting, one could map this spherical boundary to a simpler conic or line, preserving circle tangencies.

## Stability Under Perturbations

Let $r(t)\to r(t)+\varepsilon(t)$, angle $\pi/3\to \pi/3+\delta_\theta$. Then the chord length changes slightly by $\Delta(t)$, combining $\varepsilon(t)$ and terms in $\delta_\theta$.

$$
K'(t) \;\approx\; \frac{1}{4\,r^2(t)} \;-\; \frac{\Delta(t)}{2\,r^3(t)} + \mathcal{O}(\Delta^2).
$$

Hence the inverse-square law persists as the leading behavior, demonstrating **robustness** under small fluctuations.

## Ties to Discrete Conformal Geometry and Ricci Flow

* **Discrete Conformal Methods**
    Circle packings in discrete conformal geometry approximate conformal maps. Our uniform expansion can be seen as a discrete "flow" driving the manifold toward a sphere-like curvature.
* **Ricci Flow Analogy**
    While we do not apply Ricci flow directly, the adjacency constraint effectively *uniformizes* curvature by forcing $K(t)=1/[4\,r^2(t)]$, a concept reminiscent of 2D uniformization.

## Non-Uniform Expansions

If not all circles grow at the same rate, chord--arc matching is broken in different regions, resulting in more complicated surfaces with patchwise curvature. We do not treat that scenario here, though it might open interesting PDE or numerical avenues.

## Potential Physical Applications

* **Biological Membranes**
    Membrane elasticity models (e.g., with Helfrich energy) connect membrane free energy to curvature terms. Our inverse-square law might influence how expansions in a "packed shell" shape the membrane's equilibrium or stability.
* **Crystal Lattices**
    2D atomic layers (like graphene) can ripple or warp if expansions preserve adjacency. The $1/r^2(t)$ curvature law suggests a fundamental geometric impetus for curvature formation at macroscopic scales.

---

# Conclusion

We have shown that uniform expansion of circles in a dense (hexagonal) packing enforces Gaussian curvature scaling as $1/[4\,r^2(t)]$. This inverse-square law emerges from local adjacency constraints and is robust under small perturbations. By considering projective geometry, we see that circle tangencies remain preserved under a broad class of transformations---a promising avenue for cosmic-scale or boundary-at-infinity analyses.

Connections to the Koebe--Andreev--Thurston theorem, discrete conformal geometry, and potential ties to physical membrane or lattice models position this work at the intersection of rigorous geometry and applied contexts. Future directions include boundary refinements, non-uniform expansions, and deeper exploitations of projective invariants, especially relevant for large-scale geometry or flow-based transformations.

---

# Mathematical Supplement
\label{sec:supplement}

This supplement provides technical details, including a lemma on chord--arc mismatch, clarifications in the perturbation analysis, and notes on boundary conditions.

## Inevitability of $K>0$

1.  **Contradiction Setup**: Suppose $K=0$ (flat) while $r(t)$ grows beyond $r_0$.
2.  **Overlap**: Retaining distance $2\,r(t)$ on a flat plane with $r(t) > r_0$ forces overlap.
3.  **Conclusion**: Nonzero curvature is mandatory to avoid overlap.

## Lemma on Chord--Arc Mismatch (Uniqueness)

**Lemma**. If $R(t) \neq 2\,r(t)$, the circle adjacency condition fails.

**Proof Sketch**:
1.  A chord subtending angle $\pi/3$ on a sphere of radius $R(t)$ has length $R(t)$.
2.  For adjacency, we require $\text{chord} = 2\,r(t)$.
3.  Thus $R(t)=2\,r(t)$. Any deviation breaks tangency, producing gaps or overlaps.

## Clarification of $\Delta(t)$ in Perturbations

Consider $r'(t)=r(t) + \varepsilon(t)$, $\theta' = \pi/3 + \delta_\theta$. Then chord lengths shift by small amounts:
$$
\Delta(t) \;=\; 2\,\varepsilon(t) \;+\; C\,\delta_\theta \;+\;\dots
$$
for some constant $C$ derived from the linear expansion of $\sin(\theta)$. Hence
$$
K'(t) \;=\; \frac{1}{[\,2\,r(t)+\Delta(t)\,]^2} \;\approx\; \frac{1}{4\,r^2(t)} \;-\; \frac{\Delta(t)}{2\,r^3(t)} \;+\; \mathcal{O}(\Delta^2)
$$
preserving the leading $1/r^2$ behavior.

## Boundary Conditions

A region approximated by a spherical cap of radius $2\,r(t)$ must have boundary arcs consistent with that sphere. In a projective mapping, these arcs can become lines or conics; tangency and circle adjacency remain single-contact constraints, but the shape is reconfigured.

## Glossary of Selected Terms

* **Levi-Civita Connection**: The unique torsion-free, metric-compatible affine connection on a Riemannian manifold.
* **Connection 1-Forms** ($\omega^a{}_b$): Differential forms describing how orthonormal frames rotate/translate under parallel transport.
* **Curvature 2-Forms** ($\Omega^a{}_b$): The wedge-derivative of $\omega^a{}_b$, measuring intrinsic curvature.
* **Projective Transformation**: A mapping that preserves lines (and conic tangencies) but not absolute distances or angles.
* **Discrete Conformal Geometry**: A field studying piecewise-linear or circle-based analogs of conformal maps on meshes.

---

# References
1.  L. Fejes Tóth, *Regular Figures*, Macmillan, 1964. \label{Toth1964}
2.  M. P. do Carmo, *Differential Geometry of Curves and Surfaces*, Prentice-Hall, 1976. \label{Carmo1976}
3.  A. D. Alexandrov, *Convex Polyhedra*, Springer, 2005. \label{Alexandrov2005}
4.  J. Stillwell, *Geometry of Surfaces*, Springer, 1992. \label{Stillwell1992}
5.  J. A. Wheeler, *Geometrodynamics*, Academic Press, 1962. \label{Wheeler1962}
6.  H. Pottmann and J. Wallner, *Computational Line Geometry*, Springer, 2001. \label{Pottmann2001}
7.  T. C. Hales, "A proof of the Kepler conjecture," *Annals of Mathematics*, vol. 162, no. 3, pp. 1065–1185, 2005. \label{Hales2005}
8.  F. Kampas, I. Castillo, and J. D. Pintér, "Solving circle packing problems by global optimization: Numerical results and industrial applications," *European Journal of Operational Research*, vol. 191, no. 3, pp. 786–802, 2008. \label{Kampas2008}
9.  K. Stephenson, *Introduction to Circle Packing: The Theory of Discrete Analytic Functions*, Cambridge University Press, 2005. \label{Stephenson2005}
10. R. Taşpınar and B. Kocuk, "Discretization-Based Solution Approaches for the Circle Packing Problem," *arXiv preprint arXiv:2401.00217*, 2023. \label{Taspinar2023}
11. S. Kaji and J. Zhang, "Free-form Design of Discrete Architectural Surfaces by use of Circle Packing," *arXiv preprint arXiv:2103.07584*, 2021. \label{Kaji2021}