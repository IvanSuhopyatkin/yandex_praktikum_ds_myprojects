## Задачи проекта
На основе данных геологи разведки выбрать район добычи нефти. 

## Описание проекта
Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль. 

## Используемые библиотеки
pandas

numpy

sklearn
## Навыки и инструменты
-Pandas

-Scikit-learn

-бутстреп

## Выводы
В ходе работы мы изучили данные данные геологоразведки трёх регионов. Для каждого региона была обучена модель с помощью линейной регрессии. Был рассчитан минимальный запас нефти в скажине для безубыточнсти разработки скважин. Из случайных 500 скважин были выбраны лучшие 200 и с помощью техники Bootstrap были подсчитаны средняя прибыль, доверительный интервал и риск убытков. Вероятность убытков меньше допустимого значения только в регионе номер 1. Компании «ГлавРосГосНефть» рекомендуется этот регион для дальнейшей разработки.

