# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

23.03.2020- 24.03 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 4 часа

В результате тестирования выявлены следующие дефекты:
* [Баг-репорт №1](https://github.com/Ann-Zol/java-qa-1.2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* баг-репорты
* отчет о тестировании


В качестве тестовых данных использовались данные [Источника 1](https://karta.guru/sovety/2499-generator-kart-bankovskih-i-kreditnyh.html) и [Источника 2](https://developer.rbk.money/docs/payments/refs/testcards/):
* Валидные данные
	* 4822195893280145 (Visa)
	* 5466218768163721 (Master Card)
* Невалидные данные
	* 5100000000000511 (MasterCard)
	* 4222222222222220 (Visa)

Тестирование производилось в следующем окружении:
* Microsoft Windows. Version 10, 64-bit
* openjdk version "11.0.6" 2020-01-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.6+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.6+10, mixed mode)
* IntelliJ IDEA 2019.2.4 (Community Edition)