# BookPreparador

Página para quitar el fondo de imágenes y descargarlas como PNG transparente.

- Funciona 100% en el navegador (ideal para GitHub Pages): las imágenes no salen de la compu.
- Arrastrar, elegir o pegar (Ctrl+V) varias imágenes a la vez.
- Tres modos: Rápido, Equilibrado y Máxima calidad.
- Usa WebGPU si el navegador lo soporta, si no CPU.

Usa [@imgly/background-removal](https://github.com/imgly/background-removal-js). La primera vez descarga el modelo; después queda en caché.
