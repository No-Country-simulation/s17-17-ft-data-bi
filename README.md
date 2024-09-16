# s17-17-ft-data-bi

## Predicción de Ventas Online

Utilizando la base de datos de Chen y Daqing (2019), se desarrollará un aplicativo de predicción de ventas para el siguiente año (2012), utilizando datos de los dos años anteriores para productos pronosticables. Este análisis se presenta como una propuesta de valor para un cliente del sector retail, y se implementará **Prefect** junto con **MLflow** para el control y versionamiento de los modelos utilizados.

----------------------------------------------------------------------------------------

## Integrantes 

| Nombre                    | Enlace (Link)                    | Rol                 |
|------------               |----------------------------------|---------------------|
| Javier Edgar Esteban      | [https://github.com/JavierEdgarEsteban77](#) / [https://www.linkedin.com/in/jesteban77/](#)      | Data Analyst & BI   |
| Lucel Da Silva            | [https://github.com/luceldasilva](#) / [https://www.linkedin.com/in/luceldasilva/](#)      | Data Scientist              |
| Juan Arango               | [https://github.com/Vagarh](#) / [https://www.linkedin.com/in/juan-felipe-c-8a010b121/](#)      | Machine Learnin       |
| Anderson Cusma            | [https://github.com/anderson2093](#) / [https://www.linkedin.com/in/anderson-cusma-vasquez/](#)      | Team Leader         |

### Enlace a presentación en Power BI

[Enlace a Power Bi - ](<iframe title="Online retail" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiMmUzODUzYTQtMmUzMC00YWZlLTkwMjktZmE4OGY1NmMwYWIzIiwidCI6IjNiNjUzZDBiLWIzYjgtNGE0Yy05YzJlLTVkNDAzNjNkNWI0MSIsImMiOjR9" frameborder="0" allowFullScreen="true"></iframe>)

### Definición del Problema de Negocio

El proyecto tiene como objetivo predecir las ventas del año 2012 utilizando datos históricos de ventas de los años 2010 y 2011. Esto ayudará a optimizar el inventario y mejorar la toma de decisiones estratégicas para un cliente del sector retail. Además, se utilizarán herramientas avanzadas como **Prefect** y **MLflow** para asegurar el control de versiones y un flujo de trabajo robusto en el desarrollo del modelo de predicción.

### Objetivo Principal
Desarrollar y evaluar un sistema de predicción de ventas basado en datos históricos para productos del sector retail. El sistema permitirá optimizar la gestión de inventarios y mejorar la planificación de ventas.

### Problema a Resolver
Identificar y predecir las ventas futuras de productos específicos para el año 2012, utilizando datos históricos de ventas. Este sistema ayudará a mejorar la eficiencia operativa del cliente, proporcionando información precisa sobre la demanda futura.

### Habilidades y Herramientas Necesarias
- 💻 **Lenguajes de Programación:**
  - 🐍 Python: Para el análisis y desarrollo de modelos.
  
- 📚 **Bibliotecas:**
  - 📊 Pandas: Para la manipulación y análisis de datos estructurados.
  - 🔢 NumPy: Para el manejo de arreglos numéricos y operaciones matemáticas.
  - 🤖 Scikit-Learn: Para la implementación de algoritmos de machine learning.
  - 📈 Matplotlib y Seaborn: Para la visualización de datos y generación de gráficos.

- 🔄 **Versionamiento de Modelos:**
  - ⚙️ Prefect: Para la orquestación de flujos de trabajo y control de tareas.
  - 🗂️ MLflow: Para el versionamiento y gestión del ciclo de vida de los modelos.

- 🗄️ **Bases de Datos:**
  - 📝 SQL: Para la consulta y manipulación de datos almacenados en bases de datos relacionales.

- 📐 **Estadísticas:**
  - 📊 Fundamentos de estadística y machine learning: Para el análisis e interpretación de los datos y modelos predictivos.

- 📊 **Herramientas de Visualización:**
  - 📊 Power BI: Para la creación de informes visuales ejecutivos y presentaciones de datos.


### Entregables del Proyecto
1. ✅ Informes de Análisis Exploratorio de Datos (EDA).
2. ✅ Modelos de Machine Learning entrenados y evaluados.
3. ✅ Métricas de evaluación como RMSE, MSE, R².
4. ✅ Reportes de Importancia de Características (SHAP Values).
5. ✅ Documentación y presentación ejecutiva.
6. ✅ Dashboard de ventas y predicciones.

### Contexto

El sector retail enfrenta el reto constante de optimizar su inventario y satisfacer la demanda sin incurrir en sobrecostos. Este proyecto busca desarrollar un modelo que prediga con precisión las ventas del próximo año, ayudando al cliente a mejorar sus decisiones estratégicas.

### Objetivos y Métricas de Desempeño

#### Objetivo Principal
**Desarrollar un modelo de predicción de ventas:**

El modelo se entrenará usando técnicas de machine learning como Random Forest y XGBoost, y las métricas clave serán:
- **Error Cuadrático Medio (MSE):** Para medir la precisión del modelo.
- **Raíz del Error Cuadrático Medio (RMSE):** Para interpretar el error en la misma escala que las ventas.
- **R² (Coeficiente de Determinación):** Para medir qué tan bien el modelo explica la variabilidad de las ventas.

#### Restricciones

- **Tiempo:** El proyecto debe completarse en 3 semanas.
- **Presupuesto:** No se asigna presupuesto adicional.

### Stakeholders
- **Pablo Robles:** Gerente de Facility, Principal interesado (High Power, High Interest).

## Requerimientos Funcionales

### Funciones Específicas para el Analista de Datos
1. 🛠️ **Ingesta y Preprocesamiento de Datos:**
   - 📥 Cargar y limpiar el conjunto de datos.
   - 🧹 Manejar valores faltantes y eliminar datos duplicados.

2. 🔍 **Análisis Exploratorio de Datos (EDA):**
   - 📊 Crear visualizaciones para identificar patrones de ventas.
   - 🧮 Calcular estadísticas descriptivas.

3. 🤖 **Modelado y Entrenamiento:**
   - 🎯 Seleccionar las características más relevantes para el modelo.
   - 🏋️ Entrenar y validar modelos de machine learning.

4. 📊 **Evaluación del Modelo:**
   - 📏 Utilizar métricas como precisión, recall, y AUC-ROC.
   - 🔄 Generar matrices de confusión para medir el rendimiento.

5. 🔍 **Interpretabilidad:**
   - 🧠 Implementar SHAP Values para interpretar la importancia de las características.

6. 📄 **Documentación:**
   - 📝 Mantener una documentación clara y completa.
   - 💼 Presentar informes ejecutivos con visualizaciones de resultados.


## Estructura del Proyecto

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

# Reproducir el proyecto
clona el proyecto y para generar un ambiente de desarrollo similar usa el siguiente comando:
```batch
pipenv install --ignore-pipfile
```

# Referencias
Chen, Daqing (2019).Online Retail II. UCI Machine Learning Repository. [doi.org/10.24432/C5CG6D](https://doi.org/10.24432/C5CG6D).
