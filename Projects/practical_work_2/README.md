# Практическая работа 2. Прогнозирование биологического ответа 

## Оглавление
[1. Описание проекта](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/practical_work_2/README.md#Описание-проекта)
[2. Какой кейс решаем?](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/practical_work_2/README.md#Какой-кейс-решаем)
[3. Результат](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/practical_work_2/README.md#Результат)
[4. Выводы](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/practical_work_2/README.md#Выводы)

### Описание проекта
ПРОГНОЗИРОВАНИЕ БИОЛОГИЧЕСКОГО ОТВЕТА (HW-3).

:arrow_up:[к оглавлению](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/practical_work_2/README.md#Оглавление)


### Какой кейс решаем?
Необходимо предсказать биологический ответ молекул (столбец *'Activity'*) по их химическому составу (столбцы *D1-D1776*).

**Условия подбора параметров:**
Обучаем две модели: **логистическую регрессию** и **случайный лес** на уже подготовленном датасете. Далее делаем подбор гиперпараметров с помощью базовых и продвинутых методов оптимизации (*GridSeachCV, RandomizedSearchCV, Hyperopt, Optuna*)

**Метрика качества**
В качестве метрики использовали **F1-score**.

### Результат
Обучены модели **логистической регрессии** и **случайного леса**, гипепараметры подобраны при помощи четырёх методов (*GridSeachCV, RandomizedSearchCV, Hyperopt, Optuna*).


### Выводы
После обучения каждой модели дан краткий вывод, в котором приводятся значения полученных метрик и итоговое время подбора гиперпараметров.