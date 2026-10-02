---
tags:
  - teorema
  - álgebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Teorema
Sea $G$ un grupo finito y sean $cl(a1), ... , cl(ar)$ las clases de conjugación distintas en $G$. Entonces
$$
|G| = \sum_{i=1}^{r} \frac{|G|}{|C_{G}(a_{i})|} = |Z(G)| + \sum_{i:a_i \notin Z(G)} \frac{|G|}{|C_{G}(a_{i})|}
$$
## Demostración
Las clases de conjugación (orbitas) forman una partición de $G$, entonces 
$$
|G| = \sum_{i=1}^{r} |cl(a_{i})|. 
$$
Además por la proposición [[El Orden De La Clase De Partición De Un Elemento Del Centro Es Trivial]] nos queda.
$$
|G| = |Z(G)| + \sum_{i+1}^{k} |cl(ai)|.
$$
Por ultimo gracias al [[Teorema Orbita-Estabilizador]] podemos simplificar la notación obteniendo.
$$
|G| = |Z(G)| + \sum_{i+1}^{k} |G : C_{G}(ai)|.
$$
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)