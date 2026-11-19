# Auditoría y planificación integral de los tres prototipos

**Fecha:** 19-11-2026  
**Estado:** auditoría inicial completada; plan de producción propuesto. No equivale a aprobación de esbozos, arte final, paginación completa ni explotación comercial.  
**Base de trabajo:** rama `main`, estado consultado el 19-11-2026.

## 1. Dictamen ejecutivo

El proyecto dispone de una base editorial aprovechable, pero **no hay todavía ningún libro completo ni una identidad visual de colección aprobada**. *Petits* tiene cuatro PNG de esbozo y generaciones anteriores; *grans* tiene dos pruebas de cercavila; *Descobreix Reus!* carecía de carpeta de desarrollo. Las pruebas existentes no deben confundirse con páginas listas para maquetar.

D025 permite desarrollar prototipos privados completos, incluso con representaciones reconocibles de activos locales, asumiendo el riesgo jurídico. No concede licencias ni permite publicar, vender, distribuir, subir a KDP o difundir públicamente. Se mantiene el registro de procedencia por activo y la obligación de resolver derechos antes de cualquier explotación comercial.

**Recomendación de producción:** mantener la estructura aprobada de *petits* (32 páginas de maqueta, láminas a una cara) y el equilibrio aprobado de *grans* (14 láminas, distribución orientativa 7/5/2); revisar su contenido a la luz de D015/D025. Diseñar *Descobreix Reus!* desde cero como cuaderno de exploración, no como tercer libro de colorear. No fijar formato, precio ni costes KDP hasta disponer de páginas y PDF de prueba.

## 2. Comprobación del repositorio

### Documentos maestros leídos
- `README.md`
- `PROJECT_CONTEXT.md`
- `DECISIONS.md`
- `ROADMAP.md`
- `INSTRUCCIONES.md` completo (10 apartados).

Se han aplicado especialmente los criterios editoriales, propiedad intelectual, decisiones, continuidad y eficiencia de los apartados 3, 4, 6, 7, 8 y 9 de `INSTRUCCIONES.md`.

### Estructura comprobada
- `books/reus-per-pintar-petits/`: mapa, prototipo, propuesta de paginación, revisiones y carpeta de assets.
- `books/reus-per-pintar-grans/`: mapa, especificación, brief de generación externa y carpeta `tests/`.
- `books/descobreix-reus/`: no existía al auditar; se crea ahora con un documento inicial de planificación, no con contenido aprobado.
- `editorial/`: contiene `ARQUITECTURA_COLECCION.md`, que sigue en estado de propuesta.
- `research/`: auditorías de derechos, fichas comparativas, expediente y borradores de consultas.
- `commercial/`: existe una simulación económica preliminar solo para *petits*.

No se localizaron documentos de portadas, créditos finales, textos completos, registros de procedencia por imagen, maquetas completas ni PDFs de revisión de ninguno de los tres libros. Tampoco hay una especificación final común de impresión.

## 3. Decisiones vigentes y propuestas no aprobadas

### Decisiones aprobadas relevantes
- D014: maqueta de *petits* de 32 páginas con láminas a una cara y reversos en blanco.
- D015: Seguici Festiu y bestiari presentes en ambos libros de colorear; tratamiento de dificultad distinto por edad.
- D019–D020: *grans* centrado en gegants/bestiari; mapa v1.1 y distribución orientativa 7/5/2 para 14 láminas.
- D021–D022: cuatro páginas de prueba de *grans* y cercavila con cinco músicos e instrumentos variados.
- D025: prototipos privados completos de los tres libros antes del contacto institucional; riesgo jurídico asumido para el prototipado bajo las restricciones descritas en DECISIONS.md.

### No son decisiones aprobadas
- La arquitectura común de colección de `editorial/ARQUITECTURA_COLECCION.md`.
- La selección priorizada de motivos de *petits*, el número final de láminas y la sustitución de motivos.
- La selección concreta de figuras de Seguici para cada título.
- La paginación final de *grans* y su lista definitiva de 14 láminas.
- El mapa, número de actividades y paginación de *Descobreix Reus!*.
- Formato, papel, tinta, precio, costes y regalías definitivos.
- Cualquier ilustración existente: ninguna está aprobada como arte final.

## 4. Auditoría visual de *Reus per pintar – petits*

### Archivos encontrados e inspeccionados
En `books/reus-per-pintar-petits/assets/esbossos-v1/` existen:
- `00-fulla-contacte.png`
- `01-campanar-prioral.png`
- `02-mercat-central.png`
- `03-casa-navas.png`
- `04-boca-mina.png`
- Tres generaciones anteriores: `Lámina para colorear de Reus-2.png`, `Torre de campanario para colorear-1.png` y `Torre del campanario en blanco y negro-3.png`.

Se han inspeccionado visualmente la hoja de contacto, los cuatro PNG numerados y dos generaciones antiguas de campanario. El archivo `Lámina para colorear de Reus-2.png` consta en el árbol Git con 1.506.985 bytes, pero la descarga de contenido del conector devolvió contenido vacío; no se emite dictamen visual sobre ese archivo. Su existencia no se confunde con disponibilidad inspeccionable.

