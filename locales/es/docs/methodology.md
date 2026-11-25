# Metodología de ordenación y limitaciones

Las métricas de GitHub se recogen por lotes en un momento UTC fijo mediante la API GraphQL. La instantánea solo se reemplaza de forma atómica si todos los lotes tienen éxito. La única excepción es un repositorio que GitHub ya no resuelve (renombrado o borrado): su registro anterior se conserva y se marca con `missing_upstream` y una marca de tiempo `missing_since`, de modo que un proyecto desaparecido no rompe la actualización diaria. Los límites de tasa, los fallos de transporte y las respuestas parciales de GraphQL siguen interrumpiendo la ejecución y manteniendo intacta la instantánea previa.

- stars: proxy de atención de la comunidad.
- Commits a 30/90 días: conteo del historial completo de la rama por defecto, incluidos commits de documentación, merges y bots.
- Último commit: hora del HEAD de la rama por defecto; no se suplanta con pushes de otras ramas ni con cambios de metadatos del repositorio.
- La identificación de releases, archivado y licencia se guarda aparte para auditoría.

Primero se estratifica en cuatro capas — activo en los últimos 90 días, sin commits desde hace 91–365 días, sin commits desde hace más de 365 días, archivado/histórico — y luego se calcula:

```text
P = min(1, ln(1 + stars) / ln(1 + 100000))
A = min(1, ln(1 + commits_90d) / ln(1 + 500))
R = exp(-days_since_default_branch_HEAD / 90)
Puntuación de mantenimiento = 100 × (0.40P + 0.35A + 0.25R)
```

La puntuación de mantenimiento no es una puntuación de calidad del montaje, de gusto estético de edición, de capacidad de los modelos generativos, de velocidad, de VRAM, de coste ni de seguridad de derechos. Los monorepos y los commits de bots pueden inflar la actividad, y un repositorio de modelo estable puede tener pocos commits durante mucho tiempo.

La identificación automática de licencias y la revisión manual están separadas. Remotion, Hunyuan, Wav2Lip, Palmier, FFmpeg, etc. usan licencias condicionales, compuestas o dependientes de la versión; los pesos de modelos, el material, las fuentes y los servicios de terceros pueden tener términos adicionales.

Una evaluación unificada de capacidades debe fijar material, guion, versión del modelo, presupuesto y hardware, y registrar por separado la tasa de éxito de generación, la coherencia entre planos, subtítulos/sincronización labial, la editabilidad de la línea de tiempo, el volumen de revisión manual, el tiempo de renderizado, la VRAM, el coste de API y la licencia de la salida.
