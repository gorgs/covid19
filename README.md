# covid19
Proyecto para la publicación de datos en formato .CSV y .JSON de la pandemia COVID-19 (coronavirus)

Los datos son extraídos del gobierno de Baja California diaramente del sitio [Gobierno de Baja California](https://www.facebook.com/BC.Gobierno).

### Municipios censados:
- Mexicali
- Tijuana
- Rosarito
- Ensenada
- Tecate
- San Quintin

Esta información es procesada y puesta en formato .CSV y .JSON para ser utilizada por cualquier persona que quiera analizarla. Podrás buscar información histórica en la carpeta **/datos**. Los datos inician el 1 de abril del 2020 hasta la fecha.

Puedes hacer uso de **covid19-bc-latest.csv** y **covid19-bc-latest.json**, estos contienen la información más reciente.

## Estructura
- ID
- Estado
- Estado-slug
- Municipio
- Municipio-slug
- Población
- Fecha
- c-negativos (casos negativos)
- c-sospechosos (casos sospechosos)
- c-confirmados (casos confirmados)
- c-defunciones (casos defunciones)
- d-negativos (diferencia 24hrs negativos)
- d-sospechosos (diferencia 24hrs sospechosos)
- d-confirmados (diferencia 24hrs confirmados)
- d-defunciones (diferencia 24hrs defunciones)