### Dictamen por esbozo actual
| Archivo | Resultado visual | Decisión de trabajo |
|---|---|---|
| `01-campanar-prioral.png` | Silueta muy esquemática y genérica; no acredita rasgos distintivos del campanar. | No aprobar. Replantear desde referencias factuales. Las dos generaciones antiguas visibles tienen una silueta más trabajada, pero tampoco se consideran aprobadas ni se ha verificado su fidelidad. |
| `02-mercat-central.png` | Parada legible como puesto genérico, pero los alimentos son repetitivos/ambiguos y hay contactos de contorno; no comunica por sí sola el Mercat Central. | Rescatable como idea de composición, no como ilustración. Redibujar con 5–6 alimentos inequívocos y separados. |
| `03-casa-navas.png` | Fachada genérica, sin composición ni rasgos suficientes para reconocer Casa Navàs. | Rechazar esta versión y reconstruir desde cero con referencias factuales. Si el reconocimiento exige detalle incompatible con 3–5 años, sustituir el motivo. |
| `04-boca-mina.png` | Dos árboles pictográficos y camino abierto/inexistente como superficie coloreable; no se lee como paseo. | Rechazar esta versión. Reconstruir camino ancho y cerrado, árboles orgánicos y pocos elementos; no añadir escultura. |

La evaluación coincide con `esbossos-v1-revisio.md` y `evaluacion-esbozos-y-paginacion-v2.md`: el material solo sirve como exploración de masas. La discrepancia documental queda resuelta: los PNG sí están versionados; la evaluación v2 no pudo verlos en su momento. La inspección actual confirma que su existencia no cambia el dictamen de no aprobación.

### Observación transversal
El grosor aparente de los PNG no permite validar los objetivos de 2,5–3 mm ni zonas de 20–25 mm a tamaño impreso. Deben comprobarse tras decidir un formato provisional y exportar una prueba a escala real. No hay pruebas con niños; la adecuación 3–5 sigue sin validar.

## 5. Auditoría visual de *Reus per pintar – grans*

Archivos encontrados en `books/reus-per-pintar-grans/tests/`:
- `Cercavila_gemini.jpg`
- `Gemini_cercavila.jpg`

### Comparación
- **`Cercavila_gemini.jpg`**: escena de calle con profundidad, público y una banda de cinco músicos con instrumentos variados. Es la única de las dos que satisface visualmente el ajuste D022. Tiene una densidad relativamente alta, pero puede funcionar como candidata de esbozo para 6–8 años si se comprueba la escala de línea y la coloreabilidad. La arquitectura y el campanario requieren contraste factual; la escena no debe etiquetarse como reconstrucción documental de una cercavila real.
- **`Gemini_cercavila.jpg`**: solo aparecen dos músicos con instrumentos similares; no satisface la banda de cinco músicos aprobada en D022. Es una referencia de iteración anterior, no la versión que debe continuar.

**Dictamen:** utilizar `Cercavila_gemini.jpg` como base candidata para revisión, no como esbozo definitivamente aprobado ni arte final. El repositorio no conserva un registro de generación que permita demostrar qué archivo corresponde cronológicamente a la “segunda generación” valorada por el usuario; el criterio visual y D022 favorecen el primero. Añadir ficha de procedencia y corregir solo defectos concretos después de comprobar la composición a tamaño real.

No existen en el repositorio imágenes de las otras tres páginas de prueba de *grans* (Casa Navàs/Mercadal, Boca de la Mina y preparativos festivos). El brief contiene prompts autónomos y la página 1 ya refleja los cinco músicos. El mapa v1.1 y el reparto 7/5/2 están aprobados, pero la selección de figuras y la paginación completa siguen pendientes de desarrollo.

## 6. Derechos y procedencia: alcance de la auditoría

Se ha localizado y revisado la auditoría intensiva de 18 unidades del Seguici, las fichas comparativas, el expediente documental y los borradores de consulta. El estado que esos documentos acreditan sigue siendo:
- no se acredita titularidad actual ni capacidad efectiva de licencia para ninguna de las 18 unidades;
- no hay figuras autorizadas;
- las autorías conocidas son parciales y los derechos pueden estar separados por escultura, vestuario, tocados, atributos, réplicas, restauraciones, moldes, escaneos 3D y archivos;
- no se ha enviado ninguna consulta ni recibido respuesta;
- D025 permite crear prototipos privados reconocibles bajo riesgo asumido, no explotar ni difundir el material.

Para arquitectura y lugares, mantener una ficha separada: exterior permanente visible desde vía pública, interiores, mosaicos/vitrales/esculturas y obras integradas, señalética, marcas, fotografías y materiales digitales no son una única categoría. El art. 35.2 LPI no debe tratarse como cobertura automática de interiores, obras artísticas separables ni fotografías de terceros.

