# Olist Analytics

Proyecto de analítica de datos sobre el dataset de e-commerce de Olist. El repositorio organiza el flujo de datos de extremo a extremo: modelado y consultas en SQL, infraestructura y procesamiento en AWS, visualización en Power BI y documentación de apoyo.

## Estructura del repositorio

```
olist-analytics/
├── sql/        # Scripts SQL: modelado, transformaciones y consultas analíticas
├── aws/        # Infraestructura y servicios AWS (S3, Glue, Athena, Redshift, etc.)
├── powerbi/    # Reportes y dashboards de Power BI (.pbix) y recursos relacionados
├── docs/       # Documentación: diccionario de datos, diagramas y notas del proyecto
└── README.md   # Este archivo
```

## Carpetas

- **`sql/`** — Consultas y scripts SQL para crear tablas, transformar datos y generar métricas analíticas.
- **`aws/`** — Definiciones de infraestructura y configuración de los servicios de AWS usados en el pipeline de datos.
- **`powerbi/`** — Archivos de Power BI con los dashboards e informes, además de recursos auxiliares.
- **`docs/`** — Documentación del proyecto: arquitectura, diccionario de datos, decisiones de diseño y guías.

## Primeros pasos

1. Clona el repositorio.
2. Revisa la documentación en `docs/` para entender el modelo de datos.
3. Ejecuta los scripts de `sql/` contra tu base de datos o motor de consultas.
4. Abre los reportes de `powerbi/` con Power BI Desktop.

## Licencia

Por definir.
