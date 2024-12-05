# Diabetes_prediction
Este notebook explora el análisis, preprocesamiento y modelado de datos para predecir diabetes utilizando Random Forest. Se aplican técnicas de balanceo como SMOTE para mejorar el desempeño en clases minoritarias.

# Predicción de Diabetes usando Random Forest con Datos Balanceados

Este repositorio contiene un notebook de Python que aborda el análisis y modelado de un dataset para predecir diabetes en tres categorías (`Sin Diabetes`, `Prediabetes`, `Diabetes`). 

Se aplican pasos detallados como:
- Exploración de datos (EDA).
- Preprocesamiento (escalado y balanceo de clases con SMOTE).
- Entrenamiento de un modelo Random Forest.
- Evaluación del desempeño utilizando métricas como precisión, recall y F1-score.

## Archivos
- `notebook.ipynb`: Contiene el análisis completo y los resultados.
- `diabetes_data.csv`: Dataset utilizado en el notebook (asegúrate de añadirlo si los términos lo permiten).
- `LICENSE`: Licencia MIT para este repositorio.

## Requisitos
Para ejecutar el notebook, necesitas las siguientes bibliotecas de Python:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

Instálalas con:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

