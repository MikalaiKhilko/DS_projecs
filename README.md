В репозитории собраны выполненные проекты в ходе обучения в Yandex.Practicum профессии "Специалист по Data Science".

## Список проектов

| Наименование проекта | Описание | Инструменты |
|:---------------------|:---------|:------------|
|Предсказание коэффициента восстановления золота из золотосодержащей руды|Построение модели машинного обучения для  предсказания коэффициента восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками|pandas, matplotlib, numpy, seaborn, sklearn|
|Прогнозирование оттока клиентов оператора связи|Предобработка данных, построение модели, предсказывающей̆ отток клиентов для применения упреждающих мер по удержанию клиентов|pandas, matplotlib, numpy, seaborn, sklearn, xgboost, lightgbm|
|Определение наиболее выгодного региона нефтедобычи|Предобработка и анализ данных, построение моделей, определяющих регион с наиболее выгодной добычей нефти на основе характеристик скважин в регионах|pandas, matplotlib, numpy, seaborn, sklearn|
|Классификация комментариев (машинное обучение для текстов)|Предобработка текста, построение  модели, позволяющей классифицировать токсичность комментариев|pandas, sklearn, numpy, nltk, tf-idf, ightgbm|
|Определение возраста покупателя (компьютерное зрение)|Построение модели, предсказывающей возраст покупателя по фотографии, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя|pandas, keras, matplotlib, numpy, seaborn|
|Определение перспективного тарифа для оператора сотовой связи|Предобработка и анализ данных о поведении клиентов, проверка гипотез о различии выручки в зависимости от тарифа и от региона|pandas, scipy, numpy, seaborn|
|Прогнозирование оттока клиентов банка|Предобработка данных, основанная на данных о поведении клиентов, создание модели для прогнозирования вероятности ухода клиента из банка в ближайшем будущем с целью снижения затрат на удержание клиентов|pandas, matplotlib, numpy, seaborn, sklearn|



- Проект. Выпускной проект. Телеком -  исследование оттока клиентов
- Проект. Компьютерное зрение
- Проект. Аналитика в авиакомпании
- Проект. Прогнозирование тональной окраски комментариев
- Проект. Прогнозирование количества заказов такси
- Проект. Определения стоимости автомобиля
- Проект. Защита персональных данных клиентов страховой компании  
- Проект. Предсказание коэффициента восстановления золота  
- Проект. Поиск прибыльных нефтяных месторождений
- Проект. Отток клиентов
- Проект. Рекомендация тарифов
- Проект. Исследование игровых платформ
- Проект. Определение перспективного тарифа для телеком компании
- Проект. Исследование объявлений о продаже квартир
- Проект. Исследование надёжности заёмщиков

Описания проектов

Проект. Телеком - исследование оттока клиентов
Оператор связи хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

Результат: Обученная модель LGBM полностью справляется с поставленной заказчиком задачи по целевой метрике (AUC-ROC)
Стек: Pandas, Numpy, Matplotlib, Seaborn, Plotly, SKlearn, XGBoost, Catboost, LightGBM

Проект. Компьютерное зрение
Сетевой продуктовый супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:

Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
Контролировать добросовестность кассиров при продаже алкоголя. Постройте модель, которая по фотографии определит приблизительный возраст человека. В вашем распоряжении набор фотографий людей с указанием возраста.
Результат: Нейронная сеть соответствует поставленной задаче сетевого супермаркета и может быть внедрена в систему слежения, что повысит средний чек покупателей за счет рекомендации потенциально интересных товаров для возрастных групп, а также снизит риск продажи алкоголя и табака несовершеннолетним.
Стек: Pandas, Numpy, Matplotlib, Seaborn, PIL, Keras

Проект. Аналитика в авиакомпании
Российская авиакомпания F9 выполняет внутренние пассажирские перевозки. Важно понять предпочтения пользователей, покупающих билеты на разные направления.
Предстоит изучить базу данных и проанализировать спрос пассажиров на рейсы в города, где проходят крупнейшие культурные фестивали.

Результат: Проведение статистических тестов отвергло гипотезу, что наличие фестивалей влияет на продажи билетов авиакомпании.
Стек: SQL, Pandas, Numpy, Seaborn, Scipy, Plotly

