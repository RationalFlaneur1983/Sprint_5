# Спринт №5 UI-тестирование
Проект по UI-тестированию Яндекс.Практикум (Автоматизация тестирования)

Задание содержит автотесты для сервиса Stellar Burgers. Это космический фастфуд: можно собрать и заказать бургер из необычных ингредиентов. Это учебное приложение: его написал студент Практикума на курсе «React-разработчик».

## Описание тестов:
[test_registration.py](https://github.com/RationalFlaneur1983/Sprint_5/blob/main/tests/test_registration.py) проверяет регистрацию и ошибку регистрации при введении невалидного пароля

[test_login.py](https://github.com/RationalFlaneur1983/Sprint_5/blob/main/tests/test_login.py) проверяет вход в аккаунт из разных разделов сайта

[test_navigate_to_personal_account.py](https://github.com/RationalFlaneur1983/Sprint_5/blob/main/tests/test_navigate_to_personal_account.py) проверяет переход в личный кабинет по клику

[test_navigate_to_constructor.py](https://github.com/RationalFlaneur1983/Sprint_5/blob/main/tests/test_navigate_to_constructor.py) проверяет переход из личного кабинета в конструктор 

[test_logout.py](https://github.com/RationalFlaneur1983/Sprint_5/blob/main/tests/test_logout.py) проверяет выход из аккаунта

[test_navigate_bw_sections_of_the_menu.py](https://github.com/RationalFlaneur1983/Sprint_5/blob/main/tests/test_navigate_bw_sections_of_the_menu.py) проверяет переходы по разделам в конструкторе

## Дополнительный функционал:
В тестах реализован функционал создания рандомного имени пользователя, email, пароля, а также невалидного пароля: data_randomizer.py
