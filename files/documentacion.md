# Documentación del Dataset de Películas de Marvel

Este documento describe las columnas contenidas en el archivo `Marvel_Movies_Dataset.csv`, que recopila información sobre las películas de Marvel, incluyendo directores, fechas de estreno, valoraciones en diversas plataformas y datos financieros.

## Descripción de las Columnas

| Columna | Descripción | Formato/Rango |
| :--- | :--- | :--- |
| **Index** | Identificador único numérico para cada fila. | Entero |
| **Title** | El título oficial de la película. | Texto |
| **Director (1)** | Director principal del filme. | Texto |
| **Director (2)** | Segundo director, en caso de haberlo (registra 'nan' si no aplica). | Texto / 'nan' |
| **Release Date (DD-MM-YYYY)** | Fecha oficial de estreno (aunque el encabezado indica DD-MM-YYYY, los datos siguen el formato YYYY-MM-DD). | Fecha/Hora |
| **IMDb (scored out of 10)** | Puntuación promedio de los usuarios en IMDb. | Decimal (0-10) |
| **IMDB Metascore (scored out of 100)** | Puntuación crítica de Metacritic reflejada en IMDb. | Entero (0-100) |
| **Rotten Tomatoes - Critics (scored out of 100%)** | Porcentaje de reseñas positivas de críticos profesionales. | Porcentaje (0-100) |
| **Rotten Tomatoes - Audience (scored out of 100%)** | Porcentaje de reseñas positivas de la audiencia. | Porcentaje (0-100) |
| **Letterboxd (scored out of 5)** | Puntuación promedio en la plataforma Letterboxd. | Decimal (0-5) |
| **CinemaScore (grades A+ to F)** | Calificación basada en encuestas a la audiencia tras el estreno. | Letra (A+ a F) |
| **Budget (in million $)** | Presupuesto de producción estimado en millones de dólares estadounidenses. | Decimal |
| **Domestic Gross (in million $)** | Recaudación en taquilla doméstica (EE.UU. y Canadá) en millones de dólares. | Decimal |
| **Worldwide Gross (in million $)** | Recaudación total en taquilla a nivel mundial en millones de dólares. | Decimal |

## Notas adicionales
- Las cifras financieras (Presupuesto y Recaudación) están expresadas en **millones de USD**.
- Los valores 'nan' en `Director (2)` indican que la película tuvo un solo director principal.
