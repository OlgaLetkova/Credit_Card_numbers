# Отчёт о тестировании программы "Credit Card Number Validator".

## Краткое описание

20.08.2020 - было проведено тестирование методом серого ящика программы "Credit Card Number Validator", разработанной стартапом, который помогает осуществлять приём платежей с банковских карт различным организациям.

На тестирование затрачено: 1,5ч

В результате тестирования выявлены следующие дефекты:
* https://github.com/OlgaLetkova/Credit_Card_numbers/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [инструкция по работе с кодом программы](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
* [валидные номера карт для разных платежных систем](https://www.freeformatter.com/credit-card-number-generator-validator.html#validate)

В качестве тестовых данных использовались данные сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html). 
Ожидаемы результат при работе с такими данными после компиляции - Result is OK.
Тестовые данные:
* VISA:
4556312499656410;
4716599399645439;
4556871830016451588.
* MasterCard:
5159454024251370;
2720994905388236;
5349548616448921.
* American Express (AMEX):
340744252281482;
372810939773927;
370965878980578.
* Discover:
6011167735431174;
6011441152695367;
6011107734075777026.
* JCB:
3529856862932754;
3543261136151913;
3541801496023399778.
* Diners Club - North America:
5597818126958316;
5404020039102891;
5428151858058237.
* Diners Club - Carte Blanche:
30218255744577;
30447667547399;
30162019363433.
* Diners Club - International:
36555673147683;
36160837540624;
36222985757739.
* Maestro:
6304442725133999;
5893662911380265;
6761744892872788.
* Visa Electron:
4508837577708617;
4026506964483802;
4913658122315081.
* InstaPayment:
6386545387517472;
6383844789670473;
6370591145526684.

Тестирование производилось в следующем окружении:
* Microsoft Windows [Version 10.0.18363.1016]
(c) Корпорация Майкрософт (Microsoft Corporation), 2019. 
* Java 11
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
* IntelliJ IDEA 2020.2(Community Edition) 
