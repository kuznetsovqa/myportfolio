# В портфолио собраны мои проекты, выполненные во время обучения на расширенном курсе "Инженер по тестированию плюс" в Яндекс.Практикуме.

## 1)Проведение регрессионного тестирования и ретеста багово приложения "Mesto" , ссылка на приложение https://code.s3.yandex.net/qa/files/mesto/index.html
Были проанализированы требования, регрессионное тестирование происходило по тест-рану в Яндекс TMS https://tms.devexplab.ru/projects/kuznetsov-mars09-mesto/testcases
Тестовое окружение Safari версии 16.1 на MacOS Ventura 13.0.1

По итогам тестирования найдены баги, в количестве 7 штук, в том числе несколько тривиальных, которые не помешают пользователю

Баги оформлены в Яндекс Трекере:

https://tracker.yandex.ru/BUGSPLUS-48621

https://tracker.yandex.ru/BUGSPLUS-48663

https://tracker.yandex.ru/BUGSPLUS-48643

https://tracker.yandex.ru/BUGSPLUS-48683

https://tracker.yandex.ru/BUGSPLUS-48688

https://tracker.yandex.ru/BUGSPLUS-48692

https://tracker.yandex.ru/BUGSPLUS-48710


Так же был проведен ретест уже ранее зарегистрированных багов и их актуализация в Яндекс Трекере.


## 2) Проведение тест-анализа (декомпозиция требований,визуализация, поиск серых зон) в приложении Яндекс Маршруты
Были проанализированы требования к приложению в системе Wiki. [https://praktikum.notion.site/e9cf030bce59462cbcc25a78263f8ae8](https://wiki.yandex.ru/homepage/trebovanija-k-jandeks.marshruty/)https://wiki.yandex.ru/homepage/trebovanija-k-jandeks.marshruty/

По итогам работы были проанализированы, декомпозированы требования и создана визуализация MindMap в Miro. 

Ссылка: https://miro.com/app/board/uXjVPvvwFSw=/?share_link_id=649952421705

![MindMap](https://github.com/kuznetsovqa/myportfolio/blob/main/Mind%20Map.jpg)

Так же визуализирован алгоритм выбора скорости транспорта в зависимости от времени начала поездки, был выбран один вид транспорта - собственный автомобиль и создана блок-схема в draw.io 

Ссылка:https://drive.google.com/file/d/1rBY2lZ78seUuiw-hHqtrTVRIRk2VF9sG/view?pli=1

![Блок-схема](https://github.com/kuznetsovqa/myportfolio/blob/main/Блок-схема.png)


## 3) Спроектированы проверки для новой версии веб приложения "Яндекс Маршруты", форма добавления прав
Применены такие техники тест-дизайна, как классы эквивалентности и граничные значения для формы добавления прав при выборе транспорта "Каршеринг", на основе данных техник созданы тест-кейсы для проверки.

Ссылка на требования в Wiki: https://wiki.yandex.ru/homepage/trebovanija-k-jandeks-marshruty-2.0/trebovanija-k-funkcionalnosti-karshering/

Ccылка на таблицу с классами эквивалентности и граничными значениями: https://docs.google.com/spreadsheets/d/1JPUnfIJbJ0tfConfFgttBw139m_gtdr7ZoaUHbGjb-o/edit#gid=0

По реузльтатам работы создан чек-лист в Яндекс TMS  для раздела "Каршеринг":https://tms.devexplab.ru/projects/kuznetsov-3sprint/testcases

Так же созданы тест-кейсы для кнопки "Забронировать": https://tms.devexplab.ru/projects/kuznetsov-3sprint-testkeys/testcases

![Классы эквивалентности и граничные значения](https://github.com/kuznetsovqa/myportfolio/blob/main/Таблица%20КЭ%20и%20ГЗ.png)



## 4) Проведено тестирования веб приложения "Яндекс Маршруты" , форма добавления прав, а так же новый функционал "Аэротакси" 

Для тестирования новой функциональности, применялся сниффер Charles Proxy, так как бэк часть данного функционала еще не готова, целью было протестировать фонтенд часть новой функции.

В работе использовались такие функции как Break Point на вид тнанспорта и MapLocal для автозамены.

Ссылка на мою работу с Charles:https://drive.google.com/drive/folders/1KELVB2O-J4Lupbk12EY_QDKbP3zv1BBJ



![Charles](https://github.com/kuznetsovqa/myportfolio/blob/main/Charles.png)

![Charles2](https://github.com/kuznetsovqa/myportfolio/blob/main/Charles2.png)




Приложение было протестировано в Яндекс Браузере и Mozila, в том числе протестирована вёрстка. По результатам оформил баги в Яндекс Трекер:
https://tracker.yandex.ru/BUGSPLUS-80722

https://tracker.yandex.ru/BUGSPLUS-80724

https://tracker.yandex.ru/BUGSPLUS-80727

https://tracker.yandex.ru/BUGSPLUS-80729

https://tracker.yandex.ru/BUGSPLUS-80742

https://tracker.yandex.ru/BUGSPLUS-80733


Так же мной была протестирована валидация полей "Откуда" и "Куда" и оформлены баг-репорты в Яндекс Трекере:
https://tracker.yandex.ru/BUGSPLUS-80775

https://tracker.yandex.ru/BUGSPLUS-80779

https://tracker.yandex.ru/BUGSPLUS-80780

https://tracker.yandex.ru/BUGSPLUS-80781

https://tracker.yandex.ru/BUGSPLUS-82096

https://tracker.yandex.ru/BUGSPLUS-82091


В ходе тестирования в Яндекс Браузере Яндекс Маршрутов 2.0, наличие нового вида транспорта аэротакси в режиме “Свой” и отображение расчета стоимости и времени,выявлен баг с критичным приоритетом, так как название нового вида транспорта не отображается. В связи с этим дана рекомендация исправления данного бага до релиза.

## 5) Выполнял роль тест-лидера в командных проектах по проведению тестирования приложений Stellar Burgers,Продуктовый момощник и KittiGram 

Ссылка на требования Stellar Burgers: https://wiki.yandex.ru/homepage/trebovanijakstellarburgers/

Ссылка на макеты Stellar Burgers: https://www.figma.com/file/7v96lSaXZov0qXKZDnAHLT/Burger?node-id=0%3A1

Было проведено тестирование данного приложения, все известные требования были покрыты созданным нами чек-листом, зарегистрированы баг-репорты в YouTrack, так же была создана визуализация требований данного приложения в Miro.

По результатам всех работ создан отчёт о тестировании, ссылка на отчёт: https://docs.google.com/document/d/1UtWeMIeU9Pe2FXpRFRhxLMSE3Ps3NgaGtrfWxB4-ixo/edit













































