# Financial application

## Описание проекта
Financial application - это приложение для управления личными финансами. Оно позволяет отслеживать расходы по разным категориям. 

Логика у приложения такая:
1. Задается начальный баланс счета.
2. Добавляются расходы. Категории расходов пишутся самостоятельно. 
3. Если бюджет превышен, то приложение предупредит об этом.

Также приложение умеет рассчитывать траты за неделю и конвертировать рубли в другие валюты по актуальному курсу. 
Курс берется с сайта https://api.exchangerate.host через HTTP запрос.

## Инструкция по развёртыванию и системные требования
JDK 11 и выше. В Project settings -> Libraries нужно добавить com.google.code.gson:gson:2.8.9 
