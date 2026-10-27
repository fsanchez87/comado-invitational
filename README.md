# Invitational Comando

Presentación HTML editable de 13 diapositivas, inspirada en la estética de Rogue Invitational. Abre `index.html` en el navegador; no necesita instalación ni compilación.

Estructura: portada general; portada de Bases y requisitos y una única diapositiva con las reglas y condiciones de participación; portada de WODs y los nueve eventos facilitados (River Dee, Single Malt, The Viking, Packout, The Duel VI, Orlando, Pulling Power, Dunnottar y Highland Sprint).

- Navega con flechas, espacio, rueda o deslizando horizontalmente.
- `E`: editar textos. `Esc`: terminar la edición.
- `Ctrl+S`: descargar una copia HTML con los cambios.
- `F`: pantalla completa.
- Los cambios se guardan automáticamente en este navegador cuando el almacenamiento local está disponible. Para compartirlos, descarga el HTML.
- En pantallas de hasta 820 px se abre automáticamente una vista de lectura: bloques apilados, texto legible, índice desplegable y desplazamiento vertical. El botón **Diapositivas** permite comparar con el formato original.
- En escritorio, el botón **Lectura** abre la misma vista. La edición de textos se realiza en **Diapositivas**; al volver a Lectura se muestran los cambios.

**Formato:** unos 20 atletas, inscripción exclusivamente por invitación y sin categorías. Los nueve WODs son candidatos: se elegirán tres o cuatro por votación. Para cada WOD se acuerda usar los pesos masculinos o femeninos y esa opción se aplica a todos los atletas, sin elección individual. Solo se permite cambiar un movimiento o ejercicio si la instalación no dispone del material necesario; el resto de la estructura se mantiene. Quien no cumpla los pesos comunes o los movimientos acordados no puede competir.

**Pruebas:** atribuidas a Rogue Invitational 2026 según la información facilitada por la organización. Las fichas conservan los movimientos, cargas, tiempos y reglas recibidos, como referencia para votar y acordar los pesos comunes y, si falta material, las sustituciones necesarias. Los datos técnicos no especificados se marcan como pendientes, sin inventar distancias, sustituciones ni time caps. También quedan pendientes el sistema de votación, el número final de pruebas y la puntuación. No implica afiliación con Rogue.

Esta versión utiliza un espacio de guardado local nuevo para evitar que textos de la estructura anterior sobrescriban los eventos actualizados. No borra los datos de la versión anterior.

Tipografía: **Roboto Condensed** y **Roboto**, verificadas en las hojas de estilo de la web de Rogue y cargadas desde Google Fonts. Se necesita conexión para descargar las fuentes la primera vez.

Colores y tipografía: variables CSS en `:root` dentro de `index.html`. La presentación mantiene el lienzo 16:9 a 1920 × 1080 sin reorganizar sus diapositivas. La vista de lectura es un documento separado generado a partir del mismo contenido, adaptado a la pantalla sin duplicar los textos editables. La impresión sigue utilizando las diapositivas originales, incluso desde la vista móvil.

Para PDF, utiliza Imprimir → Guardar como PDF, con gráficos de fondo activados y sin encabezados ni pies del navegador. Las animaciones no se conservan.
