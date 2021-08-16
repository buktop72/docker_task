# Домашнее задание к лекции «Docker» №2

# Создайте контейнер для REST API сервера любого вашего проекта из курса по Django (например, CRUD: Склады и запасы).

## типовые команды для запуска контейнера c backend-сервером:

sudo docker build -t my_docker
sudo docker container run -d -p 8000:8000 my_docker

