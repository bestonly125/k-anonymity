# k-anonymity
[Генератор синтетических данных можно скачать здесь](https://github.com/bestonly125/marketing_syntetic_data)

#### Если тестирования проводится на новом наборе данных нужно указать искомый экселевский файл в каждом скрипте(например: df = pd.read_excel("marketing_case_v.0.7.xlsx"...)).

#### Таблица 1: Лист А1 
| Локальное время покупок | Широта | Долгота | Общая сумма покупок | Код региона | Часовой пояс | Кол-во товаров в покупке | Бренды | Категория |
|-------------------------|--------|---------|---------------------|-------------|--------------|--------------------------|--------|-----------|
| 2020-02-25T06:32+00:03  | 44.412 | 55.628  | 34440               | 38          | UTC+5        | 2                        | Lenovo | Монитор   |

#### Таблица 2: Лист А2 
| Микросегмент | Локальное время покупок| Широта | Долгота | Общая сумма покупок | Код региона | Часовой пояс | Кол-во покупок | Кол-во товаров в покупке | Бренды | Категория |
|--------------|------------------------|--------|---------|---------------------|-------------|--------------|----------------|--------------------------|--------|-----------|
| 91611037xx   | 2020-02-25T06:32+00:03 | 44.412 | 55.628  | 34440               | 38          | UTC+5        | 2              | 2                        | Lenovo | Монитор   |

#### Таблица 3: Лист А3 
| ID Микросегмент | Локальное время покупок| Код региона  | Часовой пояс | Кол-во покупок | Кол-во товаров в покупке | Бренды | Категория |
|-----------------|------------------------|--------------|--------------|----------------|--------------------------|--------|-----------|
| 1               | 2020-02-25T06:32+00:03 | 38           | UTC+5        | 2              | 2                        | Lenovo | Монитор   |

#### Таблица 4: Лист B1 
| Микросегмент | Дата просмотра рекламы  | Кол-во просмотров рекламы | Кол-во уникальных пользователей |
|--------------|-------------------------|---------------------------|---------------------------------|
| 91611037xx   | 2020-02-25              | 2                         | 3                               | 

#### Таблица 5: Лист B2 
| ID Микросегмент | Дата просмотра рекламы | Кол-во пользователей, просмотревших рекламу | Кол-во просмотров рекламы  |
|-----------------|------------------------|---------------------------------------------|----------------------------|
| 1               | 2020-02-25             | 2                                           | 3                          | 

#### Таблица 6: Лист C1 
| ID Микросегмент | Дата просмотра рекламы | Кол-во пользователей, просмотревших рекламу| Количество просмотров рекламы | Локальное время покупок| Код региона  | Часовой пояс | Кол-во покупок | Кол-во товаров в покупке | Бренды | Категория |
|-----------------|------------------------|--------------------------------------------|-------------------------------|------------------------|--------------|--------------|----------------|--------------------------|--------|-----------|
| 1               | 2020-02-25             |2                                           | 3                             | 2020-02-25T06:32+00:03 | 38           | UTC+5        | 2              | 2                        | Lenovo | Монитор   |

#### Таблица 7: Лист C2 
 | Дата просмотра реклам| Кол-во пользователей, просмотревших рекламу| Количество просмотров рекламы | Локальное время покупок| Код региона  | Часовой пояс | Кол-во покупок | Кол-во товаров в покупке | Бренды | Категория |
|----------------------|--------------------------------------------|-------------------------------|------------------------|--------------|--------------|----------------|--------------------------|--------|-----------|
| 2020-02-25           |2                                           | 3                             | 2020-02-25T06:32+00:03 | 38           | UTC+5        | 2              | 2                        | Lenovo | Монитор   |
