---
tags:
  - proposicion
---

## Proposición
Si $G$ es un grupo bajo la operación $*$. Para cado $a \in G$, $a^{-1}$ es únicamente determinado.
## Demostración
Asumimos que $b$ y $c$ son 2 inversos de $a$ y $e$ la identidad de $G$. Entonces $a \circ b = e$ y $a \circ c = e$.
$$
\begin{aligned} b &= e \cdot b && \text{(axiom (ii))} \\ &= (c \cdot a) \cdot b && \text{(since } e = c \cdot a \text{)} \\ &= c \cdot (a \cdot b) && \text{(associative law)} \\ &= c \cdot e && \text{(since } e = a \cdot b \text{)} \\ &= c && \text{(definition of } e \text{- axiom (ii))} \end{aligned}
$$
