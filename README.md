# proyecto_1_core
# Análisis y Predicción de Ventas en una Tienda de Retail

## Descripción
Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) completo, preprocesamiento y benchmarking de técnicas de machine learning para predecir las ventas en una tienda de retail. El enfoque del proyecto es aplicar diferentes modelos de machine learning, evaluar su desempeño y presentar los resultados en una presentación clara y concisa. Este análisis tiene como finalidad optimizar las estrategias de ventas y mejorar la toma de decisiones en el ámbito de retail.

## Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

/Proyecto1 |-- /data | |-- dataset.csv # Dataset utilizado para el análisis y predicción de ventas |-- /notebooks | |-- EDA.ipynb # Notebook con el análisis exploratorio de datos | |-- Preprocessing.ipynb # Notebook para el preprocesamiento de datos | |-- Benchmarking.ipynb # Notebook con el benchmarking de modelos de machine learning |-- /reports | |-- classification_report.txt # Informe de clasificación con métricas detalladas | |-- confusion_matrix.png # Imagen de la matriz de confusión de los modelos | |-- roc_curve.png # Imagen de la curva ROC de los modelos de clasificación binaria |-- /presentation | |-- onepage_presentation.pptx # Presentación en PowerPoint con los resultados del proyecto |-- README.md # Este archivo


## Instrucciones para Ejecutar

Para ejecutar los notebooks y reproducir los resultados de este proyecto, sigue los siguientes pasos:

1. Clona este repositorio en tu máquina local:
    ```
    git clone https://github.com/usuario/Proyecto1.git
    ```

2. Accede al directorio del proyecto:
    ```
    cd Proyecto1
    ```

3. Crea un entorno virtual e instale las dependencias:
    ```
    python -m venv env
    source env/bin/activate  # En Linux/macOS
    env\Scripts\activate  # En Windows
    pip install -r requirements.txt
    ```

4. Abre los notebooks de Jupyter para explorar el análisis y los modelos:
    ```
    jupyter notebook notebooks/EDA.ipynb
    jupyter notebook notebooks/Preprocessing.ipynb
    jupyter notebook notebooks/Benchmarking.ipynb
    ```

5. Revisa los resultados en las carpetas de informes (`/reports`) y la presentación en PowerPoint (`/presentation/onepage_presentation.pptx`).

## Autores

- **TSMathi** – [Rol 1]  
(Agrega más autores si es necesario)

## Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.
