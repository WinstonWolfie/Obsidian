$$
a^p \equiv a \pmod p
$$

where $a$ is an [[integer]] and $p$ is a [[prime number]]. It can also be stated as $a^p - a$ is an integer multiple of $p.$

For example, if $a = 2$ and $p = 7$, then $2^7 = 128$, and $128 - 2 = 126 = 7 \times 18$ is an integer multiple of $7.$

It's a special case of [[Euler's totient theorem]], because $\varphi(p) = p - 1,$ and

$$
a^{p-1} \equiv 1 \pmod p
$$

multiplied by $a$ on both sides gives $a^p \equiv a \pmod p.$

Anecdote: In my first Obsidian vault it looks like this:

> The original statement is $a^{p-1} \equiv 1 \pmod{p},$ where $a$ is an integer, $p$ is a prime number, and $a$ isn't divisible by $p.$
>
> A corollary, maybe a more concise statement, is obtained by multiplying both side by $a,$ thus getting $a^p \equiv a \pmod{p},$ and it's obvious that $a$'s divisibility by $p$ isn't needed any more.
>
> Looking at the corollary, we can proof it using simple combinatorics.
>
> ## Combinatoric proof
>
> Ask yourself: How many ways you can choose 5 balls from 2 bags with ball $A$ and ball $B$, each bag with 5 balls? If we list it out it's quite clear:
>
	$AAAAB, AAABA, AABAA, ABAAA, BAAAA,$
	$AAABB, AABBA, ABBAA, BBAAA, BAAAB,$
	$AABAB, ABABA, BABAA, ABAAB, BAABA,$
	$AABBB, ABBBA, BBBAA, BBAAB, BAABB,$
	$ABABB, BABBA, ABBAB, BBABA, BABAB,$
	$ABBBB, BBBBA, BBBAB, BBABB, BABBB,$
	$AAAAA,$
	$BBBBB.$
>
> Leaving $AAAAA$ and $BBBBB,$ thus the remainder is 2.
