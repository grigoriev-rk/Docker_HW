# CRUD

Собираем образ: 

docker build . --tag=hw_docker

Запускаем контейнер:

docker run --name hw_docker -d -p 6060:80 my_hw_docker