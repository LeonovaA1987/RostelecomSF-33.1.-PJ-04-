# RostelecomSF-33.1.-PJ-04-

Тестирование авторизации/регистарции "Ростелеком"

Тестируемый сайт:  https://b2c.passport.rt.ru/

При разработке тест-кейсов использовались следующие  техники тест-дизайна:
1.Метод «черного ящика» - используется для всех тест-кейсов.
2.Позитивное и негативное тестирование - всех полей ввода форм регистрации и авторизации.
3.Классы эквивалентности и анализа граничных значений - для тестирования полей ввода формы регистрации.
4.Тестирование состояний и переходов

Инструменты:
1.PyCharm 
2.DevTools 
3.Elements locator

Шаги по запуску тестов:
1.Установить requirements (Python3, библиотеки: PyTest , PyTest - Selenium; PageObject, Smart Page Object):
pip3 install -r requirements.txt
2.Скачать драйвер для вашей версии браузера
3.Запустить тесты:
python -m pytest -v --driver Chrome --driver-path ...

Тест-кейсы для сайта "Ростелеком":
https://docs.google.com/spreadsheets/d/1eGGR8rxzZRRzJdu-IAVujER2LjD8lk056ZKo5DoFHwU/edit?usp=sharing
