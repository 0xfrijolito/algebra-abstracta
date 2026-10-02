---
tags:
  - proposicion
  - algebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sean $\alpha, \beta \in S_{n}$. Si $\alpha$ y $\beta$ son **disjuntas**. Entonces conmuta,
## Demostración
**Caso 1:** Cuando $\alpha(i) = i, \beta(i) = i$. Es decir ambas permutaciones fijan el mismo elemento, Entonces, al componer, no importara que permutación se aplique primero.

**Caso 2:** Cuando $\alpha(i) = i, \beta(i) \neq i$. Si componemos, obtenemos que $\beta\alpha(i) = \beta(i)$. Como $\beta$ es inyectiva y $\beta(i) \neq i$ entonces $\beta(\beta(i)) \neq \beta(i)$. Así $\beta$ mueve a $\beta(i)$ y como $\alpha$ y $\beta$ son disjuntos $\alpha$ fija $\beta(i)$. Entonces
$$
\alpha\beta(i) = \alpha(\beta(i)) = \beta(i)
$$
Por lo tanto $\beta\alpha(i) = \alpha\beta(i)$.

**Caso 3:** Cuando $\alpha(i) \neq i, \beta(i) = i$. Es equivalente al **caso 2** entonces $\beta\alpha(i) = \alpha\beta(i)$.

Por lo tanto $\alpha$ y $\beta$ conmutan.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)