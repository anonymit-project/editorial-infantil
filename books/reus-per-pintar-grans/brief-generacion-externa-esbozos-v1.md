# Brief de generación externa — cuatro esbozos de *Reus per pintar – grans*

**Versión:** 1.2  
**Fecha:** 16-11-2026  
**Estado:** prompt de cercavila actualizado a v1.2 tras la valoración del usuario de la segunda generación. El usuario considera satisfactoria la segunda generación como planteamiento de esbozo, pendiente de incorporar el ajuste de cinco músicos y de guardar/verificar esa versión en el repositorio. Se amplía la banda a cinco músicos. Las otras tres páginas siguen pendientes.  
**Autorización editorial:** D021.  
**Especificación vinculante:** `books/reus-per-pintar-grans/especificacio-prototip-v1.md`.

## 1. Finalidad y límites

Este documento permite generar cuatro imágenes conceptuales independientes con herramientas externas mientras no esté disponible la generación de imágenes en el entorno principal. Son **esbozos para evaluar composición, lenguaje gráfico, densidad y adecuación a 6–8 años**. No son arte final, no acreditan originalidad jurídica y no autorizan publicar las imágenes.

No se debe generar ninguna figura reconocible del Seguici Festiu. La IA no debe recibir fotografías, escaneos 3D, ilustraciones, moldes, capturas de webs ni diseños de terceros como referencia. Todos los prompts parten de una descripción verbal original.

## 2. Herramientas externas: orden de prueba y cautelas

1. **Google Gemini:** primera prueba por facilidad de uso, generación y edición conversacional. La ayuda oficial indica descarga de hasta 1K sin plan de IA. Consultar disponibilidad y límites reales al iniciar sesión: https://gemini.google.com/
2. **Adobe Firefly:** alternativa para probar resultados destinados a un flujo comercial. Adobe indica que los resultados de funciones no beta pueden utilizarse en proyectos comerciales; la cuenta gratuita tiene generaciones limitadas. Revisar condiciones de la función concreta: https://firefly.adobe.com/
3. **Leonardo AI:** alternativa para iterar estilo y composición. Su ayuda indica 150 tokens diarios en el plan gratuito; las generaciones gratuitas son públicas y la plataforma obtiene amplios derechos de uso sobre los contenidos públicos. No introducir información confidencial ni briefs que no se quieran hacer públicos: https://leonardo.ai/

Las condiciones y cuotas pueden cambiar. Antes de utilizar cualquier imagen en un producto comercial, revisar los términos vigentes de la herramienta y conservar una copia/fecha de las condiciones consultadas. Que el proveedor permita uso comercial no garantiza exclusividad, protección por copyright ni ausencia de derechos de terceros. Para este prototipo, limitar el uso a evaluación interna.

## 3. Flujo de trabajo recomendado

1. Abrir una conversación nueva en la herramienta elegida.
2. Generar **una sola página por solicitud**, utilizando el prompt completo correspondiente. No pedir una cuadrícula ni una composición con cuatro viñetas.
3. Configurar orientación vertical, preferiblemente 2:3. Si no existe control de proporción, reiterar «portrait page, tall vertical composition».
4. No añadir texto, títulos, números, marcos decorativos, color, grises ni sombras.
5. Descargar la imagen original en la mayor resolución gratuita disponible. Guardar el archivo sin recortarlo ni escalarlo destructivamente.
6. Nombrar los archivos:
   - `grans-esbos-01-cercavila-ia-01.png`
   - `grans-esbos-02-casa-navas-ia-01.png`
   - `grans-esbos-03-boca-mina-ia-01.png`
   - `grans-esbos-04-preparatius-festa-ia-01.png`
   Sustituir `01` final por el número de iteración.
