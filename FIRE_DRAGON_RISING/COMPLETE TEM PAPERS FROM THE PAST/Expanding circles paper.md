
---

# **Expanding Circles and Geometric Curvature**

## **Abstract**

This paper explores the geometric consequences of uniformly expanding circles arranged in a hexagonal packing—the densest circle packing in two dimensions. We derive the necessary curvature of the underlying surface to accommodate this expansion while maintaining adjacency among the circles. Using principles from spherical geometry and incorporating established mathematical results, we demonstrate that the Gaussian curvature required is inversely proportional to the square of the circle radius. We provide formal proofs of key claims and explicitly state the assumptions and conditions under which our derivations hold. Additionally, we highlight mathematical parallels between our findings and concepts in geometrodynamics. This work offers insights into how local geometric constraints dictate global curvature and connects to existing theories in differential geometry.

---

## **Introduction**

**Figure 1:** *Hexagonal packing of circles on a flat plane, with each circle touching six neighbors.*
![[Pasted image 20241118182821.png]]

In two-dimensional geometry, the hexagonal arrangement represents the densest possible packing of equal circles, as proven by Gauss and later rigorously confirmed by Fejes Tóth [1]. Each circle is in contact with six neighbors, forming a perfectly symmetrical and efficient pattern. Suppose each circle expands uniformly over time while maintaining contact with its neighbors. This scenario leads to a surprising geometric consequence: uniform expansion while maintaining adjacency on a flat plane is geometrically impossible without overlaps, necessitating curvature of the surface to accommodate the expansion without overlaps or gaps.

---

## **The Inevitability of Curvature**

As the circles expand, the distances between their centers must increase to maintain adjacency. On a flat plane, this increase would cause overlaps, violating the packing constraint.

**Figure 2:** *Overlapping circles due to expansion on a flat plane, illustrating the impossibility of maintaining adjacency during uniform expansion on a flat surface.*
![[Pasted image 20241118182835.png]]

To reconcile the expanding radii with the fixed contact topology, the surface must curve positively—similar to a sphere. This positive curvature allows the distances between circle centers to increase appropriately, thus maintaining adjacency without overlap. This phenomenon is an example of how local geometric constraints can induce global curvature, a concept explored in differential geometry [2].

---

## **Assumptions and Justifications**

Before deriving the necessary curvature, we explicitly state the assumptions and conditions under which our analysis is valid.

### **Assumptions**

1. **Uniform Expansion**: All circles expand uniformly over time; that is, the radius of each circle is a function of time \( r(t) \), and the rate of expansion is the same for all circles.

2. **Maintenance of Adjacency**: Circles remain in contact with their immediate neighbors throughout the expansion.

3. **Hexagonal Symmetry**: The packing maintains its hexagonal symmetry during expansion.

4. **Local Spherical Approximation**: The surface can be locally approximated as a sphere due to the uniform positive curvature required to accommodate the expansion.

5. **Idealized Infinite Surface**: We consider an idealized infinite or boundary-less surface where the hexagonal packing and uniform expansion can occur without edge effects or boundary discontinuities.

### **Justification of the Spherical Approximation**

In a flat plane, uniformly expanding circles maintaining adjacency would overlap. To prevent this, the plane must curve into a shape where the surface area increases sufficiently to accommodate the expansion without overlaps. The most symmetrical and uniform way to achieve this is by curving into a sphere or a portion of a sphere. The hexagonal symmetry and uniform expansion imply that the curvature must be the same in all directions (isotropic), which is a property of a sphere. Therefore, modeling the surface as a sphere is a valid approximation for our analysis.

While higher-order effects and deviations from perfect symmetry may exist in practical scenarios, they are considered negligible for the purposes of this idealized model. The spherical approximation is valid under the conditions of uniform expansion and perfect hexagonal symmetry assumed here.

---

## **Deriving the Necessary Curvature**

### **Geometric Relationships**

We model the surface locally as a sphere, justified by the need for uniform positive curvature to accommodate the uniformly expanding circles.

