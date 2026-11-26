# Descripciones de proyectos y evidencia

Cada propósito proviene del README oficial en un commit fijo; no se instalaron ni ejecutaron todos los proyectos. Actualizar las métricas no revalida automáticamente funciones ni licencias.


## [Concat](https://github.com/jub0t/Concat)

Editor multipista local y multiplataforma con subtítulos, TTS, recorte de fondo, fotogramas clave, efectos y exportación 4K.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Los modelos locales deben descargarse en el primer uso; la IA dentro del producto y un flujo de trabajo generativo completo no son el mismo alcance.
- Estado de mantenimiento: Con commits en los últimos 90 días; 444 commits en 30 días, 1680 en 90 días.
- Licencia: [AGPL-3.0](https://api.github.com/repos/jub0t/Concat/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/jub0t/Concat/blob/504a814ebe61d4f47bba4cd7949dc2580ecc405c/README.md#L6).

## [Jellyfish](https://github.com/Forget-C/Jellyfish)

Estudio de producción de dramas cortos con IA que cubre desglose del guion, guion gráfico, gestión de activos de personajes y escenas, generación de planos y exportación.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Reutilizar activos ayuda a la consistencia pero no garantiza la calidad de generación; los servicios de modelos, los costes y los requisitos de despliegue deben verificarse según la configuración.
- Estado de mantenimiento: Con commits en los últimos 90 días; 1289 commits en 30 días, 1666 en 90 días.
- Licencia: [Apache-2.0](https://github.com/Forget-C/Jellyfish/blob/a9678194ddf2d9be3ccbe78d4287d87d5089e123/LICENSE); Licencia abierta verificada. La LICENSE raíz es Apache-2.0; los términos de modelos, material y servicios de terceros se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/Forget-C/Jellyfish/blob/a9678194ddf2d9be3ccbe78d4287d87d5089e123/README.md#L30).

## [Clypra](https://github.com/AIEraDev/Clypra)

Editor de vídeo multiplataforma con aceleración por hardware, construido con Rust/Tauri/React.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Editor de propósito general principalmente; el alcance de las funciones de IA y la madurez móvil deben verificarse por versión.
- Estado de mantenimiento: Con commits en los últimos 90 días; 288 commits en 30 días, 1852 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/AIEraDev/Clypra/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/AIEraDev/Clypra/blob/aa6b9c619cf98f7a1dfab6446345ec5f5660b93c/README.md#L9).

## [CozyClay](https://github.com/HaD0Yun/CozyClay)

Herramienta en el navegador para montar escenas, bloquear el movimiento de personajes, cortar planos y previsualizar vídeo con IA.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: La salida es principalmente previs y referencias de planos; la calidad de generación final depende de modelos de vídeo externos.
- Estado de mantenimiento: Con commits en los últimos 90 días; 196 commits en 30 días, 2138 en 90 días.
- Licencia: [AGPL-3.0](https://api.github.com/repos/HaD0Yun/CozyClay/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/HaD0Yun/CozyClay/blob/297dd2a8a077613b329962d68e2a9bb4355be091/README.md#L6).

## [Huobao Drama](https://github.com/chatfire-AI/huobao-drama)

Plataforma web/escritorio que, a partir de una frase o de una novela pegada, reescribe automáticamente el guion, genera imágenes y vídeos de planos, doblaje y subtítulos y monta el drama corto completo; el backend se orquesta con Mastra Agent y las skills son editables en la interfaz.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: La licencia CC BY-NC-SA-4.0 prohíbe expresamente el uso comercial (incluidos servicios de pago, despliegues comerciales y reventa); texto, imagen y vídeo requieren configurar claves API de servicios de modelos propios; el README orienta a usar las claves FireMux del autor; las referencias locales de Seedance necesitan una dirección pública PUBLIC_BASE_URL y la versión de escritorio sin entrada pública falla directamente; usa SQLite y almacenamiento en el directorio data, y la migración exige copiar los archivos multimedia manualmente.
- Estado de mantenimiento: Con commits en los últimos 90 días; 18 commits en 30 días, 108 en 90 días.
- Licencia: [CC BY-NC-SA-4.0 (prohibido el uso comercial)](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/LICENSE); Código fuente visible pero no open source OSI. La LICENSE es el texto completo de CC BY-NC-SA 4.0; la sección de licencia del README prohíbe expresamente el uso comercial, que requiere permiso escrito del autor; por eso GitHub licenseInfo la identifica como NOASSERTION; los derechos de los servicios de modelos invocados, el material y el doblaje se cuentan aparte
- Verificación funcional: 2026-11-25; [Fuente 1](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/README.md#L33) · [Fuente 2](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/README.md#L55) · [Fuente 3](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/README.md#L131).

## [OpenChatCut](https://github.com/0xsline/OpenChatCut)

Editor conversacional de vídeo con IA centrado en lo local, con línea de tiempo multipista, Agent Skills, MCP y renderizado Remotion.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Los límites de capacidad del agente integrado, la versión de escritorio y los agentes de codificación externos deben verificarse por separado.
- Estado de mantenimiento: Con commits en los últimos 90 días; 22 commits en 30 días, 396 en 90 días.
- Licencia: [AGPL-3.0](https://api.github.com/repos/0xsline/OpenChatCut/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/0xsline/OpenChatCut/blob/9242a95aea248ff3a8dab495514384e858320d47/README.md#L12).

## [OpenDirector](https://github.com/ThinkFlowLab/OpenDirector)

Flujo de creación de vídeo con agentes que va del diálogo y el lienzo a la organización de material y la exportación desde la línea de tiempo.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Primera versión del proyecto; la estabilidad de producción completa y el coste de los modelos requieren pruebas reales.
- Estado de mantenimiento: Con commits en los últimos 90 días; 339 commits en 30 días, 358 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/ThinkFlowLab/OpenDirector/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/ThinkFlowLab/OpenDirector/blob/39288dfdf4f816798e5479c53363258fceeb6e11/README.md#L18).

## [AID Studio](https://github.com/shijue-aid/aid-studio)

Estudio autoalojable de creación de dramas animados estilo cómic, dramas cortos y producción audiovisual, que cubre guion, personajes y escenas, guion gráfico, generación de imágenes y vídeo, doblaje, lienzo infinito y previs 3D.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Las llamadas a modelos, el almacenamiento y los recursos de cómputo pueden facturarse aparte; el paquete oficial de activos de ejemplo de imagen, audio y vídeo se distribuye por separado según la versión; el despliegue requiere dependencias como MySQL, Redis y Docker, y los derechos del contenido generado sobre guiones, personajes y material deben verificarse por cuenta propia.
- Estado de mantenimiento: Con commits en los últimos 90 días; 42 commits en 30 días, 120 en 90 días.
- Licencia: [MIT](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/LICENSE); Licencia abierta verificada. La LICENSE raíz es MIT y NOTICE conserva atribuciones de terceros como RuoYi-Vue; el paquete oficial de activos de ejemplo se distribuye por separado; los términos de proveedores de modelos, almacenamiento y recursos de cómputo se cuentan aparte
- Verificación funcional: 2026-11-23; [Fuente 1](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/README.md#L13) · [Fuente 2](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/README.md#L43) · [Fuente 3](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/README.md#L46).

## [CutVoke](https://github.com/frankShan001/CutVoke)

Editor de vídeo open source multiplataforma centrado en lo local con un servidor MCP integrado que permite a agentes como Claude Code, Codex o Cursor y a personas editar juntos en una misma línea de tiempo multipista no destructiva.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: El paquete de escritorio incluye componentes de terceros como FFmpeg (GPLv3); los subtítulos usan faster-whisper local opcional, con descarga inicial del modelo; la mayoría de los agentes conectados son servicios cloud, cuyas cuentas, costes y políticas de datos se cuentan aparte; v0.3.6 es una vista previa congelada no sincronizada con main, con problemas conocidos listados oficialmente como reutilización de la ventana de exportación, tiempos de espera agotados en la vista previa y recorte de subtítulos largos en vertical; el paquete de macOS solo tiene firma ad-hoc sin notarizar; el proyecto se creó en 2026-09 y su madurez es baja.
- Estado de mantenimiento: Con commits en los últimos 90 días; 426 commits en 30 días, 543 en 90 días.
- Licencia: [MIT](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/LICENSE); Licencia abierta verificada. La LICENSE raíz es MIT; el paquete de escritorio incluye componentes de terceros con licencia propia como FFmpeg (GPLv3); las recetas comunitarias de efectos, el modelo faster-whisper y los términos de los servicios de IA conectados se cuentan aparte
- Verificación funcional: 2026-11-25; [Fuente 1](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/README.md#L28) · [Fuente 2](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/README.md#L121) · [Fuente 3](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/README.md#L159).

## [OpenReel Video](https://github.com/Augani/openreel-video)

Editor de línea de tiempo open source para navegador y escritorio, con cortes, subtítulos, mezcla de audio y exportación sin marca de agua.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Capacidades de edición de propósito general; no debe asumirse automáticamente que sea un agente generativo con IA.
- Estado de mantenimiento: Con commits en los últimos 90 días; 9 commits en 30 días, 20 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/Augani/openreel-video/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Augani/openreel-video/blob/367d7e90b61b5181f9861b852bb8b9d7a7d2954a/README.md#L7).

## [AI Video Production Editor](https://github.com/LudwigKienle/ai-video-production-editor)

Estudio local que va del guion, la dirección y el guion gráfico a la generación de planos, la edición, el gradeado y la exportación.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: BYOK sigue enviando solicitudes a los servicios de modelos configurados; algunas capacidades gestionadas/de facturación requieren proyectos externos propios.
- Estado de mantenimiento: Con commits en los últimos 90 días; 14 commits en 30 días, 144 en 90 días.
- Licencia: [GPL-3.0](https://api.github.com/repos/LudwigKienle/ai-video-production-editor/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/LudwigKienle/ai-video-production-editor/blob/a368af45b6cfd35e22bd3b5e101db198e1ac89a9/README.md#L4).

## [MakeMyClip Editor](https://github.com/MakeMyClip/editor)

Envuelve la edición con FFmpeg mediante una línea de tiempo en navegador local, CLI, MCP y Skill.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: La edición local no necesita su API en la nube; la UI del navegador, la CLI y las herramientas de agente son entradas distintas del mismo proyecto.
- Estado de mantenimiento: Con commits en los últimos 90 días; 151 commits en 30 días, 153 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/MakeMyClip/editor/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/MakeMyClip/editor/blob/f6f05206c1d2234d74134da27d322caebb260e6d/README.md#L7).

## [OpenKatana](https://github.com/rk0neki/OpenKatana)

Motor de edición de vídeo impulsado por agentes mediante Studio, CLI, MCP y ComfyUI.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Más un motor de edición basado en código; los modelos de generación y las aplicaciones ComfyUI reales deben configurarse aparte.
- Estado de mantenimiento: Con commits en los últimos 90 días; 87 commits en 30 días, 126 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/rk0neki/OpenKatana/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/rk0neki/OpenKatana/blob/b9282bf0740a7df5b5a8862b5e289ef4cd642641/README.md#L7).

## [OpenScene](https://github.com/Theorvane/OpenScene)

Editor de vídeo de escritorio local que permite a agentes de IA manipular la línea de tiempo, generar medios y exportar.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: La rama por defecto es una rama de desarrollo; la movilidad y las capacidades de generación deben verificarse según la implementación actual.
- Estado de mantenimiento: Con commits en los últimos 90 días; 41 commits en 30 días, 114 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/Theorvane/OpenScene/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Theorvane/OpenScene/blob/4bd3d3c4c15fb27dd0b521065643b3a2d516be08/README.md#L8).

## [Waoowaoo](https://github.com/waooAI/waoowaoo)

Estudio de creación de imágenes y vídeos con IA que gestiona material de referencia, contenido generado y fusión de clips mediante un lienzo y un Assistant.

- Categoría: Editores de vídeo y estudios de producción; Licencia restringida.
- Frontera de aplicación: Actualmente es una versión beta; las capacidades de imagen y vídeo dependen de los modelos; las llamadas a modelos externos como OpenRouter pueden tener coste.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 6 en 90 días.
- Licencia: [Elastic License 2.0](https://github.com/waooAI/waoowaoo/blob/dfec20e32298ed675050329e4a41477024148399/LICENSE); Código fuente visible pero no open source OSI. Desde v0.5.0-beta.1 usa ELv2, que prohíbe ofrecer a terceros un servicio gestionado con la funcionalidad principal sin autorización; no es una licencia open source OSI; las versiones anteriores pueden tener licencias distintas.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/waooAI/waoowaoo/blob/dfec20e32298ed675050329e4a41477024148399/README_zh.md#L24).

## [SeeCut](https://github.com/YeJe-cpu/SeeCut)

Espacio de trabajo de Skills que hace que un agente de codificación entienda, edite, renderice y haga el control visual de calidad de vídeos cortos hablados a cámara.

- Categoría: Editores de vídeo y estudios de producción; Licencia restringida.
- Frontera de aplicación: Es una Skill/proceso, no un NLE de escritorio independiente; los borradores de JianYing (CapCut) son solo un ajuste fino opcional posterior.
- Estado de mantenimiento: Con commits en los últimos 90 días; 1 commits en 30 días, 11 en 90 días.
- Licencia: [PolyForm Noncommercial-1.0.0](https://github.com/YeJe-cpu/SeeCut/blob/b05d7ed27404a064060e0d370402f562b0c0c02e/LICENSE); Código fuente visible pero no open source OSI. Solo uso no comercial; no es una licencia open source OSI
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/YeJe-cpu/SeeCut/blob/b05d7ed27404a064060e0d370402f562b0c0c02e/README.md#L5).

## [ScriptCut](https://github.com/FernandoAbishai/ScriptCut)

Edición local a partir de la edición del texto transcrito, con empaquetado de clips verticales y exportación para redes sociales.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Se centra en el corte preliminar por texto; no equivale a un estudio completo de efectos visuales y generación.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 62 en 90 días.
- Licencia: [AGPL-3.0](https://api.github.com/repos/FernandoAbishai/ScriptCut/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/FernandoAbishai/ScriptCut/blob/12c6fe495939da344e6af3e942a45dfdfb2132fa/README.md#L7).

## [Cutline](https://github.com/Aepzie/cutline)

Editor de línea de tiempo en el navegador con una interfaz MCP de primer nivel para que los agentes operen en tiempo real.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Los archivos proxy de material grande y las rutas de codificación en el navegador deben evaluarse según el modo de despliegue.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 109 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/Aepzie/cutline/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Aepzie/cutline/blob/ab71520285881d8dfa78f5ebca00f8a166e84962/README.md#L8).

## [Moyin Creator](https://github.com/MemeCalculate/moyin-creator)

Herramienta de escritorio Electron de nivel producción para series con IA que encadena automáticamente la cadena guion→personajes→escenas→dirección→Seedance 2.0 y genera en lote dramas cortos y series de animación.

- Categoría: Editores de vídeo y estudios de producción; Candidato principal.
- Frontera de aplicación: Requiere claves API de proveedores de IA propios (con programación multi-proveedor y rotación de claves); la generación se factura según el proveedor; usa doble licencia AGPL-3.0 y comercial: modificaciones cerradas, integración en productos comerciales o SaaS requieren licencia comercial; la coherencia de personajes depende de una biblia de personajes y de imágenes de referencia, y la consistencia entre planos y la calidad final deben verificarse según el modelo usado; desde 2026-08-27 la rama por defecto solo ha recibido cambios de README; las etiquetas Release más recientes corresponden a versiones customizadas para patrocinadores, y las versiones de los paquetes de netdisk del README tampoco coinciden con Releases.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [AGPL-3.0 + doble licencia comercial](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/COMMERCIAL_LICENSE.md); Licencia compuesta/condicional. La LICENSE es el texto AGPL-3.0; README y COMMERCIAL_LICENSE.md declaran doble licencia: modificaciones en código cerrado, integración en productos comerciales o SaaS sin abrir el código requieren licencia comercial; los términos de dependencias internas como `@opencut/ai-core` y de los servicios de modelos se cuentan aparte
- Verificación funcional: 2026-11-25; [Fuente 1](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/README.md#L70) · [Fuente 2](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/README.md#L105) · [Fuente 3](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/README.md#L122).

## [Hypit](https://github.com/hypit-ai/hypit)

Hace que un agente de codificación replique vídeos de referencia como flujos de trabajo completos editables y repetibles, y genere variantes de contenido en lote.

- Categoría: Producción de vídeo con agentes y automatización; Licencia restringida.
- Frontera de aplicación: Replicar vídeos populares involucra el vídeo original, las personas, la música, el material y las autorizaciones de marca; los modelos de generación y las APIs son servicios externos opcionales, con costes y rutas de datos según el proveedor.
- Estado de mantenimiento: Con commits en los últimos 90 días; 16 commits en 30 días, 739 en 90 días.
- Licencia: [Hypit Open Source License (Apache-2.0 modificado)](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/LICENSE); Código fuente visible pero no open source OSI. Restringe el alojamiento multiinquilino, la redistribución comercial y la eliminación de información de marca/copyright; esos usos requieren licencia comercial; no es Apache-2.0 estándar
- Verificación funcional: 2026-11-13; [Fuente 1](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/README.md#L51) · [Fuente 2](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/README.md#L164) · [Fuente 3](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/README.md#L338).

## [OpenMotion](https://github.com/nexu-io/openmotion)

Estudio de réplica de vídeos de referencia y motion graphics de marca para agentes de codificación locales, con Motion.md, línea de tiempo visual y exportación MP4.

- Categoría: Producción de vídeo con agentes y automatización; Candidato principal.
- Frontera de aplicación: Los vídeos de referencia, las personas, la música, la marca y el material deben licenciarse aparte; la generación de medios depende de APIs/suscripciones propias, y las plantillas integradas y los componentes de terceros siguen sus propios LICENSE/NOTICE.
- Estado de mantenimiento: Con commits en los últimos 90 días; 827 commits en 30 días, 832 en 90 días.
- Licencia: [Apache-2.0](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/LICENSE); Licencia abierta verificada. La LICENSE raíz es Apache-2.0 estándar; las plantillas integradas, los iconos de modelos y los componentes vendor tienen sus propios LICENSE/NOTICE, que deben conservarse y verificarse al redistribuir o reutilizar
- Verificación funcional: 2026-11-17; [Fuente 1](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/README.md#L40) · [Fuente 2](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/README.md#L308) · [Fuente 3](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/README.md#L386).

## [OpenMontage](https://github.com/OpenMontageInc/OpenMontage)

Sistema multipipeline de producción de vídeo para agentes de codificación que cubre investigación, guion, material, doblaje, subtítulos y renderizado.

- Categoría: Producción de vídeo con agentes y automatización; Candidato principal.
- Frontera de aplicación: Algunos proveedores de generación y voz son servicios de pago; un gran volumen de archivos de Skill no significa que todos los flujos se hayan probado de forma unificada.
- Estado de mantenimiento: Con commits en los últimos 90 días; 148 commits en 30 días, 272 en 90 días.
- Licencia: [AGPL-3.0](https://api.github.com/repos/OpenMontageInc/OpenMontage/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/OpenMontageInc/OpenMontage/blob/fecb9a1e3cc23ef84de30b272059457a427f16f8/README.md#L14).

## [OpenFilm](https://github.com/openfilm/openfilm)

Permite a los agentes de codificación crear, inspeccionar, editar y renderizar vídeo con código, y aporta una interfaz editable.

- Categoría: Producción de vídeo con agentes y automatización; Candidato principal.
- Frontera de aplicación: Los planos basados en código difieren de la línea de tiempo con material real; las licencias de material y de librerías de sonido deben verificarse por activo.
- Estado de mantenimiento: Con commits en los últimos 90 días; 117 commits en 30 días, 299 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/openfilm/openfilm/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/openfilm/openfilm/blob/f59cd4e0973feaf6917dcf3229b178b6baf9ad3f/README.md#L7).

## [Rea Video](https://github.com/JuneYaooo/rea-video)

Descompone en reversa qué partes de un vídeo son grabadas, de IA o de código, y produce un plan de réplica plano a plano y un VIDEO.md.

- Categoría: Producción de vídeo con agentes y automatización; Infraestructura adyacente.
- Frontera de aplicación: Se centra en el análisis y la planificación de la réplica; no equivale directamente a un editador o generador final.
- Estado de mantenimiento: Con commits en los últimos 90 días; 218 commits en 30 días, 218 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/JuneYaooo/rea-video/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/JuneYaooo/rea-video/blob/4111ad9adb4936d92f6d57657000b414fee9f01f/README.md#L8).

## [Video Autopilot Kit](https://github.com/Hao0321/video-autopilot-kit)

Marco de automatización encargado de planificar, auditar, revisar el montaje y aprender de los resultados de los vídeos.

- Categoría: Producción de vídeo con agentes y automatización; Candidato principal.
- Frontera de aplicación: El montaje y el renderizado reales dependen de Editkin; instalar solo este repositorio no produce el montaje final.
- Estado de mantenimiento: Con commits en los últimos 90 días; 9 commits en 30 días, 33 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/Hao0321/video-autopilot-kit/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Hao0321/video-autopilot-kit/blob/b48c7d9a624ebceaa3a99f3f4aad6006e2be53fb/README.md#L1).

## [Video Director](https://github.com/win4r/video-director)

Guía a Claude Code para planificar, renderizar y revisar cortos con HTML/Canvas/SVG/Three.js/GSAP/Remotion.

- Categoría: Producción de vídeo con agentes y automatización; Candidato principal.
- Frontera de aplicación: Está afinado principalmente para modelos Claude específicos; la calidad con otros agentes no se hereda automáticamente.
- Estado de mantenimiento: Con commits en los últimos 90 días; 20 commits en 30 días, 20 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/win4r/video-director/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/win4r/video-director/blob/02d1912ab251bf5235b45e8e7aad81b4bc786b15/README.md#L11).

## [Video Use](https://github.com/browser-use/video-use)

Edita material bruto mediante un agente de codificación y FFmpeg: cortes, subtítulos, gradeado, superposición de efectos y revisión de la salida.

- Categoría: Producción de vídeo con agentes y automatización; Candidato principal.
- Frontera de aplicación: No es una herramienta de automatización de vídeo vía navegador; las dependencias concretas y las rutas a servicios cloud se verifican según la configuración del proyecto.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 5 en 90 días.
- Licencia: [MIT](https://github.com/browser-use/video-use/blob/43cfc566833548093455c9d4a46bd69913b7e552/LICENSE); Licencia abierta verificada. La LICENSE raíz es MIT; los términos de servicios de modelos, material y dependencias externas se cuentan aparte.
- Verificación funcional: 2026-11-21; [Fuente 1](https://github.com/browser-use/video-use/blob/43cfc566833548093455c9d4a46bd69913b7e552/README.md#L7).

## [WeVisCut](https://github.com/Tencent/WeVisCut)

Convierte artículos de conocimiento o guiones explicativos en vídeos de varios minutos mediante planificación, búsqueda de material, edición, revisión y reparación.

- Categoría: Producción de vídeo con agentes y automatización; Candidato principal.
- Frontera de aplicación: El modelo de estrategia de 9B, el runtime de herramientas y Studio deben desplegarse según el entorno oficial; los resultados de los autores no equivalen a un ranking entre proyectos.
- Estado de mantenimiento: Con commits en los últimos 90 días; 2 commits en 30 días, 29 en 90 días.
- Licencia: [Apache-2.0](https://github.com/Tencent/WeVisCut/blob/94dc8a7fe43a5e0da21e97d5aaf470a39329db3a/LICENSE); Licencia abierta verificada. La LICENSE raíz establece Apache-2.0 para el código, los parámetros y los pesos públicos; componentes de terceros se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Tencent/WeVisCut/blob/94dc8a7fe43a5e0da21e97d5aaf470a39329db3a/README.md#L7).

## [NeonClipping](https://github.com/iamajmeena/neonclipping)

Pega un enlace y corta localmente en clips 9:16 con subtítulos incrustados los vídeos largos de YouTube/Twitch/Kick o MP4 propios, y genera títulos y ganchos.

- Categoría: Vídeos cortos de conocimiento, clips y explicaciones; Candidato principal.
- Frontera de aplicación: El corte depende de yt-dlp, Streamlink, faster-whisper, FFmpeg y opcionalmente de un modelo local Ollama; el material sin subtítulos de YouTube requiere reconocimiento local o importar subtítulos, con pérdida de calidad; las cifras de velocidad y las 187 comprobaciones del README son autoevaluaciones del autor, no un benchmark independiente; la descarga y la redistribución están sujetas a los términos de la plataforma y a las licencias del material.
- Estado de mantenimiento: Con commits en los últimos 90 días; 89 commits en 30 días, 89 en 90 días.
- Licencia: [MIT](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/LICENSE); Licencia abierta verificada. La LICENSE raíz es MIT; las dependencias de requirements (yt-dlp, faster-whisper, Streamlink, av, static-ffmpeg, etc.), los pesos de modelos descargados con Ollama y las fuentes del sistema tienen licencias aparte
- Verificación funcional: 2026-11-23; [Fuente 1](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/README.md#L5) · [Fuente 2](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/README.md#L45) · [Fuente 3](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/README.md#L114).

## [Clipmint](https://github.com/kleZ799/clipmint)

Convierte podcasts, entrevistas, tutoriales y VOD en Shorts/Reels/TikTok verticales con subtítulos.

- Categoría: Vídeos cortos de conocimiento, clips y explicaciones; Candidato principal.
- Frontera de aplicación: La detección de momentos destacados, el recorte y la subida dependen de modelos locales y de la configuración de cada plataforma.
- Estado de mantenimiento: Con commits en los últimos 90 días; 184 commits en 30 días, 614 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/kleZ799/clipmint/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/kleZ799/clipmint/blob/f2f7ed16871a390d0fd5274fb28b157f22ac57e3/README.md#L7).

## [ChrisHKAI Video](https://github.com/ChrisHKAI/ChrisHKAI-Video)

Skill de agente de codificación que organiza los materiales públicos de un creador en un corto de animación 3D estilo juguete.

- Categoría: Vídeos cortos de conocimiento, clips y explicaciones; Candidato principal.
- Frontera de aplicación: La calidad del montaje final con Codex aún no está verificada; el uso de materiales públicos y las autorizaciones de imagen son responsabilidad del usuario.
- Estado de mantenimiento: Con commits en los últimos 90 días; 173 commits en 30 días, 206 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/ChrisHKAI/ChrisHKAI-Video/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/ChrisHKAI/ChrisHKAI-Video/blob/15b66ee613e621f82ba781d27547a67e76c55f50/README.md#L7).

## [Lanshu AI Presenter Video](https://github.com/cclank/lanshu-create-ai-presenter-video)

Agent Skill que convierte un tema o guion en vídeos explicativos verificados con avatar digital/estilizado.

- Categoría: Vídeos cortos de conocimiento, clips y explicaciones; Candidato principal.
- Frontera de aplicación: El avatar digital, la voz, la sincronización labial y el reconocimiento dependen de los proveedores externos elegidos en tiempo de ejecución.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 16 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/cclank/lanshu-create-ai-presenter-video/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/cclank/lanshu-create-ai-presenter-video/blob/762d3ee42623b75a4ec63ad6aa61ace69d78ce6e/README.md#L23).

## [Claude Animated Shorts](https://github.com/mromidev/claude-animated-shorts)

Skill para producir cortos animados verticales con historia usando Three.js, Remotion, música y efectos de sonido.

- Categoría: Vídeos cortos de conocimiento, clips y explicaciones; Candidato principal.
- Frontera de aplicación: Es un paquete metodológico basado en un corto de muestra ya terminado; la generalización a otros géneros y estilos visuales requiere pruebas.
- Estado de mantenimiento: Con commits en los últimos 90 días; 2 commits en 30 días, 2 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/mromidev/claude-animated-shorts/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/mromidev/claude-animated-shorts/blob/e3b817b6afc6cd413466d43f11ba31209e034bbf/README.md#L5).

## [Vibe Knowledge](https://github.com/andyhuo520/vibe-knowledge)

Skill de cortos de conocimiento que va de la verificación de puntos, la redacción y el doblaje a la generación por código, el control de calidad y el paquete de publicación.

- Categoría: Vídeos cortos de conocimiento, clips y explicaciones; Candidato principal.
- Frontera de aplicación: Los planos enriquecidos pueden llamar a plataformas de generación externas; la ilustración base por código y el nivel enriquecido deben compararse por separado.
- Estado de mantenimiento: Con commits en los últimos 90 días; 3 commits en 30 días, 3 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/andyhuo520/vibe-knowledge/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/andyhuo520/vibe-knowledge/blob/c3a13a85f7cc560e5d396f063baecea4b2748e1e/README.md#L5).

## [Vox Director](https://github.com/alisa0808/vox-director)

Agent Skill de extremo a extremo que lleva de un tema a un vídeo explicativo/publicitario estilo collage de papel tipo Vox.

- Categoría: Vídeos cortos de conocimiento, clips y explicaciones; Candidato principal.
- Frontera de aplicación: La generación de material depende de Atlas Cloud y FFmpeg; imitar ese estilo exige atender a las fronteras de marca y copyright.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 1 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/alisa0808/vox-director/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/alisa0808/vox-director/blob/6a85a7c341610442a6a5b1885e6e0217ab82a11f/README.md#L5).

## [Video to Shorts Skill](https://github.com/social-media-skills/video-to-shorts-skill)

Hace que un agente convierta vídeos largos o podcasts en cortos verticales con subtítulos palabra a palabra y, opcionalmente, los publique.

- Categoría: Vídeos cortos de conocimiento, clips y explicaciones; Candidato principal.
- Frontera de aplicación: La publicación automática involucra credenciales de plataforma; al descargar el vídeo origen deben respetarse los términos de la plataforma y las autorizaciones.
- Estado de mantenimiento: Con commits en los últimos 90 días; 3 commits en 30 días, 3 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/social-media-skills/video-to-shorts-skill/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/social-media-skills/video-to-shorts-skill/blob/2e20fb008b584f3927798f36f580401d75318600/README.md#L3).

## [Pixelle-Video](https://github.com/ATH-MaaS/Pixelle-Video)

A partir de un tema genera el guion, imágenes o vídeos, el doblaje y monta un vídeo corto; admite flujos ComfyUI y APIs de medios.

- Categoría: Vídeos cortos de conocimiento, clips y explicaciones; Candidato principal.
- Frontera de aplicación: La dirección original de AIDC-AI se ha migrado; la configuración, el coste y las licencias del material de ComfyUI local, RunningHub o las APIs de modelos deben verificarse por separado.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Apache-2.0](https://github.com/ATH-MaaS/Pixelle-Video/blob/848b054e4fae40dabc62ec58e960b573e83793ac/LICENSE); Licencia abierta verificada. La LICENSE raíz es Apache-2.0; NOTICE enumera las dependencias de terceros y sus licencias.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/ATH-MaaS/Pixelle-Video/blob/848b054e4fae40dabc62ec58e960b573e83793ac/README.md#L52).

## [Atlas Explainer](https://github.com/AtlasCloudAI/atlas-explainer)

Skill/CLI que genera vídeos explicativos de conocimiento con doblaje y estilo papercraft a partir de un solo tema.

- Categoría: Vídeos cortos de conocimiento, clips y explicaciones; Candidato principal.
- Frontera de aplicación: La generación de imagen, voz y demás depende de la API de Atlas Cloud; no es una cadena de producción enteramente local.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/AtlasCloudAI/atlas-explainer/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/AtlasCloudAI/atlas-explainer/blob/02f0d82392191a1c980a8a40348eb686b9e157dd/README.md#L3).

## [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill)

CLI y MCP que dan a los agentes de codificación edición local con FFmpeg: cortes, subtítulos, exportación de formatos y revisión de salida.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Requiere FFmpeg y Python en la máquina; la skill, la compilación de FFmpeg y el material siguen licencias propias; los resultados concretos no se han probado en ejecución.
- Estado de mantenimiento: Con commits en los últimos 90 días; 549 commits en 30 días, 977 en 90 días.
- Licencia: [MIT](https://github.com/kajisho5/ffmpeg-skill/blob/45df6b9ab0740cecc15d0169165e8cfbcefdfb0b/LICENSE); Licencia abierta verificada. La LICENSE raíz del repositorio de la skill es MIT; las licencias de FFmpeg y sus codificadores deben verificarse según la compilación concreta.
- Verificación funcional: 2026-11-21; [Fuente 1](https://github.com/kajisho5/ffmpeg-skill/blob/45df6b9ab0740cecc15d0169165e8cfbcefdfb0b/README.md#L67).

## [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit)

Skills, plantillas, comandos y herramientas para Claude Code: guion, doblaje, música, generación de imagen y vídeo, control de calidad, renderizado y publicación, con migración a Codex y Kiro CLI.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Requiere Node 22+ y Claude Code; los modelos de IA se despliegan en tu propia cuenta de GPU cloud Modal/RunPod con coste asociado; el coste de $0.33 y las muestras del README son autoevaluaciones del autor; los plugins comunitarios, las skills de diseño de terceros y los servicios gestionados de publicación tienen licencias y términos propios; los derechos del contenido generado, de la clonación de voces y del material deben verificarse por cuenta propia.
- Estado de mantenimiento: Con commits en los últimos 90 días; 441 commits en 30 días, 546 en 90 días.
- Licencia: [MIT](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/LICENSE); Licencia abierta verificada. La LICENSE raíz es MIT (copyright Digital Samba); las licencias son independientes entre sí para los pesos de modelos invocados (Qwen3-TTS, FLUX.2, Ideogram 4, ACE-Step, LTX-Video, etc.), servicios externos como ElevenLabs, el renderizador Remotion y los plugins comunitarios (p. ej. arkiv bajo PolyForm Perimeter)
- Verificación funcional: 2026-11-24; [Fuente 1](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/README.md#L9) · [Fuente 2](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/README.md#L12) · [Fuente 3](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/README.md#L66).

## [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft)

Aporta a los agentes recetas de planos, guiones gráficos, animación Remotion, cortes al pulso y comprobación fotograma a fotograma.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: La librería de planos es método creativo y activos de código; no sustituye a un editor de línea de tiempo de propósito general.
- Estado de mantenimiento: Con commits en los últimos 90 días; 38 commits en 30 días, 57 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/Vincentwei1021/video-shotcraft/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Vincentwei1021/video-shotcraft/blob/6700db2ba80572ebc777b99d72049679fed9840c/README.md#L26).

## [Remocn](https://github.com/Remocn/remocn)

Complemento de Claude Code, skill de agente y servidor MCP para crear vídeos con Remotion a partir de 935 componentes con licencia MIT: el agente primero planifica el storyboard y luego escribe el vídeo.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Requiere Remotion y la CLI de shadcn que instala los componentes; `scene-reviewer` solo revisa fotogramas estáticos (texto cortado, fotogramas vacíos y bajo contraste), así que la calidad final y el tiempo de render no se han medido; componentes, fuentes y el MCP alojado tienen sus propias condiciones, y Remotion se licencia aparte.
- Estado de mantenimiento: Con commits en los últimos 90 días; 147 commits en 30 días, 197 en 90 días.
- Licencia: [MIT](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/LICENSE); Licencia abierta verificada. La LICENSE raíz del repositorio es MIT; el README indica que los componentes son MIT, mientras que el renderizador Remotion, las fuentes y el servicio MCP alojado deben verificarse según sus propias condiciones.
- Verificación funcional: 2026-11-26; [Fuente 1](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/README.md#L9) · [Fuente 2](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/README.md#L37) · [Fuente 3](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/README.md#L73).

## [Kinocut](https://github.com/KyaniteLabs/kinocut)

MCP/Python/CLI de edición de vídeo local con guardias, prechequeos, recibos y puertas de calidad.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Envuelve FFmpeg y Whisper/HyperFrames opcionales; las herramientas tipadas no garantizan el criterio estético del montaje.
- Estado de mantenimiento: Con commits en los últimos 90 días; 376 commits en 30 días, 698 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/KyaniteLabs/kinocut/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/KyaniteLabs/kinocut/blob/4ad02dba114cf12163663e7cd39da92d4f735212/README.md#L13).

## [Remotion Agent Skills](https://github.com/remotion-dev/skills)

Skills oficiales para que los agentes de codificación creen, previsualicen y rendericen vídeos con Remotion.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Requiere Remotion y un anfitrión compatible con Agent Skills; no se encontró licencia en la raíz de este repositorio y Remotion tiene sus propias condiciones de licencia.
- Estado de mantenimiento: Con commits en los últimos 90 días; 9 commits en 30 días, 31 en 90 días.
- Licencia: [Licencia pendiente de verificación](https://github.com/remotion-dev/skills/tree/6f55706d1069e512430582ad86e4e57dc07afe1b); Licencia pendiente de verificación. No se encontró LICENSE en la raíz ni en el árbol del repositorio; las licencias del producto Remotion y de cada paquete deben comprobarse por separado.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/remotion-dev/skills/blob/6f55706d1069e512430582ad86e4e57dc07afe1b/README.md#L5).

## [Manju Laoli Skill](https://github.com/lixiaoxiao9888-create/manju-laoli-skill)

Juego de OpenClaw Skills para dramas animados estilo cómic y dramas cortos: guion, bloqueo de activos, guion gráfico, coreografía de pelea, prompts para Seedance y control automático.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Orientado a plataformas de agentes como OpenClaw, Coze y Dify; la única línea de modelos de vídeo del paquete es Seedance 2.5/2.0; el autor lo marca como beta y ensambla contenido open source sin enumerar por separado las fuentes externas de reglas y material; el paquete no contiene imágenes: el material debe generarse en plataformas externas y licenciarse por cuenta propia.
- Estado de mantenimiento: Con commits en los últimos 90 días; 4 commits en 30 días, 47 en 90 días.
- Licencia: [MIT](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/LICENSE); Licencia abierta verificada. Tanto la raíz como short-drama-director son MIT; el autor lo marca como beta y ensambla contenido open source sin NOTICE de terceros individualizado; la redistribución de los textos de reglas y ejemplos debe verificarse por cuenta propia
- Verificación funcional: 2026-11-23; [Fuente 1](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/README.md#L60) · [Fuente 2](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/README.md#L72) · [Fuente 3](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/README.md#L137).

## [pixelfx](https://github.com/patch-gg/pixelfx)

Biblioteca de 244 efectos y animaciones pixel-art dibujados por código, con una Skill de generación de efectos para Claude Code, hojas de sprites y utilidades de exportación GIF/MP4.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Es una librería de activos de efectos y movimiento, sin flujo de guion, edición ni publicación; la fuente Patch Pixel en `gallery/fonts` es propiedad de Patch y no está bajo MIT; parte del código adapta Sprite Fusion y Hollow Crown (ambos MIT) y debe conservarse la atribución según NOTICE; al usar el material exportado en vídeos siguen aplicando las licencias del contenido de terceros visible.
- Estado de mantenimiento: Con commits en los últimos 90 días; 10 commits en 30 días, 10 en 90 días.
- Licencia: [MIT (código y efectos) + fuente Patch Pixel excluida](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/NOTICE.md); Licencia compuesta/condicional. README declara código y efectos MIT con uso comercial permitido; NOTICE enumera efectos adaptados de Sprite Fusion (Hugo Duprez) y Hollow Crown (ambos MIT) cuya atribución debe conservarse; `gallery/fonts/PatchPixel-Regular.woff2` es de Patch, todos los derechos reservados, fuera del alcance de MIT
- Verificación funcional: 2026-11-24; [Fuente 1](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/README.md#L7) · [Fuente 2](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/README.md#L89) · [Fuente 3](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/README.md#L156).

## [Wallstreet Explainer](https://github.com/HeyChengC/wallstreet-explainer)

Skill de agente de codificación para cortos de explicación financiera/tecnológica al estilo Wall Street, con lenguaje de estilo, plantillas de componentes gráficos y guiones de búsqueda de vídeos, capturas, doblaje, croma, renderizado y mezcla.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Requiere un anfitrión como Claude Code, además de ffmpeg, dependencias Python/Node y Playwright, y descargar cinco fuentes por cuenta propia; el material proviene de descargas con yt-dlp y de capturas de noticias citadas en plan comentario; la procedencia y la autorización de redistribución deben verificarse por cuenta propia; las tomas de terceros, capturas, logos y personas de las muestras no están cubiertos por MIT.
- Estado de mantenimiento: Con commits en los últimos 90 días; 10 commits en 30 días, 16 en 90 días.
- Licencia: [MIT (código y documentación) + material de terceros en las muestras excluido](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/LICENSE); Licencia compuesta/condicional. La LICENSE es el texto MIT con cláusulas adicionales que excluyen expresitamente los fotogramas de vídeo, capturas de noticias, logos y fotos de examples/; GitHub la identifica por ello como NOASSERTION. Las fuentes deben descargarse por cuenta propia y siguen sus respectivas licencias
- Verificación funcional: 2026-11-23; [Fuente 1](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/README.md#L3) · [Fuente 2](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/README.md#L37) · [Fuente 3](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/README.md#L92).

## [ReelBench Skills](https://github.com/eternityspring/reelbench-skills)

Colección de Skills de análisis, réplica y producción de vídeo para Claude Code/Codex.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Algunos productos relacionados y servicios de material son de pago o externos; debe verificarse según la Skill concreta.
- Estado de mantenimiento: Con commits en los últimos 90 días; 1 commits en 30 días, 21 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/eternityspring/reelbench-skills/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/eternityspring/reelbench-skills/blob/8d8444894524c9beedbf8815dab517afb3ce3cbe/README.md#L5).

## [Video Agent Skills](https://github.com/Melvynx/video-agent-skills)

Organiza guion, investigación, edición, traducción y publicación de vídeos cortos/YouTube mediante Skills en Markdown.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Las skills no incluyen por sí mismas todos los modelos ni renderizadores; requieren un anfitrión y herramientas locales.
- Estado de mantenimiento: Con commits en los últimos 90 días; 1 commits en 30 días, 26 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/Melvynx/video-agent-skills/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Melvynx/video-agent-skills/blob/f4542923f7f796a1fa0e544cbfc1109d5eec87d8/README.md#L3).

## [Awesome Motion Design Agent Skills](https://github.com/frankxai/awesome-motion-design-agent-skills)

Cinco flujos de movimiento instalables en SKILL.md (incluidos remotion-video-agent y web-motion-auditor) más un índice seleccionado de herramientas GSAP, Motion, Remotion, Rive, Lottie y 3D.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Las entradas del índice apuntan a repositorios de terceros cuyas licencias y disponibilidad hay que verificar por separado; las skills solo aportan método, listas de revisión y enrutado, de modo que la calidad del movimiento y del vídeo depende del agente anfitrión y de las librerías elegidas; el README recomienda escanear primero los paquetes de terceros con SkillSpector.
- Estado de mantenimiento: Con commits en los últimos 90 días; 9 commits en 30 días, 19 en 90 días.
- Licencia: [CC0-1.0](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/LICENSE); Licencia abierta verificada. La LICENSE raíz es CC0 1.0 Universal; los proyectos, fuentes y materiales de terceros a los que apuntan el índice y las skills conservan sus propias licencias.
- Verificación funcional: 2026-11-26; [Fuente 1](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/README.md#L15) · [Fuente 2](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/README.md#L51) · [Fuente 3](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/README.md#L57).

## [HyperFrames Motion Library](https://github.com/nutllwhy/hyperframes-motion-library)

Biblioteca local de plantillas de motion graphics y activos paramétricos con HyperFrames como núcleo.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Es una librería de activos de movimiento; no incluye flujos completos de guion, generación de material ni publicación.
- Estado de mantenimiento: Con commits en los últimos 90 días; 2 commits en 30 días, 2 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/nutllwhy/hyperframes-motion-library/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/nutllwhy/hyperframes-motion-library/blob/98c40ca18f23d7dc021a5d84308ab10599482cff/README.md#L3).

## [Video Editing Skill](https://github.com/social-media-skills/video-editing-skill)

Hace que un agente ejecute el primer pase de edición y de subtítulos sobre vídeos hablados a cámara, cursos, entrevistas y vlogs.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Cubre el primer corte preliminar; no sustituye la revisión final humana, el gradeado ni el empaquetado complejo.
- Estado de mantenimiento: Con commits en los últimos 90 días; 3 commits en 30 días, 3 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/social-media-skills/video-editing-skill/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/social-media-skills/video-editing-skill/blob/f94d0517d717de281ee23569094aac616d32f4ef/README.md#L1).

## [GSAP Skills](https://github.com/greensock/gsap-skills)

Agent Skills oficiales que guían a un agente de codificación en el uso de líneas de tiempo, efectos y complementos de GSAP.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Skill de animación web; requiere un agente anfitrión; renderizar a vídeo necesita herramientas de vídeo aparte y las licencias de producto de GSAP se verifican por separado.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://github.com/greensock/gsap-skills/blob/aed9cfd3277740755f6bfc1155c7aa645403b760/LICENSE); Licencia abierta verificada. La LICENSE raíz del repositorio de Skills es MIT; la librería GSAP y el material de terceros siguen sus propios términos.
- Verificación funcional: 2026-11-21; [Fuente 1](https://github.com/greensock/gsap-skills/blob/aed9cfd3277740755f6bfc1155c7aa645403b760/README.md#L23).

## [Narrator AI CLI Skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill)

Guía al agente para usar narrator-ai-cli y producir automáticamente vídeos de comentario de películas con voz en off.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Es una Skill legible por máquinas para una CLI, no un motor de renderizado independiente; el servicio backend y las plantillas se cuentan aparte.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/NarratorAI-Studio/narrator-ai-cli-skill/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill/blob/4b17c6f2175bd532c92db778a847f8fb6bdd3177/README.md#L9).

## [OpenClip Agent Skills](https://github.com/OpenClip-App/agent-skills)

Skills para agentes: trocear vídeos largos, transcripción, conversiones, miniaturas, recorte de fondo e ideas UGC.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: Las skills operan un MCP de OpenClip alojado; los vídeos y las credenciales pasan por servicios externos.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/OpenClip-App/agent-skills/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/OpenClip-App/agent-skills/blob/ea02c98db69c437616df1db4a4400cde1f4a0832/README.md#L1).

## [MCP Video Editing](https://github.com/mfortne/mcp-video-editing)

Envuelve FFmpeg, HyperFrames y flujos locales de reutilización como MCP, librería Python y CLI.

- Categoría: Agent Skills, MCP y herramientas de edición; Candidato principal.
- Frontera de aplicación: El resultado real depende de las versiones de las herramientas externas; el proyecto es de la misma familia que Kinocut pero no es el mismo repositorio.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/mfortne/mcp-video-editing/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/mfortne/mcp-video-editing/blob/97ecab83d26c24bfe77be663784399b203b1fa55/README.md#L3).

## [HyperFrames](https://github.com/heygen-com/hyperframes)

Ecosistema de código-a-vídeo y Agent Skills basado en HTML/CSS/JS, con migración desde Remotion y otros y verificación fotograma a fotograma.

- Categoría: Code-to-video y motion graphics; Candidato principal.
- Frontera de aplicación: El proyecto y el servicio gestionado de generación de HeyGen son capas distintas; las plantillas concretas y el material externo tienen licencias aparte.
- Estado de mantenimiento: Con commits en los últimos 90 días; 1872 commits en 30 días, 4087 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/heygen-com/hyperframes/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/heygen-com/hyperframes/blob/234fb1aeef13f8d86b4f7f4cb1af624db3a81ec2/README.md#L5).

## [Remotion](https://github.com/remotion-dev/remotion)

Marco base para crear y renderizar vídeo con código en React/TypeScript.

- Categoría: Code-to-video y motion graphics; Licencia restringida.
- Frontera de aplicación: Es infraestructura de código-a-vídeo de propósito general; no trae planificación de agentes ni modelos de generación.
- Estado de mantenimiento: Con commits en los últimos 90 días; 2549 commits en 30 días, 6756 en 90 días.
- Licencia: [Remotion License](https://github.com/remotion-dev/remotion/blob/51fd2b4a06a2b2ff0d4eb058dfe4db2b7275bac3/LICENSE.md); Código fuente visible pero no open source OSI. Gratis para personas, organizaciones sin ánimo de lucro y organizaciones pequeñas; las empresas lucrativas que alcanzan los umbrales necesitan una licencia de empresa; no es una licencia OSI convencional
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/remotion-dev/remotion/blob/51fd2b4a06a2b2ff0d4eb058dfe4db2b7275bac3/README.md#L2).

## [raea](https://github.com/shinyobjectz/raea)

Motor y estudio de agente de escritorio para escribir vídeo, motion graphics, 3D y juegos en React/TypeScript, renderizados en GPU local.

- Categoría: Code-to-video y motion graphics; Candidato principal.
- Frontera de aplicación: Motor, CLI y aplicación de escritorio pueden usarse gratis; el almacenamiento en la nube, la búsqueda entre máquinas y la publicación pertenecen a Pro/Team; FSL-1.1-ALv2 prohíbe los productos competidores y cada versión pasa a Apache-2.0 dos años después de publicarse; las licencias de las fuentes de vídeo de ejemplo, los modelos, el runtime binario, los componentes de terceros y el material dentro de la cuenta se cuentan aparte.
- Estado de mantenimiento: Con commits en los últimos 90 días; 1565 commits en 30 días, 1568 en 90 días.
- Licencia: [FSL-1.1-ALv2](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/LICENSE); Código fuente visible pero no open source OSI. La LICENSE raíz es Functional Source License 1.1 (ALv2 Future License); prohíbe usar el software para productos/servicios comerciales que sustituyan a raea o a sus productos existentes; cada versión pasa a Apache-2.0 dos años después de su publicación; NOTICE y LICENSES enumeran por separado licencias de terceros como la portabilidad de HyperFrames, Bevy, FFmpeg y QuickJS
- Verificación funcional: 2026-11-22; [Fuente 1](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/README.md#L13) · [Fuente 2](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/README.md#L42) · [Fuente 3](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/README.md#L111).

## [Lemo Opuscar](https://github.com/lemomo-ai/lemo-opuscar)

Aporta estilo cinematográfico, ejemplos y la guía STYLE.md para que un agente de codificación haga vídeos con código.

- Categoría: Code-to-video y motion graphics; Licencia restringida.
- Frontera de aplicación: El proyecto recomienda usar Claude con mayor intensidad de razonamiento; reutilizar material, personas, marcas y voces de las demos debe verificarse por separado.
- Estado de mantenimiento: Con commits en los últimos 90 días; 97 commits en 30 días, 151 en 90 días.
- Licencia: [MIT (código) + CC BY-NC (documentación, licencia adicional)](https://github.com/lemomo-ai/lemo-opuscar/blob/f9e204293930952b61ba921cd8944d05f121beee/LICENSE); Licencia compuesta/condicional. El código es MIT; la documentación Markdown es CC BY-NC 4.0, que además permite leer, modificar y entregar junto a los archivos del proyecto las películas propias o de clientes; el uso comercial fuera de ese alcance requiere licencia. El material de ejemplo y parte del doblaje tienen restricciones adicionales.
- Verificación funcional: 2026-11-21; [Fuente 1](https://github.com/lemomo-ai/lemo-opuscar/blob/f9e204293930952b61ba921cd8944d05f121beee/README.md#L7).

## [Manim Community](https://github.com/ManimCommunity/manim)

Motor de vídeo para crear animaciones matemáticas y de explicación con código Python.

- Categoría: Code-to-video y motion graphics; Candidato principal.
- Frontera de aplicación: Adecuado para explicaciones basadas en código; no es un agente de IA que genere contenido automáticamente; las dependencias de renderizado, las fuentes, etc. se cuentan aparte.
- Estado de mantenimiento: Con commits en los últimos 90 días; 29 commits en 30 días, 79 en 90 días.
- Licencia: [MIT](https://github.com/ManimCommunity/manim/blob/ab7f9527fa2b37893aacc367e21b723845f44ef0/LICENSE); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/ManimCommunity/manim/blob/ab7f9527fa2b37893aacc367e21b723845f44ef0/README.md#L20).

## [GiveMotion](https://github.com/givemotion/givemotion)

Motor de código-a-vídeo en el que un agente escribe HTML/CSS, previsualiza, revisa y renderiza MP4.

- Categoría: Code-to-video y motion graphics; Candidato principal.
- Frontera de aplicación: La animación por código sirve para motion graphics y explicaciones; no equivale a editar material real ni a generar vídeo por difusión.
- Estado de mantenimiento: Con commits en los últimos 90 días; 83 commits en 30 días, 243 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/givemotion/givemotion/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/givemotion/givemotion/blob/8a7949e685bbfaec8bde20fad9aa8734cdfa6038/README.md#L6).

## [SenseNova Code2Video](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video)

Un modelo abierto pequeño genera código ejecutable que renderiza vídeos cortos.

- Categoría: Code-to-video y motion graphics; Candidato principal.
- Frontera de aplicación: Enfocado por ahora en vídeos cortos de puro código; las licencias de los pesos, del entorno de inferencia y de las herramientas de generación deben verificarse por separado.
- Estado de mantenimiento: Con commits en los últimos 90 días; 2 commits en 30 días, 3 en 90 días.
- Licencia: [Pendiente de verificación](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video/blob/776ae79824e338ba5d63fef66167455edc94ad26/README.md); Licencia pendiente de verificación. No se encontró licencia en la raíz; las condiciones de reutilización de pesos y código deben confirmarse por separado
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video/blob/776ae79824e338ba5d63fef66167455edc94ad26/README.md#L3).

## [Manim](https://github.com/3b1b/manim)

Motor de animación en Python para explicaciones matemáticas.

- Categoría: Code-to-video y motion graphics; Infraestructura adyacente.
- Frontera de aplicación: Es una herramienta de animación de propósito general y el repositorio es la versión de 3Blue1Brown, no un agente completo de vídeo con IA.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 1 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/3b1b/manim/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/3b1b/manim/blob/fafa083a4fb274bba9cabde0b6e2f50ba6da0622/README.md#L2).

## [Motion Canvas](https://github.com/motion-canvas/motion-canvas)

Crea animaciones, explicaciones y motion graphics con TypeScript y funciones generadoras.

- Categoría: Code-to-video y motion graphics; Infraestructura adyacente.
- Frontera de aplicación: Marco de animación de propósito general; las capacidades de agente vienen de Skills superiores o del anfitrión.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/motion-canvas/motion-canvas/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/motion-canvas/motion-canvas/blob/7b91435c301d530351dcf5ebb91dd139c002e405/README.md#L6).

## [three.js](https://github.com/mrdoob/three.js)

Librería de escenas y renderizado 3D en JavaScript, apta para aportar contenido 3D a los motion graphics por código.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Librería de renderizado de propósito general; no exporta vídeo automáticamente; el material y el entorno WebGL/WebGPU los gestiona el usuario.
- Estado de mantenimiento: Con commits en los últimos 90 días; 322 commits en 30 días, 884 en 90 días.
- Licencia: [MIT](https://github.com/mrdoob/three.js/blob/8b92052852735b67cfa8393f78e707b3f07a0eec/LICENSE); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/mrdoob/three.js/blob/8b92052852735b67cfa8393f78e707b3f07a0eec/README.md#L11).

## [Godot](https://github.com/godotengine/godot)

Motor de videojuegos open source para construir escenas 2D y 3D, interacción y animación.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Un motor de videojuegos no es un sistema automático de generación de vídeo; grabar o exportar el montaje final requiere diseñar flujos adicionales.
- Estado de mantenimiento: Con commits en los últimos 90 días; 527 commits en 30 días, 1895 en 90 días.
- Licencia: [MIT](https://github.com/godotengine/godot/blob/73ca6be2cebd5192d8b279979d04f29ea45c266e/LICENSE.txt); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/godotengine/godot/blob/73ca6be2cebd5192d8b279979d04f29ea45c266e/README.md#L11).

## [Motion](https://github.com/motiondivision/motion)

Librería de animaciones de interfaz y layout para JavaScript, React y Vue.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Componente de motion graphics de propósito general; se combina con un renderizador de vídeo y no aporta por sí mismo un agente de vídeo.
- Estado de mantenimiento: Con commits en los últimos 90 días; 464 commits en 30 días, 1390 en 90 días.
- Licencia: [MIT](https://github.com/motiondivision/motion/blob/cd009de7a4314e065d4d9df683057124792d5b34/LICENSE.md); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/motiondivision/motion/blob/cd009de7a4314e065d4d9df683057124792d5b34/README.md#L3).

## [Blender](https://github.com/blender/blender)

Suite 3D que cubre modelado, rigging, animación, renderizado, composición y edición de vídeo.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: El repositorio de GitHub es un espejo oficial; los complementos, modelos y material de terceros siguen sus propias licencias.
- Estado de mantenimiento: Con commits en los últimos 90 días; 1245 commits en 30 días, 3323 en 90 días.
- Licencia: [GPL-2.0-or-later](https://github.com/blender/blender/blob/611d97903ad34434934f4cb1e586155c03eddd66/COPYING); Licencia abierta verificada. COPYING apunta al texto de la licencia GPL; activos y componentes de terceros se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/blender/blender/blob/611d97903ad34434934f4cb1e586155c03eddd66/.github/README.md#L14).

## [Babylon.js](https://github.com/BabylonJS/Babylon.js)

Motor de escenas 3D, juegos y renderizado en JavaScript, utilizable como base de motion graphics por código.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: De forma predeterminada es un motor de renderizado 3D en tiempo real; la codificación de vídeo exige conectar otras herramientas, y la documentación oficial advierte de que el CDN de demostraciones no debe usarse en producción.
- Estado de mantenimiento: Con commits en los últimos 90 días; 156 commits en 30 días, 335 en 90 días.
- Licencia: [Apache-2.0](https://github.com/BabylonJS/Babylon.js/blob/6226e393cef4295d8509b8a83e82572b2af4c9c9/license.md); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/BabylonJS/Babylon.js/blob/6226e393cef4295d8509b8a83e82572b2af4c9c9/readme.md#L1).

## [Konva](https://github.com/konvajs/konva)

Librería de escenas Canvas 2D con interacción de objetos, transformaciones, animación y exportación.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Componente de lienzo de propósito general; la exportación de vídeo o audio requiere otras herramientas.
- Estado de mantenimiento: Con commits en los últimos 90 días; 32 commits en 30 días, 219 en 90 días.
- Licencia: [MIT](https://github.com/konvajs/konva/blob/bf1927c1cfec7f47eb608a470aff6ca99dd09aa9/LICENSE); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/konvajs/konva/blob/bf1927c1cfec7f47eb608a470aff6ca99dd09aa9/README.md#L16).

## [Two.js](https://github.com/jonobr1/two.js)

Crea escenas gráficas y animaciones 2D mediante WebGL, Canvas o SVG.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Librería base de dibujo 2D; generar archivos de audio/vídeo exige conectar renderizado y codificación aparte.
- Estado de mantenimiento: Con commits en los últimos 90 días; 15 commits en 30 días, 47 en 90 días.
- Licencia: [MIT](https://github.com/jonobr1/two.js/blob/bd48e27ff8f3333ef442fb3d032cb6b5391f26dc/LICENSE); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/jonobr1/two.js/blob/bd48e27ff8f3333ef442fb3d032cb6b5391f26dc/README.md#L8).

## [Shifty](https://github.com/jeremyckahn/shifty)

Motor de interpolación (tweening) en TypeScript con easing y control de reproducción.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Librería de tweening subyacente; no incluye flujos de generación o exportación de vídeo.
- Estado de mantenimiento: Con commits en los últimos 90 días; 8 commits en 30 días, 14 en 90 días.
- Licencia: [MIT](https://github.com/jeremyckahn/shifty/blob/ee4c8ed53503d5a6bf658ccdbba5af58674e3245/LICENSE-MIT); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/jeremyckahn/shifty/blob/ee4c8ed53503d5a6bf658ccdbba5af58674e3245/README.md#L7).

## [Ola](https://github.com/franciscop/ola)

Librería ligera de animación para suavizado e interpolación de valores en tiempo real.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Solo interpolación numérica; el usuario aporta la escena, la línea de tiempo y la exportación.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 3 en 90 días.
- Licencia: [MIT](https://github.com/franciscop/ola/blob/b269059c570405421acfcc55c84b3347cbeb0674/LICENSE); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/franciscop/ola/blob/b269059c570405421acfcc55c84b3347cbeb0674/readme.md#L3).

## [Anime.js](https://github.com/juliangarnier/anime)

Crea animaciones de línea de tiempo sobre propiedades CSS, SVG, DOM y JavaScript.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Motor de animación web de propósito general; la renderización de vídeo y la sincronización con audio requieren herramientas adicionales.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://github.com/juliangarnier/anime/blob/01b81be1df6843ccfe0a71c0699a746bf740dd77/LICENSE.md); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/juliangarnier/anime/blob/01b81be1df6843ccfe0a71c0699a746bf740dd77/README.md#L13).

## [Proton](https://github.com/drawcall/Proton)

Librería de animación de partículas en JavaScript para efectos de fuego, fuegos artificiales, explosiones y similares.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Biblioteca de efectos base; no es una herramienta independiente de renderizado o edición de vídeo.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://github.com/drawcall/Proton/blob/b4fdef5e5416d70a788978bec0fb4a1be26514b4/LICENSE); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/drawcall/Proton/blob/b4fdef5e5416d70a788978bec0fb4a1be26514b4/README.md#L26).

## [Lottie Web](https://github.com/airbnb/lottie-web)

Analiza y renderiza en la web animaciones vectoriales Lottie exportadas.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Un reproductor no es un editor de vídeo; las licencias de los recursos de animación y de su forma de generación se cuentan aparte.
- Estado de mantenimiento: Sin commits desde hace más de 365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://github.com/airbnb/lottie-web/blob/bede03d25d232826e0c9dca1733d542d8a7754fb/LICENSE.md); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/airbnb/lottie-web/blob/bede03d25d232826e0c9dca1733d542d8a7754fb/README.md#L3).

## [TweenJS](https://github.com/CreateJS/TweenJS)

Ofrece tweening y reproducción encadenada de valores JavaScript y propiedades CSS.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Las librerías de tweening requieren acompañarse de un renderizador y de herramientas de exportación.
- Estado de mantenimiento: Sin commits desde hace más de 365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://github.com/CreateJS/TweenJS/blob/6df2b9ce7e68d3d824cc490b67cab2bc3204810a/LICENSE.txt); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/CreateJS/TweenJS/blob/6df2b9ce7e68d3d824cc490b67cab2bc3204810a/README.md#L3).

## [LUME](https://github.com/lume/lume)

Construye escenas interactivas de gráficos 2D y 3D usando elementos HTML.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Componente 3D/gráficos de propósito general; no proporciona un flujo completo de producción de vídeo.
- Estado de mantenimiento: Sin commits desde hace más de 365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://github.com/lume/lume/blob/6336e365f1c02af6316017bcd6d7f79bd2efe13b/LICENSE); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/lume/lume/blob/6336e365f1c02af6316017bcd6d7f79bd2efe13b/README.md#L23).

## [gifenc](https://github.com/mattdesl/gifenc)

Codifica GIF con animación y transparencia en el navegador o en Node.js.

- Categoría: Animación, 3D y componentes base de codificación; Infraestructura adyacente.
- Frontera de aplicación: Produce GIF; no ofrece exportación MP4, edición de vídeo ni generación con IA de forma directa.
- Estado de mantenimiento: Sin commits desde hace más de 365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://github.com/mattdesl/gifenc/blob/27db5b982dba701ca440b55ea36fad3999040973/LICENSE.md); Licencia abierta verificada. Archivo de licencia del proyecto verificado; componentes de terceros, material y servicios gestionados se cuentan aparte.
- Verificación funcional: 2026-11-20; [Fuente 1](https://github.com/mattdesl/gifenc/blob/27db5b982dba701ca440b55ea36fad3999040973/README.md#L5).

## [VRGameDevGirl AI Video Builder](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl)

Gestiona en ComfyUI, por escenas, la planificación, los prompts, la generación, el ritmo, la revisión y el ensamblaje final.

- Categoría: ComfyUI y modelos de vídeo abiertos; Licencia restringida.
- Frontera de aplicación: Algunos nodos custom se han movido a paquetes propios; los modelos, la VRAM y la compatibilidad de instalación deben verificarse según el flujo.
- Estado de mantenimiento: Con commits en los últimos 90 días; 125 commits en 30 días, 667 en 90 días.
- Licencia: [VRGameDevGirl Community and Commercial License](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl/blob/b419bb5c2468432704e0339035844620f1b3ec18/LICENSE); Código fuente visible pero no open source OSI. El contenido generado puede comercializarse; vender/alojar/integrar comercialmente el software en sí requiere una licencia comercial escrita
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl/blob/b419bb5c2468432704e0339035844620f1b3ec18/README.md#L1).

## [LTX-Video](https://github.com/Lightricks/LTX-Video)

Modelos y herramientas de inferencia abiertos de vídeo para texto/imagen a vídeo y generación audiovisual.

- Categoría: ComfyUI y modelos de vídeo abiertos; Candidato principal.
- Frontera de aplicación: Las versiones de LTX difieren claramente en hardware, pesos y capacidades de audio.
- Estado de mantenimiento: Con commits en los últimos 90 días; 2 commits en 30 días, 2 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/Lightricks/LTX-Video/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Lightricks/LTX-Video/blob/50f0aef1297574a4b29acbdb874e3a363a6d5f2e/README.md#L4).

## [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo)

Modelo base abierto de generación de vídeo a gran escala de Tencent, con su marco de inferencia.

- Categoría: ComfyUI y modelos de vídeo abiertos; Licencia restringida.
- Frontera de aplicación: Requisitos de hardware elevados; la licencia del código y las políticas de pesos/salida del modelo deben verificarse por separado.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 3 en 90 días.
- Licencia: [Tencent Hunyuan Community License](https://github.com/Tencent-Hunyuan/HunyuanVideo/blob/4eda9cb44c3be82a6b9c4261897cb6bd3cfb084e/LICENSE.txt); Código fuente visible pero no open source OSI. Incluye exclusiones regionales, política de uso y condiciones para modelos derivados; no es una licencia OSI estándar
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Tencent-Hunyuan/HunyuanVideo/blob/4eda9cb44c3be82a6b9c4261897cb6bd3cfb084e/README.md#L1).

## [Wan2.2](https://github.com/Wan-Video/Wan2.2)

Modelos abiertos de la serie Wan de Alibaba para tareas como texto/imagen a vídeo.

- Categoría: ComfyUI y modelos de vídeo abiertos; Candidato principal.
- Frontera de aplicación: Deben comprobarse por checkpoint los distintos tamaños de modelo, los parámetros activos y las condiciones de licencia.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 2 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/Wan-Video/Wan2.2/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Wan-Video/Wan2.2/blob/1ea34ff48f87168174e12956e200b1d908b1c5ff/README.md#L1).

## [Mochi](https://github.com/genmoai/mochi)

Modelo de generación de vídeo abierto de Genmo con su código de inferencia.

- Categoría: ComfyUI y modelos de vídeo abiertos; Candidato principal.
- Frontera de aplicación: Las restricciones de pesos, VRAM, duración y resolución deben verificarse por versión.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 2 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/genmoai/mochi/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/genmoai/mochi/blob/15c9bad662df1fa3e7b53136423695b286484c08/README.md#L1).

## [Open-Sora](https://github.com/hpcaitech/Open-Sora)

Marco abierto de entrenamiento e inferencia eficiente para generación de vídeo.

- Categoría: ComfyUI y modelos de vídeo abiertos; Candidato principal.
- Frontera de aplicación: Un marco de investigación y los checkpoints del modelo no equivalen a una herramienta de escritorio para montar piezas terminadas.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/hpcaitech/Open-Sora/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/hpcaitech/Open-Sora/blob/7ad6a96a135feb81f755c84fb391818718f6beb2/README.md#L2).

## [Bernini](https://github.com/bytedance/Bernini)

Marco de investigación de generación y edición de vídeo que combina un planificador semántico y un renderizador DiT.

- Categoría: ComfyUI y modelos de vídeo abiertos; Investigación/evaluación.
- Frontera de aplicación: Los benchmarks del artículo no deben mezclarse con la puntuación de mantenimiento de los editores de producto como conclusiones de capacidad.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/bytedance/Bernini/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/bytedance/Bernini/blob/e6c2cf11843470b08491745947abcba9c3c6b079/README.md#L3).

## [HunyuanVideo-I2V](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V)

Marco personalizable de imagen a vídeo basado en HunyuanVideo.

- Categoría: ComfyUI y modelos de vídeo abiertos; Licencia restringida.
- Frontera de aplicación: Separado del proyecto T2V base; deben comprobarse las referencias de entrada y las licencias de los pesos.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Tencent Hunyuan Community License](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V/blob/c8bba70b9517f08d770a9a2a3d1e93cc6d5b7949/LICENSE.txt); Código fuente visible pero no open source OSI. Incluye exclusiones regionales, política de uso y condiciones para modelos derivados; no es una licencia OSI estándar
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V/blob/c8bba70b9517f08d770a9a2a3d1e93cc6d5b7949/README.md#L9).

## [CogVideo / CogVideoX](https://github.com/zai-org/CogVideo)

Modelos abiertos de texto/imagen a vídeo con su código de inferencia.

- Categoría: ComfyUI y modelos de vídeo abiertos; Candidato principal.
- Frontera de aplicación: Un generador de modelos no es un estudio de edición; los pesos, la VRAM, la resolución y la licencia del modelo se comprueban por versión.
- Estado de mantenimiento: Sin commits desde hace más de 365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/zai-org/CogVideo/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/zai-org/CogVideo/blob/7a1af7154511e0ce4e4be8d62faa8c5e5a3532d2/README.md#L1).

## [LiveTalking](https://github.com/lipku/LiveTalking)

Sistema interactivo de streaming en tiempo real que combina varios backends de avatar digital.

- Categoría: Avatares digitales, animación de retratos y sincronización labial; Candidato principal.
- Frontera de aplicación: Licencias, hardware, latencia y resultados varían mucho según el backend.
- Estado de mantenimiento: Con commits en los últimos 90 días; 5 commits en 30 días, 13 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/lipku/LiveTalking/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/lipku/LiveTalking/blob/c7269433a2b6ecebcd9342445d2ecc882c98b0da/README.md#L250).

## [MuseTalk](https://github.com/TMElyralab/MuseTalk)

Modelo de avatar virtual impulsado por audio para sincronización labial en tiempo real de alta calidad.

- Categoría: Avatares digitales, animación de retratos y sincronización labial; Candidato principal.
- Frontera de aplicación: El código, los pesos del modelo, los retratos de entrada y las fronteras del uso comercial deben verificarse por separado.
- Estado de mantenimiento: Con commits en los últimos 90 días; 1 commits en 30 días, 1 en 90 días.
- Licencia: [MIT](https://github.com/TMElyralab/MuseTalk/blob/0a89dec45a0192b824e3cf4daf96c239440c5ed8/LICENSE); Licencia abierta verificada. LICENSE raíz verificada manualmente; los derechos de modelos, datos y material de personas se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/TMElyralab/MuseTalk/blob/0a89dec45a0192b824e3cf4daf96c239440c5ed8/README.md#L1).

## [LivePortrait](https://github.com/KlingAIResearch/LivePortrait)

Marco eficiente de animación de retratos, composición y control de reorientación.

- Categoría: Avatares digitales, animación de retratos y sincronización labial; Candidato principal.
- Frontera de aplicación: El repositorio se ha trasladado a KlingAIResearch; las licencias del material conductor y de las personas son responsabilidad del usuario.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://github.com/KlingAIResearch/LivePortrait/blob/9b294b3d0536135442ea73cb01e6cb3ca7029dd3/LICENSE); Licencia abierta verificada. LICENSE raíz verificada manualmente; los derechos de modelos, datos y retratos se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/KlingAIResearch/LivePortrait/blob/9b294b3d0536135442ea73cb01e6cb3ca7029dd3/readme.md#L1).

## [SadTalker](https://github.com/OpenTalker/SadTalker)

Genera vídeos de cabezas parlantes desde una sola foto y audio.

- Categoría: Avatares digitales, animación de retratos y sincronización labial; Candidato principal.
- Frontera de aplicación: Generar retratos involucra derechos de las personas; las licencias del modelo y de las dependencias se rigen por la descripción actual del repositorio.
- Estado de mantenimiento: Sin commits desde hace más de 365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Apache-2.0](https://github.com/OpenTalker/SadTalker/blob/cd4c0465ae0b54a6f85af57f5c65fec9fe23e7f8/LICENSE); Licencia abierta verificada. LICENSE raíz verificada manualmente; componentes de terceros se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/OpenTalker/SadTalker/blob/cd4c0465ae0b54a6f85af57f5c65fec9fe23e7f8/README.md#L6).

## [Wav2Lip](https://github.com/Rudrabha/Wav2Lip)

Implementación clásica de investigación para sincronización labial audio-vídeo.

- Categoría: Avatares digitales, animación de retratos y sincronización labial; Licencia restringida.
- Frontera de aplicación: El código/pesos abiertos se limitan principalmente a uso personal, de investigación y no comercial; no entra en las recomendaciones habituales de open source para uso comercial.
- Estado de mantenimiento: Sin commits desde hace más de 365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Licencia personal/investigación/no comercial](https://github.com/Rudrabha/Wav2Lip/blob/bac9a81e63ecc153202353372e5724b83d9e6322/README.md#L207); Código fuente visible pero no open source OSI. README prohíbe expresamente el uso comercial del modelo de pesos abiertos
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Rudrabha/Wav2Lip/blob/bac9a81e63ecc153202353372e5724b83d9e6322/README.md#L1).

## [FFmpeg](https://github.com/FFmpeg/FFmpeg)

Cadena de herramientas base para transcodificación, filtros, multiplexado, composición y procesamiento de streams de vídeo.

- Categoría: Descarga, captura, transcodificación y CLIs de material; Infraestructura adyacente.
- Frontera de aplicación: La licencia puede ser LGPL/GPL según las opciones de compilación; gran parte de los proyectos de capa superior solo lo envuelven.
- Estado de mantenimiento: Con commits en los últimos 90 días; 391 commits en 30 días, 3002 en 90 días.
- Licencia: [LGPL-2.1+; GPL-2.0+ si se activan componentes GPL](https://github.com/FFmpeg/FFmpeg/blob/23c454005319dee4a5bcae5c370f75fdeb325230/LICENSE.md); Licencia compuesta/condicional. La licencia final depende de las opciones de compilación y de los componentes enlazados
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/FFmpeg/FFmpeg/blob/23c454005319dee4a5bcae5c370f75fdeb325230/README.md#L1).

## [yt-dlp](https://github.com/yt-dlp/yt-dlp)

Descargador de audio/vídeo por línea de órdenes muy completo, compatible con una gran cantidad de sitios.

- Categoría: Descarga, captura, transcodificación y CLIs de material; Candidato principal.
- Frontera de aplicación: Es la CLI de análisis subyacente de productos como Downvid/VidBee; no ofrece un estudio de edición completo.
- Estado de mantenimiento: Con commits en los últimos 90 días; 38 commits en 30 días, 79 en 90 días.
- Licencia: [Unlicense](https://api.github.com/repos/yt-dlp/yt-dlp/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/yt-dlp/yt-dlp/blob/412e7f0a4b0588fe884a02b344ac66a06538475b/README.md#L16).

## [Streamlink](https://github.com/streamlink/streamlink)

CLI que resuelve streams en directo de internet y los canaliza a un reproductor local.

- Categoría: Descarga, captura, transcodificación y CLIs de material; Candidato principal.
- Frontera de aplicación: Orientado a reproducción/grabación de streams; no equivale a la descarga general de vídeo bajo demanda ni a un editor.
- Estado de mantenimiento: Con commits en los últimos 90 días; 35 commits en 30 días, 155 en 90 días.
- Licencia: [BSD-2-Clause](https://api.github.com/repos/streamlink/streamlink/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/streamlink/streamlink/blob/993f9f1b63bd7a87292e05eda98d461ddc1f62c9/README.md#L13).

## [Downvid](https://github.com/Downvid/downvid)

GUI/WebUI multiplataforma de descarga de vídeo basada en yt-dlp y FFmpeg.

- Categoría: Descarga, captura, transcodificación y CLIs de material; Candidato principal.
- Frontera de aplicación: Principalmente una capa de producto; el análisis de sitios proviene de yt-dlp y su uso debe respetar los términos de la plataforma y las autorizaciones del contenido.
- Estado de mantenimiento: Con commits en los últimos 90 días; 57 commits en 30 días, 354 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/Downvid/downvid/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Downvid/downvid/blob/770bd3e3bf6157f1a2dd0ccb67ea6ce2a4b31807/README.md#L7).

## [VidBee](https://github.com/nexmoe/VidBee)

Descarga medios y ejecuta localmente transcripción, anotación de hablantes, resumen, traducción y conversación sobre el material.

- Categoría: Descarga, captura, transcodificación y CLIs de material; Candidato principal.
- Frontera de aplicación: La descarga la aporta el ecosistema yt-dlp; el resumen con IA puede llamar a modelos remotos elegidos por el usuario.
- Estado de mantenimiento: Con commits en los últimos 90 días; 11 commits en 30 días, 51 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/nexmoe/VidBee/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/nexmoe/VidBee/blob/6082e2604f0c37d942cdb896040aa0c88b5c527f/README.md#L2).

## [cobalt](https://github.com/imputnet/cobalt)

Aplicación web y API autoalojable de descarga de medios, sin anuncios ni rastreo, para sitios como YouTube, TikTok e Instagram.

- Categoría: Descarga, captura, transcodificación y CLIs de material; Candidato principal.
- Frontera de aplicación: El monorepo incluye api, web y documentación, no hay API hospedada pública y debe desplegarse una instancia propia; solo procesa contenido accesible públicamente y las autorizaciones de descarga y redistribución corren por cuenta del usuario; la marca y la mascota tienen copyright propio y no se ceden con la licencia del código.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [AGPL-3.0 (api y resto) + CC-BY-NC-SA-4.0 (web)](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L59); Licencia compuesta/condicional. La parte api y el resto del repositorio son AGPL-3.0; el código web es CC-BY-NC-SA-4.0 con uso comercial prohibido; la marca y la mascota tienen copyright aparte y solo se permite el alojamiento no comercial de instancias sin modificaciones; las licencias de componentes como ffmpeg/libav.js se cuentan aparte
- Verificación funcional: 2026-11-23; [Fuente 1](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L28) · [Fuente 2](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L33) · [Fuente 3](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L45).

## [Lux](https://github.com/iawia002/lux)

CLI de descarga de vídeo multi-sitio escrita en Go.

- Categoría: Descarga, captura, transcodificación y CLIs de material; Candidato principal.
- Frontera de aplicación: La cobertura de análisis y la frecuencia de actualización de sitios son el principal riesgo de mantenimiento.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/iawia002/lux/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/iawia002/lux/blob/dd00f6d258d80b6684a0b9402d7124e5c18ef42f/README.md#L1).

## [you-get](https://github.com/soimort/you-get)

Utilidad Python de línea de órdenes para descargar medios desde páginas web.

- Categoría: Descarga, captura, transcodificación y CLIs de material; Candidato principal.
- Frontera de aplicación: La compatibilidad de sitios y la actividad de mantenimiento deben compararse aparte frente a yt-dlp.
- Estado de mantenimiento: Sin commits desde hace más de 365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [MIT](https://github.com/soimort/you-get/blob/049548f3f3f35e67ba8d3181c71fdc71d11cf260/LICENSE.txt); Licencia abierta verificada. LICENSE.txt raíz verificado manualmente
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/soimort/you-get/blob/049548f3f3f35e67ba8d3181c71fdc71d11cf260/README.md#L1).

## [Aurora / AgentEdit-Bench](https://github.com/yeates/Aurora)

Unifica la edición de vídeo con agentes orientados a uso de herramientas y aporta AgentEdit-Bench.

- Categoría: Evaluación, investigación e índices externos; Investigación/evaluación.
- Frontera de aplicación: AgentEdit-Bench no es directamente comparable horizontalmente con las métricas de VEFX/EditVerse.
- Estado de mantenimiento: Con commits en los últimos 90 días; 4 commits en 30 días, 4 en 90 días.
- Licencia: [MIT](https://api.github.com/repos/yeates/Aurora/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/yeates/Aurora/blob/2599b748c56b29b67b9be352dc091b8ddf72ae8f/README.md#L3).

## [Awesome AI Video for Creators](https://github.com/sasateguh/awesome-ai-video-for-creators)

Organiza herramientas abiertas de edición, subtítulos, troceado, doblaje y vídeo por código según el flujo de trabajo del creador.

- Categoría: Evaluación, investigación e índices externos; Infraestructura adyacente.
- Frontera de aplicación: Las instantáneas externas de estrellas cambian; los datos finales se toman de los repositorios oficiales.
- Estado de mantenimiento: Con commits en los últimos 90 días; 9 commits en 30 días, 15 en 90 días.
- Licencia: [CC0-1.0](https://api.github.com/repos/sasateguh/awesome-ai-video-for-creators/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/sasateguh/awesome-ai-video-for-creators/blob/3b88db72b425a89b751b6ea279532e3ae0a3d6f9/README.md#L1).

## [CutCraft Bench](https://github.com/AlibabaResearch/cut-craft-bench)

Evalúa la ejecución de técnicas de montaje profesional en la generación audiovisual multipiano y aporta un baseline de agentes.

- Categoría: Evaluación, investigación e índices externos; Investigación/evaluación.
- Frontera de aplicación: La coherencia de generación y la editabilidad son métricas distintas; no basta con una puntuación compuesta.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 5 en 90 días.
- Licencia: [Pendiente de verificación](https://github.com/AlibabaResearch/cut-craft-bench/blob/df2b35d63822d0832679fe675a274c33c51f7f75/README.md); Licencia pendiente de verificación. No se encontró licencia en la raíz
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/AlibabaResearch/cut-craft-bench/blob/df2b35d63822d0832679fe675a274c33c51f7f75/README.md#L6).

## [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing)

Cataloga herramientas abiertas de edición de vídeo, Agent Skills y material utilizable.

- Categoría: Evaluación, investigación e índices externos; Infraestructura adyacente.
- Frontera de aplicación: Sirve como línea base de descubrimiento y cobertura; no interviene en juicios de capacidad.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 2 en 90 días.
- Licencia: [CC0-1.0](https://github.com/devanasolver/awesome-video-editing/blob/637c0b63835cccaca2c5362baa7e564fee89a6dc/LICENSE); Licencia abierta verificada. El contenido del catálogo está bajo CC0
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/devanasolver/awesome-video-editing/blob/637c0b63835cccaca2c5362baa7e564fee89a6dc/README.md#L1).

## [Awesome AI Video](https://github.com/thoxakihiko/awesome-ai-video)

Cataloga modelos, herramientas y recursos de texto/imagen a vídeo.

- Categoría: Evaluación, investigación e índices externos; Infraestructura adyacente.
- Frontera de aplicación: Incluye productos comerciales y modelos; no puede verse directamente como una lista de herramientas open source.
- Estado de mantenimiento: Con commits en los últimos 90 días; 0 commits en 30 días, 3 en 90 días.
- Licencia: [CC0-1.0](https://api.github.com/repos/thoxakihiko/awesome-ai-video/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/thoxakihiko/awesome-ai-video/blob/45e9e2bfb3e1e1193e4725ce94bba45d0f342c5a/README.md#L1).

## [VEFX-Bench](https://github.com/Visko-Platform/VEFX-Bench)

Evalúa el seguimiento de instrucciones y la calidad en edición de vídeo de propósito general y efectos visuales.

- Categoría: Evaluación, investigación e índices externos; Investigación/evaluación.
- Frontera de aplicación: Solo es comparable fijando antes las versiones de modelo, datos, reward y APIs comerciales.
- Estado de mantenimiento: Sin commits desde hace 91–365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/Visko-Platform/VEFX-Bench/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Visko-Platform/VEFX-Bench/blob/a82437764d1e2a2068e5e183075f437d5bd0568b/README.md#L9).

## [EditVerse](https://github.com/adobe-research/EditVerse)

Código de investigación y EditVerseBench para generación y edición de imagen/vídeo.

- Categoría: Evaluación, investigación e índices externos; Licencia restringida.
- Frontera de aplicación: El código de investigación y las descargas de datos dependen de fuentes externas; los resultados deben reproducirse con la configuración del artículo.
- Estado de mantenimiento: Sin commits desde hace más de 365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Adobe Research License (archivos parciales)](https://github.com/adobe-research/EditVerse/blob/eeca9ce9f99db2d5c90e775853735025523c9334/LICENSE.md); Código fuente visible pero no open source OSI. La LICENSE solo cubre los archivos expresamente enumerados; los demás no están bajo esa licencia
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/adobe-research/EditVerse/blob/eeca9ce9f99db2d5c90e775853735025523c9334/README.md#L1).

## [Video-Bench](https://github.com/Video-Bench/Video-Bench)

Organiza y ejecuta evaluaciones multidimensionales de modelos de generación de vídeo.

- Categoría: Evaluación, investigación e índices externos; Investigación/evaluación.
- Frontera de aplicación: Un benchmark de generación no dice nada de la calidad de un editor de línea de tiempo ni de un sistema de producción.
- Estado de mantenimiento: Sin commits desde hace más de 365 días; 0 commits en 30 días, 0 en 90 días.
- Licencia: [Apache-2.0](https://api.github.com/repos/Video-Bench/Video-Bench/license); Licencia abierta verificada. Identificada por GitHub licenseInfo; las licencias de pesos de modelos, material, fuentes, dependencias de terceros y servicios gestionados se cuentan aparte
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/Video-Bench/Video-Bench/blob/d40b917c4238011aea27d24f85b1e3bf996715bd/README.md#L1).

## [Palmier Pro](https://github.com/palmier-io/palmier-pro)

Editor de vídeo orientado a IA cuyas versiones antiguas publicaron el código fuente bajo GPLv3.

- Categoría: Versiones históricas y restringidas; Referencia histórica.
- Frontera de aplicación: Los binarios posteriores a v0.7.6 son propietarios y su código fuente actual no es público; solo last-gpl-source debe verse como la versión histórica open source.
- Estado de mantenimiento: Archivado / histórico; 5 commits en 30 días, 11 en 90 días.
- Licencia: [GPL-3.0 (código fuente hasta v0.7.6) / binarios posteriores propietarios](https://github.com/palmier-io/palmier-pro/blob/dfc810b561f1692947eb81bbb689e078923ebb59/README.md#L112); Licencia compuesta/condicional. last-gpl-source y el código anterior a v0.7.6 son GPLv3; los binarios posteriores no tienen código fuente público equivalente
- Verificación funcional: 2026-11-12; [Fuente 1](https://github.com/palmier-io/palmier-pro/blob/dfc810b561f1692947eb81bbb689e078923ebb59/README.md#L2).