7. Si se usa una imagen propia como referencia de estilo para las páginas siguientes, indicar que solo se toma como referencia de grosor de línea y nivel de detalle, nunca para repetir su composición, personajes u objetos.
8. No usar generación de imágenes para reparar una figura protegida o acercarla a un gegant/bestiari real. Si una imagen evoca accidentalmente una figura local, descartarla y cambiar la descripción.
9. Conservar el prompt exacto, herramienta, modelo si se indica, fecha, parámetros y archivo generado.

## 4. Lenguaje gráfico común

Aplicar literalmente esta dirección artística en las cuatro páginas:

- Lámina infantil de colorear original para 6–8 años, composición vertical.
- Dibujo lineal en blanco y negro, exclusivamente contornos negros limpios, cerrados, nítidos y de grosor medio consistente.
- Línea algo más fina y más variada que en un libro para 3–5 años, pero suficientemente gruesa para impresión doméstica y KDP.
- Grandes superficies coloreables combinadas con detalles secundarios de tamaño cómodo.
- Perspectiva suave, varios planos y jerarquía visual evidente; profundidad sin realismo fotográfico.
- Formas amables, expresivas y proporcionadas; personajes genéricos, no retratos.
- Composición aireada, equilibrada y con espacios de descanso visual.
- Aproximadamente 10–18 zonas principales coloreables según la página; evitar microdetalles.
- Fondo simplificado, sin patrones repetitivos ni texturas densas.
- Sin color, grises, degradados, sombreado, tramado, rellenos negros grandes, efectos 3D, acabado pictórico ni aspecto de fotografía.
- Sin texto, letras, números, rótulos, firmas, marcas de agua ni marcos.
- No imitar el estilo de ningún artista vivo ni de una franquicia, libro o ilustrador identificable.

## 5. Prompts listos para copiar

Los prompts se proporcionan en inglés porque suele ser una lengua de control eficaz en generadores visuales. No deben traducirse ni resumirse al pegarlos. Cada prompt es autónomo e incluye sus restricciones. La página 1 se ha ajustado a cinco músicos por aprobación D022; el cambio debe mantenerse en cualquier regeneración o edición.

### PÁGINA 1 — Una cercavila omple el carrer

```text
Create ONE original rough concept sketch for a children's coloring book, as a single portrait 2:3 page for children aged 6–8. Scene: a joyful street parade in Reus, Catalonia, with a stronger sense of local place and festive energy. This is NOT a depiction of any specific real festival group and must not include any recognizable protected Seguici figure or design.

COMPOSITION: create a lively, readable street scene with three distinct depth planes and a gentle diagonal movement across the page. In the foreground, on the sidewalk, show exactly two generic adults and one child watching together; their poses should clearly communicate excitement and attention. In the middle ground, show exactly five generic musicians walking together as a small street band, with varied instruments: one trumpet, one trombone or low brass instrument, one clarinet, one transverse flute and one simple generic marching drum. Keep all instruments simplified and invented from basic shapes. This is a generic visual ensemble, not a documentary claim about the actual Reus Seguici band formation. Add three or four additional small spectators along the opposite sidewalk, spaced apart and large enough to read as people rather than tiny marks. Include a few simple, non-repeating festive details such as short plain strings of triangular bunting attached high between façades, but keep the street open and the page uncluttered.

REUS IDENTITY: in the distant background, above the roofline and clearly separated from the nearer buildings, include the recognizable overall silhouette of the Campanar de la Prioral de Sant Pere in Reus as a simplified factual architectural landmark: a tall, slender bell tower with an octagonal upper section and a distinct pointed roof. Keep it secondary but unmistakable as a city landmark. Draw it as original simplified architecture from this verbal description only; do not reproduce a photograph, existing illustration, ornamental detail or exact facade. Do not add Casa Navàs, since it has its own page in this prototype.

STREET ENVIRONMENT: give the surrounding façades more individual character through varied rooflines, balconies, window proportions and simple traditional urban details, while keeping them invented and generic. Avoid a row of blank rectangular blocks. Do not add shop names, street names, plaques or readable signs.

ART DIRECTION: original black-and-white coloring-book line art, clean closed outlines, consistent medium black line weight, suitable for ages 6–8. Use large and medium enclosed coloring areas, approximately 14–18 main areas. Make the scene feel fuller and more animated than the first test, but preserve clear white space and a strong hierarchy. Use natural walking poses and clear silhouettes. Keep faces and clothing simple; no tiny instrument keys, dense crowds, repetitive cobblestones or fabric patterns.

STRICT EXCLUSIONS: absolutely no giants, giant silhouettes, giant costumes, capgrossos, fantasy parade creatures, animals from a local bestiary, distinctive festival props, recognizable uniforms, logos, crests, flags, banners bearing symbols, lettering or identifiable Reus Seguici Festiu designs. The musicians' instruments and all festive details must be generic and invented from basic shapes.

Pure black outlines on a plain white background. No color, gray, shading, gradients, hatching, large black filled areas, photorealism, 3D render, decorative border, title, text or watermark. Entire scene must be invented from this written brief, not based on a photograph or existing illustration.
```

