---
tags:
  - definicion
---
## Definición
Sea $G$ un grupo y $H \leq G$ un [[Subgrupo]] de $G$. Dados $a, b \in G$, definimos la relación:
$$
a \equiv_{d}b \Leftrightarrow ab^{-1} \in H
$$
De forma similar se define
$$
a \equiv_{i}b \Leftrightarrow a^{-1}b \in H
$$
Las clases de equivalencia con respecto a la relación $\equiv_{d} ( \equiv_{i})$ se llaman ***clases laterales derechas (izquierdas)*** de $H$ en $G$.
- La clase de equivalencia de $a \in G$ con respecto $a \equiv_{d}$ es: $$\{b \in G \mid ba^{-1} \in H \} = \{ ha \mid  h \in H \}$$
  y se denotara con $Ha$ (clase lateral derecha).
- La clase de equivalencia de $a \in G$ con respecto $a \equiv_{i}$ es: $$\{b \in G \mid b^{-1}a \in H \} = \{ ah \mid  h \in H \}$$
  y se denotara con $aH$ (clase lateral izquierda).
## Propiedades
1. [[Las Clases Laterales De Un Subgrupo Forman Una Partición]]
2. [[Clausura De Las Clases Laterales]]
3. 

## Ejemplos
1. **Grupo De Permutaciones**
   Sean $G = S_{n}$ y $H = A_{n}$, con $n \geq 2$.
$$
\begin{align*}
(1\;2)\;A_n &= \{ (1\;2)\alpha \,|\, \alpha\in A_n\} \\
& = \{\beta \in S_n \,| \, sgn\,\beta = -1\}.
\end{align*}
$$
