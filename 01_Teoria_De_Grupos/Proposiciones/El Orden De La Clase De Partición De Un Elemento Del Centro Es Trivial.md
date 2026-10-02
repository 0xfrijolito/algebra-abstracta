---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea un grupo $G$ actuando sobre si mismo bajo la [[Accion De Conjugación]] y además sea el centro $Z(G)$, si $g \in Z(G)$ entonces $|cl(g)| = 1$.
## Demostración
Primero definimos la accion de $G$ sobre si mismo.
$$
\begin{aligned}
G \times G &\to G \\
(g, a)     &\mapsto gag^{-1}
\end{aligned}
$$
Entonces las orbitas de los elementos $a \in G$ generan una partición, y las llamamos $cl(a)$ clases de partición.

Luego sea $a \in Z(G)$ y evaluamos su orbita.
$$
\begin{aligned}
	\text{orb}(a) &= \{ gag^{-1} \mid g \in G \} \\
	              &= \{ agg^{-1} \mid g \in G \} \\
	              &= \{ a \}
\end{aligned}
$$
Q.E.D.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)