---
tags:
  - teorema
  - álgebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado:
---
## Teorema
Sea $G$ un grupo finito de cardinalidad $p^{n}k$, donde $p$ es primo, $n$ es un entero positivo y $k$ un entero que no se divide por $p$. Un *p-subgrupo de Sylow* de $G$ es un subgrupo de orden $p^{n}$.

Luego si se cumple lo anterior, existe al menos un p-subgrupo de Sylow de orden $p^n$ 
## Demostración
Sea $\mathcal{S}$ el conjunto de todos lo subconjuntos de $G$ con $p^{n}$ elementos. Podemos definir la función
$$
G \times \mathcal{S} \to (g, \mathcal{S}) \mapsto \mathcal{gS}
$$
Lo que define una estructura de una [[Acción De Grupos]] de $G$ sobre $\mathcal{S}$. Luego sean $S_{1}, ... , S_{r} \in \mathcal{S}$ representantes de las distintas [[Orbita]]s de esta accion, Sabemos que es una unión disjunta debido a las [[Características De Las Orbitas]].
$$
\mathcal{S} = \text{orb}(S_{1}) \ \cup \ ... \ \cup \ \text{orb}(S_{r})
$$
Por el [[Lema de Congruencia Combinatoria de Subconjuntos]] sabemos que $|\mathcal{S}| \equiv k\ (\text{mod}\ p)$ y $k \neq 0 \ (\text{mod}\ p)$ por hipótesis. De modo que
$$
|\mathcal{S}| = |\text{orb}(S_{1})|\ +\ ...\ +\ |\text{orb}(S_{r})| \equiv k\ (mod\ p)
$$
Entonces existe una orbita $\text{orb}(S_{i})$ cuya cardinalidad no se divide por $p$ (ya que si no, $|\mathcal{S}| = 0$). Por simplicidad denotamos $S := S_{i}$ y $m$ su cardinalidad.

Por el [[Teorema Orbita-Estabilizador]] tenemos
$$
m = \frac{|G|}{|G_{S}|} = \frac{|p^{n}k|}{|G_{S}|} \Rightarrow |G_{S}| =  p^{n}t,  \; t \in \mathbb{N}
$$
Observamos que $g \in G_{S}$ significa que $gS = S$, en particular $gs \in S$ para cada $s \in S$. Luego la clase lateral $G_{S}s$ esta contenida en $S$ para cada $s \in S$.

Entonces $|G_{S}| = |G_{S}s| \leq |S| = p^{n}$. Esto implica que $|G_{S}| = p^{n}$, Luego $G_{S}$ es un p-subgrupo de Sylow de G.

Q.E.D
## Aplicaciones 
1. Supongamos que $P_{1}$ y $P_{2}$ sean dos p-subgrupos de Sylow en la misma orbita. Entonces $P_{1} = gP_{2}$ para algún $g \in G$. Esto implica que $e \in P_{2} \cup P_{1} = P_{2} \cup gP_{2}$ luego $P_{2} = gP_{2} = P_{1}$.

2. Sea $G$ un grupo de orden orden $15 = 3 \cdot 5$. Por este teorema $G$ tiene un $3$-subgrupo de Sylow y un $5$-subgrupo de Sylow.

   Observamos que los dos subgrupos de Sylow distintos cumplen que $H_{1} \cap H_{2} = \{e\}$ por el [[Teorema De Lagrange (Elementos)]] ya que los ordenes de los elementos tienen que ser diferentes.