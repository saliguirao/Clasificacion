# Miércoles de Fútbol

Clasificación individual del fútbol sala de los miércoles. Cada semana se generan dos equipos a partir de la clasificación (1º a Petos, 2º a Sin petos, 3º a Petos…) y, al guardar el resultado, la clasificación se actualiza sola.

## Puntuación

- Victoria: 3 puntos · Empate: 1 · Derrota: 0
- Puntuación final: **P = p × (0,7 + 0,3 × Pg / Pj)**
  - *p*: puntos · *Pg*: partidos ganados · *Pj*: partidos jugados
- Quienes tienen la misma puntuación final comparten puesto.

## Archivos

- `index.html`: la app completa (HTML, CSS y JavaScript en un solo archivo)
- `equipo.jpg`: foto de portada

## Publicar con GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)` → Save.

## Datos

Fuera de Claude, la app guarda los datos en el navegador de cada persona (no se comparten). Para una clasificación común hay que conectarla a una base de datos como Firebase Firestore.
