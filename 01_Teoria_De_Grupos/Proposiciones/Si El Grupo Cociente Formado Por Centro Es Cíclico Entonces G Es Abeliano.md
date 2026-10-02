---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $G$ un grupo y $Z(G)$ su [[Centro]], si $G/Z(G)$ el [[Grupo Cociente]] es cíclico entonces $G$ es abeliano. 
## Demostración
Considerando el grupo y grupo cociente definido anteriormente, si $G/Z(G)$ es cíclico entonces existe un generador tal que.
$$
G/Z(G) = \left<aZ(G)\right>
$$
Por como esta definido sabemos que cualquier $gZ(G) \in G/Z(G)$ donde $g \in G$ un representante de la clase lateral. Se puede expresar como. 
$$
gZ(G) = a^{m}Z(G) \Rightarrow g = a^{m}.
$$
Ahora como el grupo cociente forma una partición del grupo $G$ podemos evaluar lo siguiente, sean $u, v \in a^{m}Z(G)$ representantes cualquiera de alguna clase lateral tales que $u = a^{m}z_{1}$ y $v = a^{m}z_{2}$ con $z_{1},z_{2} \in Z(G)$.
$$
uv = a^{m}z_{1}a^{m}z_{2} = a^{m}a^{m}z_{1}z_{2} = a_{m}a_{m}z_{2}z_{1} = a_{m}z_{2}a^{m}z_{1} = vu.
$$
Como esto funciona para cualquier elemento de la clase lateral $a^{m}Z(G)$ y para cualquier exponente del generador entonces todos los elementos de todas las particiones conmutan, es decir $G$ es abeliano.
Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)