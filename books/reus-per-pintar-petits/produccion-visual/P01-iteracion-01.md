# P01 — La festa comença: brief de generación, iteración 01

**Libro:** Reus per pintar – petits (3–5 años)  
**Estado:** prompt preparado; pendiente de ejecución en Gemini y revisión editorial. No es una ilustración aprobada.  
**Fecha:** 20-11-2026  
**Herramienta/modelo:** Gemini, pendiente de registrar el modelo exacto que se use.  
**Salida generada/ubicación:** pendiente.  
**Evaluación/correcciones:** pendientes de recibir y revisar la imagen.

## Referencias que debe adjuntar el usuario en Gemini

1. **Referencia principal y única base de forma/pose:** `books/reus-per-pintar-petits/assets/vitxet-estudi-simplificat.jpg` — versión asignada por el usuario a *Petits*. Debe conservarse como el personaje de la página izquierda.
2. **Referencia secundaria de identidad/vestuario:** `books/reus-per-pintar-petits/assets/vitxet-estudi-detallat.jpg` — consultar solo para aclarar rasgos y ornamentos que no se lean en la versión principal; no copiar su densidad de detalle.
3. **Referencia secundaria de identidad/vestuario:** `books/reus-per-pintar-petits/assets/vitxet-estudi-intermedi.jpg` — consultar solo como apoyo de identidad; no sustituir con ella la versión simplificada.

La clasificación y los archivos se comprobaron en GitHub. En esta intervención no se pudo inspeccionar visualmente ninguno de los tres JPG; su clasificación como principal/secundarias procede de las instrucciones expresas del usuario. No se debe alegar que fueron visualmente validados.

## Prompt exacto para Gemini

Create one clean black-and-white coloring-book illustration as a complete two-page opening for a Catalan children's book for ages 3–5. The uploaded images are visual references for the left-page Vitxet only. Use the file named “vitxet-estudi-simplificat.jpg” as the primary and controlling reference. Preserve that character's recognizable face, beard, hat, clothing, silhouette, pose language and characteristic ornaments. Do not redesign, replace, reinterpret, beautify, modernize or genericize him. The detailed and intermediate studies are secondary identity references only; do not import their extra detail or let them override the simplified study. Do not combine versions. Keep the character's established appearance intact; only clean up linework as needed to integrate it into the page.

CANVAS AND PAGE GEOMETRY
- One landscape image showing two facing portrait pages, with no book mockup, page curl, shadows, border or perspective.
- Use an overall aspect ratio of approximately 1.414:1 (two A4-like portrait pages side by side; each page is approximately 0.707:1).
- Treat the left and right halves as separate pages that also read together as one calm, balanced opening.
- Keep the central 7% of the full image width clear of all essential content. This is the binding/gutter safety zone. No part of the Vitxet, child, drum, face, hands, instrument outline or other important shape may enter it. Do not draw a line or object that must connect across the fold.
- Keep all drawn content at least 5% of the canvas width from the outer edges. Leave comfortable white space.

LEFT PAGE — VITXET
- Place the supplied simplified Vitxet alone as the dominant figure, full body visible, upright and easy to recognize.
- Figure height: about 78–84% of the page height. Center him within the left page, slightly away from the gutter; leave clear white space around his full silhouette.
- Preserve the reference's anatomy, face, beard, hat, garments and characteristic decorations. Do not invent accessories or change costume details.
- Keep arms separated from the body wherever the reference allows; preserve the existing pose rather than inventing a new gesture.
- Do not crop the hat, hands, feet or any characteristic feature.
- No crowd or extra figures on this page. At most, use one simple ground line if needed.

RIGHT PAGE — CHILD LISTENING TO A GENERIC DRUM
- Draw one large, simple, unbranded generic drum and one child listening to it. These are the only secondary characters/objects; add no other scene elements.
- Put the drum in the right half of the page, approximately 42–48% of that page's height, with a simple readable cylindrical body, two drumheads/rims and only a few broad divisions. No logo, badge, lettering, strap insignia or distinctive real-world design.
- Put one child beside the drum, approximately 48–55% of page height, in a relaxed listening pose, facing the drum. Show a calm, curious expression; one hand may rest near an ear, without touching or covering the face. Use simple generic everyday clothing with no uniform, costume or symbols.
- Keep the child and drum separate, fully visible and not overlapping. Arrange them as a clear pair with open white space around both. Their faces and all essential contours must remain outside the gutter safety zone.
- Avoid implying that the child is a named or identifiable person.

COLORING-BOOK STYLE
- Pure black outlines on a plain white background; no color, gray, shading, crosshatching, gradients, textures, filled black areas or simulated paper.
- Use a consistent, bold, rounded, smooth outline across the whole spread, suitable for preschool coloring. Keep contours closed and intersections clear.
- Use very few interior lines and broad, easy-to-color enclosed areas. Aim for 4–8 large coloring regions per page, with no tiny gaps, thin slivers or intricate patterns.
- Match the line weight and simplicity of the supplied simplified Vitxet reference; simplify only the drum and child to fit it. Do not simplify or alter the Vitxet's identifying features.
- Both pages must be understandable independently. Coordinate them through scale, visual weight and the shared music/listening idea, not through a continuous background or an image crossing the fold.

DO NOT INCLUDE
Text, letters, captions, page numbers, musical notation, readable sheet music, sound-effect lettering, logos, flags, coats of arms, uniforms, crowd, buildings, scenery, confetti, stars, decorative borders, extra instruments, extra people, extra costume details, invented Vitxet attributes, or any other object not requested above.

The result is a private working prototype for editorial review only. Do not add a claim of permission, endorsement or commercial readiness. Deliver the illustration only, without explanatory text.

## Criterios de revisión al recibir el resultado

- Reconocimiento y fidelidad del Vitxet frente a la referencia simplificada: cara, barba, sombrero, vestuario, silueta y ornamentos.
- Cuerpo entero, pose legible y figura sin elementos esenciales en el pliegue.
- Niño y tambor genérico claramente legibles, separados y proporcionados.
- 4–8 áreas grandes por página, contornos cerrados y dificultad realista para 3–5 años.
- Equilibrio de masas, aire, seguridad del medianil y coherencia de línea entre ambas páginas.
- Ausencia de contenido excluido, defectos de generación y detalles ajenos a referencias.
- Riesgo de derechos: el parecido reconocible con el Vitxet sigue sujeto al límite privado de D025; no es licencia ni habilitación para publicar, vender, distribuir, subir a KDP o entregar a terceros.

**Próximo paso:** ejecutar el prompt en Gemini adjuntando los tres estudios con la jerarquía indicada y traer la imagen resultante para revisión. Registrar después el modelo exacto, el archivo, la iteración y la evaluación. No iniciar G01 ni D01.
