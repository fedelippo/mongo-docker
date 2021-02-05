# MongoDB super easy Docker container

## Description

A super simple docker-compose file to spin an instance of MongoDB.
No user will be required to access the database.

## How to run the container :ship:

`docker-compose up -d`

## How to access the container

`docker-compose exec mongo bash`

## How to connect to MongoDB

MongoDB instance will be running in the container and listening at port `27017`.

MongoDB Compass can be used to connect to the database or alternatively after accessing the
container the following command can be used:
`mongo --host localhost:27017`
