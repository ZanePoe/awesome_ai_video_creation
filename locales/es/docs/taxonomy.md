# Alcance y categorías

Se incluyen proyectos de GitHub que participen directamente en la generación de vídeo, la edición, el análisis de material, los avatares digitales, el motion por código, la automatización con agentes, la obtención de medios o la evaluación. Los productos puramente comerciales, las páginas solo demostrativas sin implementación verificable, los generadores de imagen ordinarios y los agentes genéricos sin relación con el vídeo no entran en el catálogo principal.

| Categoría | Responsabilidad principal |
| --- | --- |
| Editores de vídeo y estudios de producción | Aportan línea de tiempo, lienzo, nodos, archivo de proyecto o interfaz completa de producción |
| Producción de vídeo con agentes y automatización | Sistemas multipaso que van del objetivo/guion al material, el montaje, el control de calidad y la exportación |
| Vídeos cortos de conocimiento, clips y explicaciones | Vídeos de conocimiento, explicación con avatar digital, troceado de vídeos largos y vídeos cortos sociales |
| Agent Skills, MCP y herramientas de edición | Skills, MCP, CLIs y herramientas deterministas invocables por agentes de codificación |
| Code-to-video y motion graphics | Renderizan vídeo mediante código HTML/React/Canvas/Three.js/Python, etc. |
| Animación, 3D y componentes base de codificación | Herramientas genéricas de animación, vectores, render 3D y codificación GIF para construir escenas de vídeo; clasificadas como infraestructura adyacente |
| ComfyUI y modelos de vídeo abiertos | Modelos de vídeo por difusión/DiT, flujos ComfyUI y runtime de generación |
| Avatares digitales, animación de retratos y sincronización labial | Control por retrato, cabezas parlantes, avatares en tiempo real y sincronización labial |
| Descarga, captura, transcodificación y CLIs de material | Descarga legítima de material, streams en directo, transcodificación, multiplexado y procesamiento base |
| Evaluación, investigación e índices externos | Benchmarks de generación/edición de vídeo, código de investigación e índices de cobertura |
| Versiones históricas y restringidas | Versiones históricas open source o proyectos cuya licencia actual ya no es abierta |

Cada repositorio tiene una sola categoría principal. Una Skill puede invocar Remotion, FFmpeg o una API de modelos, pero eso no la duplica en tres categorías.

## Fronteras importantes

- Downvid/VidBee son la capa de producto; yt-dlp, FFmpeg, etc. son sus herramientas subyacentes.
- Skill/MCP no equivale a editor independiente: hay que indicar el anfitrión, el renderizador y los servicios externos.
- Que los "archivos del proyecto sean locales" no significa que las APIs de modelos, ASR, TTS o la búsqueda de material no salgan a la red.
- El vídeo generado por código, el vídeo por difusión y el montaje de material real son métodos de producción distintos.
- La licencia del código del modelo, la licencia de los pesos, los datos de entrenamiento, la política de salida y los derechos de imagen deben verificarse por separado.
- Las herramientas de descarga solo aplican a contenido que el usuario tenga derecho a guardar y procesar, y deben respetar los términos de la plataforma.
- Los resultados de benchmark solo son comparables con el mismo modelo, las mismas entradas, el mismo presupuesto y el mismo protocolo de puntuación.
