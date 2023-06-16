---
tag: srd
alias: clase, clase de personaje
---
# Clases
## SRD (Básico)

```dataview
table name as "Inglés", req as "Req. Mínimo", ppal as "[[Características#Requisito principal|Req. Principal]]", src as "Origen", pg as "Pág."
from "Clases"
where srd = true
sort name_es asc
```
## Avanzado

```dataview
table name as "Inglés", req as "Req. Mínimo", ppal as "[[Características#Requisito principal|Req. Principal]]", src as "Origen", pg as "Pág."
from "Clases"
where srd != true
sort name_es asc
```