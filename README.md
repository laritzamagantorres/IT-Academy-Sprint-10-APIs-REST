# IT Academy — Sprint 10: APIs REST

Práctica de consulta e interacción con APIs públicas mediante Python y la biblioteca `requests`, realizada desde un Jupyter Notebook.

## Objetivos

- Realizar peticiones HTTP y consultar sus códigos de estado.
- Interpretar respuestas JSON y acceder a sus datos.
- Utilizar endpoints y parámetros según la documentación de cada API.
- Convertir los resultados en DataFrames de pandas y exportarlos a CSV.

## Contenido

### Nivel 1 — JSONPlaceholder

- Consultas GET de publicaciones, usuarios y tareas.
- Recuento de elementos y comprobación de códigos de estado.
- Consulta de una publicación inexistente para obtener un error 404.
- Peticiones POST, PATCH y DELETE.

JSONPlaceholder simula las operaciones de creación, modificación y eliminación sin guardar los cambios.

### Nivel 2 — Open-Meteo

- Documentación de endpoints y parámetros.
- Búsqueda de Barcelona y obtención de sus coordenadas.
- Consulta de la previsión de lluvia acumulada diaria para 7 días.
- Conversión de la respuesta en un DataFrame.

Los valores corresponden a la previsión disponible en el momento de ejecutar la consulta y pueden cambiar.

### Nivel 3 — Open Data Barcelona

- Búsqueda de conjuntos de datos mediante `package_search`.
- Consulta de la ficha mediante `package_show`.
- Selección del recurso `2026_MeteoCat_Detall_Estacions.csv`.
- Recuperación de 100 registros mediante `datastore_search`.
- Conversión a DataFrame y exportación a CSV.

La extracción contiene diferentes variables meteorológicas. Su interpretación requiere consultar sus definiciones y unidades.

## Archivos

- [Notebook del Sprint 10](Sprint_10.ipynb): ejercicios, explicaciones y resultados.
- [Datos meteorológicos exportados](datos_meteorologicos_2026.csv): los 100 registros recuperados en el nivel 3.

## Herramientas

Python, Requests, pandas, Jupyter Notebook y Visual Studio Code.
