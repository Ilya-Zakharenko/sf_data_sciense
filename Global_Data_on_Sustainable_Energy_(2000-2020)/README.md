# <center> **PROJECT-Глобальные данные по устойчивой энергетике (2000-2020)**

## <center> **Оглавление**
[1. Описание проекта](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/project_7/README.md#Описание-проекта)

[2. Какой кейс решаем?](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/project_7/README.md#Какой-кейс-решаем)

[3. Краткая информация о данных](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/project_7/README.md#Краткая-информация-о-данных)

[4. Этапы работы над проектом](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/project_7/README.md#Этапы-работы-над-проектом)

[5. Результат](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/project_7/README.md#Результат)



## <center> **`1.` Описание проекта**

Предоставлен набор данных, демонстрирующий показатели устойчивой энергетики и другие полезные факторы по всем странам с 2000 по 2020 год. В нём собрана такая информация, как доступ к электричеству, возобновляемые источники энергии, выбросы углерода, энергоемкость, финансовые потоки и экономический рост.



## <center> **`2.` Какой кейс решаем?**

Необходимо спрогнозировать будущее потребление энергии.



## <center> **`3.` Краткая информация о данных**

В датасете представлен следующий набор данных:

* `Entity`: название страны или региона, по которому предоставляются данные;

* `Year` : год, за который представлены данные, в диапазоне от 2000 до 2020 года;

* `Access to electricity (% of population)`: процент населения, имеющего доступ к электричеству;

* `Access to clean fuels for cooking (% of population)`: процент населения, в основном использующего чистые виды топлива;

* `Renewable-electricity-generating-capacity-per-capita`: установленная мощность возобновляемой энергии на человека;

* `Financial flows to developing countries (US $)`: помощь и содействие со стороны развитых стран для проектов в области чистой энергии;

* `Renewable energy share in total final energy consumption (%)`: процент возобновляемой энергии в конечном потреблении энергии;

* `Electricity from fossil fuels (TWh)`: электроэнергия, выработанная из ископаемого топлива (уголь, нефть, газ) в тераватт-часах;

* `Electricity from nuclear (TWh)`: электроэнергия, выработанная на АЭС, в тераватт-часах

* `Electricity from renewables (TWh)`: электроэнергия, вырабатываемая из возобновляемых источников (гидроэнергия, солнечная энергия, энергия ветра и т. д.) в тераватт-часах;

* `Low-carbon electricity (% electricity)`: процент электроэнергии из источников с низким уровнем выбросов углерода (атомная энергетика и возобновляемые источники энергии);

* `Energy intensity level of primary energy (MJ/$2011 PPP GDP)`: потребление энергии на единицу ВВП по паритету покупательной способности;

* `Value_co2_emissions (metric tons per capita)`: выбросы углекислого газа на человека в метрических тоннах;

* `Renewables (% equivalent primary energy)`: эквивалентная первичная энергия, полученная из возобновляемых источников;

* `GDP growth (annual %)`: годовой темп роста ВВП, рассчитанный на основе постоянной местной валюты;

* `GDP per capita`: валовой внутренний продукт на человека;

* `Density (P/Km2)`: плотность населения в людях на квадратный километр;

* `Land Area (Km2)`: общая площадь земли в квадратных километрах;

* `Latitude`: широта центра страны в десятичных градусах;

* `Longitude`: долгота центра страны в десятичных градусах;



**Целевой признак:**

* `Primary energy consumption per capita (kWh/person)`: потребление энергии на человека в киловатт-часах.



## <center> **`4.` Этапы работы над проектом**

Проект состоит из семи частей:

`1.` **Базовый анализ и знакомство с данными**;

`2.` **Очистка данных**;

`3.` **Разведывательный анализ данных (EDA)**;

`4.` **Feature engineering (Создание новых признаков)**;

`5.` **Отбор признаков**;

`6.` **Machine Learning: AutoML**;

`7.` **Machine Learning: Linear Regression**.


### <center> **`1.` Базовый анализ и знакомство с данными**
На данном этапе мы проводим исследование предоставленных данных.

:arrow_up:[к оглавлению](https://github.com/Ilya-Zakharenko/sf_data_sciense/tree/main/project_5/README.md#Оглавление)



### <center> **`2.` Очистка данных**
На данном этапе выявим и очистим данные от пропусков, дубликатов и выбрасов.



### <center> **`3.` Разведывательный анализ данных (EDA)**

В этой части проекта мы:

* Исследуем сформированный набор данных; 

* Дополняем наш анализ визуализациями, иллюстрирующие исследование.



### <center> **`4.` Feature engineering (Создание новых признаков)**

На данном этапе преобразуем некоторые из имеющихся признаков и создаём новые.



### <center> **`5`. Отбор признаков**

На данном этапе мы отбираем самые информативные признаки.



### <center> **`6`. Machine Learning: AutoML**

В данном разделе мы используем алгоритм AutoML.



### <center> **`7.` Machine Learning: Linear Regression**
Этап моделирования. Построение модели линейной регрессии.



## <center> **`8.` Результат**

Среди задейсвованных моделей, наилучшего результата удалось получить с помощью модели **Linear Regression()**. 

Метрики получились следующие: 

* *RMSLE* на тренировочной выборке: 0.40
* *RMSLE* на валидационной выборке: 0.40

* *MAPE* на тренировочной выборке: 0.04
* *MAPE* на валидационной выборке: 0.04