# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

17.09.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Валидный номер карты (19 цифр) считается невалидным в Credit Card Number Validator](https://github.com/Ingask/Zadanie02Lection01/issues/1#issue-703399944)
* [Валидный номер карты (14 цифр) считается невалидным в Credit Card Number Validator](<https://github.com/Ingask/Zadanie02Lection01/issues/2#issue-703404890>)
* [Валидный номер карты (15 цифр) считается невалидным в Credit Card Number Validator](<https://github.com/Ingask/Zadanie02Lection01/issues/3#issue-703411827>)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* https://github.com/netology-code/javaqa-homeworks/tree/master/intro

В качестве тестовых данных использовались данные https://freeformatter.com/credit-card-number-generator-validator.html:
* 4024007191862678907, 6011511999480107420 с ожидаемым результатом ОК
* 30014125302740 с ожидаемым результатом ОК
* 372525495633477 с ожидаемым результатом ОК

Тестирование производилось в следующем окружении:
* Windows 10
* Java 11.0.8
