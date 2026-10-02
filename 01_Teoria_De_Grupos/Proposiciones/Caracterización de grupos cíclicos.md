---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sean $m, n \in \mathbb{Z}^{+}$.
1. $\mathbb{Z}/m\mathbb{Z} \times \mathbb{Z}/n\mathbb{Z} \cong \mathbb{Z}/nm\mathbb{Z}$ si y solo si $\text{gcd}(n, m) = 1$.
## Demostración
1. Vamos primero de izquierda a derecha $\Rightarrow$, entonces sea $\varphi$ el isomorfismo entre los grupos definido como.
   $$ \varphi : \mathbb{Z}/nm\mathbb{Z} \to \mathbb{Z}/n\mathbb{Z} \times \mathbb{Z}/m\mathbb{Z} $$
   ya que $\mathbb{Z}/nm\mathbb{Z}$ es cíclico con generador $a$, sabemos que para cualquier $x \in \mathbb{Z}/nm\mathbb{Z}$ se cumple para algún $j \in \mathbb{Z}$.
   $$ \varphi(x) = \varphi(a^{j}) = \varphi(a)^{j} $$
   Entonces usando el orden $nm$ nos queda
   $$ \varphi(a^{nm}) = \varphi(a)^{nn} = (e_{n}, e_{m}) = (0_{n}, 0_{m}) $$
   Entonces nos queda el siguiente sistema de ecuaciones
   $$
\begin{aligned}
	y &= 0 \; (mod \;n) \\
	z &= 0 \; (mod \;m) \\
\end{aligned}
   $$
   Luego esto es solo posible cuando $\text{gcd}(n,m) = 1$.
   
   
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)