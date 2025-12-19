# Анализ NER на русских новостях о Brexit Дедов Иван Андреевич БПИ-234

## Описание проекта
Сравнение классических ML моделей и LLM (DeepSeek) для задачи распознавания именованных сущностей на русских новостях о Brexit.

## Задача
NER (Named Entity Recognition) - определение типа сущности: PER, ORG, LOC, EVT, PRO.

## Методы
- **Классические ML:** Logistic Regression, Naive Bayes, SVM, Random Forest, Gradient Boosting
- **LLM:** DeepSeek zero-shot classification
- **Особенность:** Сравнение подходов на малом датасете (9 документов)

## Результаты
Лучшая модель: **Linear SVM** с точностью 93.75%
- Fast inference (<1ms)
- Хорошая интерпретируемость
- Минимальное переобучение

## Данные
Источник: Russian news from Balto-Slavic Natural Language Processing 2019: https://bsnlp.cs.helsinki.fi/bsnlp-2019/shared_task.html
Тема: Brexit, 9 документов