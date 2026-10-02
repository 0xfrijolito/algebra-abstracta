---
tags:
  - álgebra
  - teorema
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Teorema
Sea $G$ un grupo de orden $p^{n}k$ que cumple la definición del primer teorema. El numero de $p$-subgrupos de Sylow de $G$ es congruente a 1 modulo $p$.
## Demostración
Sea G una Acción De Grupos sobre $\mathcal{S}$ definido anteriormente. 
1. Mostraremos que cada orbita cuyo largo no se divide por $p$ tiene largo $k$ y contiene un único $p$-subgrupo de Sylow. Además cada $p$-subgrupo de Sylow esta contenido una solo de estas dichas orbitas. 
2. Entonces hay una biyeccion entre el conjunto de las orbitas cuyo largo no se divide por $p$ y el conjunto de $p$-subgrupos de Sylow.
3. Esto, junto al [[Lema de Congruencia Combinatoria de Subconjuntos]] y recordando que $k \neq 0 \ (\text{mod} \ p)$, permite concluir:$$ k \equiv |S| = \sum_{i=1}^{r}|\text{orb}(S_{i}) \equiv n_{p}k \Rightarrow n_{p} \equiv 1 \ (\text{mod} \ p)$$donde $n_{p}$ es el numero de $p$-subgrupos de Sylow.

Sabemos que $m = |\text{orb}(S)|$ que no se divide por $p$, entonces $m = k$. De hecho $G_{S}$ es un $p$-subgrupo de Sylow y $G_{S}s = S$ para cada $s \in S$. 

El subgrupo $s^{-1}G_{S}s = s^{-1}S \in \text{orb}(S)$ tiene la misma cardinalidad de $G_{S}, luego es un $p$-subgrupo de Sylow.

Viceversa, supongamos que la orbita contenga un $p$-subgrupo de Sylow $P$. Si $g \in G_{P}$, entonces $gP = P$, luego $ge = g \in P$. Entonces $G_{P} \subset P$.

Por otro lado claramente $P \subset G_{P}$, luego $P = G_{P}$. En particular, por el teorema [[Teorema Orbita-Estabilizador]], la orbita de $P$ tiene largo.
$$
\frac{G}{G_{P}} = \frac{|G|}{|P|} = \frac{p^{n}k}{p^{n}} = k.
$$
Que no se divide por $p$.

Supongamos que $P1$, $P_{2}$m sean dos $p$-subgrupos de Sylow contenidos en la misma orbita, entonces $P_{1} = gP_{2}$ para algún $g \in G$.

Esto implica que $e \in P_{2} \cup P_{1} = P_{2} \cup gP_{2}$, luego $P_{2} = gP_{2} = P_{1}$.

Q.E.D.

## Aplicación
1. Sea $G$ un grupo de orden orden $15 = 3 \cdot 5$. Por este teorema $G$ tiene un $3$-subgrupo de Sylow y un $5$-subgrupo de Sylow.

   Observamos que los dos subgrupos de Sylow distintos cumplen que $H_{1} \cap H_{2} = \{e\}$ por el [[Teorema De Lagrange (Elementos)]] ya que los ordenes de los elementos tienen que ser diferentes.
   
   Por este teorema el valor de $n_{5}$ es congruente a $1$ modulo $5$. Luego $n_{5} = 1$.

   Por lo mismo el numero $n_{3}$ es congruente a $1$ modulo $3$. Entonces $n_{3} = 1, 4. Entonces $G$ contiene $e$, $4$ elementos de orden $5$, y $2$ o $8$ de orden $3$.

   Por [[Teorema De Lagrange (Elementos)]] los demás elementos tienen orden 15, Luego $G$ es cíclico.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)