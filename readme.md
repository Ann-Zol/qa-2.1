# Отчёт о тестировании Money Transfer

## Краткое описание

28.03.20 - 29.03.20 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Некорректный результат при пополнении счета]()

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* баг-репорты
* отчет о тестировании


В качестве тестовых данных использовались следующие данные:
* Текущий счет (currentBalance = 2_000_000_000)
* Сумма перевода (transfetAmout = 500_000_000)

Тестирование производилось в следующем окружении:
* Microsoft Windows. Version 10, 64-bit
* openjdk version "11.0.6" 2020-01-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.6+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.6+10, mixed mode)
* IntelliJ IDEA 2019.2.4 (Community Edition)