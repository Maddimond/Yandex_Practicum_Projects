# Исследование надёжности заёмщиков


## Цель

На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Используемые инструменты
*предобработка данных, Python, Pandas, PyMystem3, лемматизация*


## Краткое описание проведённой работы

Входные данные от кредитного отдела банка — статистика о платёжеспособности клиентов. Очищены данные от выбросов, пропусков и дубликатов, а также преобразованы разные форматы данных. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Выделены леммы в значениях столбца и категоризированны данные. Определена доля кредитоспособных клиентов. Проанализировано влияние семейного положения и количества детей клиента на факт возврата кредита в срок. Построена модель кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.


## Вывод 

Из полученных данных можно составить портрет клиента для банка. Исходя из анализа данных пришел к выводу что на возврат кредитов влияют: количество детей, тк заемщики без детей на 2% реже возвращают кредит семейное поожение - заемщики которые не состот вотношениях возвращают кредиты на 2%чаще цели кридита связанные с недвижимостью и ремонтом возвращаются чаще на 2-3% доход заемщика - чем выше зарплата зарплате тем чаще возращают кредит.

## Статус проекта

Проект завершён
