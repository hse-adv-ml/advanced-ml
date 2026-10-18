# Семинар №6. Интерпретируемость моделей

[Ноутбук](seminar.ipynb) использует файл `world-happiness-report-2021.csv`, который не входит в репозиторий.
Источник данных указан в подготовительной части ноутбука: [World Happiness Report](https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021).

Перед запуском загрузите CSV в `/content/` в Google Colab либо измените путь в `pd.read_csv` на расположение своего файла.
Код ожидает, в частности, столбцы `Ladder score`, `Regional indicator`, `upperwhisker`, `lowerwhisker`, `Standard error of ladder score` и `Ladder score in Dystopia`.
