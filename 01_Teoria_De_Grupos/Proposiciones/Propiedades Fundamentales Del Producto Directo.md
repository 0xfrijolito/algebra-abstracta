---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $G_{1}, G_{2}, ..., G_{n}$ grupos entonces sea $G = G_{1} \times \cdots \times G_{n}$ su producto directo.
1. Para cada índice $i$ fijo el conjunto de elementos de $G$ que tiene las identidades de $G_{j}$ en la posiciones $j \neq i$ es isomorfo a $G_{i}$.
   $$ G_{i} \cong \{(e_{i},...,g_{i},...,e_{n}) \mid g_{i} \in G_{i} \}$$
   Si identificamos $G_{i}$ con su subgrupo, entonces $G_{i}$ es normal a $G$ y
$$ G/G_{i} \cong G_{1} \times \cdots \times G_{i-1} \times G_{i+1} \times \cdots \times G_{n} $$
2. Para cada $i$ fijo definimos $\pi_i : G \to G_{i}$ como
   $$ \pi_{i}((g_{i},g_{2},...,g_{n})) = g_{i}$$
   Donde $\pi_{i}$ es un homomorfismo sobreyectivo con
   $$ 
\begin{aligned}
\text{ker}(\pi_{i}) &= \{ (g_{i},...,g_{i-1},e_{i},g_{i+1},...,g_{n}) \mid g_{j} \in G_{j} \; \text{para todo}\; j \neq i \} \\
&\cong G_{1} \times \cdots \times G_{i-1} \times G_{i+1} \times \cdots G_{n}
\end{aligned}$$
3. Bajo la parte (1), si $x \in G_{i}$ y $y \in G_{j}$ para cada $i \neq j$ entonces $xy = yx$.
## Demostración
1. Sea el $G$ definido anteriormente entonces sea un $i$ fijo entonces definimos el homomorfismo 
   $$
\begin{aligned}
\varphi : G &\to G_{i} \times \cdots \times G_{i-1} \times G_{i+1} \times \cdots \times G_{n} \\
(g_{1},g_{2},...,g_{n}) &\mapsto (g_{1},...,g_{i-1},g_{i+1},...,g_{n})
\end{aligned}$$
   claramente sobreyectivo. Entonces nos queda el kernel
   $$
\begin{aligned}
\text{ker}(\varphi) &= \{(g_{1},...,g_{n}) \in G \mid (g_{1},...,g_{i-1},g_{i+1},...,g_{n}) = (e_{1},...,e_{i-1},e_{i+1},...,e_{n}) \} \\
&= \{(e_{1},...,g_{i},...,e_{n}) \mid g_{i} \in G_{i} \} \\
&\cong G_{i}
\end{aligned}
$$
   Por lo tanto usando el [[Primer Teorema Del Isomorfismo]] nos queda.
   $$
\begin{aligned}
G/\text{ker}(\varphi) &\cong \text{Im}(\varphi) \\
G/G_{i} &\cong G_{i} \times \cdots \times G_{i-1} \times G_{i+1} \times \cdots \times G_{n}
\end{aligned}
$$
2. Luego sea el homomorfismo definido en (2) entonces su kernel nos queda como 
   $$ 
\begin{aligned}
\text{ker}(\pi_{i}) &= \{ (g_{1},...,g_{n}) \in G \mid g_{i} = e_{i} \} \\
&\cong G_{i} \times \cdots \times G_{i-1} \times G_{i+1} \times \cdots \times G_{n}
\end{aligned}
$$
3. Por ultimo si $x = (e_{1},...,g_{i},...,e_{n})$ e $y = (e_{1},...,g_{j},...e_{n})$ entonces.
   $$ xy = (e_{1},...,g_{i},...,e_{n})(e_{1},...,g_{j},...e_{n}) = (e_{1},...,g_{j},...,g_{i},e_{n}) = yx $$

Q.E.D.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)