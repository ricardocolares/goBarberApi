# goBarberApi

1)yarn add

2)docker run -d --name database \
    -e POSTGRES_PASSWORD=docker \
    -e POSTGRES_USER=docker \
    -p 6543:5432 -d -t postgres

3) Install Postbird

4)docker ps (certificar que o banco database está rodando)

5)yarn dev
6) docker start postgresDB
7) docker start mongoDB
8) docker start redisDB
