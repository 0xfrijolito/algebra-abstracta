---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: true
---
## Proposición
Para cualquier grupo $G$ y un conjunto no vacío $A$  existe una biyeccion entre la accion de $G$ sobre $A$ y un homomorfismo $G$ en el grupo de permutaciones de $S_{A}$.
## Demostración
La accion de $G$ sobre $A$ de define como todas las formas que actúa todo elemento $g \in G$ sobre todo elemento $a \in A$, donde una accion individual de $g$ se define como.
$$
\sigma_{g} : A \to A,\; a \mapsto g\cdot a
$$
Por lo tanto la accion de $G$ sobre $A$ son todas las acciones individuales de los elementos de $g \in G$ en para todo $a \in A$.
$$
\mathcal{X} = \{\;\sigma_g \mid \forall g\in G\;\}
$$
La cual se asocia a el conjunto $\mathcal{H}$ de todos los homomorfismos $\psi : G \to S_{A}$.
1. Ir de la accion al homomorfismo, entonces sea una permutación cualquiera inducida por un elemento $g \in G$ denotado como $\sigma_g$, el cual cumple lo siguiente
   - $e \cdot a = a$
   - $g \cdot (h \cdot a) = (gh) \cdot a$.
   Entonces sea el homomorfismo $\varphi(g) = \sigma_{g}$ donde obviamente cumple las propiedades de homomorfismo para la composición de funciones.

 1. Ir de los homomorfismos a la accion. Ahora empezamos un homomorfismo $\varphi \in \mathcal{H}$ inventamos una accion $\cdot$ a partir de $\varphi$ que cumpla los dos axiomas de las acciones de grupos.
   - **Axioma 1:** Dado un $\varphi$ sabemos que envía la identidad de $G$ a la identidad de $S_{A}$, entonces sea. $$ e \cdot a = \varphi(e)(a) = \text{Id}_{A}(a) = a $$
   - **Axioma 2:** Para cualquier $g, h \in G$ y $a \in A$ se tiene que $$(gh) \cdot a = \varphi(gh)(a) \Rightarrow = \varphi(g) \circ \varphi(h)(a)$$
Por lo tanto existe una biyeccion de las acciones de grupos de $G$ sobre $A$ al grupo de homomorfismos de $G \to S_{A}$.

Esto quiere decir que $G$ actúa similar al grupo de permutaciones sobre un conjunto $A$.

***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)