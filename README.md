
<img src="/preview.png"/>


### 📌 О проекте

Исследование посвящено **выявлению когнитивного разрыва** — расхождения между содержанием текста отзыва и числовой оценкой пользователя. На примере отзывов о косметических товарах показано, что до **37.5% отзывов содержат такой разрыв**, а его ключевыми факторами выступают противоречия в тексте, длина отзыва и полярность сентимента.

> **Когнитивный разрыв** — не ошибка модели, а признак потребительского феномена, связанного с эффектом «ореола» бренда, эмоциональной переоценкой или невнимательностью пользователей.

### 🎯 Цель

Разработать ML-модель для прогнозирования рейтинга по тексту отзыва и выявления когнитивного разрыва между текстом и оценкой.

### Задачи

1. Сбор и предобработка данных
2. Векторизация текста (Sentence-BERT + лингвистические признаки)
3. Построение и сравнение моделей классификации тональности
4. Построение регрессионной модели прогнозирования рейтинга (XGBoost)
5. Анализ когнитивного разрыва: сила, направление, ключевые факторы

---

## Ключевые результаты

| Метрика | Значение |
|---|---|
| Объём датасета | **61 000+ отзывов** (1+ млн слов) |
| MAE (регрессия) | **0.550** |
| RMSE | **0.800** |
| R² | **0.439** |
| SVM AUC (тональность) | **0.965** |
| Доля отзывов с разрывом | **37.5%** |


[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-orange?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![XGBoost](https://img.shields.io/badge/XGBoost-boosting-red?style=for-the-badge)](https://xgboost.readthedocs.io)
[![Sentence-BERT](https://img.shields.io/badge/Sentence--BERT-embeddings-green?style=for-the-badge)](https://sbert.net)

[![Презентация](https://img.shields.io/badge/📊_Презентация-PPTX-ff69b4?style=for-the-badge)](./cognitive-gap-reviews.pptx)
[![Отчёт](https://img.shields.io/badge/📄_Отчёт-DOCX-blue?style=for-the-badge)](./cognitive-gap-reviews-otchet.docx)
[![Код](https://img.shields.io/badge/💻_Код-Jupyter-orange?style=for-the-badge)](./cognitive-gap-review-code.ipynb)
