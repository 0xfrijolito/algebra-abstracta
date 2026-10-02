---
tags:
  - proposicion
  - algebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Cada permutación se puede escribir como composición de ciclos con soportes disjuntos.
## Demostración
Sea una permutación $\sigma \in S_n$ entonces encontramos un $i \in \{ 1, ..., n\}$ siendo este el mas pequeño índice no fijado por $\sigma$. Es decir $\sigma(i) \neq i$.

Sea $r > 1$ el mas pequeño índice tal que 
$$
\sigma^{r}(i) \in \{i, \sigma(i), ..., \sigma^{r-1}(i) \}
$$
Se cumple que $\sigma^{r}(i) = i$ : con $\sigma^{r} = \sigma^{l}(i)$ con $0 < l < r -1$, entonces $\sigma^{r-l}(i) = i$ con $r - l < r$, contradiciendo la definición de $r$.

Luego se obtiene el ciclo $(i\ \sigma(i) ...\ \sigma^{r-1}(i))$. Si existe otro entero $j$ no fijado por $sigma$ que no esta en $\{i, \sigma(i), ..., \sigma^{r-1}(i) \}$ se repite el proceso con $j$.

De esta forma se obtiene una partición de $\{1, ..., n\}$ tal que cada conjunto de la partición corresponde a un ciclo de $\sigma$.

***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)