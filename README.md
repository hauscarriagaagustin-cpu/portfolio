# Portfolio web de Agustín Hauscarriaga

Trabajo Final de Diseño UX-UI 2026 · Licenciatura en Sistemas de Información · UADER FCyT, Concepción del Uruguay.

- **Sitio publicado:** https://hauscarriagaagustin-cpu.github.io/portfolio/
- **Figma (research, wireframes, design system y prototipo):** https://www.figma.com/design/gaaurpWOjeOik9yC3PFP9I/Sin-t%C3%ADtulo?node-id=0-1&t=oSwCGUClUON8U7OR-1
- **Repositorio:** https://github.com/hauscarriagaagustin-cpu/portfolio

## Concepto

Palabras clave: **Cercano, Claro, Artesanal**. Tema claro con crema, verde café y terracota, pensado para conectar con el proyecto Coffea y diferenciarse de la referencia oscura de la consigna.

## Stack

- HTML5 semántico y CSS3 puro (variables en `:root`, Flexbox y Grid, mobile-first).
- JavaScript vanilla para el menú mobile (`aria-expanded` y `aria-controls`) y el botón de copiar email.
- Tipografías de Google Fonts con `font-display: swap`: Fraunces (títulos) e Inter (texto).
- Sin frameworks JS ni constructores visuales.
- Imágenes en WebP con `width`, `height` y `loading="lazy"` debajo del pliegue.

## Estructura del sitio

One-page con anclas: Header, Hero, Métricas, Skills, Proyectos, Experiencia y formación, Sobre mí, Contacto y Footer. Incluye un caso de estudio propio (`caso-coffea.html`) y una página 404 personalizada.

## Proyectos mostrados

| Proyecto | Enlace |
|---|---|
| Coffea, landing page de una cafetería | [Caso de estudio](caso-coffea.html) |
| Cubrí, contratación digital de seguros (trabajo en grupo) | https://sofiferuader1.github.io/TP5-Cubri-Seguros/ |
| NovaStudio, contratación de sitios web | https://github.com/hauscarriagaagustin-cpu/UX-UI/tree/main/ejercicio_20 |

**Autoría:** Coffea es un trabajo individual. Cubrí Seguros fue elaborado en grupo y su sitio está publicado en otra cuenta de GitHub del grupo. NovaStudio es un trabajo propio.

## Fuentes de templates y recursos

- No se usó un template de sitio como base para este portfolio.
- Tipografías: [Fraunces](https://fonts.google.com/specimen/Fraunces) e [Inter](https://fonts.google.com/specimen/Inter) (Google Fonts, licencia OFL).
- Capturas de los tres proyectos y retrato: material propio del autor.
- Compresión de imágenes a WebP con Pillow (Python).

## Uso de IA

Se utilizó Claude (Anthropic) como asistente, y también la herramienta de IA de Figma para generar el primer borrador de las pantallas.

**Qué se generó:**
- El documento de proceso UX (proto-persona, concepto, arquitectura de información, especificación del design system y guion del test).
- El código inicial de HTML, CSS y JavaScript del sitio, y borradores de los textos.
- Un primer borrador de las pantallas en Figma, los dibujos de wireframes y design system, y las slides del proceso.

**Cómo se revisó:**
Fui revisando cada resultado paso a paso, verificando que cumpliera lo que pedía cada consigna del trabajo, y corregí los errores que fueron apareciendo durante el proceso. En concreto:
- Probé el sitio publicado y detecté que el botón de email no hacía nada en equipos sin programa de correo. Se corrigió mostrando el email visible y agregando un botón para copiarlo.
- Corrí Lighthouse sobre el sitio publicado y verifiqué los resultados.
- Corregí en Figma contenido inventado por la IA (textos, imágenes y un retrato ilustrativo) y lo reemplacé por contenido real de mis proyectos.
- Comprobé que el sitio y el Figma fueran consistentes entre sí.
- Aprobé o modifiqué cada texto antes de publicarlo.

## Proceso UX

Resumen del proceso (usuario objetivo, concepto, arquitectura de información, wireframes, design system, prototipo y test de usabilidad) en el PDF de la entrega y en el archivo de Figma.

**Test de usabilidad:** 3 participantes completaron 5 tareas sobre el sitio publicado. Tasa de éxito: 100 %. Tiempo total medio: unos 2 minutos y 30 segundos.

| Hallazgo | Cambio aplicado |
|---|---|
| Un participante tuvo que bajar mucho para encontrar el contacto | Botón "Contacto" fijo en el header en tablet y celular |
| Un participante dudó cuál era el proyecto más reciente | Etiqueta "Caso de estudio" en el proyecto principal |
| Un participante tuvo que buscar dónde estaban algunas secciones | Hallazgo menor, sin cambio específico |

## Despliegue

1. Repositorio público en GitHub con rama `main`.
2. En **Settings → Pages**: *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. Cada `git push` a `main` redespliega el sitio automáticamente.

## Calidad

Lighthouse en modo mobile sobre el sitio publicado:

| Performance | Accessibility | Best Practices | SEO |
|---|---|---|---|
| 99 | 100 | 100 | 100 |

## Capturas

Las capturas del sitio, del reporte de Lighthouse y de la comparación entre Figma y sitio están en la carpeta [`docs/`](docs/).
