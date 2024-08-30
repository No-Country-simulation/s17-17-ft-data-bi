# s17-17-ft-data-bi


# Predicción de ventas Online

Utilizando la base de datos de Chen y Daqing (2019) realizaremos un aplicativo de predicción de ventas para el siguiente año (2012), con información de dos años anteriores en productos pronosticables. Esto como propuesta de valor ante un cliente del sector retail. Además, utilizaremos Prefect con MLflow para el control del versionamiento de los modelos a escoger. 

# Estructura del Proyecto

El proyecto seguirá la siguiente estructura:

```
test/
utils/
src/
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
├── models/
├── notebooks/
├── pipelines/
```

- `data` contendrá los datos utilizados en el proyecto, divididos en subcarpetas `raw` y `processed` para almacenar los datos originales y los datos procesados.
- `models` contendrá los modelos de predicción desarrollados iniciales.
- `notebooks` contendrá los notebooks de Jupyter utilizados para el análisis y desarrollo del proyecto.
- `pipelines` contendrá los pipelines o scripts para el desarrollo del proyecto.

Esta estructura permitirá mantener un orden y organización adecuados en el proyecto, facilitando el desarrollo, mantenimiento y colaboración con otros miembros del equipo.


# Referencias
Chen, Daqing (2019).Online Retail II. UCI Machine Learning Repository. [doi.org/10.24432/C5CG6D](https://doi.org/10.24432/C5CG6D).
