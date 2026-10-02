---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $G$ un grupo y $a \in G$ el único elemento con orden 2, entonces $G_{G}(a) = G$.
## Demostración
Sea $a \in G$ el único elemento de orden 2 entonces y $g \in G$ un elemento arbitrario. Sabemos que la conjugación es un automorfismo interno de grupo y como todo isomorfismo persevera el orden de los elementos por lo tanto.
$$
|gag^{-1}| = |a| = 2
$$
Como definimos que $a$ es el único elemento de orden 2 entonces.
$$
gag^{-1} = a
$$
Luego imaginemos que existe un elemento $a,b \in G$ los cuales tienen orden 2, entonces
$$
\begin{aligned}
|gag^{-1}| = |gbg^{-1}| =2 
\end{aligned}
$$
Pero si $g = a$ tenemos 2 opciones
1. **Opción a:** $aba^{-1}= a$ Si multiplicamos por la derecha obtenemos que $ab = e$ pero como un elemento de orden 2 es su inverso al mismo tiempo $a = b$. Una contra 
2. **Opción b:** $aba^{-1}= b$, entonces agrupando obtenemos que $ab = ba$, luego si evaluamos su cuadrado $$
\begin{aligned}
(ab)^{2} = (ab)(ab) = a^{2}b^{2} = e 
\end{aligned}
$$
   Lo que nos deja con $ab = e \Rightarrow a = b$ una contradicción o que $a = e$ (sin perder generalidad) otra contradicción.
Por lo tanto queda demostrado que si $a$ es el único elemento con orden 2 entonces $G_{G}(a) = G$.
Q.E.D.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)