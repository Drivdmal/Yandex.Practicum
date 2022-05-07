# Yandex.Practicum
## Проекты, выполненные в ходе обучения в Яндекс.Практикуме по профессии ***"Специалист по Data Science"***.


| Навзание проекта             | Описание                                | Использованные библиотеки|
|-------------------------------|---------------------------------|:-------------------------------------:|
|[Музыка больших городов](https://github.com/Drivdmal/Yandex.Practicum/tree/main/ydx_music) |Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница) | `pandas` |
|[Исследование надёжности заёмщиков](https://github.com/Drivdmal/Yandex.Practicum/tree/main/reliability_of_borrowers)|По базе данных банка о платёжеспособности клиентов требуется определить - влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. | `pandas` , `pymystem3`, `collections`|
|[Исследование объявлений о продаже квартир](https://github.com/Drivdmal/Yandex.Practicum/tree/main/apartments_for_sale)|По базе данных Яндекс.Недвижимость (архив о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет) - определить рыночную стоимость объектов недвижимости.| `pandas` , `matplotlib`|
|[Определение перспективного тарифа для телеком-компании](https://github.com/Drivdmal/Yandex.Practicum/tree/main/mobile_tariff)|По базе данных 500 пользователей телеком-компании (2 разных тарифа) - определить какой тариф лучше.| `pandas` , `numpy`,  `math`, `matplotlib`, `scipy`|
|[Исследование успешноти игр](https://github.com/Drivdmal/Yandex.Practicum/tree/main/games_analisis)|По базе данных (игры разных жанров и плотформ, количество продаж, отзывы покупателей и экспертов) определить характеристики успешности игр (популярность, длительность присутствия на рынке, объемы продаж и т.п.)| `pandas`, `matplotlib`, `seaborn`,`numpy`, `scipy` |
|[Рекомендации тарифов](https://github.com/Drivdmal/Yandex.Practicum/tree/main/mobil_2)|По базе данных о поведении клиентов, использующих определенные тарифы мобильного оператора, подобрать подходящий тариф (задача классификации).| `pandas`, `sklearn`,`datetime`, `tqdm`|
|[Отток клиентов](https://github.com/Drivdmal/Yandex.Practicum/tree/main/customer_outflow)|По базе ретроспективных данных о поведении клиентов банка и расторжении с ним договоров создать модель, прогнозирующую уход клиента из банка в ближайшее время.| `pandas`, `numpy`,`matplotlib`,`sklearn`,`tqdm` |
|[Выбор региона для разработки новых нефтяных месторождений](https://github.com/Drivdmal/Yandex.Practicum/tree/main/oil_well)|По базе данных проб нефти из трёх регинов  создать модель для предсказания региона с наибольшей прибылью (с использованием техники Bootstrap).| `pandas`, `numpy`, `sklearn`, `matplotlib`,`scipy`|
|[Простроение модели по предсказанию коэффициента восстановления золота из золотосодержащей руды](https://github.com/Drivdmal/Yandex.Practicum/tree/main/recovery_au_from_ore)|По данным с параметрами процессов добычи и очистки золотосодержащей руды обучить модель, предсказывающую коэффициент воссстановления золота.| `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborm`|
|[Защита персональных данных](https://github.com/Drivdmal/Yandex.Practicum/tree/main/encryption_with_matrix)|Используя свойства матриц, зашифровать данные таким образом, чтобы не пострадало качество предсказаний, при обучении на этих данных модели линейной регрессии.|`pandas`, `sklearn`, `numpy`, `LaTeX (Jupyter)`|
|[Прогноз заказов такси](https://github.com/Drivdmal/Yandex.Practicum/tree/main/analis_taxi)|по историческим данным о заказах такси в аэропортах требуется спрогнозировать количество заказов на текущий час (построить модель машинного обучения, строющую прогнозы на временных рядах).|`pandas`, `sklearn`, `matplotlib`, `LGBMRegressor`, `CatBoostRegressor`,`GridSearchCV`|
|[Определение токсичности коментариев](https://github.com/Drivdmal/Yandex.Practicum/tree/main/tf_idf)|Задача на классификацию: создать модель, определяющую токсичность коментариев (позитивные/негативные коментарии)|`pandas`, `sklearn`, `matplotlib`, `nltk`, `re`, `WordNetLemmatizer`, `TfidVectorizer`, `LogisticRegression`, `Pipeline`, `CatBoostRegressor`, `GridSearchCV`|