#### Run docker-compose

    docker-compose up --build -d

#### Create image

    docker build . --tag image_name

#### Create container

    docker run -d --name container_name image_name 

#### Выполнение команды внутри контейнера

    docker exec -it id_контейнера bash_команда

#### Открыть консоль контейнера

    docker exec -it id_контейнера bash