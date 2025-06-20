# Кластеризация регионов России по выбросам загрязняющих веществ

## Описание
Курсовая работа по анализу атмосферных выбросов загрязняющих веществ в регионах России с применением методов машинного обучения. Проект включает предобработку данных, кластеризацию регионов по абсолютным и относительным (на душу населения) выбросам, а также анализ доминирующих отраслей (энергетика, металлургия). Построены визуализации, включая тепловые карты, географические карты и Sankey-диаграммы, с использованием seaborn, matplotlib, plotly и geopandas. На основе анализа сформулированы рекомендации по снижению экологической нагрузки.

## Ключевые функции
- Предобработка данных: очистка, нормализация и группировка данных по регионам и отраслям с использованием pandas.
- Кластеризация регионов с помощью алгоритма KMeans (sklearn) на основе абсолютных и относительных выбросов.
- Визуализация результатов: 
  - Тепловые карты корреляций (seaborn).
  - Интерактивные графики (plotly).
  - Географические карты доминирующих отраслей (geopandas).
  - Sankey-диаграммы для потоков выбросов.
  - Формулировка рекомендаций для регионов с высокой экологической нагрузкой.

## Технологии
- **Язык программирования**: Python
- **Библиотеки**: pandas, sklearn (KMeans), seaborn, matplotlib, plotly, geopandas
- **Инструменты**: Microsoft Excel


## Результаты
- Выделено три кластера регионов по уровню выбросов: низкие, средние и высокие.
- Выявлены регионы с высокой экологической нагрузкой.
- Построены интерактивные визуализации и карты, демонстрирующие распределение выбросов и доминирующие отрасли.
- Сформулированы рекомендации.

## Данные
- **Входные данные**:
  - `BUL_MO_2024.xlsx`: данные о населении.
  - `data_bs.xlsx`: выбросы по регионам и отраслям.
  - `russia_regions.geojson`: геоданные регионов России.
    
## Примеры
- **Визуализации**:
  - Топ 10 индустрий: ![top10_industries_emissions.png](https://github.com/wanderPS/emission_in_air_analysis/blob/main/plots/top10_industries_emissions.png)
  - Географическая карта: ![map_dominant_industry_numbered.png](https://github.com/wanderPS/emission_in_air_analysis/blob/main/plots/map_dominant_industry_numbered.png)
  - Кластеризация по типам выбросов: ![clustering_type_grid.png](https://github.com/wanderPS/emission_in_air_analysis/blob/main/plots/clustering_type_grid.png)
  - Метод локтя: ![elbow_silhouette_total_emissions.png](https://github.com/wanderPS/emission_in_air_analysis/blob/main/plots/elbow_silhouette_total_emissions.png)
