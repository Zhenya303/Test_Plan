
## Сценарии навигации по сайту:
### Путь №1    
1. Открыть браузер, зайти на сайт https://netology.ru
2. Нажать на кнопку "Каталог курсов", выбрать направление "Программирование"
3. Выбрать раздел профессии "Тестировщик ПО", нажать на него.
4. Спуститься в низ страницы профессии "Тестировщик ПО", до формы записи на занятия.
5. Нажать на кнопку "записаться"

### Путь №2
1. Открыть браузер, зайти на сайт https://netology.ru
2. В окне "Направление обучения" выбрать раздел "Программирование"
3. Выбрать раздел профессии "Тестировщик ПО", нажать на него.
4. Нажать на кнопку "Записаться".

## Сценарии заполнения заполнения и отправки формы:

#### Сценарий записи и отправки формы №1:
1. Выполнить сценарий навигации "Путь №1"
2. Заполнить поле "Имя", валидным значением, общераспространенное российское имя, на кириллице, больше 1 символа.
3. Заполнить номер телефона Значением из 11 цифр, начинается с +7
4. Нажать на кнопку "Записаться"

Ожидаемый результат: *Появится сообщение с подтверждением успешной записи на курс*.

#### Сценарий записи и отправки формы №2:
1. Выполнить сценарий навигации "Путь №1"
2. Заполнить поле "Имя", значением на латинице.
3. Заполнить номер телефона Значением из 11 цифр, начинается с +7
4. Нажать на кнопку "Записаться"

Ожидаемый результат: *Появится сообщение c указанием что поле ввода имени заполнено не верно*.


#### Сценарий записи и отправки формы №3:
1. Выполнить сценарий навигации "Путь №1"
2. Заполнить поле "Имя", валидным значением, общераспространенное российское имя, на кириллице, больше 1 символа..
3. Заполнить номер телефона Значением из 10 цифр.
4. Нажать на кнопку "Записаться"

Ожидаемый результат: *Появится сообщение c указанием что поле ввода телефона заполнено не верно*.


#### Сценарий записи и отправки формы №4:
1. Выполнить сценарий навигации "Путь №1"
2. Оставить поле "Имя" незаполненным.
3. Заполнить номер телефона Значением из 11 цифр, начинается с +7.
4. Нажать на кнопку "Записаться"

Ожидаемый результат: *Появится сообщение c указанием что поле "Имя" обязательно для заполнения*.


#### Сценарий записи и отправки формы №5:
1. Выполнить сценарий навигации "Путь №1"
2. Заполнить поле "Имя", валидным значением, общераспространенное российское имя, на кириллице, больше 1 символа.
3. Оставить поле ввода номера телефона незаполненым.
4. Нажать на кнопку "Записаться"

Ожидаемый результат: *Появится сообщение c указанием что поле "Имя" обязательно для заполнения*.

## Инструменты

1. Браузер Google Chrome
2. JDK InteliJ Idea
3. Gradle
4. Язык Java
5. Junit4
6. Lombok
7. Selenide
8. Gradle
9. Allure

## Разрешения

1. Разрешение владельцев сайта netology.ru
2. Доступ к тестовой базе данных.
3. Доступ к API


## Риски при автоматизации
1. Частое обновление ВЭБ интерфейса

## Специалисты

1. 1 тестировщик автоматизатор

## Интервальная оценка времени

1. 24 часа

