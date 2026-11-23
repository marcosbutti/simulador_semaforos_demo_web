# La onda verde, con engranajes

Demo web jugable de un simulador de sincronización de semáforos.

Cada semáforo es un **engranaje** y cada diente es **un segundo de luz** (verde, amarillo o rojo). Una flecha fija arriba de cada engranaje lee el diente que pasa por debajo y ese color se prende en su semáforo. Debajo, una calle con autos que frenan en rojo muestra si hay *onda verde*.

## Qué se puede hacer

- **Desafíos:** 6 niveles que se desbloquean de a uno, con estrellas. Cada uno enseña una idea: desfasar, el tiempo de viaje entre cruces, igualar ciclos, encadenar desfases y trabajar con restricciones.
- **Modo libre:** de 2 a 6 semáforos y de 1 a 10 autos, con verde, rojo y retraso ajustables. Cada configuración se puede compartir con un link.

## Cómo probarla

Abrí `index.html` en el navegador. Es un único archivo, sin dependencias ni instalación.

## Sobre el proyecto

Es una versión simplificada, pensada para jugar y aprender, de un simulador más completo en desarrollo (Python), que además incluye análisis de sincronización y proyecciones.

Hecho con HTML, CSS y JavaScript (canvas), sin librerías.
