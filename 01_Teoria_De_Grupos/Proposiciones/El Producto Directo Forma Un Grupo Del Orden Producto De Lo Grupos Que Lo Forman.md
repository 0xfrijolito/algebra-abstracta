---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $G = G_{1} \times \cdots \times G_{n}$ un producto de grupos, entonces el producto directo también es un grupo y orden $|G_{1}||G_{2}|\cdots|G_{n}|$.
## Demostración
Para que el conjunto anterior sea un grupo tiene que mantener los axiomas de grupo. Sea $G = G_{1} \times \cdots \times G_{n}$ donde tomamos los elementos $(a_{1},a_{2},...,a_{n}), (b_{1},b_{2},...,b_{n}), (c_{1},c_{2},...,c_{n}) \in G$ y evaluamos la asociatividad.
$$
\begin{aligned}
(a_{1},a_{2},...,a_{n})&[(b_{1},b_{2},...,b_{n})(c_{1},c_{2},...,c_{n})] \\
&= (b_{1}c_{1},b_{2}c_{2},...,b_{n}c_{n}) \\
&= (a_{1}(b_{1}c_{1}),a_{2}(b_{2}c_{2}),...,a_{n}(b_{n}c_{n})) \\
&= ((a_{1}b_{1})c_{1},(a_{2}b_{2})c_{2},...,(a_{n}b_{n})c_{n}) \\
&= [(a_{1},a_{2},...,a_{n})(b_{1},b_{2},...,b_{n})](c_{1},c_{2},...,c_{n}) \\
\end{aligned}
$$
Luego el elemento neutro se ve claramente de la expresión anterior $(e_{1}, e_{2},...,e_{n})$ y lo inversos son los inversos de cada componente.

Por ultimo el orden de $G$ esta claro.
Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)