# QA-Portfolio
<details>
<summary>Тестирование веб-приложения Маршруты/Фича</summary>

<details>
<summary>Задание 1: тестирование валидации полей в форме</summary>

#### 1. Визуализировать требования
 - Проанализировать требования на валидацию полей ввода часов, минут и адресов
 - Декомпозироавть логику полей формы составив таблицу
#### 2. Спроектировать тесты на проверку валидации полей
 - Выделить классы эквивалентности и граничные значения для полей "Время начала поездки", "Откуда", "Куда"
 - Выбрать тестовые значения, которые проверят каждый класс и границы, если они есть
 - Создать набор тест-кейсов на основе тестовых значений
#### 3. Протестировать валидацию полей и завести баг-репорты
 - В процессе тестирования отметить результаты выполнения теста: PASSED или FAILED
  - Если тест со статусом FAILED, завести баг-репорт в гугл-таблице
#### [Требования к сервису Маршруты](https://docs.google.com/document/d/1CiYmP0jye1pKvB6FSwkA5sDkcNYZ69UyU11CMI1Wctw/edit?usp=sharing)
</details>

<details>
<summary>Решение</summary>

#### 1. Визуализация требований
 - [Декомпозиция логики полей формы](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=1610041137#gid=1610041137&range=A3:C27)
#### 2. Проектирование тестов на проверку валидации полей
Классы эквивалентности и граничные значения
 - [Поле ввода часов](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=1304990855#gid=1304990855&range=A28:F40)
 - [Поле ввода минут](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=1304990855#gid=1304990855&range=A42:F54)
 - [Поле ввода адреса "Откуда"](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=1304990855#gid=1304990855&range=A56:F64)
 - [Поле ввода адреса "Куда"](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=1304990855#gid=1304990855&range=A66:F74)

Проверки на основе тестовых значений
 - [Тест-кейсы](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=1524919368#gid=1524919368&range=A2:I65)
#### 3. Тестирование и заведение баг-репортов
Всего обнаружено 20 багов
 - Вот [ссылка](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=454479584#gid=454479584&range=A2:I21) на баг-репорты
</details>

<details>
<summary>Задание 2: тестирование расчёта стоимости и времени поездки</summary>

#### 1. Визуализировать требования
 - Проанализировать требования расчёта времени и стоимости маршрута на собственном автомобиле
 - Декомпозировать логику расчёта времени и стоимости маршрута составив таблицу
#### 2. Спроектировать тесты на проверку валидации полей
 - Выделить классы эквивалентности и граничные значения для расстояний между адресами и временем начала движения
 - Выбрать тестовые значения, которые проверят каждый класс и границы, если они есть
 - Создать набор тест-кейсов на основе тестовых значений
#### 3. Протестировать валидацию полей и завести баг-репорты
 - В процессе тестирования отметить результаты выполнения теста: PASSED или FAILED
  - Если тест со статусом FAILED, завести баг-репорт в в Google Таблицу
#### [Требования к сервису Маршруты](https://docs.google.com/document/d/1CiYmP0jye1pKvB6FSwkA5sDkcNYZ69UyU11CMI1Wctw/edit?usp=sharing)
</details>

<details>
<summary>Решение</summary>

#### 1. Визуализация требований
 - [Декомпозиция логики расчёта времени и стоимости маршрута](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=1610041137#gid=1610041137&range=A29:C36)
#### 2. Проектирование тестов на проверку валидации полей
Классы эквивалентности и граничные значения
 - [Расстояние между адресами](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=1304990855#gid=1304990855&range=A76:F78)
 - [Время начала движения](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=1304990855#gid=1304990855&range=A79:F83)

Проверки на основе тестовых значений
 - [Тест-кейсы](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=1524919368#gid=1524919368&range=A66:I72)
#### 3. Тестирование и заведение баг-репортов
Всего обнаружено 2 бага
 - Вот [ссылка](https://docs.google.com/spreadsheets/d/1jMqll8IZeb6MZd6eN1KJK28WM19fxkmorreamYQzC4I/edit?gid=454479584#gid=454479584&range=A22:I23) на баг-репорты
</details>
</details>

<details>
<summary>Тестирование веб-приложения Маршруты/Расширенное тестирование</summary>

<details>
<summary>Задание</summary>

#### 1. Анализ требований

 - Изучить требования к сервису Маршруты

#### 2. Выбрать конфигурацию для кроссбраузерного тестирования

 - Подобрать операционные системы, браузеры и разрешения, в которых нужно провести тесты, применив попарное тестирование, чтобы уменьшить количество комбинаций 
 - Поддерживаемые ОС, браузеры и разрешения описаны в требованиях

#### 3. Тестовая документация для вёрстки интерфейса 
 
 Что нужно сделать:
 - Проанализировать требования к вёрстке
 - Составить чек-лист, для проверки верстки блока формы бронирования с выбранным тарифом "Повседневный" и элементов на карте: иконки авто и действия с ними. 

#### 4. Тестовая документация для логики интерфейса

#### Проанализировать требования к логике работы окон и составить тестовую документацию
 - Написать чек-лист на логику окон "Способ оплаты" и "Добавление карты"
 - Написать тест-кейсы на кнопку "Забронировать"

#### 5. Тестирование и заведение баг-репортов

 - Протестировать сервис Маршруты
 - Уже есть набор конфигураций, в которых нужно проверить сервис. Но на тестирование осталось не так много времени, поэтому протестировать сервис нужно на ограниченном наборе: в операционной системе Windows 10 и Яндекс.Браузере при разрешении экрана 800x600, а в Firefox — при 1920х1080
 - В процессе тестирования отметить результаты выполнения теста: PASSED или FAILED.
 - Если тест со статусом FAILED, заведи баг-репорт в в Google Таблицу
 - Тестирование вёрстки нужно провести в обоих окружениях
 - Тесты на логику нужно сделать только в Firefox — при разрешении 1920х1080

#### 6. Подведение итогов

 - Какое впечатление оставил у тебя сервис как у пользователя?
 - Расскажи, что именно тебе удалось протестировать в нескольких предложениях.
 - Подвести итоги тестирования: например, удалось провести все тесты и найти несколько багов. Приложить ссылки на них, чтобы коллеги могли их быстро открыть и посмотреть.
 - Сделать вывод: как думаешь, можно ли отдать такой продукт пользователям? Помнить, что тестировщик даёт рекомендации, а итоговое решение принимает команда менеджеров.
#### [Требования 2.0 к сервису Маршруты](https://docs.google.com/document/d/1FmV0gCiuGD5EZvKk4K5U5w0Ah92Fe5daFHJaGGKKUmY/edit?usp=sharing)
</details>

<details>
<summary>Решение</summary>

<details>
<summary>1. Анализ требований</summary>
 
Что изменилось в требованиях?

Внесены следующие дополнения:

- Поддерживаемые ОС, браузеры и разрешения экрана
- Способы перемещения и масштабирования на карте
- Построение маршрута на карте: его можно построить только через форму слева, на карте передвигать или устанавливать маршрутные точки нельзя

Кто пользователь?

Человек, которому нужно переместиться из одной точки города в другую.

Какие задачи и проблемы он решает?
Можно:
 - узнать маршрут, время в пути и стоимость проезда.
 - построить маршрут с учетом времени и цены.
 - рассчитать поездку по городу: транспорт, время и цена.
 - подобрать оптимальный способ передвижения по городу.

Какое типичное поведение пользователя?

Пользователь указывает время отправления, точки А и Б, а также выбирает предпочитаемый режим перемещения и вид транспорта. В ответ система рассчитывает и отображает время и стоимость поездки для выбранных параметров.

Чем он пользуется?

Компьютером или ноутбуком под управлением Windows 10,11 либо macOS 10.14,10.15, используя браузеры Yandex, Chrome, Edge, Opera, Firefox, Atom, IE или Safari последних и предпоследних версий. Разрешения экрана 800×600, 1280×720 либо 1920×1080.
</details>

<details>
<summary>2. Выбор конфигураций для кроссбраузерного тестирования</summary>

Сервис поддерживает:

 - Операционные системы: Win 10,11, macOS 10.14,10.15
 - Браузеры: Yandex, Chrome, Edge, Opera, Firefox, Atom, IE, Safari последних и предпоследних версий
 - Разрешения экрана: 800x600, 1280х720, 1920х1080.
 - В интернете ищем информацию об особенностях работы поддерживаемых браузеров в ОС; смотрим статистику использования браузеров по визитам за последний месяц (1-31 мая 2026 года) на Яндекс.Радаре:

#### [Windows](https://radar.yandex.ru/browsers?group=month&platform=14&selected_rows=Ct58LP%252CRysHuf%252C%252Fl27zq%252CkCujza%252Ce1IAm2%252CnmpVtr%252C%252BjXhkh%252CvDPqTi&chart_type=line-chart)
 - Yandex Browser 42,81%
 - Google Chrome 37,14%
 - Edge 9,83%
 - Opera 6,13%
 - Firefox 3,51%
 - Atom 0,16%
 - Internet Explorer 0,11%
 - Safari 0,01%
 - *основная поддержка Internet Explorer для Windows была прекращена 15 июня 2022 года, последняя версия: 11 от октября 2013
 - *разработка Safari для Windows прекращена, последняя версия: 5.1.7 от 9 мая 2012

#### [macOS](https://radar.yandex.ru/browsers?group=month&platform=15&selected_rows=Ct58LP%252CRysHuf%252C%252Fl27zq%252CkCujza%252Ce1IAm2%252CnmpVtr%252C%252BjXhkh%252CvDPqTi&chart_type=line-chart)
 - Safari 56,68%
 - Google Chrome 26,41%
 - Yandex Browser 11,17%
 - Firefox 1,45%
 - Opera 1,01%
 - Edge 0,82%
 - Atom <0,01%
*IE для macOS не поддерживается с 2005 года

Нужно покрыть тестами все комбинации ОС, браузеров и разрешений. Для уменьшения количества проверок применим попарное тестирование и автоматизируем подбор пар с помощью сервиса [pairwise](https://pairwise.yuuniworks.com).

Входные параметры:
```
os: Windows10, Windows11, macOs1014, macOs1015
browser: Yandex26.5, Yandex26.4, Chrome148, Chrome147, Edge148, Edge147, Opera132, Opera130, Firefox151, Firefox150, Atom5.11, Atom5.12,  IE11, IE10, Safari26.5, Safari26.4
size: 800600, 1280720, 19201080

if [os] = "macOs1014" OR [os] = "macOs1015"
then [browser] <> "IE11" AND [browser] <> "IE10";

if [os] = "Windows10" OR [os] = "Windows11"
then [browser] <> "IE11" AND [browser] <> "IE10" AND [browser] <> "Safari26.5" AND [browser] <> "Safari26.4";
```

<details>
<summary>Конфигурации ОС, браузеров и разрешений</summary>

| №|    OC     |  Браузер   | Разрешение |
|:-| :-------- | :--------- | :--------- |
|1 | Windows10 | Yandex26.5 |  1920x1080 |
|2 | Windows10 | Yandex26.4 |  800x600   |
|3 | Windows10 | Chrome148  |  800x600   |
|4 | Windows10 | Chrome147  |  1920x1080 |
|5 | Windows10 | Edge148    |  800x600   |
|6 | Windows10 | Edge147    |  800x600   |
|7 | Windows10 | Opera132   |  800x600   |
|8 | Windows10 | Opera130   |  1920x1080 |
|9 | Windows10 | Firefox151 |  800x600   |
|10| Windows10 | Firefox150 |  1280x720  |
|11| Windows10 | Atom5.12   |  1920x1080 |
|12| Windows10 | Atom5.11   |  800x600   |
|13| Windows11 | Yandex26.5 |  1280x720  |
|14| Windows11 | Yandex26.4 |  1280x720  |
|15| Windows11 | Chrome148  |  800x600   |
|16| Windows11 | Chrome147  |  1280x720  |
|17| Windows11 | Edge148    |  1920x1080 |
|18| Windows11 | Edge147    |  1280x720  |
|19| Windows11 | Opera132   |  1280x720  |
|20| Windows11 | Opera130   |  1280x720  |
|21| Windows11 | Firefox151 |  1920x1080 |
|22| Windows11 | Firefox150 |  1920x1080 |
|23| Windows11 | Atom5.12   |  1920x1080 |
|24| Windows11 | Atom5.11   |  800x600   |
|25| MacOS1014 | Safari26.5 |  1280x720  |
|26| MacOS1014 | Safari26.4 |  800x600   |
|27| MacOS1014 | Chrome148  |  1920x1080 |
|28| MacOS1014 | Chrome147  |  1280x720  |
|29| MacOS1014 | Yandex26.5 |  800x600   |
|30| MacOS1014 | Yandex26.4 |  1920x1080 |
|31| MacOS1014 | Firefox151 |  1280x720  |
|32| MacOS1014 | Firefox150 |  800x600   |
|33| MacOS1014 | Opera132   |  1920x1080 |
|34| MacOS1014 | Opera130   |  800x600   |
|35| MacOS1014 | Edge148    |  1280x720  |
|36| MacOS1014 | Edge147    |  1920x1080 |
|37| MacOS1014 | Atom5.12   |  1280x720  |
|38| MacOS1014 | Atom5.11   |  1280x720  |
|39| MacOS1015 | Safari26.5 |  800x600   |
|40| MacOS1015 | Safari26.4 |  1280x720  |
|41| MacOS1015 | Chrome148  |  1280x720  |
|42| MacOS1015 | Chrome147  |  800x600   |
|43| MacOS1015 | Yandex26.5 |  1920x1080 |
|44| MacOS1015 | Yandex26.4 |  1920x1080 |
|45| MacOS1015 | Firefox151 |  1280x720  |
|46| MacOS1015 | Firefox150 |  1280x720  |
|47| MacOS1015 | Opera132   |  1280x720  |
|48| MacOS1015 | Opera130   |  1920x1080 |
|49| MacOS1015 | Edge148    |  1280x720  |
|50| MacOS1015 | Edge147    |  1280x720  |
|51| MacOS1015 | Atom5.12   |  800x600   |
|52| MacOS1015 | Atom5.11   |  1920x1080 |
|53| MacOS1015 | Safari26.5 |  1920x1080 |
|54| MacOS1015 | Safari26.4 |  1920x1080 |

</details>
</details>

#### 3. Тестовая документация для вёрстки интерфейса

 - [Чек-лист](https://docs.google.com/spreadsheets/d/1e5cC66W9Dcy0O1PTM_xpG91rrTXxJ5jna_wTFOUWLUc/edit?gid=899462569#gid=899462569&range=A1) вёрстки блока формы и элементов на карте

#### 4. Тестовая документация для логики интерфейса

 - [Чек-лист](https://docs.google.com/spreadsheets/d/1e5cC66W9Dcy0O1PTM_xpG91rrTXxJ5jna_wTFOUWLUc/edit?gid=1540435533#gid=1540435533&range=A1:D1) на логику окон "Способ оплаты", "Добавление карты"
 - [Тест-кейсы](https://docs.google.com/spreadsheets/d/1e5cC66W9Dcy0O1PTM_xpG91rrTXxJ5jna_wTFOUWLUc/edit?gid=1567345705#gid=1567345705&range=A1) на кнопку "Забронировать"

#### 5-6. Тестирование и заведение баг-репортов. Подведение итогов
- Проведено тестирование вёрстки и пользовательского интерфейса сервиса "Маршруты". 
- Выполнена проверка соответствия макетам и реализация фронтенда: работа полей ввода, панелей выбора режимов и видов транспорта, а также логика окон "Способ оплаты", "Добавление карты" и функциональность кнопки "Забронировать".

- В ходе проверки выявлено 45 дефектов. Из них 20 имеют критический приоритет. Также обнаружены ошибки со стандартным и желательным приоритетом, негативно влияющие на удобство использования (UX) и репутацию продукта. Команда рекомендует исправить ошибки перед передачей продукта пользователям.

 - Всего нашли 45 багов 
 - Вот [ссылка](https://docs.google.com/spreadsheets/d/1e5cC66W9Dcy0O1PTM_xpG91rrTXxJ5jna_wTFOUWLUc/edit?gid=977751969#gid=977751969&range=A1) на баг-репорты
</details>
</details>

<details>
<summary>Тестирование мобильного приложения Метро</summary>

<details>
<summary>Задание</summary>

#### 1. Провести анализ требований к мобильному приложению Метро
#### 2. Разработать чек-лист для проведения тестирования на основе требований, выделенных полужирным шрифтом
#### 3. Написать чек-лист, который учитывает особенности мобильного приложения, для проведения регрессионого тестирования
#### 4. Выполнить тестирование мобильного приложения в эмуляторе с помощью Android Studio и завести баг-репорты в Google Таблицу 
#### 5. Подготовить отчет о тестировании
#### [Требования к мобильному приложению Метро](https://docs.google.com/document/d/1xshltciCwXPYInKNsYCOXU3peHa8ePOa9ntkA3u6zok/edit?usp=sharing)
</details>

<details>
<summary>Решение</summary>

#### 1/2. Тестовая документация: функциональное тестирование
 - [Чек-лист](https://docs.google.com/spreadsheets/d/1buLf_5diG87XFjTViHrw8ANDMLabxGokKtiC9jEQvQE/edit?gid=899462569#gid=899462569&range=A1) проверки требований, затронутых изменениями
#### 1/3. Тестовая документация: регрессионное тестирование
 - [Чек-лист](https://docs.google.com/spreadsheets/d/1buLf_5diG87XFjTViHrw8ANDMLabxGokKtiC9jEQvQE/edit?gid=1540435533#gid=1540435533&range=A1) проверки нативных функций и управления состоянием приложения
#### 4-5. Тестирование и заведение баг-репортов. Подведение итогов 
Результаты выполненных проверок
 - [Функциональное тестирование](https://docs.google.com/spreadsheets/d/1buLf_5diG87XFjTViHrw8ANDMLabxGokKtiC9jEQvQE/edit?gid=899462569#gid=899462569&range=A1)
 - [Регрессионное тестирование](https://docs.google.com/spreadsheets/d/1buLf_5diG87XFjTViHrw8ANDMLabxGokKtiC9jEQvQE/edit?gid=1540435533#gid=1540435533&range=A1)
 - [Ссылка](https://docs.google.com/spreadsheets/d/1buLf_5diG87XFjTViHrw8ANDMLabxGokKtiC9jEQvQE/edit?gid=667530685#gid=667530685&range=A1) на баг-репорты
 - [Ссылка](https://docs.google.com/document/d/1K5nGv9Ouyfojdcxlxfzo7h85GEnGZzlYfXjTNYoH7PE/edit?usp=sharing) на отчёт о тестировании Метро 
</details>
</details>

<details>
<summary>Тестирование API Прилавка</summary>

<details>
<summary>Задание</summary>

#### 1. Проанализировать требования к новой функциональности бэкенда. Изучить документацию к API в Apidoc
#### 2. Разработать чек-лист для проведения тестирования на основе требований, выделенных полужирным шрифтом
#### 3. Выполнить тестирование API через Postman и завести баг-репорты в Google Таблицу 
#### 4. Написать отчет о тестировании
#### [Требования к бэкенду приложения API Прилавка](https://docs.google.com/document/d/1l-bX4hNkhmt2tzB_-N_9s4_cRiR05IarRsgMYwiLiPY/edit?usp=sharing)
</details>

<details>
<summary>Решение</summary>

#### 1-2. Тестовая документация: новая функциональность API
 - [Чек-лист](https://docs.google.com/spreadsheets/d/1VLImydWsU0ZgQS16FDUmf8CvO_Drzerjrk2TxVSaJ5M/edit?gid=2006427015#gid=2006427015&range=A2) проверки требований, затронутых изменениями
#### 3-4. Тестирование и заведение баг-репортов. Подведение итогов 
Результаты выполненных проверок
 - [Тестирование фичи API](https://docs.google.com/spreadsheets/d/1VLImydWsU0ZgQS16FDUmf8CvO_Drzerjrk2TxVSaJ5M/edit?gid=2006427015#gid=2006427015&range=A2)
 - [Ссылка](https://docs.google.com/spreadsheets/d/1VLImydWsU0ZgQS16FDUmf8CvO_Drzerjrk2TxVSaJ5M/edit?gid=1727683287#gid=1727683287&range=A1) на баг-репорты
 - [Ссылка](https://docs.google.com/document/d/1tQZ4pMqYDtOIF2JpMgM3pw5WeJL8A12BwCMYDz0OIlA/edit?usp=sharing) на отчёт о тестировании API Прилавка
</details>
</details>

<details>
<summary>Работа с реляционными базами данных</summary>

#### [Описание базы данных](https://docs.google.com/document/d/1gU1DZFrhmjNxecHddcLXMMs4ctQEerZ5Qc92yt6sobE/edit?usp=sharing)

<details>
<summary>Задание 1</summary>

Вывести объем привлеченных средств для стартапов категории "news" в регионе "USA", отсортировав лидеров по бюджету.
### Решение 
Примененить фильтрацию (WHERE) по двум атрибутам одновременно и отсортировать (ORDER BY) по убыванию
```
SELECT funding_total
FROM company 
WHERE category_code = 'news' AND country_code = 'USA'
ORDER BY funding_total DESC;
```
</details>

<details>
<summary>Задание 2</summary>

Найти всех сотрудников, чьи названия аккаунтов начинаются на строку ('Silver')
### Решение
Использовать оператор LIKE с символом % в конце шаблона для поиска по началу строки
```
SELECT first_name,
last_name, 
network_username
FROM people
WHERE network_username LIKE 'Silver%';
```
</details>

<details>
<summary>Задание 3</summary>

Выбрать людей, у которых в названии аккаунта есть подстрока "money", а фамилия начинается на букву "K"
### Решение
Комбинировать условия LIKE '%...%' (поиск внутри строки) и LIKE '...'%' (поиск по началу строки) через оператор AND
```
SELECT *
FROM people
WHERE network_username LIKE '%money%' 
AND last_name LIKE 'K%';
```
</details>

<details>
<summary>Задание 4</summary>

Отобразить общую сумму привлеченных инвестиций, которые получили компании, зарегистрированные в этой стране
### Решение
Группировка (GROUP BY) по коду страны с применением агрегатной функции SUM, отсортировав результат по вычисляемому полю
```
SELECT country_code,
SUM(funding_total) AS total_investment
FROM company
GROUP BY country_code
ORDER BY total_investment DESC;
```
</details>

<details>
<summary>Задание 5</summary>

Получить полный список персонала с указанием учебного заведения, если данные об образовании присутствуют
### Решение
Использовать LEFT OUTER JOIN для сохранения всех записей из основной таблицы (people) при подтягивании связанных данных из справочника (education)
```
SELECT p.first_name, 
p.last_name, 
e.institution AS educational_institution
FROM people AS p
LEFT JOIN education AS e ON p.id = e.person_id;
```
</details>

<details>
<summary>Задание 6</summary>

Подсчитать общий объем сделок типа "Cash-only" за 2011–2013 годы
### Решение
Фильтрация (WHERE) по атрибуту 'cash', приведение типов даты (CAST), фильтрация диапазона дат (BETWEEN) и агрегация суммы (SUM)
```
SELECT SUM(price_amount) AS total_cash_acquisitions
FROM acquisition
WHERE term_code = 'cash'
AND CAST(acquired_at AS DATE) BETWEEN '2011-01-01' AND '2013-12-31';
```
</details>

<details>
<summary>Задание 7</summary>

Определить топ-10 стран с наиболее активными фондами (основание 2010–2012), исключив страны с нулевой активностью. 

Для каждой страны посчитать минимальное, максимальное и среднее число компаний, в которые инвестировали фонды этой страны. Отсортировать таблицу по среднему количеству компаний от большего к меньшему. Добавь сортировку по коду страны в лексикографическом порядке.
### Решение
Фильтрация дат (WHERE/CAST), группировка (GROUP BY) по коду страны, расчет (Min/Max/Average), исключение групп (HAVING), двойная сортировка, ограничения количества стран (LIMIT).
```
SELECT country_code,
MIN(invested_companies), 
MAX(invested_companies), 
AVG(invested_companies)
FROM fund
WHERE CAST(founded_at AS DATE) BETWEEN '2010-01-01' AND '2012-12-31'
GROUP BY country_code
HAVING MIN(invested_companies) > 0
ORDER BY AVG(invested_companies) DESC, country_code ASC
LIMIT 10;
```
</details>
</details>