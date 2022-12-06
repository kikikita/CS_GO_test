# CS_GO_test
## Тестовое задание по предсказанию победителей в игре CS:GO

Задача: классифицировать команду - победителя (бинарная классификация), основываясь на данных о предыдущих результатах матчей из таблицы train.csv, а также числовых характеристиках игроков из таблицы players_feats.csv.

Для решения данной задачи были использованы следующие библиотеки машинного обучения, основанные на градиентном бустинге:

- [CatBoost](https://catboost.ai/)
- [XGBoost](https://xgboost.readthedocs.io/en/stable/)
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/pythonapi/lightgbm.LGBMClassifier.html)
- [H2O AutoML](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html)

Для оптимизации гиперпараметров были использованы следующи фреймворки:

- [Optuna](https://optuna.org/)

## Эксперименты
- [Ноутбук с экспериментами](https://github.com/kikikita/CS_GO_test/blob/main/notebooks/cs_go_contest.ipynb) - ноутбук c проведенными экспериментами (находится в папке 'notebooks')

## Результаты экспериментов:
- [Предсказания](https://github.com/kikikita/CS_GO_test/tree/main/predictions) - 3 csv файла с предсказаниями от трех разных моделей.