**Qué revisar en la segunda iteración:** familia en primer plano; dos músicos en movimiento; 3–4 espectadores adicionales legibles; campanario reconocible pero secundario; fachadas con carácter; ambiente festivo sin saturación; superficies coloreables; ausencia total de figuras festivas reconocibles. Comparar con la primera prueba (`tests/Gemini_cercavila.jpg`): debe mejorar la identidad de Reus y la riqueza narrativa sin perder limpieza ni coloreabilidad. Si el campanario sale irreconocible o se inventan detalles arquitectónicos excesivos, corregir la descripción o descartar la iteración.

### PÁGINA 2 — Casa Navàs i la plaça del Mercadal

```text
Create ONE original rough concept sketch for a children's coloring book, as a single portrait 2:3 page for children aged 6–8. Subject: the exterior of Casa Navàs facing Plaça del Mercadal in Reus, Catalonia, interpreted as a clear, simplified architectural coloring illustration.

COMPOSITION: Casa Navàs is the dominant subject and occupies most of the middle and upper page. Show a gentle corner perspective so that the building has readable volume, not a flat frontal elevation. Preserve only the broad, factual architectural character needed to make the building recognizable: its overall silhouette, main levels, large openings and the prominent projecting galleries/balconies. Keep the architecture legible and simplified. In the foreground, show the open square with two or three small generic pedestrians and either one simple bicycle or one bench. Other surrounding façades appear only as quiet secondary masses.

ART DIRECTION: original black-and-white coloring-book line art, clean closed contours, consistent medium black line weight. Three readable architectural depth levels, approximately 10–16 large or medium coloring areas. Use broad architectural shapes and selected structural details, not intricate ornament. The building should feel substantial and interesting for a 6–8-year-old to color, while leaving enough white space.

STRICT EXCLUSIONS: do not copy or reconstruct any photograph, existing illustration, floor plan, promotional image or exact ornamental artwork. Do not draw mosaics, stained glass, decorative panels, interior rooms or separately authored artworks. Do not invent intricate decorative patterns that imitate the building's actual mosaics or windows. No shop logos, business signs, readable lettering, flags, crests or advertising.

Pure black outlines on a plain white background. No color, no gray, no shading, no gradients, no hatching, no photorealism, no 3D render, no decorative border, no title, no text, no watermark. Create an original simplified architectural interpretation from the written description alone.
```

**Qué revisar:** Casa Navàs domina; perspectiva de esquina; tribunas y huecos principales legibles; plaza con 2–3 personas; arquitectura secundaria discreta. Eliminar o rehacer cualquier mosaico, vitral o decoración artística detallada.

### PÁGINA 3 — El passeig de la Boca de la Mina

