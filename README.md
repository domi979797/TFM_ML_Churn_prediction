# TFM - Predicción de Churn en el Sector Asegurador con Machine Learning

Este repositorio contiene el Trabajo de Fin de Máster (TFM) de Domingo Martínez Pérez, presentado en el Máster Universitario en Ciencia de Datos, titulado:

**"Algoritmos de Machine Learning para la modelización de la caída de cartera en el sector asegurador"**

## Descripción

El objetivo principal del proyecto es implementar un modelo predictivo capaz de identificar a clientes con alta probabilidad de cancelar sus pólizas (churn) utilizando técnicas de aprendizaje automático. Esta herramienta puede ayudar a las aseguradoras a implementar estrategias de fidelización más efectivas y optimizar la retención de clientes.

El trabajo se apoya en la metodología **CRISP-DM** y utiliza un conjunto de datos que contienen información socioeconómica, comportamiento de clientes y características de las pólizas.

## Técnicas y Modelos

Los modelos implementados incluyen:

- Regresión Logística
- Random Forest
- XGBoost
- LightGBM
- Aplicación de técnicas de:
  - Oversampling (SMOTE)
  - Cost-sensitive learning
  - Reducción de dimensionalidad (PCA)

## Tecnologías

- Lenguaje: Python
- Librerías principales:
  - `pandas`, `numpy`, `scikit-learn`, `xgboost`, `lightgbm`, `shap`
- Entorno de desarrollo: Visual Studio Code

## Resultados

El mejor rendimiento se obtuvo con el modelo **LightGBM con cost-sensitive learning**, alcanzando:

- **Recall (churn=1)**: 0.46  
- **Precision (churn=1)**: 0.47  
- **F1-score (churn=1)**: 0.47  
- **Tiempo de ejecución (churn=1)**: 4.4 segundos

## Consideraciones éticas

- Los datos utilizados han sido anonimizados.
- No se utilizaron variables sensibles como género, raza o etnia.
- El modelo ha sido diseñado para minimizar el sesgo y cumplir con el RGPD.

## Futuras mejoras

- Añadir variables nuevas.
- Optimización de hiperparámetros.
- Despliegue en entorno real.

## Autor

**Domingo Martínez Pérez**  
Máster Universitario en Ciencia de Datos  
Universitat Oberta de Catalunya  
Junio 2025
