---
tags:
  - proposicion
---
## Proposición
Sea $X$ un $G$-conjunto y $x \in X$. El estabilizador $G_x = \{g \in G \mid g \cdot x = x\}$ es un subgrupo de $G$.
## Demostración
Para demostrar que $G_x \leq G$, verificaremos las tres condiciones del criterio de subgrupos:

**1. El elemento neutro pertenece a $G_x$:**
Sea $e \in G$ el elemento neutro del grupo. Por el primer axioma de la acción de un grupo sobre un conjunto, sabemos que:
$$
e \cdot x = x
$$
Por definición del estabilizador, esto implica que $e \in G_x$. Así, $G_x \neq \emptyset$.

**2. Cerradura bajo la operación del grupo:**
Sean $g, h \in G_x$. Esto significa que $g \cdot x = x$ y $h \cdot x = x$. Evaluamos la acción de la composición $(gh)$ sobre $x$ usando el segundo axioma de acciones de grupo (compatibilidad):
$$
(gh) \cdot x = g \cdot (h \cdot x) = g \cdot x = x
$$
Como $(gh) \cdot x = x$, concluimos que $gh \in G_x$.

**3. Cerradura bajo la toma de inversos:**
Sea $g \in G_x$, de modo que $g \cdot x = x$. Aplicamos la acción del inverso $g^{-1} \in G$ a ambos lados de esta igualdad:
$$
\begin{aligned}
g^{-1} \cdot (g \cdot x) &= g^{-1} \cdot x \\
(g^{-1}g) \cdot x &= g^{-1} \cdot x \\
e \cdot x &= g^{-1} \cdot x \\
x &= g^{-1} \cdot x
\end{aligned}
$$
Dado que $g^{-1} \cdot x = x$, entonces $g^{-1} \in G_x$.

Al satisfacerse las tres condiciones, demostramos que $G_x$ es efectivamente un subgrupo de $G$.
Q.E.D.