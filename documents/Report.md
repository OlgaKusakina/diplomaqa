# Отчёт о проведённом тестировании

## Краткое описание

Автоматизировно тестирование комплексного сервиса покупки тура, взаимодействующего с СУБД и API Банка.

Общее количество тест кейсов: **54**

## Статистика успешных/неуспешных кейсов

### При подключении к БД MySQL
![tests result mysql](https://user-images.githubusercontent.com/67016228/99875233-f8c0bb00-2bfe-11eb-8a0f-b7d24e64c46f.jpg)

- Успешных кейсов 48% (26 кейсов)
- Неуспешных кейсов 52% (28 кейсов)


### При подключении к БД PostgreSQL
![tests result postgresql](https://user-images.githubusercontent.com/67016228/99875356-ff9bfd80-2bff-11eb-9b92-315fce8d4fb0.jpg)

- Успешных кейсов 44% (24 кейса)
- Неуспешных кейсов 56% (30 кейсов)



## UI-тесты при подключении к БД MySQL
Позитивные (HappyPath) тесты - **4**

Негативные - **46**

![tests result mysql](https://user-images.githubusercontent.com/67016228/99875414-9cf73180-2c00-11eb-8342-178f2c374b2c.jpg)


## UI-тесты при подключении к БД PostgreSQL
Позитивные (HappyPath) тесты - **4**

Негативные - **46**

![tests result postgresql](https://user-images.githubusercontent.com/67016228/99875426-b7310f80-2c00-11eb-8507-e4418b3fee50.jpg)


## API-тесты

При подключении к обеим БД все тест-кейсы прошли успешно (4 шт.)
![api tests](https://user-images.githubusercontent.com/67016228/99875464-f19aac80-2c00-11eb-8306-130cc81e7752.jpg)


## Общие рекомендации


Полный список найденных дефектов находится в [Issues](https://github.com/ekorneeva/QA-Diploma/issues)
