---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $G$ u grupo con dos subgrupos $H$ y $K$ tal que
1. $H$ y $K$ son normales, y
2. $|H \cap K| = \{e\}$
Entonces $HK \cong H \times K$.
## Demostración
Primero sabemos que como uno de los subgrupos es normal por definición $HK \leq G$ y además por la proposición [[Unicidad de la Representación en Productos de Subgrupos]] existe solo una forma de expresar los elementos  de $HK$, entonces podemos definir el mapeo
$$
\begin{aligned}
\varphi : HK &\to H \times K \\
hk &\mapsto (h, k)
\end{aligned}
$$
Esta bien definida, además es un homomorfismo ya que sean $h_{1},h_{2} \in H$ y $k_{1}, k_{2} \in K$, entonces
$$
\begin{aligned}
\varphi(h_{1}k_{1}h_{2}k_{2}) &= (h_{1}h_{2}, k_{1}k_{2}) \\
&= (h_{1},k_{1})(h_{2},k_{2}) = \varphi(h_{1}k_{1})\varphi(h_{2}k_{2})
\end{aligned}
$$
Luego se ve que es biyectiva entonces es isomorfo.
$$
HK \cong H \times K.
$$
Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)