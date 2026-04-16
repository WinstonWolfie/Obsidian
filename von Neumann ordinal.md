$$
\begin{alignat}{2}
   0 &  && {} = \{\}             &&     {} = \varnothing \\
   1 & = 0 \cup \{0\} && {} = \{0\}   && = \{ \varnothing\} \\
   2 & = 1 \cup \{1\} && {} = \{0,1\} && {}  = \{\varnothing,\{\varnothing\}\}\\
   3 & = 2 \cup \{2\} && {} = \{0,1,2\} && {} = \{\varnothing,\{\varnothing\},\{\varnothing,\{\varnothing\}\}\} \\
 n & = n-1 \cup \{n-1\} && {} = \{0,1, ...,n-1\} && {} = \{\varnothing,\{\varnothing\},...,\{\varnothing,\{\varnothing\},...\}\}\\
  
 \end{alignat}
$$

thus, von Neumann ordinals are defined recursively as $0=\emptyset, 1=\{0\}, 2=\{0,1\},$ etc. This is in accordance with the [[axiom of infinity]].

A consequence of this definition is that every [[natural number]] is equal to the [[set]] of all preceding natural numbers.
