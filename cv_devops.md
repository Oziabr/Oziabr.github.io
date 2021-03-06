# Юрий (oziabr) Твардовский

![](https://avatars0.githubusercontent.com/u/5451508)

> +7 999 872 13 05
> oziabr@gmail.com

Больше всего люблю налаживать сложные процессы, поэтому ушел из разработки в devOps. Ещё из-за своей продуктовой ориентированности.

Делаю, исторически, из подручных ресурсов - супердёшево. При этом мои законченные проекты имеют запас прочности на века (ничего сложного, просто оцениваю big "O" и применяю подходящие решения).

Предпочитаю мягко оптимизировать процессы вместе с командой, но могу и жестко всех построить, если надо.

Знаю очень мало (весь цикл жизни продукта, но не бросаюсь на новое), разбираюсь в задачах любой сложности очень быстро.

## Экспа

За 18 лет в разработке реализовал три проекта для средних команд (5-15 devs) и готов браться за крупные - эта облась масштабируется линейно, надо просто брать и делать.

### CD, управление разработкой
> Подготовка
- Запилил отдел тестирования (manual + auto) с нуля, руками стажеров
- Научил базу храниться в гите (ни одного готового решения не нашел, пришлось писать)
- Написал методички для персонала и руководства
> Система
- деплой: vhosts-PHP, nodejs, nginx
- сборка: composer, gulp
- cvs: github (смигрировал с gitlab - ускорение изменений)
- флоу: git-flow (смигрировал с branch based - ликвидация конфликтов)
- CD: striderCD
- трекер: redmine
> Результат
- Переход от ручной тяги на автоматизированные процессы

### CI/CD, исправление процессов
> Подготовка
- Написал методички, собрал прототипы
- Внедрил линтер (девы имеют неприятное свойство бесконечно спорить о феншуйности скобок и пробелов. линтер не только лишает их этой возможности, но и позволяет контролировать качество кода)
> Система
- деплой: docker
- сборка: ansible, npm
- cvs: bitbucket
- флоу: serial branches (смигрировал с поломанного git-flow - под передачу кода в эксплуатацию)
- CD: circle-ci
- трекер: jira
> Результат
- Исчезли мерж-конфликты, которым лид посвящал одну неделю в месяц
- Неудачные коммиты (которых стало меньше) перестали ломать тестовый инстанс
- Появились метрики качества кода

## Прочее
- стек: nodejs, postgresql, nginx, debian, docker
- ci/cd: могу на консольном гите и CGI, и естественно jenkins, teamcity (нахрена оно надо, travis лучший, лол)
- админ сетей, линуксов и freebsd-ей
- DBA - иногда
- fluently speak English and able to conduct serious negotiations with native speakers (and they love me!)

## Опыт разработки

### 2015-2017
> Globalpas (тимлид, группа из пяти фулстек программистов)
- Разработка платформы управления продажами
  - задизайнил и заимплементил DB-level per resource role access control
  - задизайнил и заимплементил конфигурируемый калькулятор KPI
  - смигрировал приложение с PHP на NodeJS (помодульно, не ломая приложение и UI)
  - заимплементил систему пользовательских настроек
  - создал открытый модуль для автоматической генерации меню исходя из доступных действий https://github.com/Oziabr/ui-menu
- привёл разработку к единообразному виду
  - перевёл разработку на git-flow
  - мигрировал репозиторий на github
  - создал CI для автоматического обновления тестовых серверов
  - создал группу QA (2 человека ручное+авто тестирование, контроль изменений от разработчиков) - нанял, обучил
> Angular, YII2, Sailsjs, PostgreSQL

### 2013-2014
> AMF (Ведущий разработчик, группа из пяти фронт/бэк разработчиков)
- Реанимировал электронный магазин
  - откопал и восстановил старую корзину заказав (по просьбе маркетинга)
  - починил узкие места
- восстановил позицию и инструментарий контент-менеджмента в системе - нанял, обучил
> JQuery, Angular, Generic PHP, MySQL

### 2012
> BeeLine (Старший разработчик)
- Разработка инвентарной системы для группы компаний
  - заимплементил контроль доступа
  - интегрировал геокодер
> JQuery, Apex, Oracle

### 2011
> TKS-Bank (Разработчик)
- Разработка различных маркетинговых веб-приложений
  - конструктор форм для отдела кредитования и любого другого сложного анкетирования
  - интегрировал геокодер
  - виджет интеграции для партнёров (оплата в кредит)
  - обновил калькулятор сбережений
> JQuery, PHP, Java, PostgreSQL

### 2005-2010
> RTComm Developer (Разработчик)
- Разработка ERP системы для регионального интернет-провайдера (учёт задачь и ресурсов, мониторинг)
  - заимплементил интеграцию с бухгалтерией, инвентарной системой, мониторингом и EIP
  - допилил открытый мониторинг под задачи бизнеса
  - заимплементил модуль агреггирования данных cbQoS
  - обновил несколько подсистем инвернтарная, учёт задачь
  - создал дашборд с визуализацией деградации сервиса для NOC
> Java, JQuery, Apex, Oracle, PostgreSQL

## Работадателю
Большой плюс - bullshit free. Жизнь коротка, сделать надо дофига, тратить время на мозгоёблю - зачем? Указатели гроссовых зарплат, вы вот подумайте: вы разводите работника, а потом он будет либо туповат, либо искать способ развести вас (за ваши же деньги).

Внядрять какую-нибудь бессмысленную свистелку за которые откат уже получен - сразу идите лесом, оно же вскроется через неделю.

Орать на людей и истерить - нельзя. Рабочее пространство обязано вентилироваться.

