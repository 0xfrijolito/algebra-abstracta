---
tags:
  - álgebra
  - teorema
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Teorema
Sea $P$ un $p$-subgrupo de Sylow de un grupo finito $G$ y $Q$ un $p$-subgrupo de $G$. Entonces $Q$ esta contenido en un subgrupo conjugado de $P$.
## Demostración
Sea $\mathcal{P} = \{ gPg^{-1} \mid g \in G \}$ consideramos la Acción De Grupos de $G$ sobre $\mathcal{P}$ como la conjugación.

La orbita de $P$ es $\{P\}$. Mostramos que $P$ es el único elemento de $\mathcal{P}$ con esta propiedad.

Si la orbita de $gPg^{-1}$ contiene un solo elemento entonces
$$
xgPg^{-1}x^{-1} = gPg^{-1}, \ \forall x \in P
$$
o sea $g^{-1}xg \in N_{G}(P)$ para cada $x \in P$.

Entonces $g^{-1}Pg$ es un $p$-subgrupo de Sylow de $N_{G}(P)$. Luego $g^{-1}Pg = P$ . Luego $g^{-1}Pg= P$ por el lema de que [[Cada p-subgrupo del Normalizador De un P-subgrupo esta contenido en P]].

La orbita de cada elemento $\mathcal{P}$ es distinto a $P$ tiene largo $> 1$. 

Por [[Teorema Orbita-Estabilizador]] todas dichas orbitas tienen largo $\equiv 0$ modulo $p$. Entonces $|\mathcal{P}| = 1 \ (mod \ p)$ 

Ahora consideramos $\mathcal{P}$ como $Q$-conjunto con la conjugación. Como $|\mathcal{P}| \equiv 1 \ (mod \ p)$ y cada orbita tiene largo una potencia de $p$, existe una orbita de largo 1. Entonces existe $g \in G$ tal que $x(gPg^{-1})x^{-1} = gPg^{-1}$ para cada $x \in Q$.

Esto implica como antes que $g^{-1}Qg \subset N_{G}(P)$. Por el lema [[Cada p-subgrupo del Normalizador De un P-subgrupo esta contenido en P]] $g^{-1}Qg \subset P$, y luego $Q \subset gPg^{-1}$.

Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)