- **Circle Radius**: \( r(t) \)
- **Chord Length (Distance Between Centers)**: \( c(t) = 2r(t) \)
- **Arc Length Between Centers on Curved Surface**: \( d(t) = R(t) \phi \)
- **Radius of Curvature of the Surface**: \( R(t) \)
- **Angular Separation Between Adjacent Circles**: \( \phi = \dfrac{\pi}{3} \)

**Justification of \( \phi = \dfrac{\pi}{3} \):**

In the hexagonal packing, the centers of three mutually adjacent circles form an equilateral triangle. The interior angles of an equilateral triangle are \( 60^\circ \) or \( \dfrac{\pi}{3} \) radians. This angle represents the angular separation between adjacent circles when measured from the center of the sphere.

**Figure 3:** *Equilateral triangle formed by centers of three adjacent circles in hexagonal packing.*
![[Pasted image 20241118182848.png]]
### **Relating Chord Length and Arc Length**

On a sphere, the relationship between the chord length \( c(t) \), the central angle \( \phi \), and the radius \( R(t) \) is given by:

\[
c(t) = 2R(t) \sin\left( \dfrac{\phi}{2} \right)
\]

**Explanation:**

- **Chord Length**: The straight-line distance between two points on the sphere's surface.
- **Central Angle**: The angle subtended at the center of the sphere by the arc connecting the two points.

**Substituting \( c(t) = 2r(t) \):**

\[
2r(t) = 2R(t) \sin\left( \dfrac{\phi}{2} \right)
\]

Simplifying:

\[
r(t) = R(t) \sin\left( \dfrac{\phi}{2} \right)
\]

Since \( \phi = \dfrac{\pi}{3} \), half of this angle is \( \dfrac{\pi}{6} \). Recall that:

\[
\sin\left( \dfrac{\pi}{6} \right) = \sin(30^\circ) = \dfrac{1}{2}
\]

Therefore:

\[
R(t) = \dfrac{r(t)}{\dfrac{1}{2}} = 2r(t)
\]

### **Calculating the Gaussian Curvature**

**Definition 1:** *The radius of curvature \( R(t) \) at a point on a surface is the radius of the osculating sphere that best approximates the surface at that point [4].*

**Definition 2:** *The Gaussian curvature \( K(t) \) of a surface at a point is the product of the principal curvatures at that point. For a sphere of radius \( R(t) \), the Gaussian curvature is:*

\[
K(t) = \dfrac{1}{R^2(t)}
\]

Substituting \( R(t) = 2r(t) \):

\[
K(t) = \dfrac{1}{(2r(t))^2} = \dfrac{1}{4r^2(t)}
\]

Thus:

\[
K(t) = \dfrac{1}{4} \cdot \dfrac{1}{r^2(t)} \implies K(t) \propto \dfrac{1}{r^2(t)}
\]

### **Theorem 1**

**Theorem 1:** *The necessary Gaussian curvature \( K(t) \) to accommodate uniformly expanding circles in a hexagonal packing is inversely proportional to the square of the circle radius \( r(t) \).*

**Proof:** As shown above.

---

## **Formal Proofs of Key Claims**

### **Lemma 1: Inevitability of Positive Curvature**

**Lemma 1:** *Uniformly expanding circles arranged in a hexagonal packing on a surface necessitate positive Gaussian curvature to maintain adjacency without overlaps.*

**Proof:**

1. **Assumption:** Suppose the surface remains flat (zero curvature) as the circles expand.

2. **Contradiction:** In a flat plane, maintaining adjacency while increasing the radius \( r(t) \) leads to overlaps because the distance between circle centers remains constant, but the circles grow larger.

3. **Necessity of Increased Center Separation:** To avoid overlaps, the distance between circle centers must increase.

4. **Conclusion:** The only way to increase distances between centers while maintaining the hexagonal arrangement and adjacency is for the surface to curve positively. This introduces additional surface area, accommodating the larger circles without overlaps.

5. **Therefore:** Positive Gaussian curvature is inevitable under these conditions.

### **Theorem 2: Uniqueness of Curvature for Given Circle Radius**

**Theorem 2:** *For a given configuration of uniformly expanding circles in a hexagonal packing, the required Gaussian curvature \( K(t) \) is uniquely determined by the circle radius \( r(t) \).*

**Proof:**