```text
Create ONE original rough concept sketch for a children's coloring book, as a single portrait 2:3 page for children aged 6–8. Scene: a peaceful tree-lined public promenade inspired by the general landscape idea of a long walking path in Reus, with no specific sculpture or commemorative object.

COMPOSITION: a broad path begins in the lower foreground and recedes toward a soft, distant vanishing point. Show exactly two principal trees with generous, simple canopies, one on each side or staggered along the path. Add grouped low vegetation in broad masses rather than individual leaves. Include a simple bench and a simplified narrow water channel or stream in the foreground or along one side. Show one generic adult couple walking with one child. The people should be secondary to the path and landscape. Make the perspective clear but gentle and welcoming.

ART DIRECTION: original black-and-white coloring-book line art for ages 6–8. Clean closed contours, consistent medium black line weight, large organic coloring shapes and a few medium details. Approximately 10–15 main coloring areas. Tree canopies should be divided into a few broad sections, not hundreds of leaves. Keep the path wide, the water channel simple and the vegetation uncluttered. Use overlapping planes to create depth without dense texture.

STRICT EXCLUSIONS: no sculpture, no statue, no vendor figure, no commemorative monument, no coat of arms, no inscriptions, no plaques, no logos, no signs, no recognizable landmark artwork. Do not depict the specific sculpture known as the venedora d'anissos. No tiny leaves, grass strokes, paving patterns or repetitive textures.

Pure black outlines on a plain white background. No color, no gray, no shading, no gradients, no hatching, no photorealism, no 3D render, no decorative border, no title, no text, no watermark. Invent the landscape from this written brief; do not trace or imitate a photograph or existing illustration.
```

**Qué revisar:** camino con fuga clara; dos árboles principales; masas vegetales grandes; banco y agua reconocibles; tres caminantes; ninguna escultura ni elemento conmemorativo.

### PÁGINA 4 — Abans que comenci la festa

```text
Create ONE original rough concept sketch for a children's coloring book, as a single portrait 2:3 page for children aged 6–8. Scene: an invented, generic community preparing for a local celebration before it begins. This is an imaginative everyday scene, NOT a documentary reconstruction of any real Reus festival procedure.

COMPOSITION: use a simple neutral outdoor or multipurpose preparation space, not a recognizable real workshop. Show two generic adults preparing a plain open storage box and sorting a few generic logistical items. A third generic person checks a sheet of music. A fourth generic person may be present as a musician talking with them, holding a simple generic instrument case or a very simplified drum. Keep the total number of people at four maximum. On the ground or beside the box, include a loose ribbon, a plain generic drum and a few non-distinctive packing objects. The scene should communicate cooperation and anticipation, not a specific ritual or costume preparation.

ART DIRECTION: original black-and-white coloring-book line art for ages 6–8. Clean closed outlines, consistent medium black line weight, clear readable gestures and a simple narrative hierarchy. Approximately 10–14 large or medium coloring areas. Use varied but natural poses, clear separation between people and objects, and enough empty space. Keep the box, ribbon, drum and paper simple and generic.

STRICT EXCLUSIONS: no giant structures, no giant heads, no giant frames, no giant costumes, no bestiary attributes, no animal figures, no distinctive festival clothing, no uniforms, no sashes worn as recognizable group attire, no logos, no crests, no flags, no banners, no local symbols, no real workshop details. Do not imply that this exact preparation process is an authentic documented practice. Do not include readable music notation or text; the paper can show only a few abstract lines.

Pure black outlines on a plain white background. No color, no gray, no shading, no gradients, no hatching, no photorealism, no 3D render, no decorative border, no title, no text, no watermark. Invent the scene entirely from this written brief, without using a photograph or existing illustration as reference.
```

**Qué revisar:** escena de colaboración, caja y objetos genéricos, máximo cuatro personas, partitura no legible, tambor no distintivo y ausencia de estructuras/vestuarios/atributos del Seguici.

## 6. Prompt de corrección (solo para defectos menores)

