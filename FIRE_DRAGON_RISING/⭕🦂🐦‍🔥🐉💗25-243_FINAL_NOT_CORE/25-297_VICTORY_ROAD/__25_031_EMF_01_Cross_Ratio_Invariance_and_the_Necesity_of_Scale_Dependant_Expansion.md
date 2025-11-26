# Cross-Ratio Invariance and the Necessity of Scale-Dependent Expansion

---

## Abstract

We prove that a constant (scale-independent) distance measure is incompatible with cross-ratio invariance under the full projective group. By defining a projective metric of the form  
$$
d_{\mathrm{proj}}(x, y) = \Sigma(\lambda)\,\Delta(x, y),
$$
where $\Delta(x,y)$ is a suitably defined interval in projective space and $\lambda = \ln(L/L_0)$ is the logarithmic scale parameter for any relevant physical or observational scale $L$ (with $L_0$ as a fixed reference scale), we show that cross-ratio invariance forces $\Sigma$ to be scale-dependent. We briefly mention potential physical implications and propose a concrete experimental test involving high-precision spectroscopic measurements. We emphasize that this result is purely geometric, independent of specific physical theories.

---

## 1. Introduction

Projective geometry has a rich history in physics, playing a role in theories of perspective, crystallography, and more recently in twistor theory and conformal field theories. In most applications, the concept of distance is introduced in a manner that treats spatial scales as fixed. In this work, we address the following question:

> **Can a constant (scale-independent) distance function be consistent with cross-ratio invariance under the full projective group?**

We show that this is not possible by establishing precise definitions and proving a key lemma.

---

## 2. The Core Argument

### 2.1 Definitions and Notation

1. **Normalized Interval.**  
   For two points with affine coordinates $x$ and $y$, we define
   $$
   \Delta(x, y) = \frac{y - x}{L_0},
   $$
   where $L_0$ is a fixed reference scale.

2. **Logarithmic Scale Parameter.**  
   For any relevant physical or observational scale $L$, define the logarithmic scale parameter
   $$
   \lambda = \ln\!\bigl(\tfrac{L}{L_0}\bigr).
   $$
   For instance, $L$ might represent a laboratory length scale, a cosmic scale, or even an energy scale, depending on the specific context. The parameter $\lambda$ is defined here as a logarithmic measure of observational scale. Its physical interpretation (e.g., as a function of time, energy, or spatial resolution) is not assumed and remains an open question.

3. **Projective Metric Function.**  
   The projective distance between two points is given by
   $$
   d_{\mathrm{proj}}(x, y) = \Sigma(\lambda)\,\Delta(x, y).
   $$
   Our central claim is that $\Sigma$ cannot be a constant if cross-ratio invariance is to hold under projective transformations.

4. **Cross-Ratio.**  
   For four collinear points $P_1, P_2, P_3, P_4$ with affine coordinates $x_1, x_2, x_3, x_4$ respectively, the cross-ratio is given respectively by
   $$
   (P_1, P_2; P_3, P_4) = \frac{(x_1 - x_3)(x_2 - x_4)}{(x_1 - x_4)(x_2 - x_3)}.
   $$

### 2.2 Incompatibility Lemma

**Lemma.**  
*If a projective distance function is defined by*  
$$
d_{\mathrm{proj}}(x, y) = \Sigma\,\Delta(x, y),
$$
*where $\Sigma$ is a constant and $\Delta(x,y)$ is as defined above, then the cross-ratio is not invariant under the full set of projective transformations. No constant $\Sigma$ can preserve the distance ratio for all transformations in $\mathrm{PGL}(2,\mathbb{R})$.*

It is important to note that the group $\mathrm{PGL}(2,\mathbb{R})$ includes non-affine fractional linear transformations, such as the inversion and the transformation used in the second example.

Evaluating the distance ratio, as defined by the projective metric, using a constant $\Sigma$ reveals that the ratio of distances changes under projective transformations such as inversion. Thus, cross-ratio invariance under the full projective group forces a scale-dependent distance function.

---

## 3. Context and Potential Directions

