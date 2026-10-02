---
tags:
  - proposicion
  - algebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Si $\varphi : G_{2} \to G_{2}$ es un homomorfismo de grupos, entonces 
1. $\varphi(ab^{−1}) = \varphi(a)\varphi(b)^{−1}$ y $\varphi(b^{−1}a) = \varphi(b)^{−1}\varphi(a)$ para cada $a, b ∈ G_1$, 
2. $\varphi(a^{−1}) = \varphi(a)^{−1}$ para cada $a \in G_{i}$, 
3. $\text{ker}(\varphi) := \{a \in G_{1} \mid \varphi(a) = e \}$ es un subgrupo normal de $G_{1}$, 
4. $\text{Im}(\varphi) := \{\varphi(a) \mid a \in G_{1} \}$ es un subgrupo de $G_{2}$.
## Demostración
1. Como  $\varphi(1_{G}) = \varphi(1_{G} 1_{G}) = \varphi(1_{G})\varphi(1_{G})$, bajo la ley de cancelación (1) se sostiene.
2. $\varphi(1_{G}) = \varphi(gg^{-1})=\varphi(g)\varphi(g^{-1})$ usando el resultado (1) $1_{H} = \varphi(g)\varphi(g^{-1}) \Rightarrow \varphi(g^{1}) = \varphi(g)^{-1}$.
3. Esta parte esta demostrada en [[Kernel]] 
4. Ya que $\varphi(1_G) = 1_{H} \in \text{Im}(\varphi)$, luego sea $x, y \in \text{Im}(\varphi)$ entonces existe un $a, b \in G_{1}$ tal que $\varphi(a) = x$ e $\varphi(b) = y$ entonces evaluamos 
   $$ \varphi(a)\varphi(b)^{-1} = \varphi(ab^{-1}) = \varphi(c) \in \text{Im}(\varphi)$$
   Por lo tanto es un subgrupo de $H$.
Q.E.D.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)