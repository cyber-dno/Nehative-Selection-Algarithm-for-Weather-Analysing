# Negative-Selection-Algorithm-for-Weather-Analysing

### Алгоритм отрицательного отбора для обнаружения аномалий погоды

Приведены данные погоды в Санкт-Петербурге. В папке Data содержится исходная выборка и дальнейший её анализ.
В результате иерархической кластеризации были отброжены выбросы в данных. Погода представлена в качестве временных
рядов. Один ряд - 365 наблюдений. Одно наблюдение - показатели погоды за конкретный день.

На основе анализируемых рядов был составлен ВР, описывающий среднее поведение погоды в течении года.
На основе данного ряда были сгенерированы детекторы с различными параметрами. Детекторы используются для анализа 
погоды за конкретный год и поиска аномалий.
