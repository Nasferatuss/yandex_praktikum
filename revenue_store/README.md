# Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста

## Данные

В проекте предоставлены данные крупного интернет-магазина:  

Данные для первой части  
Файл /datasets/hypothesis.csv.     
- Hypothesis — краткое описание гипотезы;  
- Reach — охват пользователей по 10-балльной шкале;  
- Impact — влияние на пользователей по 10-балльной шкале;    
- Confidence — уверенность в гипотезе по 10-балльной шкале;  
- Efforts — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.  

Данные для второй части  
Файл /datasets/orders.csv.  
- transactionId — идентификатор заказа;  
- visitorId — идентификатор пользователя, совершившего заказ;  
- date — дата, когда был совершён заказ;  
- revenue — выручка заказа;  
- group — группа A/B-теста, в которую попал заказ.  

Файл /datasets/visitors.csv.
- date — дата;  
- group — группа A/B-теста;  
- visitors — количество пользователей в указанную дату в указанной группе A/B-теста  

## Задача

Вместе с отделом маркетинга мы подготовили список гипотез для увеличения выручки.
Нужно приоритизировать гипотезы, запустить A/B-тест и проанализировать результаты. 

## Используемые библиотеки
*Pandas*, *Matplotlib*, *SciPy*