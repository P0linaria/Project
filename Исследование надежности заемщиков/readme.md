**Описание проекта:**

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. 

Входные данные от банка — статистика о платёжеспособности клиентов.

Результаты исследования будут учтены при построении модели кредитного скоринга

**Описание данных**
- children — количество детей в семье
- days_employed — общий трудовой стаж в днях
- dob_years — возраст клиента в годах
- education — уровень образования клиента
- education_id — идентификатор уровня образования
- family_status — семейное положение
- family_status_id — идентификатор семейного положения
- gender — пол клиента
- income_type — тип занятости
- debt — имел ли задолженность по возврату кредитов
- total_income — ежемесячный доход
- purpose — цель получения кредита

**Вывод:**

В каждой иследованной группе люди имеют задолженность по возврату кредита не более, чем в 10% случаях и не менее, чем в 5% случаях. 

1. Зависимость между количеством детей и возвратом кредита в срок показывает, что чаще всего кредиты возвращают в срок родители с 1, 2 или 5 детьми, реже всего родители с 4 детьми:
- 0 детей: 7.5%
- 1 ребенок: 9.2%
- 2 ребенка: 9.5%
- 3 ребенка: 8.2%
- 4 ребенка: 9.8%
- 5 детей: 0%

2. Зависимость между семейным положением и возвратом кредита в срок показывает, что чаще возвращают кредиты люди, которые находятся или ранее были в официальном браке. Оставшие группы возвращают кредиты в срок реже.
- в разводе: 7.1%
- вдовец/вдова: 6.6%
- женат/замужем: 7.6%
- не женат/не замужем: 9.8%
- в гражданском браке: 9.3%

3. Зависимость между уровнем дохода и возвратом кредита в срок показывает, что люди из группы E с доходом менее 30000 чаще других имеют задолженности, люди из группы E имеющие доход немного выше (от 30000 до 50000) возвращают кредиты гораздо чаще, чем любая другая группа. 
- 0–30000 — 'E': 9.1%
- 30001–50000 — 'D': 6%
- 50001–200000 — 'C': 8.5%
- 200001–1000000 — 'B': 7.1%
- 1000001 и выше — 'A': 8%

4. Зависимость между целью кредита и возвратом кредита в срок показывает, что люди, взявшие кредиты на покупку недвижимости и проведение свадьбы имеют долг реже, а люди, взявщие кредиты на покупку автомобиля или получения образования имеют долг чаще.
- операции с недвижимостью: 7.3%
- проведение свадьбы: 7.9%
- операции с автомобилем: 9.3%
- получение образования: 9.3%