**Registro obligatorio por imagen:** archivo/ID, libro y página, motivo y componentes, autoría de la ilustración, herramienta/modelo, fecha, prompt exacto y versión, referencias factuales y visuales, derechos de cada fuente, exclusiones, iteraciones, resolución y decisión editorial. No usar fotos ni ilustraciones ajenas como plantilla de generación.

## 7. Auditoría de la identidad de colección

`editorial/ARQUITECTURA_COLECCION.md` ofrece una buena hipótesis: familia común en portada, tipografía, paleta y tono; interiores diferenciados por función. No es una dirección artística aprobada y todavía no define logotipo/título, retícula, tipografías concretas, paleta con valores, sistema de iconos, marcos, folios, créditos ni reglas de portada.

**Recomendación para la fase de dirección artística:** construir una identidad modular común (nombre de colección discreto, tipografía y sistema de títulos, paleta y reglas de portada/contraportada), sin imponer la misma densidad interior:
- *Petits*: formas grandes, alto contraste, mucho blanco, composición aislada y amable.
- *Grans*: línea algo más fina, escenas con planos, movimiento y pequeños retos, sin microdetalle.
- *Descobreix*: color como sistema de navegación, iconos, mapas, fichas y recursos de juego; no páginas de colorear.

No cerrar todavía tipografías ni paleta hasta comparar pruebas de portada y legibilidad.

## 8. Plan de producción recomendado

### Fase 1 — Auditoría y planificación (este documento)
Cerrada como auditoría documental/visual inicial, con una limitación de inspección indicada para un PNG antiguo.

### Fase 2 — Dirección artística de colección y títulos
Entregables: guía común y tres fichas de dirección visual; retícula y reglas tipográficas; pruebas de portada; escala de línea y densidad por edad. Debe distinguir elementos compartidos de recursos específicos.

### Fase 3 — Contenidos y arquitectura de páginas
- *Petits*: revisar mapa y propuesta de paginación de 32 páginas; integrar D015/D025 y decidir qué motivos se sustituyen, sin aumentar páginas automáticamente.
- *Grans*: convertir mapa 7/5/2 en secuencia completa de 14 láminas; elegir figuras y escenas, documentar fuentes y ajustar el prototipo de cuatro páginas a la autorización D025.
- *Descobreix*: desarrollar mapa de 12–20 actividades, progresión 5–8, textos breves en catalán, soluciones/guía adulta si aporta valor y fuentes por dato.
- Revisar solapamientos: el mismo hito puede aparecer si cambia la acción infantil; nunca repetir la misma ilustración o ejercicio.

### Fase 4 — Producción visual
Trabajar con Gemini, una imagen cada vez. Para cada página: función, ficha, composición, prompt autónomo, exclusiones, generación, crítica, corrección y validación. No generar lotes ni páginas siguientes hasta validar la actual. Las portadas se desarrollarán como piezas independientes.

### Fase 5 — Maquetación y control
Maquetas privadas completas con portada, contraportada, portadilla, créditos/aviso legal, instrucciones, todos los interiores, actividades y páginas finales pertinentes. Verificar paginación, márgenes, resolución, tipografía, catalán, escala de línea, consistencia y exportación PDF. No subir archivos a KDP ni solicitar pruebas de autor mientras rija D025.

### Fase 6 — Preparación de presentación privada
Seleccionar muestras representativas, explicar público/valor diferencial y mantener un anexo de activos con derechos pendientes. Presentación selectiva y privada a ReusCultura solo tras establecer contacto. No entregar copias ni difundir públicamente.

## 9. Riesgos y bloqueos actuales

1. **Derechos:** D025 permite prototipar, pero no elimina riesgo ni resuelve licencias comerciales.
2. **Reconocimiento cultural:** Casa Navàs y campanar necesitan referencias factuales y simplificación controlada.
3. **Petits:** las cuatro pruebas no superan todavía el filtro visual; no hay prueba infantil.
4. **Grans:** solo una página de cercavila es candidata; faltan otras tres páginas de prueba y la selección completa.
5. **Descobreix:** sin mapa de contenidos previo a este documento.
6. **Producción:** no hay formatos ni costes definitivos, portadas, maquetas ni PDFs.
7. **Trazabilidad:** faltan fichas de procedencia para las imágenes existentes y la relación entre iteración y archivo de cercavila no está demostrada.

## 10. Criterios de cierre de cada fase

- Dirección artística: tres lenguajes diferenciados y una familia visual coherente, documentados con pruebas.
- Contenidos: mapa y paginación completos, catalán revisado y fuentes verificables para todo dato factual.
- Imagen: cumple composición, lectura, coloreabilidad/función, edad, coherencia y exclusiones; procedencia registrada. Ningún promedio compensa un incumplimiento crítico.
- Maqueta: todos los elementos editoriales presentes y comprobación técnica a escala real.
- Presentación: muestras seleccionadas, narrativa comercial prudente y relación transparente de derechos pendientes.

**Siguiente acción:** abrir un chat de trabajo nuevo con el prompt de relevo de esta auditoría y desarrollar la Fase 2 (dirección artística) antes de ampliar la producción de imágenes.
