This is a demo of CDC from MySql database into Apache Iceberg table 

# Prerequisites
- Java 8 installation: 
- Kafka 3.6.0 with Scala 2.13 installation:
- Zookeeper 3.9.1 installation:
- MySQL and Adminer installation in docker-compose file

### All commands below are executed under root folder of my project, make sure you are running as SuperUser

# 1, Setup MySQL data source
```
docker-compose -f ./docker-compose/mysql-with-adminer.docker-compose.yml up -d
```

# 2, Setup Zookeeper and Kafka