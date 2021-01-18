 Отчёт о тестировании " функциональность валидации номера банковской карты."

 20.12.2020 -23.12.2020

Было проведено функциональное тестирование приложения Credit Card Number Validator

На тестирование затрачено: 9 часа

В результате тестирования выявлены следующие дефекты: 
* [функциональность валидации номера банковской карты, не определяет, карты платёжной системы American Express (AMEX) #1](https://github.com/nansan77/checking-cards/issues/1)



Описание процесса тестирования

В процессе тестирования использовались следующие артефакт:
* код в Idea  (IntelliJ IDEA)

В качестве тестовых данных использовались 
* [Номера банковских карт](https://www.freeformatter.com/credit-card-number-generator-validator.html) c Ожидаемым результатом

* платежных систем VISA, 

* VISA с № 4485962178806888 ОК

* VISA с № 4929891556456152 ОК

* VISA с № 4024007115784061215 FATl

* платежных систем Discover

* Discover с № 6011990397628047 ОК

* Discover с № 6011431220351176 ОК

* Discover с № 6011605044675553653 FATl

* платежных систем MasterCard

* MasterCard с № 5247338995574791 ОК

* MasterCard с № 5101996418495822 ОК

* MasterCard с № 2221005830888630 FATl

* платежных систем Diners Club - North America:

* Diners Club - North America: № 5580989542252961 ОК 

* Diners Club - North America: № 5408108166415347 ОК

* Diners Club - North America: № 5568356565262762 ОК
* платежных систем Maestro

* Maestro с № 6762552687760574 ОК

* Maestro с № 6304542832078266 ОК

* Maestro с № 676166853167700 ОК3

* платежных систем American Express (AMEX)

* American Express (AMEX) с № 374166510238469 ОК

* American Express (AMEX) с № 344505283643024 ОК

* American Express (AMEX) с № 374771740382522 ОК

* платежных систем American Express (AMEX)

* American Express (AMEX) с № 374166510238469 ОК

* American Express (AMEX) с № 344505283643024 ОК

* American Express (AMEX) с № 374771740382522 ОК

Тестирование производилось в следующем окружении:

* IdeaPad-L340

* Windows 10 pro 64 bit

* IntelliJ IDEA

* версия Java 11
