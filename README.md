
# Análisis del Despacho de Energía Eléctrica en Colombia

Este proyecto realiza un análisis estadístico del despacho de energía eléctrica en Colombia durante el año 2024. Utiliza datos históricos y herramientas estadísticas para explorar el comportamiento del sistema eléctrico colombiano, con énfasis en las variables operativas clave del mercado mayorista.


## Estructura del Proyecto

- `analisis-despacho-energia.Rmd`: Documento fuente en R Markdown que contiene el código, análisis y visualizaciones.
- `analisis-despacho-energia.html`: Documento HTML generado a partir del Rmd, que contiene el informe final con todo el análisis.
- `data/`: Carpeta que contiene los archivos de datos utilizados. Incluye un archivo Excel con información del despacho.

## Contenido del Análisis

- Exploración y limpieza de datos históricos de despacho.
- Visualización de series temporales de generación y demanda.
- Análisis de participación de tecnologías (hidráulica, térmica, etc.).
- Estadísticas descriptivas por agente generador.
- Estimaciones y visualización de precios y energía despachada.
- Análisis gráfico interactivo y validación de supuestos estadísticos.

## Principales librerías utilizadas

- `openxlsx`
- `tidyverse`
- `janitor`
- `flextable`
- `kableExtra`
- `scales`
- `ggplot2`
- `plotly`
- `dplyr`
- `forcats`
- `nortest`

## Cómo usar este proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/agarcia9608/despacho-energia-colombia-con-R
   ```

2. Abre el archivo `analisis-despacho-energia.Rmd` con RStudio.

3. Asegúrate de tener las dependencias instaladas. Puedes ejecutar:
   ```r
   install.packages(c(
       "openxlsx", "tidyverse", "janitor", "flextable", "kableExtra",
       "scales", "ggplot2", "plotly", "dplyr", "forcats", "nortest"
   ))
   ```

4. Ejecuta el documento (`Knit`) para generar el HTML actualizado con los datos.

## Requisitos

- R >= 4.0.0
- RStudio
- Paquetes listados anteriormente

## 📬 Contacto
Puedes encontrar más información sobre mi trabajo en:
- [LinkedIn](https://www.linkedin.com/in/ing-abraham-garcia/)
- [GitHub](https://github.com/agarcia9608/)
