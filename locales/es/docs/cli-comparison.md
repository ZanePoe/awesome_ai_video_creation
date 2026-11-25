# Comparativa de Downvid y CLIs de vídeo

El usuario mencionó haber usado otra CLI en el pasado, pero OpenViking y el historial local actualmente consultables no permiten identificar su nombre de forma única. Esta página compara los proyectos principales verificables y no especula sobre la identidad de aquella herramienta histórica.

| Proyecto | Forma | Uso principal | Relación con Downvid | Frontera clave |
| --- | --- | --- | --- | --- |
| Downvid | GUI de escritorio / WebUI | Descarga multi-sitio, elección de formato y fusión con FFmpeg | Capa de producto; depende internamente de yt-dlp y FFmpeg | La capacidad de análisis evoluciona con yt-dlp; hay que respetar los términos de cada sitio |
| VidBee | Aplicación de escritorio + CLI | Descarga, transcripción, anotación de hablantes, resumen, traducción y conversación sobre medios | Aporta una cadena de comprensión multimedia más amplia que Downvid | Los proveedores de IA pueden salir a la red; la descarga sigue dependiendo de yt-dlp |
| yt-dlp | CLI en Python | Análisis, descarga, metadatos y posprocesado de audio/vídeo multi-sitio | El parser subyacente principal de Downvid/VidBee | Curva de aprendizaje alta como CLI; los cambios de los sitios exigen actualizaciones frecuentes |
| you-get | CLI en Python | Descarga sencilla de medios desde páginas web | Alternativa directa de CLI más ligera | La actividad de mantenimiento y la cobertura de sitios deben compararse frente a yt-dlp |
| Lux | CLI en Go | Descarga de vídeo multi-sitio | Alternativa de estilo binario único | La adaptación a sitios y la frecuencia de mantenimiento son el riesgo central |
| Streamlink | CLI en Python | Envía streams en directo a reproductores o cadenas de grabación | Complemento para directo; no es un descargador general bajo demanda | Más orientado al stream en tiempo real que a la edición |
| FFmpeg | Cadena de herramientas en C | Transcodificación, filtros, fusión, multiplexado y streaming | Base de fusión/transcodificación de Downvid | Las opciones de compilación deciden LGPL/GPL; no analiza sitios |

## Sugerencias de elección

- Si quieres "abrir y usar": Downvid.
- Si quieres transcribir, resumir y buscar material justo después de descargar: VidBee.
- Si quieres escribir guiones, procesar por lotes y controlar con precisión formatos y posprocesado: yt-dlp + FFmpeg.
- Si trabajas principalmente con directo: Streamlink.
- Si buscas una experiencia de CLI simple o de binario único: evalúa you-get y Lux por separado, y confirma primero que los sitios objetivo siguen soportados.

Este catálogo no equipara la capacidad de descarga con un "derecho sin marca de agua". Que una herramienta pueda analizar un contenido no significa que el usuario tenga derecho a descargarlo, quitarle la marca, volver a editarlo o publicarlo.
