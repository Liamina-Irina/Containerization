# Containerization

***Homework 5. Docker Compose и Docker Swarm***
 
1. Создать сервис, состоящий из 2 различных контейнеров: 1 - веб, 2 - БД (compose)

Задание со звездочкой - повышенной сложности..

** не обязательно 2. Необходимо создать 3 сервиса в каждом окружении (dev, prod, lab)

** не обязательно 3. По итогу на каждой ноде должно быть по 2 работающих контейнера

4. Выводы зафиксировать

---

1. Создаем директорию "compose" и переходим в неё:

*mkdir compose*

*cd compose*

2. В данной директории создаем файл "compose.yaml" и меняем его содержимое: 

*nano compose.yaml*

![1](https://github.com/Liamina-Irina/Containerization/assets/119972026/0312d2fe-177a-472e-b0fc-092b7156c680)

3. Создаем сервис из 2-х контейнеров (web и db)

![2](https://github.com/Liamina-Irina/Containerization/assets/119972026/127fed02-dc6f-45d1-b0e0-69eafa21f8a5)

4. Запуск Docker Compose:  

*docker-compose up -d*

![3](https://github.com/Liamina-Irina/Containerization/assets/119972026/77633cbc-44f1-43bb-84a9-52fd525fa2d2)

Проверяем активность контейнера

docker-compose ps

![4](https://github.com/Liamina-Irina/Containerization/assets/119972026/9a091d72-dd25-40a5-9010-8a33999e7a43)


