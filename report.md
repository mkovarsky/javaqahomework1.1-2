# Отчёт о тестировании Main.

<14.02.2020> - <14.02.2020> Проведено тетирование программы валидации номера банковской карты.

На тестирование затрачено: 0,5 часа

В результате тестирования дефектов не выявлено.

## Описание процесса тестирования

1. Устанавливаем и запускаем согласно [инструкции](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md) IntelliJ IDEA
1. Запускаем программу с разными тестовыми данными (запуск описан в п. "Шаг 20" [инструкции](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md))

В качестве тестовых данных использовались данные:

Для негативного сценария:

* 0000000000000000
* 1234567812345678
* аааааааааааааааа


Для позитивного сценария:

* 4242424242424242
* 5555555555554444

Данные взяты из [таблицы](https://developer.rbk.money/docs/payments/refs/testcards/#_1) для Visa и MasterCard

### Тестирование производилось в следующем окружении:
IntelliJ IDEA 2019.3.3 (Community Edition)
Build #IC-193.6494.35, built on February 11, 2020
Runtime version: 11.0.5+10-b520.38 amd64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o
Windows 10 10.0
GC: ParNew, ConcurrentMarkSweep
Memory: 2014M
Cores: 4
Registry: 
Non-Bundled Plugins: 