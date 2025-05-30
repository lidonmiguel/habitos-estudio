# Análisis de Hábitos de Estudio y su Influencia en la Nota Final

Este proyecto contiene un estudio realizado sobre un dataset de Kaggle que analiza los hábitos de estudio de los estudiantes y cómo estos influyen en la nota final obtenida. El análisis se presenta en un notebook de Jupyter, junto con una versión HTML para una visualización más amigable.

## Contenidos

- **estudio_habitos.ipynb**: Notebook con el análisis completo, código y visualizaciones.  
- **estudio_habitos.py**: Script Python que reproduce el análisis de hábitos de estudio y genera visualizaciones, ideal para ejecutar sin entorno Jupyter.  
- **Predicción_Rendimiento.ipynb**: Notebook que construye y evalúa un modelo de machine learning para predecir la nota final en función de los hábitos del estudiante. Incluye una interfaz interactiva para realizar predicciones ingresando datos manualmente.  
- **Predicción_Rendimiento.py**: Script Python que contiene funciones para cargar el modelo entrenado y predecir la nota final dado un conjunto de hábitos, ideal para usar en producción o integraciones.

## Dataset

El dataset original se obtuvo de Kaggle. Puedes encontrarlo en el siguiente enlace:

[Dataset en Kaggle](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)

## Cómo usar este repositorio

- **Ver el análisis directamente en GitHub**  
  Puedes ver el notebook `.ipynb` renderizado directamente en GitHub (aunque no se ejecuta el código).

- **Descargar y abrir los notebooks localmente**  
  Descarga los archivos `.ipynb` y ábrelos con Jupyter Notebook o JupyterLab para ejecutar y modificar el código.

- **Visualizar el análisis sin ejecutar código**  
  Abre el archivo `.html` en cualquier navegador para una visualización interactiva y limpia.

- **Ejecutar el script de predicción**  
  Puedes usar `Predicción_Rendimiento.py` para hacer predicciones automáticas sobre la nota final a partir de un conjunto de hábitos.

## Requisitos (para ejecutar el notebook y el script)

- Python 3.x  
- Jupyter Notebook o JupyterLab (para los `.ipynb`)  
- Bibliotecas: pandas, scikit-learn, numpy (instalables con pip)
