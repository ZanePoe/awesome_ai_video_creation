# Metodología de búsqueda, palabras clave y registro de cobertura

Fecha de investigación: 2026-11-12. El objetivo era derivar el ecosistema de generación y edición de vídeo con IA a partir de los 22 proyectos de referencia del usuario, no mezclar modelos generativos, NLE tradicionales, descargadores y Skills en una sola tabla.

## Palabras clave

| Dirección | Palabras clave en inglés | Palabras clave en chino |
| --- | --- | --- |
| Edición con agente | agent video editor, video MCP, editing skill | Agent 剪辑、视频 Skill、剪辑 MCP |
| Producción completa | agentic video production, script-to-video, timeline | 视频生产 Agent、脚本成片、时间线 |
| Vídeos cortos de conocimiento | explainer video, knowledge article to video, shorts | 知识类短视频、讲解视频、长视频切片 |
| Code-to-video | Remotion, HyperFrames, HTML video, motion graphics | 代码成片、动效、数据故事 |
| Avatares digitales | digital presenter, talking avatar, lip sync | 数字人、口播、肖像动画、唇同步 |
| Modelos generativos | text-to-video, image-to-video, video diffusion | 文生视频、图生视频、视频扩散模型 |
| CLI de medios | video downloader CLI, FFmpeg, yt-dlp, Streamlink | 视频下载 CLI、转码、直播流 |
| Evaluación | video editing benchmark, VFX benchmark, agent editing | 视频编辑评测、多镜头剪辑、AgentEdit |

## Proceso de tres rondas

| Ronda | Lotes | Resultados | Fuentes nuevas | Tasa de fuentes nuevas |
| --- | ---: | ---: | ---: | ---: |
| 1 | 14 | 394 | 377 | 95.7% |
| 2 | 7 | 130 | 101 | 77.7% |
| 3 | 7 | 270 | 208 | 77.0% |

La primera ronda cubrió los proyectos del usuario, búsquedas en GitHub, la comparativa de CLIs, los riesgos, los benchmarks y el índice externo Awesome Video Editing.

La segunda ronda revisó OpenFilm, OpenKatana, Kinocut, OpenMontage, OpenClip, MakeMyClip, WeVisCut, VidBee y GiveMotion, además de nuevas entidades como VEFX/CutCraft/AgentEdit.

La tercera ronda completó los modelos de vídeo abiertos, los avatares digitales, las explicaciones de conocimiento, las bases de code-to-video y las CLIs de descarga, y registró en lote los README primarios y las métricas de GitHub de todos los proyectos finales.

La razón de parada fue el límite predeterminado de tres rondas, no la saturación del espacio de búsqueda. La tercera ronda aún tenía una tasa alta de fuentes nuevas, así que el catálogo debe mantenerse de forma incremental.

## Content Factory

Se invocó `/search/api/query` por la ruta curl de `content-factory-search-api`. Las consultas incluyeron:

- `AI 视频剪辑 OR 视频生成 OR 知识类短视频`
- `SeeCut OR OpenChatCut OR Clypra OR ReelBench`
- `Downvid OR yt-dlp OR 视频下载 CLI`
- `OpenFilm OR OpenKatana OR Kinocut OR WeVisCut`

Las consultas empezaron por los últimos 30 días y, cuando eran escasas, se ampliaron a 90/180/365 días según las reglas de la skill. Tras la normalización, Content Factory aportó 69 fuentes y ayudó a descubrir Clypra, GeekReel, VidBee, WeVisCut, OpenFilm, OpenMontage y el ecosistema de Skills de vídeo con agentes. Las consultas amplias de vídeo con IA también generaron mucha evaluación de modelos y contenido irrelevante; la decisión final sobre cada proyecto volvió al repositorio oficial.

No se enviaron al repositorio público direcciones de servicios privados, claves ni el cuerpo de artículos internos.

## Correcciones clave de clasificación

- **Downvid no es un parser del mismo nivel que yt-dlp.** Es una GUI/WebUI multiplataforma; el análisis proviene de yt-dlp y la fusión y transcodificación de FFmpeg.
- **VidBee es un producto de comprensión de medios posterior a la descarga.** Además de descargar, ofrece transcripción local, anotación de hablantes, resumen, traducción y conversación sobre el material.
- **SeeCut es un espacio de trabajo de Skills para agentes, no un NLE independiente.**
- **Video Autopilot Kit planifica y audita; Editkin hace el renderizado real.**
- **CozyClay es una herramienta de previs y planificación de planos.** La generación final corre a cargo de modelos de vídeo externos.
- **Rea Video hace descomposición en reversa y planificación de réplicas.** No es el editador final.
- **OpenFilm/GiveMotion/HyperFrames pertenecen a código-a-vídeo.** No se comparan directamente con capacidades de línea de tiempo tradicional.
- **Los repositorios de modelos generativos y las aplicaciones de creación van separados.** Wan, Hunyuan, LTX, CogVideo, Mochi, etc. aportan modelos y código de inferencia, no gestión completa de la producción.

