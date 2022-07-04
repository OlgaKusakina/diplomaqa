# Дипломный проект по курсу «Тестировщик ПО»
## О проекте
В рамках данного проекта необходимо автоматизировать тестирование комплексного сервиса покупки тура, взаимодействующего с СУБД и API Банка.

База данных хранит информацию о заказах, платежах, статусах карт, способах оплаты.

Покупка тура возможна с помощью карты и в кредит. Данные по картам обрабатываются отдельными сервисами (Payment Gate, Credit Gate)

Полные условия и исходные данные описанного кейса можно посмотреть [здесь](https://github.com/netology-code/qa-diploma)

## Документация 

[План автоматизации тестирования веб-формы сервиса покупки туров интернет-банка](https://github.com/ekorneeva/diplomaQA/blob/main/documents/Plan.md)

[Отчёт о проведённом тестировании](https://github.com/ekorneeva/diplomaQA/blob/main/documents/Report.md)

[Комплексный отчёт о проведённой автоматизации тестирования](https://github.com/ekorneeva/diplomaQA/blob/main/documents/Summary.md)



## Запуск приложения

Перед запуском необходимо выполнить следующие предусловия. Если у вас уже есть необходимое ПО, то понадобится только п.1 и запуск Docker.

*Предусловия:*
1. Необходимо склонировать репозиторий или скачать архив по [ссылке](https://github.com/ekorneeva/diplomaQA.git). Или воспользоваться VCS Git, встроенной в  IntelliJ IDEA.
2. Установать и запустить Docker Desktop. Это можно сделать [здесь](https://docs.docker.com/desktop/) в зависимости от операционной системы. Дополнительные инструкции можно найти по [ссылке](https://github.com/netology-code/aqa-homeworks/blob/aqa4/docker/installation.md)
3. Открыть проект в IntelliJ IDEA


## Запуск тестов
1. В новой вкладке терминала ввести команду в зависимости от запущенной БД. Запуска:
- `gradlew clean test -Ddb.url=jdbc:mysql://localhost:3306/app` - для MySQL
- `gradlew clean test -Ddb.url=jdbc:postgresql://localhost:5432/app` - для PostgreSQL
