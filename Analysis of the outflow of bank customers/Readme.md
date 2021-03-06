# Анализ оттока клиентов банка
## Описание

В распоряжении имеются данные о клиентах регионального банка, который располагается в Ярославле, Ростове Великом и Рыбинске. 
Необходимо проанализировать предложенные данные и выявить клиентов, которые склонны уходить из банка.

## Данные
В качестве данных для проекта использовался csv-файл со следующими данными:
- `userid` — идентификатор пользователя,
- `score` — баллы кредитного скоринга,
- `City` — город,
- `Gender` — пол,
- `Age` — возраст,
- `Objects` — количество объектов в собственности,
- `Balance` — баланс на счёте,
- `Products` — количество продуктов, которыми пользуется клиент,
- `CreditCard` — есть ли кредитная карта,
- `Loyalty` — активный клиент,
- `estimated_salary` — заработная плата клиента,
- `Churn` — ушёл или нет.

## Задачи
- Провести исследовательский анализ данных,
- Выделить портреты клиентов, которые склонны уходить из банка,
- Проверьте статистические гипотезы:
    * Гипотезу о различии дохода между теми клиентами, которые ушли и теми, которые остались
    * Гипотезы о различии баланса между теми клиентами, которые ушли и теми, которые остались

## Используемые библиотеки
*pandas, matplotlib, seaborn, scipy, sklearn*
