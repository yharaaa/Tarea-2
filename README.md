# Tarea 2 - Mapas 

Este repositorio contiene un análisis espacial de tres capas geográficas de Colombia: ríos, aeropuertos y divisiones administrativas. Se incluye el código en Python para generar un mapa con las tres capas superpuestas y las instrucciones para reproducir el análisis.

### Fuentes de datos
- **Divisiones administrativas (Departamentos de Colombia)**: [ArcGIS Hub - Departamentos de Colombia](https://hub.arcgis.com/datasets/c4715bdc65b34778982dcbf8498d1396/explore?location=4.193000%2C-73.499916%2C4.62)
- **Aeropuertos en Colombia**: [OurAirports - Aeropuertos de Colombia](https://ourairports.com/countries/CO/)
- **Peajes en Colombia**: [ArcGIS Hub - Hidrografía de Colombia](https://hub.arcgis.com/datasets/c4715bdc65b34778982dcbf8498d1396/explore?location=4.311710%2C-71.744268%2C5.58)

## Diccionario de Datos

1. **Divisiones Administrativas (Departamentos de Colombia)**:
   - `DEPTO`: Nombre del departamento.
   - `ShapeSTArea`: Área del departamento.
   - `ShapeSTLength`: Longitud del perímetro del departamento.

2. **Aeropuertos en Colombia**: Puntos color verde
   - `latitude_deg`: Latitud del aeropuerto.
   - `longitude_deg`: Longitud del aeropuerto.
   - `elevation_ft`: Altitud del aeropuerto en pies.

3. **Ríos en Colombia**: lineas azules
   - `geometry`: Geometría de las líneas azules que representan los ríos.

4. **Peajes en colombia**: puntos color celeste 

## Gráfico del mapa

![mapa](https://github.com/user-attachments/assets/572ff89b-b25c-4979-9d6d-047670444060)

## Enlace al mapa publicado

Puedes ver el mapa de las divisiones administrativas, los ríos y los aeropuertos en Colombia en el siguiente enlace: [Mapa Publicado](https://yharaaa.github.io/Tarea-2/).


