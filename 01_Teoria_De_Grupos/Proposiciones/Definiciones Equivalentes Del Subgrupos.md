---
tags:
  - algebra
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: true
---
## Proposición
Dado un subconjunto $H$ de un grupo $G$, son equivalentes:
1. $H$ es un subgrupo de $G$;
2. $H \neq \emptyset$ y $ab^{-1} \in H$ para cada $a, b \in H$.
## Demostración
- **$(1) \Rightarrow (2)$**
  Sean $a, b \in H$ entonces $b^{-1} \in H$ de modo que $a(b^{-1})^{-1} = ab \in H$ para cualquier $a, b \in H$.  

- $(2) \Rightarrow (1)$
  Consideremos un conjunto $H$ tal que cualquiera sean los elementos $a, b \in H$  $ab^{-1} \in H$, entonces si $a = b$ (y sin perder la generalidad) se cumple $aa^{-1} = e \in H$. Luego $eb^{-1} = b^{-1} \in H$.

  Por ultimo si $b^{-1} \in H$ entonces $a(b^{-1})^{-1} = ab \in H$ luego la operación respeta la asociatividad de $G$ por lo tanto $H \leq G$.

   Q.E.D.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)