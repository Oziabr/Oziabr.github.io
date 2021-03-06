---
date: 2018-06-03
tags: [cavart, knowledge]
---

# Почему умирали хакерские традиции?

Содержит ответы на вопросы:
- почему такой звездец в ИТ
- как вернуть пользователям контроль над контентом

## В двух словах

Корпорации убивают знание.

## Хакерская культура

Это гаражные мастера цифрового мира.
Люди, решающие сложные задачи ради интеллектуального или эстетического удовольствия.
Или ещё проще: потому что могут.

Сильная хакерская культура существовала в 70-х и 90-х годах прошлого века.
Культура 70-х умерла из-за судебных рисков - никто не хотел работать с технологией, за которую могут наказать.
Культура 90-х маргинализовалась, и к 10ым годам в мейнстрим попадают только старые их наработки (e.g. Linux).

## Интеллектуальная собственность против знания

ИС - это попытка корпораций приватизировать знание.

Но для знания приватизация губительна.
Просто посмотрите где оказался советский НТК, параноидально секретивший любые разработки.
И сравните с проектами, финансировавшимися ообороной США (UNIX, интернет, OracleDB).

Здесь мы имеем конфликт интересов:
1. Корпорации хотят зарабатывать
2. Корпорации не умеют зарабатывать на знании иначе чем через ИС.
3. Знание ставшее ИС портится.

То, что хорошо работает в авторском праве: автор придумывает новый оригинальный контент, и контролирует его развитие.
Защита авторского контента побуждает других создателей искать новые оригинальные варианты, которых в творческом поле бесчётное множество.
АП не препятствует ни распространению знания, ни даже независимой работе с ним (фанфики).


Не работает в ИС, где оптимальное решение зависит от платформы (до квантовых компьютеров она была одна, с небольшими вариациями),
и задачи (которые общие для индустрии).
Поэтому присвоение корпорацией оптимального решения бьёт по среде, заставляя других учасников костылестроить неоптимальные решения.

Это всё привело к кризису 70-х.

## Новые способы убийства знания

Когда стало ясно, что ИС не работает: патентовать алгоритмы не вышло, а попытка патентовать строки кода привела к замене строк
на оригинальные в спорных продуктах. Корпорациям пришлось искать другие способы заработать на знании.

### Майкрософт и присвоение контента

Майкрософт ловко сыграл на печатной революции.

В доофисные времена люди свободно писали и обменивались текстами с помощью модемов, и казалось, что вот она свобода:
пользовательский контент свободен, децентрализован.
И этот фарш не провернуть назад.

И тут МС дал пользователям **Word**, позволивший печатать красиво оформленные документы.
Можно подумать, что это сделало тексты свободнее предоставив для них новую среду.
Но печатный текст теряет большую часть свойств текста электронного:
- лёкгость редактирования и цитирования
- лёгкость хранения и передачи
- лёгкость индексации и поиска
Инструменты сканирования и распознавания до сих пор не достаточно широко распространены, что бы устранить эти недостатки.

Но было уже продано.
Купившись на красивую печать мир потерял куда больше, чем распечатанный текст.

Не отделив контент от представления (текст от типографики) МС сделал пользовательский контент заложником офисного пакета:
- прочитать файлы теперь стало можно только при помощи **word**
- причём только достаточно новых версий
- копировать из **word** без бубна не удавалось - копировались "непечатаемые символы" накапливавшиеся в тексте процессе работы с ним
- в какой-то момент МС добрался до буфера обмена, и стал пихать туда текст в перемешку с форматированием, которое понимал сам хорошо, а вот сторонним приложениям приходилось справляться с этим недокументированным мусором самостоятельно
- любые структуры (e.g. оглавление) рассыпались при выносе текста из офиса

Получилась удивительная история, совершенно не вероятная во времена фидонета и раннего емейла: пользователи стали приносить свой контент и своё удобство в жертву тренду.

Да, тренду, не красивой печати.
Для красивой печати в издательствах использовались другие инструменты, поддержка которых требовала специально обученных редакторов.

### WWW и приватизация знания

Бум доткомов серидины - конца 90х донёс "гениальную" идею Интеллектуальной Собственности до авторов контента.
Появилась среда, обещавшая любому желающему возможность лично публиковать свой контент.
Такая маленькая персональная централизация для всех.

Казалось, что вот наконец тексты перестанут бродяжничать по фидо-эхам и обретут седе давно заслуженный домик.
Всё так и вышло, но потребовалось некоторое время что бы осознать, что домик стоит на зыбучих песках, а вокруг него минное поле.

Контент начал умирать по куче причин:
1. основной из которых был хостер
    - аварии и несвоевременные бэкапы - и ваш сайт превращается в тыкву.
    попробуйте найти у себя резервную копию.
    - дыры в хостерском софте (позже в CMS) и ваш контент превращается в жизнерадостную жопу с ушами.
    куда всё делось - хостер не знает.
    - забыли заплатить и ваш аккаунт анулирован, а контент восстановлению не подлежит
