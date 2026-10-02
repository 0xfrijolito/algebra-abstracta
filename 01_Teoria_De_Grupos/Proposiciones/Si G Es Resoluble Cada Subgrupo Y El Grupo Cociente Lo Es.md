---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $G$ un grupo resoluble. Entonces
1. cada subgrupo $H$ de $G$ es resoluble,
2. cada grupo cociente $G/N$, con $N$ subgrupo normal de $G$, es resoluble.
## Demostración
Como $G$ es resoluble, tiene una serie normal
$$
G = G_{0} \geq G_{1} \geq \cdots \geq G_{r} = \{ e \}.
$$
Con cocientes $G_{0}/G_{1}, G_{1}/G_{2},...,G_{r-1}/G_{r}$ abelianos.
1. Consideramos la serie 
   $$ H = H \cap G_{0} \geq H \cap G_{1} \geq \cdots \geq H \cap G_{r} = \{ e \}. $$
   Es una serie normal para $H$, además por la [[Proposicion Zassenhaus]].
   $$ \frac{H \cap G_{i}}{H \cap G_{i+1}} = \frac{H \cap G_{i}}{(H \cap G_{i}) \cap G_{i+1}} \cong \frac{(H \cap G_{i})G_{i+1}}{G_{i+1}} \leq G_{i}/G_{i+1}$$
   Donde el isomorfismo es por el primer teorema del isomorfismo. Luego los cocientes son abelianos.

2. Sea $\pi : G \to G/N$ el homomorfismo cociente. Consideramos la serie
   $$ G/N = \pi(G_{0}) $$
   Observamos que $\pi(G_{i})$ es un subgrupo normal de $G/N$ para cada $i$ por ser $\pi$ sobreyectiva. Además los homomorfismos sobreyectivos $G_{i} \to \pi(G_{i})$ inducen un homomorfismo sobreyectivo.
   $$ G_{i}/G_{i+1} \to \pi(G_{i})/\pi(G_{i+1}). $$
   Como $G_{i}/G_{i+1}$ es abeliano, entonces $pi(G_{i})/\pi(G_{i+1})$ es abeliano también. Luego $G/N$ es resoluble.

Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)