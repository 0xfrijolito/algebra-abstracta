---
tags:
  - definicion
  - fundamental
  - estructura
  - álgebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: true
---
## Definición
Un ** [[Grupo]] abeliano** (o grupo conmutativo) es un conjunto $G$ dotado de una operación binaria interna $\ast: G \times G \rightarrow G$ que cumple con los siguientes cuatro axiomas fundamentales:
- **Asociatividad:** Para todo $a, b, c \in G$, se cumple que $(a \ast b) \ast c = a \ast (b \ast c)$.
- **Elemento neutro:** Existe un elemento $e \in G$ tal que, para todo $a \in G$, se cumple $a \ast e = e \ast a = a$.
- **Elemento simétrico:** Para cada $a \in G$, existe un elemento $a^{-1} \in G$ tal que $a \ast a^{-1} = a^{-1} \ast a = e$.
- **Conmutatividad:** Para todo $a, b \in G$, se cumple que $a \ast b = b \ast a$.
## Observaciones
1. Su tabla de multiplicación es simétrica respecto a la diagonal principal.
## Teoremas
1. 
## Proposiciones
1. [[Los Subgrupos De Un Grupo Abeliano Son Normales]]
2. [[Los Subgrupos De Un Grupo Abeliano Finitamente Generado Es Finitamente Generado]]
## Ejemplos
1. **[[Grupos de Klein]]:** 
   El grupo de Klein $V_4$ es un ejemplo de grupo abeliano no cíclico.
2. **[[Grupo Cicliclo]]:**
   Todo grupo cíclico $G = \langle a \rangle$ es abeliano. Dado que cualquier par de elementos $x, y \in G$ pueden expresarse como potencias de $a$ (es decir, $x = a^m$ y $y = a^n$), se cumple que $xy = a^m a^n = a^{m+n} = a^{n+m} = a^n a^m = yx$.
   
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)