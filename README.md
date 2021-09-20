# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

07.09.21 - 07.09.21 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлен следующий дефект:
* [Программа Credit Card Number Validator не валидирует карты с количеством цифр в номере, отличающимся от 16](https://github.com/anvartdinovtimurlinux/CreditCardNumberValidator/issues/7)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [код тестируемого сервиса](https://github.com/anvartdinovtimurlinux/CreditCardNumberValidator/blob/main/src/com/anvartdinov/Main.java)

В качестве тестовых данных использовались валидные номера карт, сгененированные сервисом https://www.freeformatter.com/credit-card-number-generator-validator.html:
* VISA 4637750264620421
* VISA 4929787415908038644
* Visa Electron 4508517205406889
* MasterCard 5366230649659067
* Maestro 5038989538599548
* Discover 6011282495437947
* Discover 6011324908143203564
* JCB 3544350547081097
* JCB 3529004452990889952
* Diners Club - Carte Blanche 30144836491886
* Diners Club - International 36762414372311
* Diners Club - North America 5403835327581113
* InstaPayment 6377165316993479
* American Express 340874327414477


Тестирование производилось в следующем окружении:
* MacOS Big Sur 11.5, 64-битная версия
* Java 16.0.2
* IntelliJ IDEA 2021.1.3 CE
