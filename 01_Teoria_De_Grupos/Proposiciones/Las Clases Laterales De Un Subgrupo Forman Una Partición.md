---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $N$ un subgrupo cualquiera de $G$. La colección de clases laterales izquierdas de $N$ en $G$ forman una partición de $G$. Además para todo $u, v \in G$, $uN = vN$ si y solo si $v^{-1}u \in N$ en particular, $uN = vN$ si y solo si $u, v$ son representantes de la misma clase lateral.
## Demostración
Primero notamos que $N$ es un subgrupo de $G$, Entonces $e \in N$. Como $g = ge \in gN$ para todo $g \in G$ se cumple
$$
G = \bigcup_{g \in G}gN
$$
Para mostrar que cada clase lateral izquierda tiene intersección vacía suponemos que $uN \cap vN = \emptyset$. Demostramos $uN = vN$. Sea $x \in uN \cap vN$
$$
x = un = vm, \;\; \text{Para algun n, m}\in N.
$$
Luego multiplicando por $n^{-1}$ y obtenemos
$$
u = vmn^{-1} = vm_{1} \;\; \text{Donde}\; m_{1} = mn^{-1} \in N.
$$
Ahora cualquier elemento $ut$ de $uN \; (t \in N)$, 
$$
ut = (vm_{1})t = v(m_{1}t) \in vN
$$
Por lo tanto $uN \subseteq vN$. Repitiendo la misma demostración para un $n_{1}$ obtenemos el resultado equivalente entonces $uN = vN$.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)