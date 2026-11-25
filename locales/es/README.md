🌐 [English](../../README.md) · [简体中文](../zh/README.md) · **Español** · [हिन्दी](../hi/README.md) · [Français](../fr/README.md)

# awesome_ai_video_creation

**Catálogo abierto de generación y edición de vídeo con IA, vídeos cortos de conocimiento, avatares digitales, Agent Skills, ComfyUI y CLIs de medios.**

Curación open source de generación y edición de vídeo con IA, producción con agentes, código-a-vídeo, presentadores digitales, flujos ComfyUI, CLIs de medios y benchmarks — con descripciones enlazadas a evidencia y rankings reproducibles de mantenimiento en GitHub.

Este catálogo cubre la cadena completa: obtención legítima de material, planificación de guion y planos, generación de imagen/vídeo, avatares digitales, montaje en línea de tiempo, subtítulos y doblaje, motion graphics, control de calidad y exportación. Modelos, estudios, Skills, CLIs y benchmarks se clasifican por separado.

[Índice de categorías](#índice-de-categorías) · [Ficha detallada de proyectos](docs/projects.md) · [Comparativa de CLIs](docs/cli-comparison.md) · [Ordenaciones](docs/rankings.md) · [Registro de búsqueda](docs/research.md) · [Contribuir](CONTRIBUTING.md)

```mermaid
flowchart LR
    A[Tema / guion / material] --> B[Plan de planos / guion gráfico]
    B --> C[Grabación real / modelo generativo / motion por código]
    C --> D[Línea de tiempo / subtítulos / doblaje / música]
    D --> E[Revisión / control de calidad / reparación]
    E --> D
    E --> F[Exportación / paquete de publicación]
```

La primera versión ofrece un mapa verificable del ecosistema; no pretende agotar todos los modelos de vídeo, las APIs comerciales ni los complementos de NLE tradicionales.

## Ir a una categoría

[Editores de vídeo y estudios de producción](#editores-de-vídeo-y-estudios-de-producción) · [Producción de vídeo con agentes y automatización](#producción-de-vídeo-con-agentes-y-automatización) · [Vídeos cortos de conocimiento, clips y explicaciones](#vídeos-cortos-de-conocimiento-clips-y-explicaciones) · [Agent Skills, MCP y herramientas de edición](#agent-skills-mcp-y-herramientas-de-edición) · [Code-to-video y motion graphics](#code-to-video-y-motion-graphics) · [Animación, 3D y componentes base de codificación](#animación-3d-y-componentes-base-de-codificación) · [ComfyUI y modelos de vídeo abiertos](#comfyui-y-modelos-de-vídeo-abiertos) · [Avatares digitales, animación de retratos y sincronización labial](#avatares-digitales-animación-de-retratos-y-sincronización-labial) · [Descarga, captura, transcodificación y CLIs de material](#descarga-captura-transcodificación-y-clis-de-material) · [Evaluación, investigación e índices externos](#evaluación-investigación-e-índices-externos) · [Versiones históricas y restringidas](#versiones-históricas-y-restringidas)

## Catálogo actual

**109 proyectos, de los cuales 22 son proyectos de referencia del usuario y 87 se han añadido en esta ronda.** Verificación funcional: 2026-11-25; instantánea de métricas: `2026-11-25T00:17:13+00:00` (UTC).

Dentro de cada categoría se estratifica primero por estado de mantenimiento y luego se ordena combinando estrellas (40%), commits en la rama por defecto a 90 días (35%) y último commit (25%). La puntuación de mantenimiento no representa la calidad del montaje final, la capacidad de los modelos, la seguridad de derechos ni la madurez de producción.

## Vistazo rápido a los proyectos nucleares activos

Solo se muestran los candidatos principales con licencia abierta verificada y commits en los últimos 90 días; las licencias restringidas, los modelos base, los benchmarks de investigación y las herramientas adyacentes no entran en esta tabla.

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento |
| --- | --- | --- | --- | --- | --- |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | Ecosistema de código-a-vídeo y Agent Skills basado en HTML/CSS/JS, con migración desde Remotion y otros y verificación fotograma a fotograma. | 89,564 | 3,965 | 2026-11-24 | 99.6 |
| [Concat](https://github.com/jub0t/Concat) | Editor multipista local y multiplataforma con subtítulos, TTS, recorte de fondo, fotogramas clave, efectos y exportación 4K. | 19,997 | 1,677 | 2026-11-25 | 94.4 |
| [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) | Sistema multipipeline de producción de vídeo para agentes de codificación que cubre investigación, guion, material, doblaje, subtítulos y renderizado. | 83,059 | 272 | 2026-11-16 | 93.6 |
| [OpenMotion](https://github.com/nexu-io/openmotion) | Estudio de réplica de vídeos de referencia y motion graphics de marca para agentes de codificación locales, con Motion.md, línea de tiempo visual y exportación MP4. | 16,018 | 758 | 2026-11-24 | 93.6 |
| [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill) | CLI y MCP que dan a los agentes de codificación edición local con FFmpeg: cortes, subtítulos, exportación de formatos y revisión de salida. | 10,672 | 966 | 2026-11-24 | 92.0 |
| [Jellyfish](https://github.com/Forget-C/Jellyfish) | Estudio de producción de dramas cortos con IA que cubre desglose del guion, guion gráfico, gestión de activos de personajes y escenas, generación de planos y exportación. | 7,311 | 1,665 | 2026-11-23 | 90.4 |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Descargador de audio/vídeo por línea de órdenes muy completo, compatible con una gran cantidad de sitios. | 210,460 | 81 | 2026-11-24 | 89.7 |
| [OpenFilm](https://github.com/openfilm/openfilm) | Permite a los agentes de codificación crear, inspeccionar, editar y renderizar vídeo con código, y aporta una interfaz editable. | 9,289 | 298 | 2026-11-23 | 88.4 |
| [Clypra](https://github.com/AIEraDev/Clypra) | Editor de vídeo multiplataforma con aceleración por hardware, construido con Rust/Tauri/React. | 3,374 | 1,916 | 2026-11-22 | 87.5 |
| [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | Skills, plantillas, comandos y herramientas para Claude Code: guion, doblaje, música, generación de imagen y vídeo, control de calidad, renderizado y publicación, con migración a Codex y Kiro CLI. | 2,751 | 537 | 2026-11-24 | 87.5 |
| [CozyClay](https://github.com/HaD0Yun/CozyClay) | Herramienta en el navegador para montar escenas, bloquear el movimiento de personajes, cortar planos y previsualizar vídeo con IA. | 2,026 | 2,169 | 2026-11-24 | 86.3 |
| [Manim Community](https://github.com/ManimCommunity/manim) | Motor de vídeo para crear animaciones matemáticas y de explicación con código Python. | 42,881 | 78 | 2026-11-23 | 86.3 |

## Índice de categorías

`★Referencia del usuario` indica proyectos aportados directamente por el usuario. Modelos, editores, Skills, CLIs y benchmarks se clasifican por separado.

| Categoría | Cantidad | Proyectos mejor posicionados por mantenimiento |
| --- | --- | --- |
| Editores de vídeo y estudios de producción | 19 | Concat, Jellyfish, Clypra |
| Producción de vídeo con agentes y automatización | 9 | Hypit, OpenMontage, OpenMotion |
| Vídeos cortos de conocimiento, clips y explicaciones | 10 | NeonClipping, Clipmint, ChrisHKAI Video |
| Agent Skills, MCP y herramientas de edición | 16 | FFmpeg Skill, Claude Code Video Toolkit, Video Shotcraft |
| Code-to-video y motion graphics | 9 | HyperFrames, Remotion, raea |
| Animación, 3D y componentes base de codificación | 15 | Godot, three.js, Motion |
| ComfyUI y modelos de vídeo abiertos | 9 | VRGameDevGirl AI Video Builder, LTX-Video, HunyuanVideo |
| Avatares digitales, animación de retratos y sincronización labial | 5 | LiveTalking, MuseTalk, LivePortrait |
| Descarga, captura, transcodificación y CLIs de material | 8 | FFmpeg, yt-dlp, Streamlink |
| Evaluación, investigación e índices externos | 8 | Aurora / AgentEdit-Bench, Awesome AI Video for Creators, CutCraft Bench |
| Versiones históricas y restringidas | 1 | Palmier Pro |

### Editores de vídeo y estudios de producción

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [Concat](https://github.com/jub0t/Concat) · ★Referencia del usuario | Editor multipista local y multiplataforma con subtítulos, TTS, recorte de fondo, fotogramas clave, efectos y exportación 4K. | 19,997 | 1,677 | 2026-11-25 | 94.4 | AGPL-3.0 |
| [Jellyfish](https://github.com/Forget-C/Jellyfish) | Estudio de producción de dramas cortos con IA que cubre desglose del guion, guion gráfico, gestión de activos de personajes y escenas, generación de planos y exportación. | 7,311 | 1,665 | 2026-11-23 | 90.4 | Apache-2.0 |
| [Clypra](https://github.com/AIEraDev/Clypra) · ★Referencia del usuario | Editor de vídeo multiplataforma con aceleración por hardware, construido con Rust/Tauri/React. | 3,374 | 1,916 | 2026-11-22 | 87.5 | MIT |
| [CozyClay](https://github.com/HaD0Yun/CozyClay) · ★Referencia del usuario | Herramienta en el navegador para montar escenas, bloquear el movimiento de personajes, cortar planos y previsualizar vídeo con IA. | 2,026 | 2,169 | 2026-11-24 | 86.3 | AGPL-3.0 |
| [Huobao Drama](https://github.com/chatfire-AI/huobao-drama) · Aviso de licencia | Plataforma web/escritorio que, a partir de una frase o de una novela pegada, reescribe automáticamente el guion, genera imágenes y vídeos de planos, doblaje y subtítulos y monta el drama corto completo; el backend se orquesta con Mastra Agent y las skills son editables en la interfaz. | 17,971 | 108 | 2026-11-21 | 84.4 | CC BY-NC-SA-4.0 (prohibido el uso comercial) |
| [OpenChatCut](https://github.com/0xsline/OpenChatCut) · ★Referencia del usuario | Editor conversacional de vídeo con IA centrado en lo local, con línea de tiempo multipista, Agent Skills, MCP y renderizado Remotion. | 3,310 | 403 | 2026-11-12 | 83.7 | AGPL-3.0 |
| [OpenDirector](https://github.com/ThinkFlowLab/OpenDirector) | Flujo de creación de vídeo con agentes que va del diálogo y el lienzo a la organización de material y la exportación desde la línea de tiempo. | 437 | 348 | 2026-11-24 | 79.0 | Apache-2.0 |
| [AID Studio](https://github.com/shijue-aid/aid-studio) | Estudio autoalojable de creación de dramas animados estilo cómic, dramas cortos y producción audiovisual, que cubre guion, personajes y escenas, guion gráfico, generación de imágenes y vídeo, doblaje, lienzo infinito y previs 3D. | 1,764 | 125 | 2026-11-22 | 77.6 | MIT |
| [CutVoke](https://github.com/frankShan001/CutVoke) | Editor de vídeo open source multiplataforma centrado en lo local con un servidor MCP integrado que permite a agentes como Claude Code, Codex o Cursor y a personas editar juntos en una misma línea de tiempo multipista no destructiva. | 45 | 505 | 2026-11-24 | 73.3 | MIT |
| [OpenReel Video](https://github.com/Augani/openreel-video) · ★Referencia del usuario | Editor de línea de tiempo open source para navegador y escritorio, con cortes, subtítulos, mezcla de audio y exportación sin marca de agua. | 6,446 | 19 | 2026-11-23 | 71.9 | MIT |
| [AI Video Production Editor](https://github.com/LudwigKienle/ai-video-production-editor) · ★Referencia del usuario | Estudio local que va del guion, la dirección y el guion gráfico a la generación de planos, la edición, el gradeado y la exportación. | 194 | 144 | 2026-11-20 | 70.1 | GPL-3.0 |
| [MakeMyClip Editor](https://github.com/MakeMyClip/editor) | Envuelve la edición con FFmpeg mediante una línea de tiempo en navegador local, CLI, MCP y Skill. | 36 | 153 | 2026-11-16 | 63.6 | MIT |
| [OpenKatana](https://github.com/rk0neki/OpenKatana) | Motor de edición de vídeo impulsado por agentes mediante Studio, CLI, MCP y ComfyUI. | 85 | 126 | 2026-11-04 | 62.5 | Apache-2.0 |
| [OpenScene](https://github.com/Theorvane/OpenScene) | Editor de vídeo de escritorio local que permite a agentes de IA manipular la línea de tiempo, generar medios y exportar. | 11 | 113 | 2026-11-24 | 60.3 | MIT |
| [Waoowaoo](https://github.com/waooAI/waoowaoo) · Aviso de licencia | Estudio de creación de imágenes y vídeos con IA que gestiona material de referencia, contenido generado y fusión de clips mediante un lienzo y un Assistant. | 14,979 | 6 | 2026-09-21 | 56.6 | Elastic License 2.0 |
| [SeeCut](https://github.com/YeJe-cpu/SeeCut) · ★Referencia del usuario · Aviso de licencia | Espacio de trabajo de Skills que hace que un agente de codificación entienda, edite, renderice y haga el control visual de calidad de vídeos cortos hablados a cámara. | 487 | 11 | 2026-10-30 | 54.3 | PolyForm Noncommercial-1.0.0 |
| [ScriptCut](https://github.com/FernandoAbishai/ScriptCut) | Edición local a partir de la edición del texto transcrito, con empaquetado de clips verticales y exportación para redes sociales. | 23 | 62 | 2026-10-14 | 50.1 | AGPL-3.0 |
| [Cutline](https://github.com/Aepzie/cutline) | Editor de línea de tiempo en el navegador con una interfaz MCP de primer nivel para que los agentes operen en tiempo real. | 1 | 109 | 2026-10-16 | 45.0 | MIT |
| [Moyin Creator](https://github.com/MemeCalculate/moyin-creator) · Aviso de licencia | Herramienta de escritorio Electron de nivel producción para series con IA que encadena automáticamente la cadena guion→personajes→escenas→dirección→Seedance 2.0 y genera en lote dramas cortos y series de animación. | 4,871 | 2 | 2026-08-27 | 44.9 | AGPL-3.0 + doble licencia comercial |

### Producción de vídeo con agentes y automatización

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [Hypit](https://github.com/hypit-ai/hypit) · Aviso de licencia | Hace que un agente de codificación replique vídeos de referencia como flujos de trabajo completos editables y repetibles, y genere variantes de contenido en lote. | 31,391 | 783 | 2026-11-24 | 95.8 | Hypit Open Source License (Apache-2.0 modificado) |
| [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) | Sistema multipipeline de producción de vídeo para agentes de codificación que cubre investigación, guion, material, doblaje, subtítulos y renderizado. | 83,059 | 272 | 2026-11-16 | 93.6 | AGPL-3.0 |
| [OpenMotion](https://github.com/nexu-io/openmotion) | Estudio de réplica de vídeos de referencia y motion graphics de marca para agentes de codificación locales, con Motion.md, línea de tiempo visual y exportación MP4. | 16,018 | 758 | 2026-11-24 | 93.6 | Apache-2.0 |
| [OpenFilm](https://github.com/openfilm/openfilm) | Permite a los agentes de codificación crear, inspeccionar, editar y renderizar vídeo con código, y aporta una interfaz editable. | 9,289 | 298 | 2026-11-23 | 88.4 | MIT |
| [Rea Video](https://github.com/JuneYaooo/rea-video) · ★Referencia del usuario | Descompone en reversa qué partes de un vídeo son grabadas, de IA o de código, y produce un plan de réplica plano a plano y un VIDEO.md. | 12,996 | 215 | 2026-11-24 | 88.1 | Apache-2.0 |
| [Video Autopilot Kit](https://github.com/Hao0321/video-autopilot-kit) · ★Referencia del usuario | Marco de automatización encargado de planificar, auditar, revisar el montaje y aprender de los resultados de los vídeos. | 2,358 | 51 | 2026-11-13 | 71.1 | MIT |
| [Video Use](https://github.com/browser-use/video-use) | Edita material bruto mediante un agente de codificación y FFmpeg: cortes, subtítulos, gradeado, superposición de efectos y revisión de la salida. | 31,531 | 5 | 2026-10-08 | 60.9 | MIT |
| [Video Director](https://github.com/win4r/video-director) · ★Referencia del usuario | Guía a Claude Code para planificar, renderizar y revisar cortos con HTML/Canvas/SVG/Three.js/GSAP/Remotion. | 528 | 19 | 2026-11-07 | 59.2 | MIT |
| [WeVisCut](https://github.com/Tencent/WeVisCut) | Convierte artículos de conocimiento o guiones explicativos en vídeos de varios minutos mediante planificación, búsqueda de material, edición, revisión y reparación. | 114 | 29 | 2026-10-30 | 54.4 | Apache-2.0 |

### Vídeos cortos de conocimiento, clips y explicaciones

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [NeonClipping](https://github.com/iamajmeena/neonclipping) | Pega un enlace y corta localmente en clips 9:16 con subtítulos incrustados los vídeos largos de YouTube/Twitch/Kick o MP4 propios, y genera títulos y ganchos. | 2,482 | 89 | 2026-11-24 | 77.4 | MIT |
| [Clipmint](https://github.com/kleZ799/clipmint) | Convierte podcasts, entrevistas, tutoriales y VOD en Shorts/Reels/TikTok verticales con subtítulos. | 68 | 620 | 2026-11-24 | 74.5 | MIT |
| [ChrisHKAI Video](https://github.com/ChrisHKAI/ChrisHKAI-Video) · ★Referencia del usuario | Skill de agente de codificación que organiza los materiales públicos de un creador en un corto de animación 3D estilo juguete. | 162 | 198 | 2026-11-24 | 72.4 | MIT |
| [Lanshu AI Presenter Video](https://github.com/cclank/lanshu-create-ai-presenter-video) · ★Referencia del usuario | Agent Skill que convierte un tema o guion en vídeos explicativos verificados con avatar digital/estilizado. | 3,079 | 16 | 2026-10-11 | 59.2 | MIT |
| [Claude Animated Shorts](https://github.com/mromidev/claude-animated-shorts) · ★Referencia del usuario | Skill para producir cortos animados verticales con historia usando Three.js, Remotion, música y efectos de sonido. | 4,811 | 2 | 2026-11-01 | 54.8 | MIT |
| [Vibe Knowledge](https://github.com/andyhuo520/vibe-knowledge) · ★Referencia del usuario | Skill de cortos de conocimiento que va de la verificación de puntos, la redacción y el doblaje a la generación por código, el control de calidad y el paquete de publicación. | 805 | 3 | 2026-10-28 | 49.5 | MIT |
| [Vox Director](https://github.com/alisa0808/vox-director) | Agent Skill de extremo a extremo que lleva de un tema a un vídeo explicativo/publicitario estilo collage de papel tipo Vox. | 3,127 | 1 | 2026-10-05 | 46.2 | MIT |
| [Video to Shorts Skill](https://github.com/social-media-skills/video-to-shorts-skill) | Hace que un agente convierta vídeos largos o podcasts en cortos verticales con subtítulos palabra a palabra y, opcionalmente, los publique. | 4 | 3 | 2026-11-11 | 35.0 | MIT |
| [Pixelle-Video](https://github.com/ATH-MaaS/Pixelle-Video) | A partir de un tema genera el guion, imágenes o vídeos, el doblaje y monta un vídeo corto; admite flujos ComfyUI y APIs de medios. | 30,491 | 0 | 2026-06-14 | 39.9 | Apache-2.0 |
| [Atlas Explainer](https://github.com/AtlasCloudAI/atlas-explainer) | Skill/CLI que genera vídeos explicativos de conocimiento con doblaje y estilo papercraft a partir de un solo tema. | 3 | 0 | 2026-07-10 | 10.2 | MIT |

### Agent Skills, MCP y herramientas de edición

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill) | CLI y MCP que dan a los agentes de codificación edición local con FFmpeg: cortes, subtítulos, exportación de formatos y revisión de salida. | 10,672 | 966 | 2026-11-24 | 92.0 | MIT |
| [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | Skills, plantillas, comandos y herramientas para Claude Code: guion, doblaje, música, generación de imagen y vídeo, control de calidad, renderizado y publicación, con migración a Codex y Kiro CLI. | 2,751 | 537 | 2026-11-24 | 87.5 | MIT |
| [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft) · ★Referencia del usuario | Aporta a los agentes recetas de planos, guiones gráficos, animación Remotion, cortes al pulso y comprobación fotograma a fotograma. | 22,444 | 54 | 2026-11-21 | 81.5 | Apache-2.0 |
| [Kinocut](https://github.com/KyaniteLabs/kinocut) | MCP/Python/CLI de edición de vídeo local con guardias, prechequeos, recibos y puertas de calidad. | 280 | 659 | 2026-11-24 | 79.5 | Apache-2.0 |
| [Remotion Agent Skills](https://github.com/remotion-dev/skills) · Aviso de licencia | Skills oficiales para que los agentes de codificación creen, previsualicen y rendericen vídeos con Remotion. | 7,954 | 31 | 2026-11-24 | 75.6 | Licencia pendiente de verificación |
| [Manju Laoli Skill](https://github.com/lixiaoxiao9888-create/manju-laoli-skill) | Juego de OpenClaw Skills para dramas animados estilo cómic y dramas cortos: guion, bloqueo de activos, guion gráfico, coreografía de pelea, prompts para Seedance y control automático. | 3,081 | 50 | 2026-11-19 | 73.5 | MIT |
| [pixelfx](https://github.com/patch-gg/pixelfx) · Aviso de licencia | Biblioteca de 244 efectos y animaciones pixel-art dibujados por código, con una Skill de generación de efectos para Claude Code, hojas de sprites y utilidades de exportación GIF/MP4. | 9,055 | 10 | 2026-11-12 | 66.9 | MIT (código y efectos) + fuente Patch Pixel excluida |
| [Wallstreet Explainer](https://github.com/HeyChengC/wallstreet-explainer) · Aviso de licencia | Skill de agente de codificación para cortos de explicación financiera/tecnológica al estilo Wall Street, con lenguaje de estilo, plantillas de componentes gráficos y guiones de búsqueda de vídeos, capturas, doblaje, croma, renderizado y mezcla. | 1,312 | 16 | 2026-11-20 | 64.7 | MIT (código y documentación) + material de terceros en las muestras excluido |
| [ReelBench Skills](https://github.com/eternityspring/reelbench-skills) · ★Referencia del usuario | Colección de Skills de análisis, réplica y producción de vídeo para Claude Code/Codex. | 1,253 | 21 | 2026-11-09 | 63.3 | Apache-2.0 |
| [Video Agent Skills](https://github.com/Melvynx/video-agent-skills) | Organiza guion, investigación, edición, traducción y publicación de vídeos cortos/YouTube mediante Skills en Markdown. | 211 | 26 | 2026-11-06 | 57.5 | MIT |
| [HyperFrames Motion Library](https://github.com/nutllwhy/hyperframes-motion-library) · ★Referencia del usuario | Biblioteca local de plantillas de motion graphics y activos paramétricos con HyperFrames como núcleo. | 326 | 2 | 2026-10-28 | 44.8 | MIT |
| [Video Editing Skill](https://github.com/social-media-skills/video-editing-skill) | Hace que un agente ejecute el primer pase de edición y de subtítulos sobre vídeos hablados a cámara, cursos, entrevistas y vlogs. | 10 | 3 | 2026-11-11 | 37.7 | MIT |
| [GSAP Skills](https://github.com/greensock/gsap-skills) | Agent Skills oficiales que guían a un agente de codificación en el uso de líneas de tiempo, efectos y complementos de GSAP. | 19,019 | 0 | 2026-04-21 | 36.5 | MIT |
| [Narrator AI CLI Skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill) · ★Referencia del usuario | Guía al agente para usar narrator-ai-cli y producir automáticamente vídeos de comentario de películas con voz en off. | 3,323 | 0 | 2026-07-05 | 33.3 | MIT |
| [OpenClip Agent Skills](https://github.com/OpenClip-App/agent-skills) | Skills para agentes: trocear vídeos largos, transcripción, conversiones, miniaturas, recorte de fondo e ideas UGC. | 1 | 0 | 2026-08-07 | 9.8 | MIT |
| [MCP Video Editing](https://github.com/mfortne/mcp-video-editing) | Envuelve FFmpeg, HyperFrames y flujos locales de reutilización como MCP, librería Python y CLI. | 2 | 0 | 2026-06-04 | 7.5 | Apache-2.0 |

### Code-to-video y motion graphics

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | Ecosistema de código-a-vídeo y Agent Skills basado en HTML/CSS/JS, con migración desde Remotion y otros y verificación fotograma a fotograma. | 89,564 | 3,965 | 2026-11-24 | 99.6 | Apache-2.0 |
| [Remotion](https://github.com/remotion-dev/remotion) · Aviso de licencia | Marco base para crear y renderizar vídeo con código en React/TypeScript. | 75,476 | 6,717 | 2026-11-24 | 99.0 | Remotion License |
| [raea](https://github.com/shinyobjectz/raea) · Aviso de licencia | Motor y estudio de agente de escritorio para escribir vídeo, motion graphics, 3D y juegos en React/TypeScript, renderizados en GPU local. | 5,002 | 1,457 | 2026-11-24 | 89.3 | FSL-1.1-ALv2 |
| [Lemo Opuscar](https://github.com/lemomo-ai/lemo-opuscar) · Aviso de licencia | Aporta estilo cinematográfico, ejemplos y la guía STYLE.md para que un agente de codificación haga vídeos con código. | 20,684 | 148 | 2026-11-23 | 87.2 | MIT (código) + CC BY-NC (documentación, licencia adicional) |
| [Manim Community](https://github.com/ManimCommunity/manim) | Motor de vídeo para crear animaciones matemáticas y de explicación con código Python. | 42,881 | 78 | 2026-11-23 | 86.3 | MIT |
| [GiveMotion](https://github.com/givemotion/givemotion) | Motor de código-a-vídeo en el que un agente escribe HTML/CSS, previsualiza, revisa y renderiza MP4. | 92 | 243 | 2026-11-19 | 70.1 | MIT |
| [Manim](https://github.com/3b1b/manim) | Motor de animación en Python para explicaciones matemáticas. | 96,918 | 1 | 2026-09-09 | 54.5 | MIT |
| [SenseNova Code2Video](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video) · ★Referencia del usuario · Aviso de licencia | Un modelo abierto pequeño genera código ejecutable que renderiza vídeos cortos. | 767 | 2 | 2026-10-27 | 47.5 | Pendiente de verificación |
| [Motion Canvas](https://github.com/motion-canvas/motion-canvas) | Crea animaciones, explicaciones y motion graphics con TypeScript y funciones generadoras. | 20,204 | 0 | 2026-07-02 | 39.4 | MIT |

### Animación, 3D y componentes base de codificación

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [Godot](https://github.com/godotengine/godot) | Motor de videojuegos open source para construir escenas 2D y 3D, interacción y animación. | 120,738 | 1,923 | 2026-11-24 | 100.0 | MIT |
| [three.js](https://github.com/mrdoob/three.js) | Librería de escenas y renderizado 3D en JavaScript, apta para aportar contenido 3D a los motion graphics por código. | 119,308 | 874 | 2026-11-24 | 99.9 | MIT |
| [Motion](https://github.com/motiondivision/motion) | Librería de animaciones de interfaz y layout para JavaScript, React y Vue. | 35,531 | 1,390 | 2026-11-24 | 96.3 | MIT |
| [Blender](https://github.com/blender/blender) | Suite 3D que cubre modelado, rigging, animación, renderizado, composición y edición de vídeo. | 22,468 | 3,310 | 2026-11-25 | 94.8 | GPL-2.0-or-later |
| [Babylon.js](https://github.com/BabylonJS/Babylon.js) | Motor de escenas 3D, juegos y renderizado en JavaScript, utilizable como base de motion graphics por código. | 26,439 | 342 | 2026-11-24 | 93.2 | Apache-2.0 |
| [Konva](https://github.com/konvajs/konva) | Librería de escenas Canvas 2D con interacción de objetos, transformaciones, animación y exportación. | 15,012 | 217 | 2026-11-23 | 88.4 | MIT |
| [Two.js](https://github.com/jonobr1/two.js) | Crea escenas gráficas y animaciones 2D mediante WebGL, Canvas o SVG. | 8,762 | 47 | 2026-11-17 | 76.3 | MIT |
| [Shifty](https://github.com/jeremyckahn/shifty) | Motor de interpolación (tweening) en TypeScript con easing y control de reproducción. | 1,598 | 14 | 2026-11-14 | 63.2 | MIT |
| [Ola](https://github.com/franciscop/ola) | Librería ligera de animación para suavizado e interpolación de valores en tiempo real. | 1,869 | 3 | 2026-10-24 | 51.6 | MIT |
| [Anime.js](https://github.com/juliangarnier/anime) | Crea animaciones de línea de tiempo sobre propiedades CSS, SVG, DOM y JavaScript. | 75,039 | 0 | 2026-08-09 | 46.6 | MIT |
| [Proton](https://github.com/drawcall/Proton) | Librería de animación de partículas en JavaScript para efectos de fuego, fuegos artificiales, explosiones y similares. | 2,531 | 0 | 2026-03-06 | 28.6 | MIT |
| [Lottie Web](https://github.com/airbnb/lottie-web) | Analiza y renderiza en la web animaciones vectoriales Lottie exportadas. | 32,572 | 0 | 2024-11-19 | 36.1 | MIT |
| [TweenJS](https://github.com/CreateJS/TweenJS) | Ofrece tweening y reproducción encadenada de valores JavaScript y propiedades CSS. | 3,578 | 0 | 2021-03-27 | 28.4 | MIT |
| [LUME](https://github.com/lume/lume) | Construye escenas interactivas de gráficos 2D y 3D usando elementos HTML. | 1,576 | 0 | 2025-10-14 | 25.9 | MIT |
| [gifenc](https://github.com/mattdesl/gifenc) | Codifica GIF con animación y transparencia en el navegador o en Node.js. | 382 | 0 | 2024-09-19 | 20.7 | MIT |

### ComfyUI y modelos de vídeo abiertos

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [VRGameDevGirl AI Video Builder](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl) · ★Referencia del usuario · Aviso de licencia | Gestiona en ComfyUI, por escenas, la planificación, los prompts, la generación, el ritmo, la revisión y el ensamblaje final. | 904 | 677 | 2026-11-24 | 83.6 | VRGameDevGirl Community and Commercial License |
| [LTX-Video](https://github.com/Lightricks/LTX-Video) | Modelos y herramientas de inferencia abiertos de vídeo para texto/imagen a vídeo y generación audiovisual. | 11,479 | 2 | 2026-11-02 | 58.2 | Apache-2.0 |
| [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) · Aviso de licencia | Modelo base abierto de generación de vídeo a gran escala de Tencent, con su marco de inferencia. | 12,827 | 3 | 2026-10-08 | 55.4 | Tencent Hunyuan Community License |
| [Wan2.2](https://github.com/Wan-Video/Wan2.2) | Modelos abiertos de la serie Wan de Alibaba para tareas como texto/imagen a vídeo. | 18,891 | 2 | 2026-09-21 | 52.6 | Apache-2.0 |
| [Mochi](https://github.com/genmoai/mochi) | Modelo de generación de vídeo abierto de Genmo con su código de inferencia. | 3,767 | 2 | 2026-10-22 | 52.1 | Apache-2.0 |
| [Open-Sora](https://github.com/hpcaitech/Open-Sora) | Marco abierto de entrenamiento e inferencia eficiente para generación de vídeo. | 29,949 | 0 | 2026-04-09 | 37.8 | Apache-2.0 |
| [Bernini](https://github.com/bytedance/Bernini) | Marco de investigación de generación y edición de vídeo que combina un planificador semántico y un renderizador DiT. | 1,373 | 0 | 2026-08-13 | 33.0 | Apache-2.0 |
| [HunyuanVideo-I2V](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V) · Aviso de licencia | Marco personalizable de imagen a vídeo basado en HunyuanVideo. | 1,858 | 0 | 2026-04-07 | 28.1 | Tencent Hunyuan Community License |
| [CogVideo / CogVideoX](https://github.com/zai-org/CogVideo) | Modelos abiertos de texto/imagen a vídeo con su código de inferencia. | 13,229 | 0 | 2025-11-04 | 33.3 | Apache-2.0 |

### Avatares digitales, animación de retratos y sincronización labial

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [LiveTalking](https://github.com/lipku/LiveTalking) | Sistema interactivo de streaming en tiempo real que combina varios backends de avatar digital. | 11,131 | 8 | 2026-10-20 | 61.5 | Apache-2.0 |
| [MuseTalk](https://github.com/TMElyralab/MuseTalk) | Modelo de avatar virtual impulsado por audio para sincronización labial en tiempo real de alta calidad. | 7,031 | 1 | 2026-11-19 | 58.2 | MIT |
| [LivePortrait](https://github.com/KlingAIResearch/LivePortrait) | Marco eficiente de animación de retratos, composición y control de reorientación. | 19,566 | 0 | 2026-06-01 | 37.9 | MIT |
| [SadTalker](https://github.com/OpenTalker/SadTalker) | Genera vídeos de cabezas parlantes desde una sola foto y audio. | 14,220 | 0 | 2023-10-10 | 33.2 | Apache-2.0 |
| [Wav2Lip](https://github.com/Rudrabha/Wav2Lip) · Aviso de licencia | Implementación clásica de investigación para sincronización labial audio-vídeo. | 13,284 | 0 | 2025-06-22 | 33.1 | Licencia personal/investigación/no comercial |

### Descarga, captura, transcodificación y CLIs de material

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [FFmpeg](https://github.com/FFmpeg/FFmpeg) · Aviso de licencia | Cadena de herramientas base para transcodificación, filtros, multiplexado, composición y procesamiento de streams de vídeo. | 68,093 | 2,986 | 2026-11-24 | 98.7 | LGPL-2.1+; GPL-2.0+ si se activan componentes GPL |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Descargador de audio/vídeo por línea de órdenes muy completo, compatible con una gran cantidad de sitios. | 210,460 | 81 | 2026-11-24 | 89.7 | Unlicense |
| [Streamlink](https://github.com/streamlink/streamlink) | CLI que resuelve streams en directo de internet y los canaliza a un reproductor local. | 11,998 | 155 | 2026-11-18 | 84.4 | BSD-2-Clause |
| [Downvid](https://github.com/Downvid/downvid) · ★Referencia del usuario | GUI/WebUI multiplataforma de descarga de vídeo basada en yt-dlp y FFmpeg. | 1,678 | 354 | 2026-11-11 | 80.4 | MIT |
| [VidBee](https://github.com/nexmoe/VidBee) | Descarga medios y ejecuta localmente transcripción, anotación de hablantes, resumen, traducción y conversación sobre el material. | 11,207 | 51 | 2026-11-21 | 78.6 | MIT |
| [cobalt](https://github.com/imputnet/cobalt) · Aviso de licencia | Aplicación web y API autoalojable de descarga de medios, sin anuncios ni rastreo, para sitios como YouTube, TikTok e Instagram. | 47,172 | 0 | 2026-04-06 | 39.3 | AGPL-3.0 (api y resto) + CC-BY-NC-SA-4.0 (web) |
| [Lux](https://github.com/iawia002/lux) | CLI de descarga de vídeo multi-sitio escrita en Go. | 31,857 | 0 | 2025-12-29 | 36.7 | MIT |
| [you-get](https://github.com/soimort/you-get) | Utilidad Python de línea de órdenes para descargar medios desde páginas web. | 56,849 | 0 | 2025-04-27 | 38.1 | MIT |

### Evaluación, investigación e índices externos

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [Aurora / AgentEdit-Bench](https://github.com/yeates/Aurora) | Unifica la edición de vídeo con agentes orientados a uso de herramientas y aporta AgentEdit-Bench. | 461 | 4 | 2026-11-13 | 52.5 | MIT |
| [Awesome AI Video for Creators](https://github.com/sasateguh/awesome-ai-video-for-creators) | Organiza herramientas abiertas de edición, subtítulos, troceado, doblaje y vídeo por código según el flujo de trabajo del creador. | 19 | 15 | 2026-11-24 | 50.9 | CC0-1.0 |
| [CutCraft Bench](https://github.com/AlibabaResearch/cut-craft-bench) · Aviso de licencia | Evalúa la ejecución de técnicas de montaje profesional en la generación audiovisual multipiano y aporta un baseline de agentes. | 43 | 5 | 2026-09-14 | 34.5 | Pendiente de verificación |
| [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing) | Cataloga herramientas abiertas de edición de vídeo, Agent Skills y material utilizable. | 5 | 2 | 2026-10-17 | 28.8 | CC0-1.0 |
| [Awesome AI Video](https://github.com/thoxakihiko/awesome-ai-video) | Cataloga modelos, herramientas y recursos de texto/imagen a vídeo. | 3 | 3 | 2026-09-27 | 25.7 | CC0-1.0 |
| [VEFX-Bench](https://github.com/Visko-Platform/VEFX-Bench) | Evalúa el seguimiento de instrucciones y la calidad en edición de vídeo de propósito general y efectos visuales. | 177 | 0 | 2026-05-16 | 20.9 | Apache-2.0 |
| [EditVerse](https://github.com/adobe-research/EditVerse) · Aviso de licencia | Código de investigación y EditVerseBench para generación y edición de imagen/vídeo. | 140 | 0 | 2025-10-09 | 17.4 | Adobe Research License (archivos parciales) |
| [Video-Bench](https://github.com/Video-Bench/Video-Bench) | Organiza y ejecuta evaluaciones multidimensionales de modelos de generación de vídeo. | 82 | 0 | 2025-06-09 | 15.4 | Apache-2.0 |

### Versiones históricas y restringidas

| Proyecto | Propósito | Estrellas | Commits 90 d | Último commit UTC | Puntuación de mantenimiento | Licencia |
| --- | --- | --- | --- | --- | --- | --- |
| [Palmier Pro](https://github.com/palmier-io/palmier-pro) · ★Referencia del usuario · Archivado/histórico · Aviso de licencia | Editor de vídeo orientado a IA cuyas versiones antiguas publicaron el código fuente bajo GPLv3. | 14,803 | 10 | 2026-11-20 | 70.5 | GPL-3.0 (código fuente hasta v0.7.6) / binarios posteriores propietarios |

## Cómo elegir

- Si ya tienes material y necesitas montar: mira los editores/estudios o las Skills/MCP.
- Del tema y el guion al montaje final: mira la producción con agentes y los vídeos cortos de conocimiento.
- Para motion graphics, demos de producto e historias de datos: mira Code-to-video.
- Para generación por difusión en local: mira ComfyUI y los modelos abiertos.
- Para avatares digitales o presentación hablada: mira la animación de retratos y la sincronización labial, y revisa primero los derechos de las personas.
- Para obtener material con licencia legítima: mira [Comparativa de CLIs](docs/cli-comparison.md).

Las fronteras completas están en [Ficha detallada de proyectos](docs/projects.md) y los criterios de clasificación en [Alcance y categorías](docs/taxonomy.md).

## Datos y mantenimiento

- [Ordenaciones combinada, por estrellas, por actividad y por último commit](docs/rankings.md)
- [Comparativa de Downvid y de las CLIs de descarga/medios](docs/cli-comparison.md)
- [Metodología de ordenación y limitaciones](docs/methodology.md)
- [Palabras clave de búsqueda, fuentes y cobertura](docs/research.md)
- [Guía de contribución](CONTRIBUTING.md)

```sh
python scripts/refresh_metrics.py
python scripts/build.py
python -m unittest discover -s tests -v
python scripts/build.py --check
```

## Licencias y agradecimientos

La compilación original y los scripts de este catálogo están bajo [MIT](../../LICENSE); los proyectos enlazados, modelos, pesos, material y fuentes siguen sus propias licencias. Las fronteras de source-available, uso no comercial, modelos comunitarios y licencias condicionales se conservan tal cual.

El descubrimiento de proyectos tomó como referencia índices externos como [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing); cada entrada final se verificó en el repositorio oficial.

El [registro de cambios](../../record/) conserva el texto original tal como se redactó en el momento de cada verificación (en chino), para poder auditar el origen y la formulación de cada juicio.
