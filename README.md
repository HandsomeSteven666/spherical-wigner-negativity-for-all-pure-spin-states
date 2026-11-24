# Spherical Wigner Negativity for All Pure Spin States

Research manuscript by Xiuzhi Yang, 24 November 2026.

For every positive integer or half-integer spin, the spherical Wigner function of every normalized pure state takes a strictly negative value. The result holds for all sign choices of the self-dual Stratonovich–Weyl kernel, including the kernel specified in [problem F18 of Open Quantum Problems](https://openquantumproblems.com/p/F18).

The proof uses Gichev's orbit–hyperplane theorem to find a rotation taking the state to an orthogonal state. The trace identity and real analyticity of the spherical Wigner functions then give strict negativity. [Gichev's orbit–hyperplane theorem](https://arxiv.org/abs/math/0511688) · [Davis et al. on spin coherent states](https://doi.org/10.1088/1751-8121/acd918)

For each spin $j>0$, the paper also gives a uniform lower bound on the integrated negative part $\delta_j(\rho)$ over all pure states $\rho$ of that spin.

$$
\delta_j(\rho)\geq \frac{\sqrt{2j+1}}{4}
\exp\bigl(-4(1+e^{-1})j\bigr).
$$

## Manuscripts

| Language | PDF | LaTeX source |
| --- | --- | --- |
| English | [F18_en.pdf](F18_en.pdf) | [F18_en.tex](F18_en.tex) |
| Chinese | [F18_zh.pdf](F18_zh.pdf) | [F18_zh.tex](F18_zh.tex) |

Each source includes its bibliography. Compile with XeLaTeX twice to resolve cross-references. The Chinese edition uses the CTeX package.
