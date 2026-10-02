# IO2 — TP3a: Entrega

Investigación de Operaciones II (11.87) — RedBaires S.A. El informe (`.docx`) se entrega
como archivo separado; esta carpeta tiene el resto de lo que lo respalda.

## Contenido

- **`modelo_logico_simulador.drawio`** — modelo lógico del simulador (diagrama de flujo
  del motor de eventos discretos). El informe lo referencia con un enlace a
  `viewer.diagrams.net`; este es el archivo fuente editable.
- **`notebooks/`** — los 3 notebooks que sustentan el informe, documentados y
  ejecutados sin errores:
  - `limpieza_datos_TP3.ipynb` — limpieza del dataset crudo (7 pasos).
  - `ajuste_distribuciones_TP3.ipynb` — ajuste de distribuciones a cada variable
    aleatoria, incluido el GLM Binomial Negativa de `multiplicador_base`.
  - `diagrama_relaciones_TP3.ipynb` — genera los 2 diagramas de relación/influencia
    entre variables que están en el Anexo del informe.
- **`Datos/`** — datasets usados por los notebooks (crudo, limpio, parámetros
  económicos, y los dos CSV de resultados de ajuste que producen los notebooks).
- **`figuras/`** — imágenes generadas por los notebooks/proceso, embebidas en el
  informe.
- **`prompts/`** — el enunciado del trabajo (memo de RedBaires), el template de
  informe de la cátedra, y la rúbrica de evaluación.

## Cómo correr los notebooks

Mantener la estructura de carpetas tal cual (`notebooks/` y `Datos/` como hermanas) —
usan rutas relativas `../Datos/...`.
