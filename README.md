 Отчёт о тестировании  <функциональность валидации номера банковской карты.>

 <20.12.2020> -<23.12.2020>

Было проведено функциональное тестирование приложения Credit Card Number Validator

На тестирование затрачено: <9 часа>

В результате тестирования выявлены следующие дефекты: 
* [функционал валидации номера банковской карты, не определяет, карты платёжной системы American Express (AMEX) #1](https://github.com/nansan77/checking-cards/issues/1)



Описание процесса тестирования

В процессе тестирования использовались следующие артефакт:
* код в Idea  (IntelliJ IDEA)

В качестве тестовых данных использовались 
* [Номера банковских карт](https://www.freeformatter.com/credit-card-number-generator-validator.html) 

 Ожидаемым результатом


* платежных систем American Express (AMEX)

* American Express (AMEX) с № 374166510238469 ОК

* American Express (AMEX) с № 344505283643024 ОК

* American Express (AMEX) с № 374771740382522 ОК

Фактический результат:

* American Express (AMEX) с № 374166510238469 FATL

* American Express (AMEX) с № 344505283643024 FATL

* American Express (AMEX) с № 374771740382522 FATL

Тестирование производилось в следующем окружении:

* IdeaPad-L340

* Windows 10 pro 64 bit

* IntelliJ IDEA

* версия Java 11
