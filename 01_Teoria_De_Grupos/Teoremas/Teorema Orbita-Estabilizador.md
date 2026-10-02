---
tags:
  - teorema
  - accion
fecha_creacion:
ultima_edicion:
estudiado:
---
## Teorema
Sea $G$ un Grupo y sea X-un Acción De Grupos. Luego para cada la [[Orbita]] de cada $x \in X$ cumple que.
$$
|\text{orb}(x)| = |G:G_{x}|
$$
Donde $G : G_{x}$ se le llama índice del [[Estabilizador]] sobre $G$.
## Demostración
Dado $x \in X$ definimos la siguiente función
$$
\begin{aligned}
\theta: \; \text{orb}(x) &\to \{\text{clases laterales izquierdas de }G_{x}\} \\
g \cdot x & \mapsto gG_{x}.
\end{aligned}
$$
Mostramos que $\theta$ esta bien definida: Supongamos que $g \cdot x = h \cdot x$, luego
$$
(h^{-1}g) \cdot x = h^{-1} \cdot (g \cdot x) = h^{-1} \cdot (h \cdot x) = (h^{-1}h)\cdot x = x,
$$
luego $h^{-1}g \in G_{x}$ y $gG_{x} = hG_{x}$.
Claramente $\theta$ es sobreyectiva. Ahora mostramos que $\theta$ es inyectiva. Supongamos
$$
g_{1}G_{x} = \theta(g_{1}\cdot x) = \theta(g_{2}\cdot x) = g_{2}G_{x}.
$$
o sea $g_{2}^{-1}g_{1} \in G_{x}$. Entonces
$$
\begin{aligned}
g_{2}^{-1}g_{1} \cdot x &= x \\
\Rightarrow g_{2} \cdot (g_{2}^{-1}g_{1})\cdot x &= g_{2} \cdot x \\
\Rightarrow g_{1} \cdot x &=(g_{2}g_{2}^{-1}g_{1})\cdot x \\
&= g_{2} \cdot x
\end{aligned}
$$
Q.E.D.