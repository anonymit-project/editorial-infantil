# Resolución técnica de doble página — Reus per pintar – petits

**Fecha:** 20-11-2026  
**Estado:** recomendación técnica de Fase 3; pendiente de prueba física y confirmación en el configurador KDP.  
**Decisiones de referencia:** D014, D026 y D028.

## 1. Problema a resolver

D014 fija una maqueta de 32 páginas. D026 exige composiciones coordinadas de doble página enfrentada y protege el medianil. D028 permite impresión a doble cara cuando sea necesaria y mantiene las 32 páginas. No se debe interpretar «doble página» como una ilustración panorámica que tenga que cruzar el pliegue.

La solución debe distinguir:
1. la pareja visual de páginas que el lector ve simultáneamente;
2. las dos caras físicas de cada hoja;
3. el archivo PDF que KDP recibe, que debe contener páginas individuales.

## 2. Paginación física

En un libro de lectura izquierda-derecha:
- Las páginas impares se imprimen como recto/derecha.
- Las páginas pares son verso/izquierda.
- Las parejas interiores que el lector ve enfrentadas son 2–3, 4–5, 6–7, 8–9, etc.
- La cara posterior de una página no es la página enfrentada: es el reverso físico de esa misma hoja.
- KDP exige que el interior se entregue como páginas individuales, no como pliegos de dos páginas.

Por ello, una composición enfrentada se construye sobre una pareja de páginas consecutivas, pero se exporta como dos páginas individuales.

## 3. Comparación editorial y de impresión

**Una cara con reversos blancos:** reduce transparencia y transferencia, pero no aprovecha las páginas para spreads coordinados sin crear spreads vacíos intercalados. Con 32 páginas, el número de dibujos útiles cae de forma importante.

**Doble cara con contenido en cada página:** permite una secuencia completa de dobles páginas coordinadas. Cada cara posterior tendrá otra ilustración del libro. Puede haber transparencia visual o transferencia de cera por presión, especialmente si se usan rotuladores o materiales líquidos.

**Recomendación:** usar contenido a doble cara, sin fondos, sin grandes masas negras y con contornos limpios. Recomendar ceras y lápices de colores; desaconsejar rotuladores. No prometer que el papel evitará toda transferencia. Probar una copia física antes de cerrar.

## 4. Arquitectura recomendada de 32 páginas

- Página 1: portadilla/título.
- Página 2: créditos, nota de uso e instrucción breve en catalán.
- Página 3: blanca, como protección del reverso de la primera página de coloreado.
- Páginas 4–31: 14 dobles páginas ilustradas (28 páginas individuales), coordinadas por tema, ritmo o contexto.
- Página 32: blanca, como protección del reverso de la última página de coloreado.

Las parejas son: 4–5, 6–7, 8–9, 10–11, 12–13, 14–15, 16–17, 18–19, 20–21, 22–23, 24–25, 26–27, 28–29 y 30–31.

Cada página debe contener una idea principal y funcionar por sí sola. La pareja no debe depender de continuidad gráfica a través del medianil.

## 5. Protección del medianil

El mínimo técnico de KDP para 24–150 páginas es un margen interior de 0,375 pulgadas (9,6 mm). Este mínimo no equivale a una recomendación compositiva suficiente para una doble página infantil.

Criterio editorial inicial:
- reservar una banda central de 12–15 mm a cada lado del eje del pliegue;
- no ubicar ojos, caras, atributos, siluetas esenciales, campanas, puertas, ventanas distintivas ni texto en esa banda;
- evitar líneas que deban coincidir exactamente a través del pliegue;
- dejar una separación visual suficiente entre los dos dibujos;
- comprobar la apertura real en una copia impresa.

La medida final del margen se fijará en la plantilla KDP vigente para el tamaño y recuento definitivos.

## 6. Requisitos KDP comprobados (20-11-2026)

- Mínimo de tapa blanda: 24 páginas; 32 páginas es admisible.
- Páginas interiores individuales, no pliegos.
- Resolución de imágenes: mínimo 300 ppp.
- Grosor mínimo técnico de línea: 0,75 pt / 0,3 mm aproximadamente.
- Margen interior: 0,375 in / 9,6 mm para 24–150 páginas.
- Margen exterior mínimo: 0,25 in / 6,4 mm sin sangrado; 0,375 in / 9,6 mm con sangrado.
- Tamaños personalizados admitidos hasta 8,5 × 11,69 in. El A4 aproximado 8,27 × 11,69 in queda dentro del rango, pero debe confirmarse en el configurador y plantilla descargada.
- El A4 supera el umbral de tamaño regular y entra en la categoría de tamaño grande para costes. El coste final debe confirmarse con el PDF y el calculador KDP.

Fuentes oficiales:
- https://kdp.amazon.com/en_US/help/topic/G201857950
- https://kdp.amazon.com/en_US/help/topic/GVBQ3CMEQW3W2VL6
- https://kdp.amazon.com/en_US/help/topic/G201834180
- https://kdp.amazon.com/en_US/help/topic/G201834340

## 7. Riesgo de transparencia y prueba física

La ayuda de KDP establece mínimos de archivo y márgenes, pero no garantiza que el papel sea opaco para ceras, lápices o presión infantil. El riesgo depende de la herramienta, presión, cantidad de tinta y contraste del reverso.

Prueba obligatoria:
1. dummy PDF de 32 páginas con la paginación propuesta;
2. copia física KDP con papel blanco y tinta negra;
3. prueba con cera gruesa y lápiz de color;
4. observación de transparencia a luz normal;
5. comprobación de transferencia por contacto y presión;
6. evaluación del medianil, márgenes y legibilidad en apertura natural.

Si el resultado no es aceptable, se deberá rediseñar la densidad del reverso o presentar una nueva propuesta que modifique la estructura de 32 páginas. No cambiar D014/D028 unilateralmente.

## 8. Conclusión

La arquitectura recomendada mantiene las 32 páginas, permite dobles páginas coordinadas sin obligar a cruzar el pliegue y aprovecha la impresión a doble cara. Es técnicamente compatible con la regla de KDP de páginas individuales, pero la experiencia de coloreado no queda validada hasta probar una copia física. No se fija todavía formato final, papel, PVP ni coste.