Si la composición es válida y solo hay que corregir un defecto puntual, utilizar la función de edición de la propia herramienta con una instrucción concreta, por ejemplo:

```text
Keep the overall composition, character count, perspective and visual style unchanged. Correct only this issue: [describe one precise issue]. Preserve the clean, closed black outlines and large coloring areas. Do not add any new objects, people, symbols, text or decorative details. Maintain all exclusions in the original brief.
```

No intentar corregir mediante edición una imagen que contenga una figura local reconocible o que incumpla gravemente la composición: descartarla y regenerar desde el prompt original.

## 7. Lista de control editorial para cada imagen

Puntuar cada criterio de 0 a 2: 0 = no cumple; 1 = cumple parcialmente; 2 = cumple. No sumar puntos para ocultar un incumplimiento crítico.

| Criterio | Qué comprobar |
|---|---|
| Composición | Respeta los planos, personajes y objetos requeridos |
| Lectura | Se entiende la escena sin explicación |
| Perspectiva | Profundidad clara y natural, sin deformaciones |
| Línea | Contornos negros, limpios, cerrados y consistentes |
| Coloreabilidad | Zonas grandes/medianas, sin áreas minúsculas dominantes |
| Densidad | Nivel adecuado a 6–8 años, sin saturación |
| Jerarquía | Protagonista y elementos secundarios bien diferenciados |
| Coherencia | Comparte lenguaje gráfico con las otras tres páginas |
| Originalidad visual | No parece calco ni imitación evidente de una obra concreta |
| Restricciones | No incorpora símbolos, diseños o elementos excluidos |

**Umbral orientativo:** 16/20 para considerar una imagen candidata a revisión. Es una herramienta interna de evaluación, no una certificación jurídica ni una aprobación de arte final.

**Rechazo automático, independientemente de la puntuación:**
- aparece una figura, silueta, vestuario o atributo reconocible del Seguici;
- se ha utilizado una imagen de terceros como referencia de generación o calco;
- la composición contradice la especificación aprobada;
- la línea no permite colorear (sombras, grises, áreas negras o trazos abiertos dominantes);
- hay estereotipos raciales, culturales o caricaturas ofensivas.

## 8. Comparación entre páginas y diferencia respecto a *petits*

La revisión conjunta debe comprobar:
- misma familia de contorno, grosor, acabado y nivel de detalle;
- variedad de composiciones: calle urbana, arquitectura, paisaje y escena narrativa;
- profundidad y varios planos en las cuatro páginas;
- más información visual que *petits*, sin convertir las páginas en láminas recargadas;
- suficiente superficie coloreable y ausencia de microdetalle esencial;
- ninguna página depende del color para comunicar su significado.

## 9. Registro de procedencia

Al incorporar cada imagen, anotar:

| Campo | Dato |
|---|---|
| Nombre de archivo | |
| Herramienta y URL | |
| Modelo indicado por la plataforma | |
| Fecha de generación | |
| Prompt exacto y versión | |
| Parámetros / proporción / resolución | |
| Iteración y correcciones | |
| Condiciones de uso consultadas y fecha | |
| Resultado de la lista de control | |
| Decisión editorial | A revisar / descartar / candidata a revisión |

## 10. Estado y siguiente paso

- D021 autoriza los cuatro esbozos; D022 modifica la página 1 para incluir cinco músicos variados.
- El usuario considera que la segunda generación de la cercavila tiene un planteamiento visual válido, salvo la necesidad de ampliar la banda; el archivo de esa segunda iteración aún debe guardarse y verificarse en el repositorio; se trata como candidata de esbozo, no como arte final ni como validación jurídica.
- La especificación y el prompt de la página 1 quedan actualizados a cinco músicos.
- Las páginas 2–4 siguen pendientes de generación y evaluación. La fase completa continúa abierta hasta revisar las cuatro páginas y documentar sus fichas de procedencia.
- No se autoriza arte final ni representación reconocible de diseños protegidos.
