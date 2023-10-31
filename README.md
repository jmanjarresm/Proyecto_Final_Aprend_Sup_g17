<h1 align="center">
  <a href="https://github.com/dfgomezc/aribnb_optimize_prices">
    <!-- Please provide path to your logo here -->
    <img src="docs/images/logo.png" alt="Centro de Investigación de Crímenes contra poblaciones vulnerables" width="720" height="480">
  </a>
</h1>

<div align="center">
  ¿Cómo podemos predecir el precio de alquiler, teniendo en cuenta las características específicas de los alojamientos, utilizando análisis de datos históricos y técnicas de aprendizaje automático, para ayudar a los anfitriones de Airbnb a establecer precios competitivos y a su vez generar mayores ingresos?  
  <br />
  <a href="#acerca-de"><strong>Explorar gráficas »</strong></a>
  <br />
</div>

<div align="center">
<br />

[![Project license](https://img.shields.io/github/license/jmanjarresm/Proyecto_Final_Aprend_Sup_g17.svg?style=flat-square)](LICENSE)

[![Pull Requests welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg?style=flat-square)](https://github.com/dfgomezc/aribnb_optimize_prices/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
[![Propuesta Inicial](https://img.shields.io/badge/Propuesta-Inicial-green)](https://github.com/jmanjarresm)

</div>

<details open="open">
<summary>Tabla de Contenido</summary>

- [Acerca de](#acerca-de)
  - [Creado con](#creado-con)
- [Empezando](#empezando)
  - [Prerrequisitos](#prerrequisitos)
- [Usos](#usos)
- [Hoja de Ruta](#hoja-de-ruta)
- [Soporte](#soporte)
- [Contribuciones](#contribuciones)
- [Autores](#autores)
- [Licencia](#licencia)
- [Agradecimientos](#agradecimientos)

</details>

---

## Acerca de

<table><tr><td>

Este proyecto busca ayudar a determinar que precio deben dar los anfitriones a su alojamiento en Airbnb con ubicación en New York para generar los mayores ingresos posibles. Airbnb es una startup que inicio su funcionamiento en 2008 en San Francisco, después de cambios en su servicio y de inversionistas, los servicios de alquilar espacios para hospedaje para quienes lo necesiten en 190 países en el mundo. La startup no tienen viviendas a su nombre es un intermediario entre los dueños y la personas que necesitan el servicio. Los precios de alquiler dependen de muchos factores entre los que se encuentran: ubicación, espacio, baños, beneficios para las personas que lo utilizaran, entre otros. De acuerdo lo anterior se encuentra la necesidad crucial de predecir el precio de alquiler adecuado en Airbnb, no solo para nuevos anfitriones, sino también para aquellos que ya ofrecen sus propiedades en la plataforma. La fijación del precio correcto es esencial para el éxito de una oferta en este mercado de alquileres. Los propietarios enfrentan el desafío de establecer un precio óptimo que afecta directamente su rentabilidad y la atracción de inquilinos. Se empleará análisis de datos históricos y técnicas de aprendizaje automático para desarrollar un modelo de predicción de precios que tome en cuenta características de los alojamientos de acuerdo con lo encontrado La herramienta resultante proporcionará recomendaciones sólidas para establecer precios competitivos y justos, permitiendo a los anfitriones atraer huéspedes y a los consumidores establecer un presupuesto confiable para su estancia en la ciudad. Esto contribuirá al crecimiento sostenible del mercado de Airbnb y al bienestar de ambas partes.  

<details>
<summary>Resumen gráfico de la información disponible</summary>
<br>

|                               Historico Número de Homicidios                               |                               Relación Domicilios por Grupo de Edad                              |
| :-------------------------------------------------------------------: | :--------------------------------------------------------------------: |
| <img src="docs/images/Total de Homicidios a lo largo del Tiempo.png" title="Historico Número de Homicidios" width="100%"> | <img src="docs/images/Distribución del Número de Homicidios por Grupo de Edad.png" title="Relación Domicilios por Grupo de Edad" width="100%"> |

</details>

</td></tr></table>

### Creado con

En este proyecto, se ha realizado un análisis de datos y Random Forest utilizando Python como herramienta principal.

#### Uso de Python

Para el desarrollo del proyecto se da uso a Python para todo el proceso de análisis de datos. Python nos proporciona una amplia gama de bibliotecas y herramientas para realizar análisis de datos de manera efectiva, lo que incluye la limpieza de datos, la visualización de resultados y la implementación de algoritmos de análisis de puntos calientes.

#### Random Forest

El algoritmo de Random Forest fue elegido debido a su capacidad para manejar grandes conjuntos de datos y variables predictoras, así como su habilidad para gestionar relaciones complejas entre las características del lugar y los precios de alojamiento. Su capacidad para generar modelos predictivos precisos y su resistencia al sobreajuste hacen de este algoritmo una opción ideal para el proyecto, permitiendo a los anfitriones establecer precios competitivos basados en las características específicas de su propiedad.

## Empezando

### Prerrequisitos

Para trabajar en este proyecto y ejecutar los análisis de datos y puntos calientes, se deben cumplir con los siguientes prerrequisitos:

Python: Tener Python instalado en el sistema. Este proyecto se ha desarrollado utilizando Python 3. Se puede descargar Python desde python.org.

Bibliotecas de Python: Instalar las bibliotecas de Python necesarias utilizando el gestor de paquetes pip. Se debe instalar ejecutando el siguiente comando en la terminal:

pip install pandas matplotlib seaborn scikit-learn

Estas bibliotecas son esenciales para el análisis de datos, visualización y análisis de puntos calientes en Python.

## Usos

Este proyecto se podrá usar como fuente de toma de decisiones observando la información desarrollada en [Proyecto](https://github.com/dfgomezc/aribnb_optimize_prices/blob/main/DOCS/Mejorando_la_Competitividad_en_Airbnb-_Optimizaci%C3%B3n_de_Precios_de_Alquiler_en_Nueva_York_V4.pdf)
En el que se podrá ver los resultados encontrados como consecuencia del análisis de puntos calientes realizado.

## Autores

El Repositorio fue creado por [Diego Gomez](https://github.com/dfgomezc).

El Proyecto fue realizado por:
- Mayra Neisa
- [Juan Felipe Manjarres](https://github.com/jmanjarresm)
- Lina Marcela Ladino

Para ver todos los autores ver la [página de contribuciones](https://github.com/dfgomezc/aribnb_optimize_prices/graphs/contributors).


## Licencia

Este proyecto esta licenciado bajo **MIT license**.

Ver [LICENCIA](LICENSE) para más información.

## Agradecimientos

Se agradece el apoyo de la Universidad de los Andes en el desarrollo de este proyecto
