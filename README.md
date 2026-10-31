# Observatorio GovTech · Atheron AI

Ediciones diarias del Observatorio GovTech (https://atheron.ai/observatorio/).

- `data/AAAA-MM-DD.md`: una edición por día. La tarea programada "Observatorio GovTech diario" la escribe cada mañana.
- La web las descarga sola mediante `observatorio/sync.php` (una vez por hora como máximo).

Formato de cada noticia:

```
## Titular
cat: municipio, fondos, tecnologia, competencia   (una o varias)
fuente: https://...
Resumen de una o dos frases.
comercial: uso en ventas
gestion: KPI, objetivo o acción
```
