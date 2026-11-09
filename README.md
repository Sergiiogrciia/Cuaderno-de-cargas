# Cuaderno de Cargas

App web para anotar el entreno de hipertrofia: rutina de 5 días, series con RIR, sugerencia de carga (8-12 reps), temporizador de descanso, récords y progreso por ejercicio.

- Funciona sin conexión (service worker) y se instala en el iPhone desde Safari: Compartir > Añadir a pantalla de inicio.
- Los datos se guardan solo en el dispositivo. Ajustes > Guardar copia crea un `.json` para restaurarlos; también exporta a CSV.
- Todo está en `index.html`. Al publicar cambios, sube `VERSION` en `sw.js`.