1. From the geometric relationships, we derived:

   \[
   K(t) = \dfrac{1}{4r^2(t)}
   \]

2. This equation shows a direct functional relationship between \( K(t) \) and \( r(t) \), with no arbitrary constants or parameters.

3. Therefore, for each value of \( r(t) \), there is a unique corresponding value of \( K(t) \).

4. **Clarification:** These results are valid under the assumptions of uniform expansion, perfect hexagonal symmetry, and an idealized infinite surface, as detailed in the "Assumptions and Justifications" section. Deviations from these conditions are beyond the scope of this model.

---

## **Geometric Parallels to Geometrodynamics**

The mathematical relationship we have derived warrants careful examination in the context of geometric dynamics. Our finding that uniform expansion necessitates specific curvature relationships mirrors fundamental principles in geometrodynamics, as formalized by Wheeler [9].

### **Mathematical Relationship in Our Model**

In our model, the Gaussian curvature required by uniform expansion follows:

\[
K(t) = \dfrac{1}{4r^2(t)}
\]

This relationship emerges purely from the geometric constraints of maintaining adjacency during uniform expansion in a hexagonal packing.

### **Comparison with Geometrodynamics**

Geometrodynamics explores the geometry of spacetime and how it relates to gravitational phenomena. In certain formulations, the curvature of spacetime due to mass-energy distributions can exhibit inverse square relationships with respect to distance [9].

While the physical context differs, the mathematical form of the inverse square dependence is noteworthy. Both in our geometric model and in geometrodynamics, curvature scales inversely with the square of a characteristic length (in our case, the circle radius \( r(t) \)).

### **Clarifying the Mathematical Parallel**

- **Structural Similarity:** The inverse square relationship \( K \propto \dfrac{1}{r^2} \) appears in both our geometric derivation and in certain expressions within geometrodynamics.

- **Distinct Contexts:** It is important to note that, in geometrodynamics, curvature arises from the presence of mass-energy influencing spacetime, whereas in our model, curvature results from purely geometric constraints of expanding circles.

- **Mathematical Observation:** The similarity in mathematical form suggests a potential underlying connection in the way geometry governs structural relationships, even across different fields.

### **Academic Neutrality**

We emphasize that this comparison is a mathematical observation rather than a claim of physical equivalence. Our model is purely geometric, and any resemblance to physical theories is coincidental in terms of mathematical structure.

---

## **Clarification of Trigonometric Derivations**

To ensure clarity in our derivations, we provide detailed explanations of the trigonometric steps involved.

### **Explanation of \( \sin\left( \dfrac{\pi}{6} \right) = \dfrac{1}{2} \)**

- **Angle Conversion:**

  \[
  \dfrac{\pi}{6} \text{ radians} = 30^\circ
  \]

- **Sine of \( 30^\circ \):**

  \[
  \sin(30^\circ) = \dfrac{1}{2}
  \]

**Justification:**

In the unit circle, the sine of an angle corresponds to the y-coordinate of the point where the terminal side of the angle intersects the circle. For \( 30^\circ \), this value is \( \dfrac{1}{2} \).

### **Diagrammatic Representation**

**Figure 4:** *Unit circle illustrating the angle \( \dfrac{\pi}{6} \) and its corresponding sine value.*
![[Pasted image 20241118182906.png]]

By providing these explanations, we ensure that all readers, regardless of their familiarity with standard trigonometric values, can follow the derivations.

---

## **Future Work**

The mathematical parallel between expansion-induced curvature in our model and curvature relationships found in geometrodynamics suggests several promising directions for future research:

### **Exploring Higher Dimensions**

- **Three-Dimensional Analysis:**

  - Extend the concept to uniformly expanding spheres in close packing.
  - Examine how curvature relationships manifest in three dimensions.
  - Investigate whether similar inverse square relationships hold in higher-dimensional geometric configurations.

### **Mathematical Foundations**

- **Investigation of Uniform Expansion and Curvature:**

  - Explore the relationship between uniform expansion and geometric curvature in other contexts and geometries.
  - Analyze whether the inverse square relationship is a unique solution to maintaining geometric consistency under uniform expansion.

