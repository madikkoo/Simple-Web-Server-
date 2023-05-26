# Simple-Web-Server-
Практика Golang май 2023 ЕНУ

## I'm ` Madikk` 
- How to Create a Go (Golang) based web server 
>
- How to run
>go run /cmd/main.go
- Go to your favorite browser and enter the url:
> http://localhost:9000

## Запролнить readme:

## Шаг 1: Импортирование пакетов
 > "net/http" и "fmt" для работы с веб-сервером и вывода текста.

## Шаг 2: Создание обработчика запросов
> Функция должна принимать два аргумента: объект ResponseWriter и объект Request.

> Внутри функции-обработчика нужно определить логику для обработки запроса и формирования ответа. Например, вы можете отправить "Привет ЕНУ" в качестве ответа на любой входящий запрос.

## Шаг 3: Регистрация обработчика и запуск сервера