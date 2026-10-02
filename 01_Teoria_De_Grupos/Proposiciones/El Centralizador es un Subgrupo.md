---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea un grupo $G$ y un subconjunto $A$ el centralizador $G_{G}(A)$ es un subgrupo de $G$.
## Demostración
1. Demostramos primero que el elemento neutro pertenece a $G_{G}(A)$, se ve fácilmente que para todo $a \in A$ se cumple que $ae = ea$, por lo tanto $e \in G_{G}(A)$.

 2. Ahora usando la definición típica, sean $x, y \in G_{G}(A)$ arbitrarios y evaluamos si $xy \in G_{G}(A)$, entonces sea un elemento $a \in A$. $$a(xy) = (ax)y = x(ay) = (xy)a$$Entonces $G_{G}(A)$ respeta la clausura sobre la operación de $G$. 
 3. Por ultimo verificamos la existencia de los inversos, para esto sea $g \in G_{G}(A)$ de modo que para todo $a \in A$ se cumpla que $ga =ag$. $$
\begin{aligned}
ga &= ag \\
g^{-1}ga &= g^{-1}ag \\
a &= g^{-1}ag \\
ag^{-1} &= g^{-1}agg^{-1} \\
ag^{-1} &= g^{-1}a
\end{aligned}
$$Por lo tanto $g^{-1} \in G_{G}(A)$ para todo $g$.
Al satisfacerse las tres condiciones demostramos que $G_{G}(A)$ es un subgrupo de $G$.
Q.E.D.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)