# Guía de contribución

Se aceptan de buen grado nuevos proyectos, correcciones de categoría, de frontera funcional o de licencia.

1. Modifica `data/projects.json`; no edites directamente las tablas generadas.
2. Aporta el repositorio canonical de GitHub, una categoría principal, el propósito, las limitaciones y evidencia del README en un commit fijo.
3. Deja claro si es un estudio, un sistema de agentes, una Skill/MCP, motion por código, un modelo generativo, un avatar digital, una CLI o un benchmark.
4. No presentes roadmaps, demos ni benchmarks de los autores como conclusiones de pruebas independientes.
5. Verifica por separado el código, los pesos del modelo, el material, las fuentes, las APIs de terceros y la licencia del contenido de salida.
6. Los proyectos de descarga/captura deben conservar las fronteras de los términos de la plataforma y de las autorizaciones del contenido.
7. Tras añadir un proyecto, ejecuta:

```sh
python scripts/refresh_metrics.py
python scripts/build.py
python -m unittest discover -s tests -v
python scripts/build.py --check
```

No envíes claves de API, vídeos privados, material sin autorización, direcciones internas de Content Factory ni datos personales. Los registros de cambios van en `record/YYYY-MM-DD-tema-en-chino.md` (los registros de auditoría se conservan en chino, tal como se redactaron en el momento de la verificación).

## Archivos multilingües

- `data/projects.json` guarda el texto revisado canónico en chino; un dato se corrige una sola vez ahí.
- Los demás idiomas leen `locales/<lang>/entries.json` (`description`, `boundary`, `license_label`, `license_note`, y `name` cuando el nombre canónico lleva caracteres chinos) y `locales/<lang>/ui.json`. `zh` recurre directamente a `data/projects.json`, así que no existe `locales/zh/entries.json`.
- Al añadir un proyecto o reformular su propósito, su límite o su veredicto de licencia, actualiza los cuatro idiomas en la misma pull request; si no, fallan `python scripts/build.py --check` y `python -m unittest discover -s tests -v`.
- La prosa fija: el inglés vive en `docs/` y `CONTRIBUTING.md` de la raíz; los demás idiomas usan las mismas rutas relativas bajo `locales/<lang>/`. Los enlaces de un espejo se resuelven desde el directorio del propio archivo: en `locales/<lang>/docs/research.md` hay que escribir `../../../research/…`, y en `locales/<lang>/CONTRIBUTING.md`, `../../…`; `docs/readme-intro.md` es la excepción porque se inserta en el README y se resuelve desde la raíz del idioma.
- Los archivos generados (`README.md`, `docs/projects.md`, `docs/rankings.md`, `data/rankings.csv` y sus espejos) nunca se editan a mano; ejecuta `python scripts/build.py`.
