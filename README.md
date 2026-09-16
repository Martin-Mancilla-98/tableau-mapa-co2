# Mapa de emisiones de CO₂ per cápita por país y año — Tableau

Libro de Tableau (`CO2_map/CO2_map_year.twb`) con un **mapa de emisiones de CO₂ per cápita
(toneladas métricas) por país**, con un **filtro por año**. La fuente combina tres datasets
(emisiones, PBI y población) unidos por país y año. Práctica del curso *Fundamentos de
Visualización con Tableau* de la Universidad Austral.

## Contenido

| Archivo | Qué es |
|---|---|
| `CO2_map/CO2_map_year.twb` | El libro de Tableau (una hoja: el mapa con el filtro de año) |
| `CO2_map/CO2-Dataset.xlsx` | Emisiones de CO₂ por país y año |
| `CO2_map/GDP-Dataset.xlsx` | PBI por país y año |
| `CO2_map/Population-Dataset.xlsx` | Población por país y año |
| `CO2_map/Dataset.xlsx` | Tabla combinada ("CO2 Data Cleaned") que usa el libro |

## Cómo verlo

Abrir el `.twb` con Tableau Desktop o Tableau Public (gratis) con los `.xlsx` en la misma carpeta:
el libro referencia los datasets por ruta relativa.

## Qué muestra

Dónde se emite más CO₂ **por persona** y cómo cambia con los años: el mapa colorea cada país por
su valor per cápita y el filtro de año permite recorrer la serie. Los datasets de PBI y población
están unidos a la fuente para poder extender el análisis (emisiones por unidad de PBI, por ejemplo).
