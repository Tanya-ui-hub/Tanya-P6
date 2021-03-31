Отчет о тестировании
Краткое описание

<31.03.20>-<31.03.20> проведено функциональное тестирование валидных номеров карт,предоставленных сервисом Credit Card Number Validator.

На тестирование затрачено: <3 часа>

В результате тестирования выявлены следующие дефекты:

* [Result is FAIL при вводе валидного значения в поле "Номер карты" #1](https://github.com/Tanya-ui-hub/Tanya-P6/issues/1)

Описание процесса тестирования:

Были использованы следующие артефакты:

* [Домашнее задание к занятию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
* [IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

В качестве тестируемых данных были использованы валидные данные карт с сайта https://www.getcreditcardnumbers.com/generated-credit-card-numbers

Карты VISA:
* 4532945868739751 Ожидаемый результат: Result is OK
* 4916374281134258 Ожидаемый результат: Result is OK
* 4539447184051741 Ожидаемый результат: Result is OK

Карты Mastercard 
* 5578872860657223 Ожидаемый результат: Result is OK
* 5451124603457863 Ожидаемый результат: Result is OK
* 5438352259274641 Ожидаемый результат: Result is OK

Карты Discover
* 6011238691929665 Ожидаемый результат: Result is OK
* 6011870581208964 Ожидаемый результат: Result is OK
* 6011907931832653 Ожидаемый результат: Result is OK

Карты American Express
* 348933494361879 Ожидаемый результат: Result is OK
* 374829719102477 Ожидаемый результат: Result is OK
* 341647711337184 Ожидаемый результат: Result is OK

Тестирование производилось в следующем окружении:
* Windows 10 Home 64 bit
* версия Java 11.0.10