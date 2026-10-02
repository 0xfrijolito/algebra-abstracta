---
tags:
  - proposicion
  - algebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: true
---
## Proposición
$Inn(G)$ es un subgrupo de $Aut(G)$ y $G/Z(G) \cong Inn(G)$.
## Demostración
Consideremos la función
$$
\theta: G \to Aut(G), \; x \mapsto \phi_x
$$
Un homomorfismo ya que absorbe esa propiedad de su imagen. Luego $\theta$  la imagen $\text{Im}(\theta) = Inn(G)$ claramente.

Entonces el kernel nos queda como
$$
\text{ker}(\theta) = \{ g \in G \mid \phi_x = id \} = \{ g \in G \mid xgx^{-1} = g ,\; \forall g\in G \} = Z(G)
$$
Entonces usando [[Primer Teorema Del Isomorfismo]]
$$
G/Z(G) \cong Inn(G).
$$

***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)