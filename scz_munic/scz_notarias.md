# Capa de Notarías – Santa Cruz de la Sierra (Bolivia)

**Descripción:** Capa de puntos con la ubicación aproximada de las notarías de fe pública del municipio de Santa Cruz de la Sierra. Cada registro incluye número oficial, nombre/titular, dirección postal y coordenadas (WGS84).

**Cobertura:** Municipio de Santa Cruz de la Sierra, Departamento de Santa Cruz, Bolivia.  
**CRS:** WGS84 (EPSG:4326)  
**Fecha de lista oficial:** 18 de octubre de 2025.  
**Fecha de elaboración:** octubre de 2025.

## Archivos
- `scz_notarias.csv` — datos tabulares con columnas: `num_notaria`, `nombre_notaria`, `direccion`, `lat`, `lon`.
- `scz_notarias.geojson` — capa geográfica (GeoJSON) lista para cargar en QGIS, ArcGIS, Kepler.gl, Leaflet/Mapbox u otros.

## Metodología (resumen)
1. La referencia (número, nombre/titular y dirección) proviene de listados oficiales del sistema notarial y del municipio.  
2. Las coordenadas se construyeron por integración jerárquica de tres fuentes: ubicaciones verificadas en Google Maps; geocodificación de direcciones; y datos abiertos de OpenStreetMap, en ese orden de prioridad.  
3. Se efectuó control visual y normalización a WGS84 (grados decimales).

## Limitaciones
- La precisión puede variar entre pocos metros (ubicaciones verificadas) y hasta una cuadra (geocodificación aproximada).  
- Este dataset es informativo y no sustituye la información oficial del sistema notarial.

## Licencia
Sugerida: **CC BY 4.0** (Atribución).

## Créditos
Elaboración propia con base en fuentes oficiales y datos abiertos. Contribuciones y correcciones son bienvenidas mediante *issues* y *pull requests*.