- **Connections to Geometric Dynamics:**

  - Study the mathematical similarities between our geometric findings and principles in geometrodynamics.
  - Consider whether insights from our model could inform or inspire new approaches in the study of geometric dynamics.

### **Potential Applications**

- **Interdisciplinary Exploration:**

  - Encourage collaboration between mathematicians and physicists to further examine the significance of the mathematical parallels.
  - Use our geometric model as a pedagogical tool to illustrate concepts in geometry and curvature.

---

## **Conclusion**

We have demonstrated that uniformly expanding circles arranged in a hexagonal packing necessitate a specific curvature of the underlying surface to maintain adjacency without overlaps. The Gaussian curvature required is inversely proportional to the square of the circle radius, leading the surface to become flatter as the circles expand.

By highlighting the mathematical parallels between our findings and concepts in geometrodynamics, we open avenues for future research that could deepen our understanding of geometric curvature. While our model remains purely geometric, the structural similarities in the mathematical relationships suggest potential interdisciplinary connections worth exploring.

By formalizing the mathematical relationships, explicitly stating our assumptions, and situating our findings within existing geometric theories, we provide a rigorous foundation for this phenomenon. Our model offers a fresh perspective on curvature and could serve as a useful analogy in educational contexts or inspire further mathematical exploration.

---

## **References**

1. L. Fejes Tóth, *Regular Figures*, Macmillan, 1964.

2. M. P. do Carmo, *Differential Geometry of Curves and Surfaces*, Prentice-Hall, 1976.

3. J. Stillwell, *Geometry of Surfaces*, Springer, 1992.

4. B. O'Neill, *Elementary Differential Geometry*, Academic Press, 1966.

5. A. D. Alexandrov, *Convex Polyhedra*, Springer, 2005.

6. F. Luo, "A Characterization of Spherical Polyhedral Surfaces," *Journal of Differential Geometry*, vol. 74, no. 3, pp. 407–424, 2006.

7. H. Pottmann and J. Wallner, *Computational Line Geometry*, Springer, 2001.

8. M. P. do Carmo, *Riemannian Geometry*, Birkhäuser, 1992.

9. J. A. Wheeler, *Geometrodynamics*, Academic Press, 1962.

10. J. B. Marion and S. T. Thornton, *Classical Dynamics of Particles and Systems*, 4th ed., Saunders College Publishing, 1995.

11. T. C. Hales, "A proof of the Kepler conjecture," *Annals of Mathematics*, vol. 162, no. 3, pp. 1065–1185, 2005.

---

## **Figures**

**Figure 1:** *Hexagonal packing of circles on a flat plane. Each circle touches six neighbors, forming the densest possible packing in two dimensions.*
![[Pasted image 20241118181616.png]]

**Figure 2:** *Illustration of overlapping circles due to uniform expansion on a flat plane. This demonstrates the impossibility of maintaining adjacency without curvature.*
![[Pasted image 20241118181608.png]]

**Figure 3:** *Equilateral triangle formed by the centers of three adjacent circles in hexagonal packing, illustrating the angular separation.*
![[Pasted image 20241118181600.png]]

**Figure 4:** *Unit circle illustrating the angle \( \dfrac{\pi}{6} \) and its corresponding sine value.*
![[Pasted image 20241118181545.png]]
---

## **Acknowledgments**

We thank the mathematical community for inspiring discussions on geometric packings and curvature, particularly the foundational work on circle packings and differential geometry.

---

## **Appendix**

### **Technical Terms Defined**

- **Hexagonal Packing:** An arrangement of circles where each circle is surrounded by six others, forming a hexagon. It is the most efficient way to pack circles in two dimensions.

- **Gaussian Curvature (\( K(t) \)):** A measure of intrinsic curvature at a point on a surface, defined as the product of the principal curvatures.

- **Radius of Curvature (\( R(t) \)):** The radius of the osculating sphere that best approximates the surface at a given point.

- **Spherical Geometry:** A branch of geometry that deals with figures on the surface of a sphere, where the usual rules of Euclidean geometry do not all apply.

- **Principal Curvatures:** The maximum and minimum curvatures of a surface at a given point, obtained in perpendicular directions.

---