2. вебмастера вызвались помогать с публикациями технически не грамотным пользователям
    - они пропадали вместе с аккаунтами к хостингу и доменам, окирпичивая сайты
    - ошибались и ломали публикации
    - начинали вымогать деньги за свои незаменимые услуги
3. программисты подключились позже, когда пришли хайп на динамические сайты и CMS - системы автоматической публикации
    - делали все предыдущие пункты
    - решали проблемы программированием превращая их в ещё большие проблемы - в какой-то момент никто не мог поддерживать CMS и приходилось либо бросить, либо нанимать новых программистов что бы сделали всё с нуля
4. последними в оргию включились контентные платформы (e.g. **wix**, **Тильда**), они оказались значительно гуманнее предшественников:
    - просто зарабатывали на авторах либо размещая рекламу, либо собирая взносы

### Социальные сети и обесценивание контента

Социальные сети взяли у поисковиков идею, что зарабатывать на знании можно аккумулируя его.
Но изменили пассивную стратегию поисковиков на активную:
не стали ждать пока пользователи сами о себе что-нибудь сообщат, начали их к тому активно подталкивать.

Авторский контент в этой истории пал жертвой обстоятельств.
Соцсетям нужно что бы пользователи взаимодействовали между собой,
но идеальные взаимодействия с их точки зрения - обмен лайками, стикерами и поздравлениями.

Только **ЖЖ** не может найти себе места - он задумывался как платформа для публикации длинных текстов,
и теперь ни заработать не может, ни пользователей удержать.

**Твиттер** - просто опофеоз экономики соцсетей.

**Facebook** позволяет писать длинные тексты, но их выдача в ленте не приоритетна и их мало кто видит.

И задача вытащить свой контент из соцсети для переноса, или просто что бы поискать, не является тривиальной.

## Корпорации и хакеры

Помимо того, что корпорации разрушают информационную экосистему, они ещё и прямо борются с хакерами.

Когда у тебя многомилионный бизнес, продающий фальшивые ёлочные игрушки,
и десятитысячная армия программистов, производящая сама для себя баги и героически их закрывающая.
Тебе совсем не нужен гаражный умелец Вася, который по приколу запускает космические корабли.
Твой имидж от этого страдает, продажи падают.

Методы повторяют историю борьбы со знанием:
- 80-е показали что суды не сильно помогают, и правовое давление с тех пор спало
- стали изготовлять суперсложные, блестящие, и очень дорогие инструменты (часто бесплатные для студентов).
  помогло не всем, и не на долго.
  плюс все, кому помогло - вымерли (e.g. flash).
  когда технология была интересная - хакеры развивали её самостоятельно (e.g. postgreSQL заменил OracleDB)
- стали платить безумные деньги работающим с бестолковыми технологиями (e.g. Java, и яростное продвижение ООП в другие языки)
- стали просто собирать талантливых ребят под своим менеджментом, что бы контролировать их активность (Google и остальная кремниевая долина)
- просто пропаганда - выставить независимых мастеров дураками и изобретателями велосипедов (кто бы говорил, конечно)

Это бы давно прошло, если бы успешно запустившие ракету хакеры не начинали строить собственную корпорацию.
В результате индустрия бегает за своим хвостом, подбирая крошки у хакеров.
Часто очень черствые крошки из прошлого века.

## Что же делать с контентом?

Для начала попробуйте провести внутри себя ревизию, во сколько вы оцениваете продукты своего интеллектуального труда?
Все описанные события не были возможны без того, что инструменты стали дороже продуктов труда.

Пока пользователи жертвовали свои мысли и тексты корпоративной маммоне, проблему решили те самые хакеры 90-х, ушедшие из мейнстрима.

В начале нулевых Линус Торвальд создал (для разработки линукса) **git** - распределённую систему контроля версий.
Репозиторий в **git** - это дерево актуальных файлов и история их изменений, в которой можно порыться специальными командами или инструментами.
Сделан для совместной работы.

Примерно тогда же Джон Грубер создал текстовый формат **markdown** - естественный формат для структурированного текста.
Он позволяет писать текст в стиле раннего емейла, но с заголовками, цитатами, ссылками и всем остальным что может потребоваться автору.
Идеальный формат для работы с текстом, не требующий вспомогательных инструментов.

В 2008 был создан [github.com](github.com), объединивший эти технологии в облачной CMS.

Сейчас, 10 лет спустя, это самая стабильная и высоконагруженная облачная платформа.
Инструментарий для работы с текстами не является для неё основным (приоритетен программный код, который немножко другой текст),
но активно используется для документирования.
На столько активно, что иногда на нём пишутся книги.

Так же он предоставляет другие инструменты для организации работы: трекер задачь, вики, и даже хостинг статических веб-страниц.
Всё по цене $0.

## Леденящие новости

Позавчера (2018-06-01) посыпались новости о возможном приобритении github Майкрософтом.

Это, конечно, пичально.
Но не опасно: github - просто сервис.
Технологии, на которых он стоит, его переживут.
Заменить его для частного использования можно за 15минут - есть больше дюжины продуктов.
Развернуть облачную инфраструктуру можно за месяц.
