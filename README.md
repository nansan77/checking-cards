 Отчёт о тестировании " функциональность валидации номера банковской карты."

 20.12.2020 -23.12.2020

Было проведено функциональное тестирование 

На тестирование затрачено: 9 часа

В результате тестирования выявлены следующие дефекты: 
https://github.com/nansan77/checking-cards/issues/1

В процессе тестирования использовались следующие артефакт -код в Idea  (IntelliJ IDEA)

В качестве тестовых данных использовались 
Номера банковских карт. платежных систем VISA, Discover, MasterCard, Diners Club - North America, 
Maestro, American Express (AMEX)

Ожидаемый результат 

Работоспособность функциональности валидации номеров банковских карт.

VISA с № 4485962178806888 ОК

VISA с № 4929891556456152 ОК

VISA с № 4024007115784061215 FATl

Discover с № 6011990397628047 ОК

Discover с № 6011431220351176 ОК

Discover с № 6011605044675553653 FATl

MasterCard с № 5247338995574791 ОК

MasterCard с № 5101996418495822 ОК

MasterCard с № 2221005830888630 FATl

Diners Club - North America: № 5580989542252961 ОК 

Diners Club - North America: № 5408108166415347 ОК

Diners Club - North America: № 5568356565262762 ОК

Maestro с № 6762552687760574 ОК

Maestro с № 6304542832078266 ОК

Maestro с № 6761668531677300 ОК

American Express (AMEX) с № 374166510238469 ОК

American Express (AMEX) с № 344505283643024 ОК

American Express (AMEX) с № 374771740382522 ОК


Тестирование производилось в следующем окружении:

IdeaPad-L340

Windows 10 pro 64 bit

IntelliJ IDEA

версия Java 11
