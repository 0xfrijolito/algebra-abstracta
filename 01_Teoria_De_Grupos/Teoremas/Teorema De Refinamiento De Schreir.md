---
tags:
  - teorema
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Teorema
Cada par de series subnormales (normales) de un grupo $G$ tienen refinamientos subnormales (normales) isomorfos.
## Demostración
Sean las series del grupo $G$.
$$
\begin{aligned}
G &= G_{0} \geq G_{1} \geq \cdots \geq G_{r} = \{ e \} \;\;\;\;\;\; (1) \\
G &= H_{0} \geq H_{1} \geq \cdots \geq G_{s} = \{ e \} \;\;\;\;\;\; (2) \\
\end{aligned}
$$
Encontramos un refinamiento que llamamos $(1')$ sobre $(1)$ y similar para la otra serie tenemos un refinamiento $(2')$ sobre $(2)$ que son isomorfos.

Se define $G_{i,j} := (G_{i} \cap H_{j})G_{i+1}$ para cada $j=0,...,s$ y $i=0,...,r-1$. 
Se tiene $G_{i,0} = (G_{i} \cap H_{0})G_{i+1} = G_{i}$, además $G_{i,s} = (G_{I} \cap H_{s})G_{i+1} = (G_{i+1})$.
Entonces para cada $i$ se obtiene un refinamiento.
$$
G_{i} = G_{i,0} \geq G_{i,1} \geq \cdots \geq G_{i,s} = G_{i+1} 
$$
Repitiendo para cada $i$ se obtiene un refinamiento de $(1)$. Observamos que se pueden omitir los términos $G_{i, s}$ cuando $i < r - 1$ porque.
$$
G_{i,s} = G_{i+1} = G_{i+1,0}
$$
Luego se obtiene un refinamiento de $(1)$ con $r(s+1) - (r-1) = rs + 1$ subgrupos.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)