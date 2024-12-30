# Análisis de Series Temporales con SARIMA

Este proyecto implementa un pipeline para el análisis y modelado de series temporales, enfocado en datos de consumo energético por subestación. Utiliza métodos estadísticos como descomposición de series y pruebas de estacionariedad, y un modelo SARIMA para realizar predicciones.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Requisitos](#requisitos)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Uso](#uso)
- [Resultados Esperados](#resultados-esperados)
- [Contribución](#contribución)
- [Licencia](#licencia)

## Descripción

El objetivo de este proyecto es:

1. Realizar un análisis exploratorio de datos de series temporales.
2. Verificar la estacionariedad mediante las pruebas ADF y KPSS.
3. Entrenar un modelo SARIMA para predecir el consumo energético.
4. Visualizar resultados y evaluar el desempeño del modelo utilizando métricas como RMSE y MAE.

## Requisitos

Este proyecto utiliza Python y las siguientes librerías:

- `pandas`
- `numpy`
- `statsmodels`
- `matplotlib`
- `scikit-learn`

Puedes instalar todas las dependencias necesarias ejecutando:

```bash
pip install -r requirements.txt