## Downvid y las CLIs

Las fuentes disponibles de OpenViking y del historial local no permitieron identificar de forma única "la CLI que el usuario usaba antes", por lo que no se especuló. La [comparativa de CLIs](cli-comparison.md) final cubre:

- Downvid: GUI/WebUI, depende de yt-dlp + FFmpeg.
- VidBee: escritorio + CLI; tras la descarga sigue con transcripción local y comprensión de medios.
- yt-dlp: la CLI principal subyacente de análisis multi-sitio y descarga.
- you-get / Lux: rutas más ligeras en Python / Go.
- Streamlink: streams en directo hacia reproductores o cadenas de grabación.
- FFmpeg: transcodificación, filtros, fusión y multiplexado; no analiza sitios.

Si en el futuro se confirma el nombre de aquella CLI histórica, podrá añadirse como entrada incremental a esta comparativa.

## Correcciones de licencias

- SeeCut: PolyForm Noncommercial.
- Remotion: gratuito para personas/organizaciones pequeñas; las empresas que alcanzan ciertas condiciones necesitan licencia comercial.
- VRGameDevGirl: source-available; el contenido generado puede comercializarse, pero el software en sí requiere autorización para uso comercial.
- HunyuanVideo / I2V: licencia comunitaria de Tencent, con exclusiones regionales y política de uso.
- Wav2Lip: uso personal, de investigación y no comercial.
- Palmier: GPL el código fuente hasta v0.7.6; los binarios posteriores son propietarios sin fuente pública correspondiente.
- EditVerse: la Adobe Research License solo cubre los archivos expresamente enumerados.
- FFmpeg: LGPL por defecto; la licencia global cambia al activar componentes GPL específicos.
- SenseNova Code2Video, CutCraft: no se encontró licencia raíz clara.

La descripción de licencias no sustituye un asesoramiento legal; el material, las fuentes, la música, los retratos, los datos de entrenamiento y la salida de los modelos siguen teniendo fronteras de derechos independientes.

## Cobertura

Las 22 URLs de GitHub de la línea base del usuario entraron todas en el registro de investigación; cobertura de URLs: 100%. La única no coincidencia, `CLI-oriented`, es una frase descriptiva común de la nota del usuario, no un proyecto.

La cobertura del índice externo `devanasolver/awesome-video-editing` es del 53.3%. Su alcance incluye además NLE tradicionales, herramientas de audio, subtítulos, grabación de pantalla, iconos, fuentes, HDRI, sitios de música/vídeo gratuitos y muchas URLs de insignias. Como este catálogo deliberadamente no copia todos los sitios de material y herramientas tradicionales, esa brecha es una diferencia de alcance; los proyectos del índice externo directamente relacionados con vídeo con IA/agentes se usaron como pistas de descubrimiento.

## Lo que no se hizo en esta ronda

No se instalaron ni ejecutaron los proyectos del catálogo, no se descargaron pesos de modelos grandes, no se llamaron a APIs de generación de pago, no se descargó, desmarcó, editó ni publicó material del usuario, y no se reprodujo ningún benchmark de forma unificada.

Las estrellas y el volumen de commits de GitHub solo sirven para la ordenación por mantenimiento. Una comparación real debe fijar material, guion, modelos, hardware, presupuesto de API y formato de salida, y registrar la tasa de piezas terminadas, el volumen de ajustes manuales, la coherencia entre planos, subtítulos y sincronización labial, el tiempo de renderizado, la VRAM, el coste y la licencia.

## Archivos verificables

- [Registro de búsquedas](../../../research/search-log.json)
- [Decisiones de inclusión y evidencia fija](../../../research/decisions.json)
- [Cobertura de proyectos del usuario](../../../research/coverage-user.json)
- [Cobertura del índice externo](../../../research/coverage-external.json)
- [Instantánea inicial de métricas](../../../research/initial-metrics.json)
- [Estado de la investigación](../../../research/status.json)
- [Verificación de integridad](../../../research/verification.json)

El registro de investigación contiene 686 fuentes, 144 decisiones y 216 conjuntos de métricas de GitHub. El texto web completo y los registros de herramientas locales se quedan en local.
