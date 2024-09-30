# ProyectoFraudeSegurosVehiculos

# Modelos Predictivos con Árboles de Decisión para la Detección de Fraudes en Reclamaciones de Seguros de Vehículos

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar modelos predictivos basados en árboles de decisión para detectar fraudes en reclamaciones de seguros de Vehículos. Utilizamos diferentes técnicas de Machine Learning con un enfoque en la construcción de modelos interpretables, con el fin de identificar patrones en los datos que puedan indicar actividades fraudulentas.

## Integrantes

- **Johanna Barzola; johanna.barzola.sarm@gmail.com**
- **Nancy Buestán; nancy.buestan@gmail.com**

## Estructura del Proyecto

El proyecto consta de las siguientes fases:

1. **Análisis Exploratorio de los Datos (EDA)**: En esta fase, se realiza un análisis exhaustivo de los datos para identificar tendencias, anomalías y correlaciones relevantes. Se visualizan distribuciones y relaciones clave entre las variables.
   
2. **Preprocesamiento de Datos**: Aquí se lleva a cabo la limpieza y transformación de los datos, que incluye:
   - Codificación de variables categóricas.
   - Escalamiento de variables numéricas (opcional).
   - Tratamiento de valores faltantes.
   
3. **Construcción de Features**: Creación de nuevas variables a partir de las existentes para mejorar la capacidad predictiva del modelo.

4. **Entrenamiento del Modelo**: Se entrena un modelo de árbol de decisión con ajustes de hiperparámetros utilizando técnicas como GridSearchCV o RandomizedSearchCV para optimizar el rendimiento.

5. **Interpretabilidad del Modelo**: Aplicación de técnicas de interpretabilidad como SHAP para entender cómo las variables influyen en las predicciones.

6. **Evaluación del Modelo**: Evaluación del rendimiento del modelo en un conjunto de pruebas mediante métricas como precisión, sensibilidad y área bajo la curva ROC (AUC-ROC).

## Estructura de Archivos

- `data/`: Contiene los datasets utilizados para entrenar el modelo.
- `notebooks/`: Jupyter Notebooks con análisis detallados y experimentos.
- `models/`: Modelos entrenados guardados para futuras predicciones.
- `reports/`: Informes generados con resultados y visualizaciones clave.

## Requisitos Previos

- **Python 3.8 o superior**
- Librerías necesarias para la ejecución del proyecto de Modelos Predictivos con Árboles de Decisión para la Detección de Fraudes en Reclamaciones de Seguros de Vehículos
