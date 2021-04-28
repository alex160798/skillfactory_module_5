  Проект 6 (Юнит 5)

  Название проекта: "Выбираем авто выгодно"

  Цели проекта: собрать данные о подержанных машинах, подготовить их и обучить модель для предсказания
стоимости авто по его характеристикам.

  Задачи проекта: провести анализ тестовых данных, и на их основе спарсить информацию с сайта auto.ru;
провести исследовательский анализ данных, провести обработку признаков, на основе имеющихся создать новые;
на основе созданных признаков провести обучение моделей на выбор; попробовать кросс-валидацию и стекинг.

  Результат: были построены несколько моделей: RandomForest c кросс-валидацией и без; CatBoost с кросс-
валидацией и без; стэкинг на основе двух предыдущих моделей, линейной регрессии и Ridge.

 Наилучшая полученная метрика MAPE - 22.49%
 
  Личные выводы:
  Данный проект дался мне чрезвычайно сложно, поскольку я начал его поздно и огромное количество вре-
мени потерял на парсинг. Фактически, завершил сборку датасета я всего за 2 дня до дедлайна, что не ос-
тавило практически никакого времени ни на другой, более подробный, парсинг, ни на вдумчивую работу над
признаками, да и переодически возникающие ошибки значительно меня тормозили. Ну и, разумеется, я уже не мог присоединиться к команде, поскольку время уже было потеряно. 
  
  Что я мог сделать лучше:
  - Провести повторный парсинг. Это бы позволило задействовать больше признаков из тестового датасета,
  от которых пришлось отказаться;
  - Лучше очистить данные;
  - Подобрать настройки моделей. Как CatBoost, так и RandomForest были использованы с почти стандартны-
  ми настройками, что, наверняка, значительно ухудшило качество предсказаний. Такие же ненастроенные мо-
  дели использовались и в стекинге;
  - И, в первую очередь, мне следовало начать проект сильно заранее, чтобы иметь возможность работать
  с другими людьми. Это бы в разы ускорило процесс.
