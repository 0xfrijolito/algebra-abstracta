---
tags:
  - teorema
  - álgebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Teorema
Un grupo abeliano $A$ finitamente generado y no trivial es isomorfo a un [[Producto Directo]] de la forma
$$
\mathbb{Z}^{r} \times \mathbb{Z}/a_{1}\mathbb{Z} \times ... \times \mathbb{Z}/d_{k}\mathbb{Z} 
$$
donde cada $a_{i}$ es un entero positivo y divide $a_{i+1}$. El numero $r$ y los números $a_{i}$ son unívocamente determinados por el grupo $A$ y dos grupos isomorfos tienen los mismos números. El numero $r$ se llama *rango* del grupo abeliano.
## Demostración
Probamos aquí solamente la existencia de dicha descomposición. Como $A$ es un grupo abeliano finitamente generado existe un homomorfismo sobreyectivo $f: \mathbb{Z}^{n} \to A$ para algún $n \geq 0$. El núcleo $H$ de $f$ es un grupo abeliano f.g y libre por la proposición [[El Subgrupo De Un Grupo Abeliano Finitamente Generado Es Finitamente Generado]]. Además por la proposición [[nose]] una base de $H$ es de la forma $a_{i}e_{i}, ..., a_{k}e_{k}$ donde $e_{1}, ..., e_{n}$ es una base de $\mathbb{Z}^{n}$ y $a_{i}\mid a_{i+1}$ para cada $i$. Entonces
$$
A \cong Z^{n}/H \cong \mathbb{Z}^{n - k} \times \mathbb{Z}/a_{1}\mathbb{Z} \times ... \times \mathbb{Z}/d_{k}\mathbb{Z} 
$$

***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)