# Отчёт о тестировании "Credit Card Number Validator".

## Краткое описание
08.05.2021 г. было проведено функциональное тестирование на компонентном уровне приложения "Credit Card Number Validator".

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* Баг-репорт №1 - https://github.com/Ekaterina5885/DZ-1.1/issues/1
* Баг-репорт №2 - https://github.com/Ekaterina5885/DZ-1.1/issues/2
* Баг-репорт №3 - https://github.com/Ekaterina5885/DZ-1.1/issues/3

## Описание процесса тестирования


В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
* Номер карты VISA: Результат "Result is OK".
* Номер карты MasterCard: Результат "Result is OK".
* Номер карты American Express (AMEX): Результат "Result is OK".
* Номер карты Discover: Результат "Result is OK".
* Номер карты JCB: Результат "Result is OK".
* Номер карты Diners Club - North America: Результат "Result is OK".
* Номер карты Diners Club - Carte Blanche: Результат "Result is OK".
* Номер карты Diners Club - International: Результат "Result is OK".
* Номер карты Maestro: Результат "Result is OK".
* Номер карты Visa Electron: Результат "Result is OK".
* Номер карты InstaPayment: Результат "Result is OK".

Тестирование производилось в следующем окружении:
* Windows 10.0.19042.928
* Java "11.0.11" 2021-04-20
* Intellij IDEA 2020.1 (Community Edition) 11.0.6+8-b765.25