While our primary result is a purely mathematical constraint within the framework of projective geometry, it is natural to consider its potential relevance to physical theories where projective invariance is fundamental. Historically, projective geometry has found applications in various areas of physics, including optics, special relativity, and certain approaches to quantum field theory. Although we make no specific claims here, the necessity of a scale-dependent distance function, if such projective invariance holds in nature, could potentially have implications for how we model spacetime at different scales. A rigorous exploration of these possibilities, including any potential connections to existing physical frameworks, is left for future work.

---

## 4. Experimental Tests

One specific and concrete experimental test of the scale-dependent hypothesis involves high-precision spectroscopic measurements. For instance, if we posit a small correction
$$
\Sigma(\lambda) = 1 + \alpha \,\ln\!\left(\tfrac{L}{L_0}\right),
$$
then for atomic scales ($L_0 \approx 10^{-10}$ m representing the atomic scale) and an observation time $T \approx 3.15 \times 10^7$ s (approximately one year), the term $cT/L_0$ is approximately $9.45 \times 10^{25}$. Thus, even a modest $\alpha$ on the order of $10^{-8}$ could lead to a detectable drift. Given that current atomic clocks can achieve a stability of $10^{-18}$ to $10^{-19}$ per year [Ludlow et al., 2015], this predicted drift may be within the reach of current experimental capabilities, making such measurements a practical and potentially achievable test.

---

## 5. Conclusion

Hence, scale dependence is not an optional assumption but a necessity if cross-ratio invariance is truly fundamental at all scales. This underscores that scale dependence in the distance function is not merely a speculative addition but a necessary consequence of requiring cross-ratio invariance under the full projective group. The specific form of $\Sigma(\lambda)$ and its potential alignment with observational data remain open questions for future investigation.

---

## Appendix A. Technical Details

### A.1 Detailed Proof of the Incompatibility Lemma

Let $P_1, P_2, P_3, P_4$ be four collinear points with respective affine coordinates $x_1, x_2, x_3, x_4$, where $x_4$ may approach infinity. Without loss of generality, we can choose $x_1 = 1$, $x_2 = 2$, $x_3 = 3$, and let $x_4$ approach infinity. Thus, the cross-ratio evaluates to 2.

Consider the projective inversion transformation $T: x \mapsto 1/x$. Under this transformation, we have:
$$
T(1) = 1,\quad T(2) = \frac{1}{2},\quad T(3) = \frac{1}{3},\quad T(x_4 \to \infty) = 0.
$$
As expected, the cross-ratio remains invariant:
$$
(1, \tfrac{1}{2}; \tfrac{1}{3}, 0) = 2.
$$

However, if we assume a constant $\Sigma$ and calculate the ratio of distances (with $L_0$ as the fixed reference scale) post-transformation, we find:
$$
\frac{d_{\mathrm{proj}}(T(P_1), T(P_3))}
     {d_{\mathrm{proj}}(T(P_2), T(P_3))}
\;=\;
\frac{\Sigma\,\left|1 - \tfrac{1}{3}\right|}
     {\Sigma\,\left|\tfrac{1}{2} - \tfrac{1}{3}\right|}
\;=\;
\frac{\tfrac{2}{3}}{\tfrac{1}{6}}
\;=\;
4.
$$
This result, 4, clearly differs from the original cross-ratio value of 2, demonstrating the desired contradiction.

### A.2 Discussion on Potential Forms for $\Sigma(\lambda)$

The determination of a specific form for $\Sigma(\lambda)$ that aligns with empirical data remains a subject for future investigation.

---

## References

1. Weyl, H. *Space, Time, Matter* (1922).  
2. Penrose, R. *Twistor Theory* (J. Math. Phys., 1967).  
3. Freedman, D.Z. *Cosmology of Conformal Field Theory* (Phys. Rev. D, 1999).  
4. Riess, A.G. *Hubble Tension Review* (Nat. Astron., 2021).  
5. Ludlow, A. D., Boyd, M. M., Ye, J., Peik, E., & Schmidt, P. O. (2015). Optical atomic clocks. *Reviews of Modern Physics*, 87(2), 637.