# Мой путь в IT

> [!TIP]
> Если вы не хотите тратить время на предысторию, то можете сразу перейти к интересующим вас частям.

### Что было до IT

1. Мое знакомство с программированием началось в школе, где мы изучали **Basic**, и в университете, где немного изучали **Pascal**.
   Школьное обучение было несколько углубленное за счет факультативных занятий, но в университет программирование было
   непрофильным предметом.
2. Далее периодически увлекался как хобби **Visual Basic** и **C#**.
3. Несколько лет занимался программированием микроконтроллеров *Pic16* и *Pic18* на **Assembler** и совсем немного
   *Pic32* на **C**. Проектов в репозиториях нет, в то время не пользовался git. Основным был проект стенда для проверки ТНВД
   и форсунок, но не закончен из-за отказа напарника разрабатывать аппаратную и механическую части. Было мной реализовано:
   - драйвер ps/2 клавиатуры
   - драйвер 4-строчного ЖК дисплея с управлением по шину I2C
   - предаврительное управление насосом ТНВД
4. В начале 2018 на волне интереса к криптобиржам переписал найденный в сети Python-код для считывания данных валютных пар,
   дополнил его доступом к нескольким биржам и сделал вывод данных в Excel для анализа арбиртажа между биржами.

### Обучение

В конце 2018 года я решил сменить профессиональную деятельность и заняться программированием как профессией.
Обучался я всегда самостоятельно по книгам (крайне редко - по видеокурсам).

1. С конца 2018 по март 2019 я изучал фронтенд. Я не планировал работать в этой области, но хотел иметь некоторое
   представление об общих принципах работы фронтендером. Были изучены **HTML/CSS**, **JavaScript** и **jQuery**.
2. Далее я начал изучать **PHP**, так как на тот момент по этому языку был больше предложений о работе. Более-менее
   значительным был проект по написанию веб-калькулятора для расчета стоимости лестницы в коттеджи.
   Его можно посмотреть в моем [репозитории Stairs](https://github.com/TreasureMaster/Stairs).
   Проект не был дописан по нескольким причинам: наша бригада по сборке и установке лестниц распалась плюс на тот момент
   не хватило знаний по фронту.
3. Чтобы расширить недостающие знания я начал изучать **Bootstrap**, который впоследствии часть применял. А также
   начал изучать **Vue.js**, но не закончил.
4. Далее по предложению друга перешел к изучению **Python** (чтобы писать своместные проекты). Где-то с февраля 2020
   в течение года я учил **Python**, **Flask** и различные библиотеки (н-р, **tkinter**).
   Совместный учебный проект есть в [репозитории validation-calculator](https://github.com/ezik117/validation-calculator/tree/alu).

### Периоды работы в IT

1. с марта 2021 по июнь 2021 - работа (как стажировка) на фрилансе для студентов. Всего было выполнено около 20 работ с марта по июнь 2021.
   Ниже приведены ссылки на некоторые работы:
   - Каталог книг на фреймворке Kivy ([ссылка на репо](https://github.com/TreasureMaster/11052021_book_catalog_2))
   - Финансовые отчеты организации на Flask и MS SQL ([ссылка на репо](https://github.com/TreasureMaster/09062021_webfinance))
2. с июля 2021 по август 2021 постоянно и далее до начала 2022 эпизодически разрабатывалась GUI на **tkinter**
   для управления, прошивки, мониторинга блоков управления отопителей грузовых автомобилей по шине LIN. Проект был заморожен
   вначале из-за отсутствия времени на его постоянную разработку и в дальнейшем из-за известных мировых событий.
   Ссылка на [репозиторий](https://github.com/TreasureMaster/PreheaterService/tree/firmware). Текущая ветка - *firmware*.
   Тех.стек в эти 2 периода:
   - языки программирования: Python, PHP, JavaScript
   - фронтенд: Bootstrap, jQuery
   - бэкенд фреймворки: Flask, Django (последний мало)
   - базы данных: MySQL, SQLite, MS SQL
   - GUI: tkinter, kivy
   - обработка данных: jupyter notebook, kaggle datasets, pandas, matplotlib
   - протоколы связи: pySerial, LIN
   - VCS: git, github
   - документирование: gitbook
   - ОС: Windows
3. с августа 2021 по март 2022 - постоянная работа программистом в ["Орби Системс"](https://www.orbismap.ru/). В период работы
   перешел на ОС Linux, изучил docker, выполнял небольшие задания по devops (н-р, сборка образов, содержащих библиотеки
   для работы с геоданными на Ubuntu/Debian), написал брокер сообщений (по упрощенному типу RabbitMQ) на асинхронном
   фреймворке **aiohttp**, вносил небольшие изменения в основной проект организации.
   Стек технологий, используемый мною в работе:
   - языки программирования: Python
   - бэкенд фреймворки: Flask, aiohttp
   - базы данных и ОРМ: PostgreSQL, SQLAlchemy.
   - devops: docker, docker-compose, makefile
   - VCS: git, gitlab, mercurial
   - ОС: Linux
   Примеры проектов выставить невозможно из-за соглашения о конфиденциальности.
   Пример выполненного [тестового задания](https://gitlab.com/TreasureMaster/test_ka).
4. с марта 2022 по настоящее время - работа на фрилансе. Выполнено 8 заданий (в основном GUI-оболочка к базе данных).
   Один из примеров [GUI на tkinter и PostgeSQL](https://github.com/TreasureMaster/guidb_estate_register).
   Есть другие варианты, написанные с БД **MariaDB** и ОРМ **SQLAchemy**.
   Стек технологий, используемый мною в текущих работах (будет периодически обновляться):
   - языки программирования: Python
   - бекенд фреймворки: Flask, Django
   - фронтенд: Bootstrap
   - базы данных: PostgreSQL, MySQL, MariaDB
   - ОРМ: SQLAlchemy, самописная ОРМ на базе psycopg2
   - GUI: tkinter
   - очереди: Celery (Redis, RabbitMQ)
   - архитектуры, протоколы: RESTful
   - VCS: git (github)
   - документирование: Gitbook
   - ОС: Linux, Windows

### Ближайшие планы на будущее

1. Углубленное изучение **Django**
2. Системное администрирование Linux
