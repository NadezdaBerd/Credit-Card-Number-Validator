# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

30.03.2021 было проведено функциональное тестирование Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлен дефект:
* Не принимается номер карты системы American Express в Credit Card Number Validation 
  https://github.com/NadezdaBerd/Credit-Card-Number-Validator/issues/1#issue-843973402: https://github.com/NadezdaBerd/Credit-Card-Number-Validator/issues/1#issue-843973402


## Описание процесса тестирования

В процессе тестирования использовались:
* код программы
* чек-лист изменения кода



В качестве тестовых данных использовались данные [freeformatter.com](freeformatter.com):
* номер карты системы Виза 4716402075057732, ожидаемый результат: вывод кода Result OK.
* номер карты системы MasterCard 5544294875185846, ожидаемый результат: вывод кода Result OK.
* номер карты системы Visa Electron 4917028051585581, ожидаемый результат: вывод кода Result OK.
* номер карты системы Маэстро 6304618595060038, ожидаемый результат: вывод кода Result OK.
* номер карты системы American Express 342753611723603, ожидаемый результат: вывод кода Result OK.

Тестирование производилось в следующем окружении:
* Microsoft Windows Version 10.0.19041.867, х64
* версия Java 11.0.10