# Классификаиция клиентов телеком компании


## Описание проекта

Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям один из новых тариф.


## Инструменты:

*Python, Pandas, Sklearn*

## Краткое содержание о проделанной работе:

Разработана система, способная проанализировать поведение клиентов и предложить пользователям новый тариф.

## Вывод

Обучили модели классификации, в качестве оценки используем f_1 score: 

1) линейная регресия:
 - получили f_1 score:  0.76 

2) дерево решений: 
 - получили f_1 score:  0.57 

3) модель LightGBM: 
 - получили f_1 score:  0.71 

Лучшей моделью показала себя линейная регрессия. Протестируем ее на тестовой выборке:
 - получили f_1 score:  0.75


Далее мы проверили модель случайного леса на тестовой выборке. После тестирования модели получили значение метрики f_1 score - 0.75.

В результате получили модель которая способна классифицировать комментарии на позитивные и негативные. 

## Статус проекта

Завершен
