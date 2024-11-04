# Простейшая конфигурация kafka

Необходимо предварительно создать внешнюю сеть в docker

``docker network create docker_default``

## Запуск

``docker-compose up -d``

## Остановка

``docker-compose down``

## akhq

GUI для работы с Kafka будет доступен по адресу [http://127.0.0.1:4080/](http://127.0.0.1:4080/)
