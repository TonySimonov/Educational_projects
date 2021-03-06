# Анализ пользовательского поведения в мобильном приложении
## Описание
В проекте проводилось исследование пути пользователя до покупки в приложении. На основе данного пути строилась и анализировалась воронка продаж. 
Проводился анализ результатов А/А/В эксперимента внедрения новых шрифтов. В рамках анализа проводилось сравнение двух контрольных выборок на предмет правильности разделения всех пользователей на группы, а также множественные сравнения контрольных групп с тестовой для проверки гипотезы о влиянии новых шрифтов на конверсию пользователей.

## Данные
В качестве данных для проекта использовался csv-файл со следующими колонками:
- EventName — название события,
- DeviceIDHash — уникальный идентификатор пользователя,
- EventTimestamp — время события,
- ExpId — номер эксперимента: 246 и 247 — контрольные группы, 248 — экспериментальная.

## Задачи
- Проанализировать воронку продаж
- Проанализировать результаты А/А и А/В тестирований

## Используемые библиотеки
*pandas, matplotlib, seaborn, numpy, scipy, plotly, statsmodels*
