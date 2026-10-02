---
tags:
  - proposicion
  - algebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea un grupo $G$ y un subgrupo $A$ entonces $N_{G}(A) \leq G$.
## Demostración
El normalizador se define como:
$$
\begin{aligned}
N_{G}(A) &= \{ g \in G \mid gAg^{-1} = A \} \\
&= \{ g \in G \mid gA = Ag \}
\end{aligned}
$$
Donde 
$$
gAg^{-1} = \{ gag^{-1} \mid a \in A \}
$$
Entonces sean $x, y \in N_G(A)$ evaluamos
$$
(xy^{-1})A(xy^{-1})^{-1} = x(y^{-1}Ay)x^{-1} = xAx^{-1} = A.
$$
Entonces $N_{G}(A) \leq G$. 

Q.E.D.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)