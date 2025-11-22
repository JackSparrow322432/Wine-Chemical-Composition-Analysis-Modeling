Wine Chemical Composition Analysis
Author: Amanali Karatay

 Overview
This project analyzes the chemical composition of wine and identifies which components influence alcohol content and overall wine characteristics.
The work includes:

Data cleaning & preprocessing

Exploratory Data Analysis (EDA)

Correlation and feature importance visualization

Machine learning modeling

Final insights and conclusions

Проект выполнен в образовательных целях и демонстрирует навыки Data Science, статистики и визуализации данных.

Project Structure
project_wine/
│
├── data/                 # Dataset (raw/clean)
├── notebooks/            # Jupyter Notebooks with analysis
├── src/                  # Python scripts (helpers, preprocessing, models)
├── models/               # Saved ML models
├── results/              # Plots, charts and exported results
│
├── README.md             # Project description (this file)
└── requirements.txt      # Python dependencies

Technologies
Проект построен с использованием следующих библиотек и инструментов:

Python 3.x

NumPy

pandas

Matplotlib

Seaborn

scikit-learn

Jupyter Notebook

 How to Run the Project
 Install Dependencies
nginx
Копировать код
pip install -r requirements.txt
 Open Jupyter Notebook
nginx
Копировать код
jupyter notebook
 Run the analysis
Открой файл в notebooks/ (например wine_analysis.ipynb), запусти все ячейки по порядку.

 Key Results
В ходе анализа были получены следующие наблюдения:

✔ Найдены химические компоненты, наиболее влияющие на алкогольность вина
✔ Построен корреляционный анализ между признаками
✔ Выявлены паттерны, влияющие на качество вина
✔ Создана ML-модель, которая предсказывает характеристики вин по химическим параметрам
✔ Получены визуализации, подтверждающие зависимости в данных

 Machine Learning Models
В проекте можно использовать:

Логистическую регрессию

Random Forest

Gradient Boosting

KNN
или любую другую модель из scikit-learn.

 Visualizations
Проект включает:

Корреляционные матрицы

Гистограммы распределения признаков

Boxplot для выбросов

Scatterplots для взаимосвязей

Feature Importance графики

 Future Improvements
Планируемые улучшения:

Улучшить очистку данных

Добавить модели с более высокой точностью

Добавить сравнение нескольких алгоритмов

Добавить интерактивный дашборд (Streamlit / Plotly Dash)
