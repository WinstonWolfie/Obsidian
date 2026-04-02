$$
\sum_{n=1}^\infty \frac{1}{n^2} = \frac{1}{1^2} + \frac{1}{2^2} + \frac{1}{3^2} + \cdots
$$

## Proof using [[Maclaurin series]] of sin *x* and [[Vieta's formulas]]

$$
\sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \frac{x^7}{7!} + \cdots
$$

$$
\frac{\sin x}{x} = 1 - \frac{x^2}{3!} + \frac{x^4}{5!} - \frac{x^6}{7!} + \cdots
$$

let $z = x^2$

$$f(z) = 1 - \frac{z}{3!} + \frac{z^2}{5!} - \frac{z^3}{7!} + \dots$$

the roots of $f(z) = 0$ are

$$z = \pi^2, (2\pi)^2, (3\pi)^2, \dots, (n\pi)^2.$$

For [[polynomial]] $P(z) = 1 + a_1z + a_2z^2 + \dots$, Vieta's formula yields

$$\sum_{n=1}^{\infty} \frac{1}{r_n} = -a_1$$

where $r_n$ are roots, therefore

$$\frac{1}{\pi^2} + \frac{1}{(2\pi)^2} + \frac{1}{(3\pi)^2} + \dots = -\left(-\frac{1}{6}\right) = \frac{1}{6}$$

$$\frac{1}{\pi^2} \left( 1 + \frac{1}{2^2} + \frac{1}{3^2} + \dots \right) = \frac{1}{6}$$

$$\sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}.$$
