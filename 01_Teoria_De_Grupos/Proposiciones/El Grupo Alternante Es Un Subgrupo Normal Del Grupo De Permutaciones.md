---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: true
---
## Proposición
Sea $S_{n}$ un grupo de permutaciones, el grupo alternante $A_{n}$ es un subgrupo normal de $S_{n}$.
## Demostración
Si $\alpha = \text{id}$ por definición $\text{sign}(\text{id}) = +1$, así $\alpha = \text{id} \in A_{n}$. Luego sean $\alpha, \beta \in A_{n}$ evaluamos si es cerrado bajo su operación.
$$
\text{sign}(\alpha\beta) = \text{sign}(\alpha)\text{sign}(\beta) = (+1)(+1) = +1.
$$
Y por ultimo si es que se encuentran los inversos de nuestros elementos, sabemos que $\alpha^{-1}\alpha = \text{id}$ entonces.
$$
\text{sign}(\alpha^{-1}\alpha) = \text{sign}(\text{id}) = +1
$$
Por lo tanto $\text{sign}(\alpha) = +1 \Rightarrow \alpha \in A_{n}$.
Ahora para mostrar que es normal, sean $n \in A_{n}$  y $g \in S_{n}$ evaluamos $\text{sign}(gng^{-1})$.
$$
\text{sign}(gng^{-1}) = \text{sign}(g)\text{sign}(n)\text{sign}(g^{-1})
$$
1. Si $\text{sign}(g) = (-1)$ entonces.
$$
\text{sign}(gng^{-1}) = (-1)(+1)(-1) = +1
$$
2. Si $\text{sign}(g) = (+1)$ entonces
$$
\text{sign}(gng^{-1}) = (+1)(+1)(+1) = +1
$$

Así $gng^{-1} \in A_{n}$ entonces es un subgrupo normal.
Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)