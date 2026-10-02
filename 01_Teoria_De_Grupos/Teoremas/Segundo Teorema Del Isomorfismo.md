---
tags:
  - teorema
  - álgebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Teorema
Sean $H, N$ subgrupos de un grupo $G$ con $N$ normal. Entonces $N$ es un subgrupo normal de $\left<H, N\right> = HN$ y $H \cup N$ es un subgrupo normal de $H$. Además
$$
H/(H \cap N) \cong HN/N.
$$
## Demostración
Como $N$ es normal en $G$, entonces es normal en $NH$ también. Consideramos la función
$$
f : H \to HN/N, \; h \mapsto hN
$$
Es un homomorfismo:
$$
f(hh') = hh'N = hN \cdot h'N = f(h)f(h').
$$
Donde el kernel de $f$ es.
$$
\text{ker}(f) = \{ h \in H \mid hN = N \} = \{ h \in N \mid h \in N \} = H \cap N.
$$
Además $f$ es sobreyectiva entonces por el [[Primer Teorema Del Isomorfismo]] nos queda.
$$
H/(H \cap N) \cong HN/N.
$$
Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)