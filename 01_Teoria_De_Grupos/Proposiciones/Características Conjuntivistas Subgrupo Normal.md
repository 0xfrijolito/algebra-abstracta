---
tags:
  - proposicion
  - algebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $G$ un grupo. 
1. Si $H \leq G$ y $N \unlhd G$, entonces $H \cap N \unlhd H$. 
2. si $N_{i} \unlhd G$, $i \in I$, entonces $\bigcap_{i \in I} N_{i} \unlhd G$ y $\left<N_{i} \mid i \in I\right> \unlhd G$. 
3. si $H \leq G$ y $N \unlhd G$, entonces $$HN := \{hn \mid h \in H, n \in N\} \leq G.$$Además $HN = NH = \left<H, N\right>$.
## Demostración
1. Para la primera proposición usamos los subgrupos definidos anteriormente como la intersección arbitraria de subgrupos es un subgrupo podemos tomar elementos arbitrarios $n \in H \cap N$ y $g \in H$ para evaluar su normalidad $gng^{-1} \in H$ ya que funciona para cualquier elemento de $H$ ya que este esta contenido en $G$ donde $N$ es normal.

2. Ahora considerando la misma estrategia sea un $g \in G$ y $n \in  \bigcap_{i \in I} N_{i} \unlhd G$ entonces $n \in N_{i}\; \forall i \in I$. Entonces $gng^{-1} \in N_{i}\; \forall i \in I$ es decir un subgrupo normal para $G$. 
 
   Luego evaluamos $\left<N_{i} \mid i \in I\right>$ donde sus elementos son las combinaciones de elementos de todos los grupos normales indexados.

   Entonces sea un elemento $g \in G$ y $n \in \left<N_{i} \mid i \in I\right>$ por lo tanto cumple que es producto de elementos de $N_{i}$ para todo $i$, $n = x_1 x_2 \cdots x_k$ donde cada $x_j \in N_{i_j}$.

   Formamos el conjugado y utilizamos el truco algebraico estándar de intercalar la identidad $e = g^{-1}g$ entre cada factor$$
   gng^{-1} = g(x_1 x_2 \cdots x_k)g^{-1} = (gx_1g^{-1})(gx_2g^{-1})\cdots(gx_kg^{-1})$$Como cada producto pertenece a algún $N_{i}$ entonces $\langle N_i \mid i \in I \rangle \unlhd G$
   
3. Ahora consideramos $HN := \{hn \mid h \in H, n \in N\}$, donde agarramos un elemento arbitrario $a b \in HN$ y evaluamos 
   $$
\begin{aligned} 
ab^{-1} &= h_{1}n_{1}n_{2}^{-1}h_{2}^{-1} \\ 
&= h_{1}n_{1}(h_{2}^{-1}h_{2})n_{2}^{-1}h_{2}^{-1} \\
&= (h_{1}n_{1}h_{2}^{-1})(h_{2}n_{2}^{-1}h_{2}^{-1}) \\
&= (h_{1}n_{1}h_{2}^{-1})n_{2}' \\
&= h_{1}h_{2}^{-1}(h_{2}n_{1}h_{2}^{-1})n_{2}' \\
&= (h_{1}h_{2}^{-1})(n_{1}'n_{2}') \\
&= (h'n') \in HN
\end{aligned}$$
   Luego como la identidad pertenece a $HN$ este es un subgrupo de $G$.

Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)