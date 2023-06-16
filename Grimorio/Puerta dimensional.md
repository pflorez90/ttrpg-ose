---
name: Dimension Door
name_es: Puerta dimensional
cls-lvl: Mago-4
rev:
dur: 1 ronda
ran: 10’
---
# `=this.name_es`
###### (`=this.name`)

>**Duración:** `=this.dur`
>**Alcance:** `=this.ran`

El lanzador o una única criatura se transporta instantáneamente a otro lugar a 360’. El destino puede elegirse de dos maneras:
1. **Lugar conocido:** Un lugar en un radio de 360’ que conozca el lanzador.
2. **Lugar desconocido:** Calculado a partir de distancias aproximadas (120’ al norte, 160’ al este, etc.) que no sumen más de 360’’.

**Restricciones:** Se aplican las siguientes restricciones:
- ▶ **Si el destino está ocupado por un objeto sólido:** El hechizo falla.
- ▶ **Si el objetivo se resiste:** Puede hacer una tirada de salvación contra hechizos para resistirse a la teleportación.