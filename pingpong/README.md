# Copa Familiar · Ping Pong 2026

Miniweb estática para gestionar el torneo familiar desde un móvil, tablet o portátil.

## Flujo

1. Revisa/edita las cinco parejas de participantes.
2. Pulsa **Hacer el sorteo**: cada pareja se separa entre Grupo A y Grupo B.
3. En **Liga**, toca cada partido e introduce los dos juegos a 11; si queda 1–1 aparece el super tie-break a 10.
4. La clasificación se recalcula automáticamente con 3/2/1/0 puntos.
5. Genera el **Playoff**: pasan 4 por grupo y se crean cuartos, semifinales, tercer puesto y final.
6. Al guardar la final aparece el podio y la celebración del campeón.

Los datos se guardan en `localStorage`, por lo que para el torneo conviene usar un dispositivo como marcador maestro. La sección de copia permite exportar/importar el estado.

## Publicación

Se incluye un workflow de GitHub Pages en `.github/workflows/deploy-pingpong-pages.yml`. También puede abrirse el `index.html` con cualquier hosting estático.