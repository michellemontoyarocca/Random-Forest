# Random Forest · experimentos con series financieras

Cuaderno de exploración de Random Forest con datos de mercado descargados mediante `yfinance`. Incluye preparación de variables, clasificación y regresión, visualizaciones y controles interactivos. Reúne varias iteraciones del experimento en un solo archivo; no es un modelo de pronóstico validado para operar.

Abrir `Random_Forest.ipynb` en Jupyter o Colab y ejecutar por secciones. Requiere `pandas`, `numpy`, `scikit-learn`, `yfinance`, `matplotlib`, `seaborn`, `plotly` e `ipywidgets`, además de Internet para los datos. Las fechas y precios descargados pueden variar según el proveedor.

Para evaluar un modelo de series temporales, separar entrenamiento y prueba **por fecha**, comparar con un pronóstico ingenuo, documentar costos de operación y evitar usar información futura al construir variables. Las gráficas del cuaderno ilustran experimentos; no constituyen recomendaciones de inversión.
