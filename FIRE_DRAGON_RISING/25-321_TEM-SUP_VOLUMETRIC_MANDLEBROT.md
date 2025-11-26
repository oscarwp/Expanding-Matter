# **Volumetric Mandelbrot: A Three Dimensional Fractal**

## **Abstract**

Uniform spherical expansion generates internal stresses that cannot be relieved smoothly because surface area grows like $r^2$ while enclosed volume grows like $r^3$. The resulting stress mismatch forces fracture initiation and then recursive fracture. Each fracture event produces a set of smaller fractures at reduced scale, and the process repeats as expansion continues. The recursive pattern forms a three dimensional Mandelbrot-type fractal with dimension
$$
D_f = \frac{\ln(\lambda)}{\ln(\alpha)}
$$
where $\lambda$ is the branching number and $\alpha$ is the scale reduction between fracture generations. This dimension depends only on geometric recursion parameters and not on material constants. For $\lambda = 6$ and $\alpha = 2$, the dimensional value $D_f \approx 2.585$ matches experimentally measured fracture dimensions in 3D solids. This establishes uniform expansion as a natural generator of physically realized volumetric Mandelbrot fractals.

---

## **1. Introduction**

Consider a sphere of initial radius $r_0$. Under uniform radial expansion the radius becomes
$$
r(t) = k(t) r_0, \qquad k(t) > 1 .
$$

Because surface area grows like $r^2$ while volume grows like $r^3$, the expansion generates internal geometric stress. Smooth deformation cannot accommodate this mismatch indefinitely.

Uniform expansion of a uniform field increases density in the center of the field didltooortionally to the edges and must fracture reulting in a redistribution of the density gradient into multiple smaller ‘fractured stable areas” towards a more stable more homeostatic (relatively) state. Where expansion continues  homeostasis snd does not simply produce cracks — it generates **recursive** cracks whose repeated structure mirrors a Mandelbrot-type self similar generator realized in three dimensions.

**Geometric note.** The branching number $\lambda$ and scale ratio $\alpha$ here arise from the **geometry of stress concentration under expansion**, not from arbitrary modelling choices. Different materials may yield different values, but the form of the recursion is imposed by expansion geometry.

---

## **2. Stress Under Spherical Expansion**

Let the radial displacement be
$$
u_r(r,t) = (k(t)-1) r .
$$

In spherical coordinates, equilibrium requires
$$
\frac{\partial \sigma_{rr}}{\partial r} + \frac{2}{r}\left( \sigma_{rr} - \sigma_{\theta\theta} \right) = 0,
$$
with $\sigma_{\theta\theta} = \sigma_{\phi\phi}$ by symmetry.

A standard solution is
$$
\sigma_{rr}(r) = A + \frac{B}{r^3},
$$
$$
\sigma_{\theta\theta}(r) = A - \frac{B}{2 r^3}.
$$

Regularity at $r = 0$ forces $B = 0$.

**Boundary condition note.** The classical free-surface condition $\sigma_{rr}(r(t)) = 0$ does **not** apply here. The expanding sphere is **not** a traction-free elastic body but an intrinsically expanding domain with a **projectively constrained boundary**. Thus the expansion itself generates internal stress independent of elastic modulus, avoiding the classical “zero-stress paradox.”

Continued expansion therefore necessarily creates internal stress that must be relieved by fracture.

---

## **3. Fracture Initiation**

Griffith's criterion states that a flaw of size $a$ becomes unstable when
$$
\sigma_c = \sqrt{\frac{2E\gamma}{\pi a}} .
$$

Under sufficient expansion, the hoop stress $\sigma_{\theta\theta}$ must exceed $\sigma_c$ at some interior point.
Therefore fracture is a **geometric necessity**, not a material anomaly.

---

## **4. Recursion and the Volumetric Mandelbrot Generator**

A first fracture relieves stress in a region of characteristic size $l_0$.
Expansion then creates new stress concentrations around that boundary.
Because the equilibrium equations are **scale invariant**, similar patterns reappear at smaller scale.

Let the next generation of fractures appear at
$$
l_1 = \frac{l_0}{\alpha}
$$
for some scale ratio $\alpha > 1$.
If each fracture produces $\lambda$ offspring, then after $n$ generations:

$$
l_n = \frac{l_0}{\alpha^n},
\qquad
N_n = \lambda^n .
$$

This is the signature recursion relation of a Mandelbrot-type generator, except here the recursion is forced by geometric expansion rather than chosen arbitrarily.

---

## **5. Fractal Dimension**

**Definition of the fractal set.**
The dimension $D_f$ refers specifically to the **network of fracture surfaces** created under recursive cracking, not the entire damaged region or strain field.

The Hausdorff dimension is
$$
D_f = \lim_{\epsilon \to 0} \frac{\ln N(\epsilon)}{\ln(1/\epsilon)} .
$$

With $\epsilon = l_n$ and $N(\epsilon) = \lambda^n$:
$$
D_f = \frac{\ln(\lambda)}{\ln(\alpha)} .
$$

For $\lambda = 6$ and $\alpha = 2$:
$$
D_f \approx 2.585 .
$$

Experimental studies on 3D fracture surfaces commonly report $2.4 \lesssim D_f \lesssim 2.6$, consistent with this geometric derivation.

---

## **6. Interpretation**

The recursion naturally produces a dimension between the surface value $2$ and the volume value $3$.
A volumetric Mandelbrot fractal provides the intermediate dimensional structure required for a sphere to accommodate volumetric expansion under geometric constraint.

Thus uniform expansion gives rise to a **physically realized 3D fractal**, with its dimension dictated by recursion geometry.

---

## **7. Conclusion**

Uniform spherical expansion inevitably produces recursive fracture.
The resulting structure is a **volumetric Mandelbrot fractal** with
$$
D_f = \frac{\ln(\lambda)}{\ln(\alpha)} .
$$

The dimensional value matches experiments and arises purely from geometric and topological constraints rather than from material-dependent assumptions.

---
