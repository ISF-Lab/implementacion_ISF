# Metodología ISF Chile

Presentación interactiva para explicar el programa y una intervención de Ingeniería Humanitaria. Preparada para una reunión con Mercedes, con el formulario `_2026 Anexo-A-Formulario-Postulacion-Banco_v20-09(1).pdf` como fuente principal.

## Abrir y presentar

1. Descomprime la carpeta completa.
2. Abre `index.html` en Chrome, Edge, Firefox o Safari. No necesita instalación ni conexión a internet para mostrar la presentación.
3. Haz clic en una de las 12 intervenciones. Explora comunidad, ISF, empresas y el ciclo central.
4. Usa «Volver» o la ruta superior para subir de nivel. El botón inferior permite un recorrido ordenado.
5. Flechas izquierda/derecha: avanzar por el recorrido. Dentro del ciclo: cambiar de etapa. Esc: volver de nivel o cerrar una ventana.
6. «Pantalla completa» amplía la presentación si el navegador lo permite.

Las 12 posiciones son una representación del programa, no comunidades individualizadas. El ejemplo hídrico es genérico y no compromete una obra específica. La presentación profundiza en agua y saneamiento sin cambiar el alcance de servicios básicos del formulario.

## Agregar documentos sin editar código

1. Abre `editor.html`.
2. Selecciona una etapa y completa título, descripción y enlace del documento. Puedes agregar o quitar filas.
3. Revisa el resultado en la vista previa, que se actualiza automáticamente.
4. Presiona «Descargar ejemplos.js».
5. Reemplaza el archivo `ejemplos.js` de esta carpeta con el descargado. Si el navegador agrega `(1)` al nombre, renómbralo exactamente `ejemplos.js`.
6. Recarga `index.html`. Si ya está publicado, sube el nuevo archivo a GitHub y espera que se actualice GitHub Pages.

El borrador del editor vive solamente en ese navegador. Descargar y reemplazar el archivo es lo que conserva los cambios para otras personas. No se ejecuta código cargado por el usuario y no hay servidor ni base de datos.

Solo se muestran documentos con enlaces http:// o https:// válidos. Un espacio con URL vacía permanece oculto en la presentación. Comprueba tú mismo los permisos de acceso de cada documento. El editor no cambia esos permisos.

## Editar e iterar

- `contenido.js`: nombre del programa, etapas, preguntas, responsables, entregables, condiciones y desafíos. Se puede editar con VS Code u otro editor de texto.
- `ejemplos.js`: documentos asociados a cada etapa; puede generarse con el editor visual.
- `app.js`: vistas, textos de actores y métricas, iconos y navegación.
- `estilos.css`: colores, tamaños, distribución, animación y adaptación a móvil.
- `assets/logo-isf.png`: logo proporcionado por ISF, sin modificaciones.

Para revisar cambios, guarda el archivo y recarga el navegador. No hay dependencias, instalación ni compilación. Si tu navegador restringe la vista previa del editor al abrir archivos locales, abre la carpeta con «Live Server» de VS Code o ejecuta `python -m http.server 8000` dentro de ella y visita `http://localhost:8000`.

## Subir a GitHub

La entrega es una carpeta lista para subir; no se ha publicado automáticamente.

1. Crea o elige un repositorio.
2. Sube todo el contenido de esta carpeta, manteniendo `index.html` en la raíz.
3. Si quieres una URL pública y tu cuenta/repositorio permite GitHub Pages, abre Settings → Pages y elige publicar desde la rama correspondiente y la carpeta raíz. Los nombres de las opciones pueden variar.
4. Abre la URL que entregue GitHub. Los archivos usan rutas relativas y funcionan también bajo el nombre del repositorio.

No se incluyen los PDFs originales, datos personales ni documentos internos. Al publicar el repositorio/página, los enlaces que agregues en `ejemplos.js` serán visibles en el código, aunque los documentos puedan mantener permisos de acceso propios.

## Criterios de contenido

- El PDF de postulación manda sobre la síntesis del otro chat.
- Cifras iniciales: 12 intervenciones, 36 meses, 5 regiones y meta de 1.920 beneficiarios directos.
- Las 160 personas por intervención son un promedio referencial, no un mínimo.
- No se dibuja un calendario mensual de ejecución: los rangos de duración y la Gantt del PDF requieren lectura conjunta; esta página no introduce nuevos compromisos de plazo por etapa.
- La formación de capacidades se muestra como transversal, con productos propios en la implementación y el cierre.
- Se mantienen los compromisos de género y beneficio económico del PDF, accesibles desde Resultados.
- La experiencia institucional reproduce las coberturas del CV, incluyendo directos e indirectos. No se suman ni se presentan como personas únicas.
- No se añade un compromiso de seguimiento posterior al cierre.
- Los controles y documentos se describen según corresponda a cada intervención. Los permisos se exigen antes de implementar la obra.

Paleta extraída de `ISF Campaign Kit.html`: azul #0920A6, celeste #64A7DB, naranja #FF961F, blanco #FFFFFF. Tipografía de sistema para funcionar sin descargas externas. Iconos vectoriales incluidos en el código. El logo se conserva tal como fue entregado.
