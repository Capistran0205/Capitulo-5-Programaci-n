# Resumen del Capítulo 5

## Título
**Introducción a las hojas de estilo en cascada (Cascading Style Sheets, CSS): parte 2**

## De qué trata
Continúa el capítulo 4 y presenta las nuevas características de **CSS3**. Estas herramientas se están integrando en los navegadores, lo que permite un desarrollo Web más económico y veloz, mejora el rendimiento del lado cliente y reduce la necesidad de bibliotecas de JavaScript y de programas de gráficos como Photoshop o Illustrator para crear efectos visuales.

## Objetivos del capítulo
Al terminar el capítulo, el lector aprenderá a:

- Agregar sombras de texto y efectos de trazo de texto.
- Crear esquinas redondeadas.
- Agregar sombras a elementos.
- Crear gradientes lineales y radiales, además de reflexiones.
- Crear animaciones, transiciones y transformaciones.
- Usar múltiples imágenes de fondo y bordes de imágenes.
- Crear un diseño de varias columnas.
- Usar el diseño de modelo de cajas flexible y los selectores `:nth-child`.
- Usar la regla `@font-face` para especificar las fuentes de una página Web.
- Usar colores RGBA y HSLA.
- Usar prefijos de proveedor.
- Usar consultas de medios para adaptar el contenido a diversos tamaños de pantalla.

## Ideas centrales
1. **CSS3 permite lograr efectos visuales sólo con estilos:** `text-shadow`, `box-shadow`, `border-radius`, gradientes, múltiples fondos, `border-image` y, en WebKit, trazo de texto y reflejos.
2. **Los prefijos de proveedor** (`-webkit-`, `-moz-`, `-o-`, `-ms-`) permiten usar funciones que aún no están terminadas en el estándar; se escriben antes de la versión sin prefijo.
3. **Animación y transición no son lo mismo:** la animación controla los estados intermedios con `@keyframes`; la transición sólo define el valor inicial y el final. Las transformaciones (`rotate`, `scale`, `skew`) y `:hover` las hacen interactivas.
4. **El diseño se vuelve más flexible:** caja flexible, selectores `:nth-child`, texto multicolumna y fuentes descargables con `@font-face`.
5. **Las consultas de medios (`@media`)** aplican estilos según las características del dispositivo, como su anchura, y son la base para adaptar una misma página a teléfonos, tabletas y equipos de escritorio.
