An integer has the form $a — b$, where $a$ and $b$ are [[natural number]]s. Two integers are considered to be equal, $a — b = c — d$, if and only if $a + d = c + b.$ (Terence Tao, Analysis I)

Informally, integers are what you get by subtracting two [[natural number]]s.

In [[set theory]] terms, we are starting with the [[space]] $\mathbf N \times \mathbf N$ of [[ordered pairs]] $(a, b)$ of natural numbers. Then we declare $(a, b) \sim (c, d)$ iff $a + d = c + b.$ Note that $a — b$ is the space of all pairs equivalent to $(a, b) : a — b := \{(c, d) \in \mathbf{N} \times \mathbf{N} : (a, b) \sim (c, d)\};$ by [[axiom of replacement]], we get $\mathbf Z = \{a — b : (a, b) \in \mathbf N \times \mathbf N\}.$

Consider that if $(a, b) = (0, 2),$ then $0 — 2$ is the set

$$
\{(0, 2), (1, 3), (2, 4), (3, 5), \dots\}
$$

note that they are all natural numbers, thus constructing $\mathbf Z$ from $\mathbf N.$ The axiom of replacement ensures $\mathbf Z$ is a set because we have a starting set and a clear mapping.