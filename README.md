# Proyecto OLIVER

Sitio estático: `index.html` es el visor completo (3D, planta, estadística, modelo de bloques). No necesita servidor ni base de datos para funcionar; los datos van dentro de la página.

`data/` contiene la base de datos para quien quiera explotarla:
- `oliver.sqlite`: tablas collar, survey, assay, geology, weathering, topo_points, intervalos_3d, modelo_bloques
- CSV del modelo de bloques e intervalos con coordenadas 3D
- `originales/`: archivos originales del tutorial (menos la foto aérea de 30 MB, que se incluye reducida)

Modelo de bloques: estimación exploratoria IDW, no es un recurso formal.
