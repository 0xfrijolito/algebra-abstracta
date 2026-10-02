---
tags:
  - teorema
  - álgebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Teorema
Sean $H, N$ subgrupos normales de un grupo $G$ con $N \subset H$. Entonces $H/N$ es un subgrupo normal de $G/N$ y
$$
(G/N)/(H/N) \cong G/H.
$$
## Demostración
Consideremos la función
$$
f : G/N \to G/H, \; gN \mapsto gH. 
$$
Las funciones esta bien definida si $gN = g'N$ o sea $g^{-1}g' \in N$, entonces $g^{-1}g \in H$ luego $gH=g'H$. 

Es un homomorfismo:
$$
f(gH \cdot g'N) = f(gg'N) = gg'H = gH \cdot g'H = f(gN)\cdot f(g'N).
$$
Claramente es sobreyectiva y además
$$
\text{ker}(f) = \{gN \in G/N \mid gH = H \} = \{ gN \in G/N \mid g \in H \} = H/N
$$
Por lo tanto usando [[Primer Teorema Del Isomorfismo]] nos queda que.
$$
(G/N)/(H/N) \cong G/H.
$$
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)