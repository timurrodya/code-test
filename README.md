# Тестовое задание Freelancehunt

## Quest 1 🏆
Вы присоединились к небольшому стартапу из 8 человек, который предоставляет путешественникам возможность отмечаться из разных стран 
и строить карту своих путешествий, а также следить, где побывали из друзья.  
Менеджер по продукту Евгений очень рад, что в команде наконец появился разрабочик, и передал вам файл `input.csv`, 
в котором он вручную отслеживал пользователей и очень просил все автоматизировать. Например, он знает, с какого IP 
отмечались пользователи, но не знает, какая это страна или город.
Вы уточнили у Евгения значения колонок в файле: 

| Колонка            | Описание                                                                                       |
|--------------------|------------------------------------------------------------------------------------------------|
|  name              | Имя путешественника. Имя уникально: если Ольга встречается два раза, это один человек, но Ольга и Olga — разные люди |
|  checkin_date | Дата чекина из определенной страны                                                                               |
|  ip                | IP адрес, с которого путешественник отметился                                                  |
|  rating            | Рейтинг, полученный за отметку в стране                                                                        | 
|  country           | Любимая страна путешественника                                                                                         |
|  is_active         | Активен путешественник или нет                                                                 |

### Какие перед вам стоят задачи? 🧠

1. Создать структуру базы данных под исходные данные
2. Загрузить исходные данные в базу
3. Обогатить данные информацией о стране и городе, с которой пользователь отметился (по IP)
4. Ответить на вопросы Евгения:
    * Кто побывал в наибольшем количестве городов?
    * В каком городе бывали чаще всего? 
    * Какое самое распространенное имя путешественика?
    * Кто из путешественников получил максимальный рейтинг за чекин в Украине?

## Условия

1. Язык реализации: PHP 7.1+
2. База данных: MySQL-совместимая
3. Тип приложения: на ваше усмотрение (консольный скрипт или веб-приложение)
4. Получение геоданных по IP: на ваше усмотрение
5. Тесты, без них никак 🏅
6. Код вместе с инструкцией по запуску на Github 

## Quest 2 🏆
Команда стартапа решила предложить пользователям что-то новенькое, ведь на одном чекине далеко не уедешь. После мозгового штурма вам, как одному из самых технически подкованных членов команды, поручили разработать архитектуру нового сервиса: на нем хозяева квартир и домов будут размещать страницы с описанием своего жилья, а путешественники будут присылать им свои заявки переночевать на доступные даты. 

Исходные условия:

* Команда уверена, что такой сервис всем нужен и это будет высоконагруженный проект
* Сервис будет работать в разных странах, но большая часть пользователей будет заходить из одной страны
* Бекенд на PHP — так как в команде уже знают этот язык
* Нужно предусмотреть API доступ к функционалу сайта
* Важно обеспечить отказоустойчивость в случае сбоя сервера или DDoS атаки 

Результатом вашей работы будет архитектурна диаграмма, а вопросы ниже помогут вам нарисовать ее:

* Где вы разместите инфраструктуру? Будет ли это облако или своя стойка в датацентре?
* Сколько серверов вам понадобится?
* Как вы обеспечите отказоустойчивость?
* Какую базу данных вы используете? Нужен ли вам будет кеш?
* Как вы обеспечите безопасный доступ к сайту?

# Что дальше?
Ответы на вопросы отправляйте на join@freelancehunt.com — мы их оценим и сможем обсудить на Skype-интервью. Желаем удачи! 🤞
