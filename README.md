Análisis de Series Temporales con SARIMA
Este proyecto implementa un pipeline para el análisis y modelado de series temporales, enfocado en datos de consumo energético por subestación. Utiliza métodos estadísticos como descomposición de series y pruebas de estacionariedad, y un modelo SARIMA para realizar predicciones.

Tabla de Contenidos
Descripción
Requisitos
Estructura del Proyecto
Uso
Resultados Esperados
Contribución
Licencia
Descripción
El objetivo de este proyecto es:

Realizar un análisis exploratorio de datos de series temporales.
Verificar la estacionariedad mediante las pruebas ADF y KPSS.
Entrenar un modelo SARIMA para predecir el consumo energético.
Visualizar resultados y evaluar el desempeño del modelo utilizando métricas como RMSE y MAE.
Requisitos
Este proyecto utiliza Python y las siguientes librerías:

pandas
numpy
statsmodels
matplotlib
scikit-learn
Puedes instalar todas las dependencias necesarias ejecutando:

bash
Copiar código
pip install -r requirements.txt
Estructura del Proyecto
main.py: Archivo principal que contiene el pipeline de análisis y modelado.
train.csv: Datos de entrenamiento (consumo histórico por subestación).
test.csv: Datos de prueba para validación del modelo.
Uso
Asegúrate de tener los archivos train.csv y test.csv en el directorio raíz del proyecto.

Ejecuta el script principal:

bash
Copiar código
python main.py
El script analizará cada subestación, realizará predicciones y generará gráficos comparativos entre valores reales y predichos.

Resultados Esperados
El modelo genera los siguientes resultados:

Pruebas ADF y KPSS para evaluar estacionariedad.
Descomposición de la serie temporal en componentes (tendencia, estacionalidad, y residuos).
Gráficos de ACF y PACF.
Predicciones del modelo SARIMA comparadas con valores reales.
Métricas de evaluación como RMSE y MAE.
Contribución
Si deseas contribuir:

Realiza un fork del repositorio.
Crea una rama para tu funcionalidad (git checkout -b nueva-funcionalidad).
Haz commit de tus cambios (git commit -m 'Añadida nueva funcionalidad').
Sube tus cambios (git push origin nueva-funcionalidad).
Abre un pull request.
Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
