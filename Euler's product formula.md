$$
\zeta(s) = \sum_{n=1}^\infty\frac{1}{n^s} = \prod_{p \text{ prime}} \frac{1}{1-p^{-s}}
$$

where $\zeta(s)$ is the [[Riemann zeta function]].

## Proof

$$
\zeta(s) = 1+\frac{1}{2^s}+\frac{1}{3^s}+\frac{1}{4^s}+\frac{1}{5^s}+ \ldots
$$

$$
\frac{1}{2^s}\zeta(s) = \frac{1}{2^s}+\frac{1}{4^s}+\frac{1}{6^s}+\frac{1}{8^s}+\frac{1}{10^s}+ \ldots
$$

$$
\left(1-\frac{1}{2^s}\right)\zeta(s) = 1+\frac{1}{3^s}+\frac{1}{5^s}+\frac{1}{7^s}+\frac{1}{9^s}+\frac{1}{11^s}+\frac{1}{13^s}+ \ldots
$$

$$
\frac{1}{3^s}\left(1-\frac{1}{2^s}\right)\zeta(s) = \frac{1}{3^s}+\frac{1}{9^s}+\frac{1}{15^s}+\frac{1}{21^s}+\frac{1}{27^s}+\frac{1}{33^s}+ \ldots
$$

$$
\left(1-\frac{1}{3^s}\right)\left(1-\frac{1}{2^s}\right)\zeta(s) = 1+\frac{1}{5^s}+\frac{1}{7^s}+\frac{1}{11^s}+\frac{1}{13^s}+\frac{1}{17^s}+ \ldots
$$

$$
\ldots \left(1-\frac{1}{11^s}\right)\left(1-\frac{1}{7^s}\right)\left(1-\frac{1}{5^s}\right)\left(1-\frac{1}{3^s}\right)\left(1-\frac{1}{2^s} \right)\zeta(s) = 1
$$

$$
\zeta(s) = \frac{1}{\left(1-\frac{1}{2^s}\right)\left(1-\frac{1}{3^s}\right)\left(1-\frac{1}{5^s}\right)\left(1-\frac{1}{7^s}\right)\left(1-\frac{1}{11^s}\right) \ldots }
$$

$$
\zeta(s) = \prod_{p \text{ prime}} \frac{1}{1-p^{-s}}.
$$