Проект. Прогнозирование тональной окраски комментариев
Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

Результат: Для данной задачи лучшая для заказчика в плане качества предсказания, скорости предсказания, время обучения, является модель - LogisticRegression.
Стек: Pandas, Numpy, Seaborn, SKlearn, Re, Nltk, Torch, Transformers, XGBoost, Catboost, LightGBM

Проект. Прогнозирование количества заказов такси
Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Построить модель для такого предсказания.

Результат: Наиболее оптимальной для поставленной задачи "Прогнозирования количество заказов такси на следующий час" является XGBRegressor.
Стек: Pandas, Numpy, Matplotlib, SKlearn, XGBoost, Catboost, LightGBM

Проект. Определения стоимости автомобиля
Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Нужно построить модель для определения стоимости.

Результат: Для данной задачи было обучено несколько моделей. Лучшая в плане качества предсказания, скорости предсказания, времени обучения оказалась - LGBMRegressor. Т.к. лучше всего справляется с поставленной задачей.
Стек: Pandas, Numpy, Matplotlib, Seaborn, SKlearn, XGBoost, Catboost, LightGBM

Проект. Защита персональных данных клиентов страховой компании
Необходимо защитить данные клиентов страховой компании. Разработать метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обосновать корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.

Результат: Предложенный алгоритм преобразования данных справляется для решения задачи шифрования данных, полностью удовлетворяет поставленной задаче Защиты персональных данных клиентов страховой компании.
Стек: Pandas, Numpy, Matplotlib, Seaborn, SKlearn

Проект. Предсказание коэффициента восстановления золота
Необходимо подготовить прототип модели машинного обучения для компании, разрабатывающей решения для эффективной работы промышленных предприятий.Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В распоряжении данные с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

Результат: Обученная модель Random Forest подходит для предсказания коэффициент восстановления золота из золотосодержащей руды, как для чернового концентрата, так и финального концентрата. Тем самым может оптимизировать производство, и заранее предсказывать, если предприятие будет с убыточными характеристиками.
Стек: Pandas, Numpy, Matplotlib, Seaborn, SKlearn

Проект. Поиск прибыльных нефтяных месторождений
Для добывающей компании нужно решить, где бурить новую скважину. Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Необходимо построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализировать возможную прибыль и риски техникой Bootstrap.

Результат: Обученная модель Линейная регрессия предсказывает наличие запасов нефти с точность до 0.9 тыс.баррелей, определен регион с максимальной прибылью при минимальных рисках.
Стек: Pandas, Numpy, Scipy, SKlearn, Bootstrap

Проект. Отток клиентов
Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Результат: Обученную для задачи классификации модель можно использовать для прогнозирования, уйдёт клиент из банка в ближайшее время или нет.
Стек: Pandas, Matplotlib, SKlearn

Проект. Рекомендация тарифов
Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». В распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф.

Результат: Построенна модель для задачи классификации, способная подобрать для пользователей, пользующихся архивными тарифами, более подходящий тариф («Смарт» или «Ультра»).
Стек: Pandas, SKlearn

Проект. Исследование игровых платформ
Интернет-магазине продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы. Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

Проведен анализ: Потенциально прибыльных платформ, жанров игр; портрет пользователя для рекламных компаниях в каждом регионе.
Стек: Pandas, Numpy, Scipy, Math, Matplotlib, Seaborn

Проект. Определение перспективного тарифа для телеком компании
Клиентам оператора сотовой связи предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Необходимо сделать предварительный анализ тарифов на небольшой выборке клиентов. В распоряжении данные 500 пользователей. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

Проведен анализ: Оптимальный тариф для пользователей, Прибыльный тариф для оператора сотовой связи
Стек: Pandas, Numpy, Scipy, Math, Matplotlib, Seaborn

Проект. Исследование объявлений о продаже квартир
В распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

Проведен анализ: Зависимости цены квартиры от удаленности от центра, количества комнат, типа этажности квартиры, даты размещения (дня недели, месяца, года)
Стек: Pandas, Matplotlib

Проект. Исследование надёжности заёмщиков
Влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок? Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга.

Проведен анализ: Зависимости возврата кредита в срок от наличия детей, семейного положения, уровня дохода, цели кредита, возраста и образования.
Стек: Pandas
