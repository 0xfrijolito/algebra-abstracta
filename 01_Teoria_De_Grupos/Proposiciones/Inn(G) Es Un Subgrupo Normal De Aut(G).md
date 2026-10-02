---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $G$ un grupo cualquiera entonces $Inn(G)$ es un subgrupo de $Aut(G)$. 
## Demostración
Sea entonces $Aut(G)$ el grupo formado por todos los isomorfismos, Luego sean los isomorfismos
$$
\begin{aligned}
\varphi_g : G &\to G \\
x &\mapsto gxg^{-1}
\end{aligned}
$$
que se encuentran en $Inn(G)$ donde $\varphi_{e}$ se encuentra y es el isomorfismo identidad. Luego sean $\varphi_{a}, \varphi_{b} \in Inn(G)$ nos interesa obtener que
$$
(\varphi_{a} \circ \varphi_{b}^{-1})(x) \in Inn(G)
$$
Entonces  
$$
\begin{aligned}
(\varphi_{a} \circ \varphi_{b}^{-1})(x) &= \varphi_{a}(\varphi_{b}^{-1}(x)) \\
&=  a(\varphi_{b}^{-1}(x))a^{-1}
\end{aligned}
$$
Como $\varphi_{b}^{-1} \in Aut(G)$ entonces el resultado de esa operación es un elemento $y \in G$ tal que $byb^{-1} = x \Rightarrow y = b^{-1}xb$.
$$
\begin{aligned}
\varphi_{a}(\varphi_{b}^{-1}(x)) &= (ab^{-1})x(ba^{-1}) \\
&= (ab^{-1}) x (ab^{-1})^{-1} = \varphi_{ab^{-1}}(x) \in Inn(G)
\end{aligned}
$$
Entonces es un subgrupo de $Aut(G)$.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)