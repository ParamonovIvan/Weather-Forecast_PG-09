# Проект: «Виджет с прогнозом погоды»

### Задача проекта:

Создать виджет с прогнозом погоды.

Этот виджет позволит получать информацию о погоде:

+ В любом городе по запросу;

+ По текущей геолокации пользователя.

Также пользователь сможет выбрать, на какой период он хочет узнать погоду:

+ На текущее время;

+ На ближайшие 5 дней.

Все данные о погоде будут собираться из OpenWeatherMap по API.

### Функциональные требования:

В реализованном проекте можно:

+ Вводить вручную местоположение в строку поиска;

+ Получать текущую геопозицию пользователя;

+ По текущей геопозиции или вручную введенному местоположению получать информацию о погоде из OpenWeatherMap;

+ Получать 2 вида информации о погоде — прогноз на 5 дней или только на сегодня.

### Требования к коду:

+ Проект написан с помощью React.

+ Использован компонентный подход.

+ Соблюдено единообразие оформления кода. Корректные отступы между смысловыми блоками, единый формат отступов от левого края и так далее.

+ Все переменные, компоненты и функции имеют осмысленные имена.

+ Проект следует принципам DRY (Don’t Repeat Yourself) и KISS (Keep It Short and Simple).

+ Для получения данных о погоде используется сторонний сервис OpenWeatherMap.

### Этапы выполнения проекта:

#### Этап 1 

Подготовить дизайн проекта.

Обязательные элементы дизайна:

+ Поисковая строка для ввода города или населенного пункта.

+ Кнопка для получения текущей геолокации пользователя.

+ Кнопка для получения прогноза погоды.

+ Блок или несколько блоков с полученной информацией о погоде.

+ Переключатель для выбора, какие данные получить. Текущую погоду или прогноз на 5 дней.

#### Этап 2

Спроектировать верхнеуровненую структуру React-компонентов для всего приложения.

Зафиксировать, какие компоненты будут в проекте и как они взаимодействуют друг с другом.

#### Этап 3

Получить ключ OpenWeatherMap API на сайте проекта.

#### Этап 4

Создать компонент поисковой строки.

#### Этап 5

Создать кнопку для получения текущего местоположения пользователя.

Учесть, что пользователь может не дать разрешение на чтение его локации. Обработать этот кейс.

#### Этап 6

Создать кнопку для получения погоды. 

#### Этап 7

Реализовать логику получения данных о погоде по заданному местоположению из API. Добавить соответствующий обработчик на кнопку.

Учесть, что пользователь может ничего не ввести в поисковую строку и не воспользоваться функцией определения геопозиции. В таком случае можно показать пользователю специальное сообщение или использовать что-то другое.

#### Этап 8

Добавить компонент (или компоненты) для отображения данных о погоде, которые были получены из API на прошлом этапе.

Данные, которые необходимо показать пользователю:

+ Температуру в градусах Цельсия.

+ Текстовое описание погоды: например, «пасмурно», и соответствующую картинку.

+ Давление.

+ Влажность.

+ Скорость ветра.

+ Время восхода и заката солнца.

Учесть, что данные могут не прийти. Это происходит по разным причинам: от ошибки в запросе до отсутствия данных на сервере. Помочь пользователю понять, что произошло.

#### Этап 9

Добавить компонент, в котором будет возможность переключать варианты получения погоды — на текущий момент или на 5 дней вперёд.

#### Этап 10

Формат данных текущей погоды отличается от формата данных прогноза на 5 дней. Сделать так, чтобы виджет работал корректно в обоих случаях.

### Результат работы:
#### Страница виджета с прогнозом погоды

<img width="445" alt="weather" src="https://github.com/ParamonovIvan/Weather-Forecast_PG-09/assets/131868856/b39be946-6743-47b8-8e44-6b5b4fe4f2da">
