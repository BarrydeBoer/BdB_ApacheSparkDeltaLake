# BdB_ApacheSparkDeltaLake
Quick sample of Apache Spark with Delta Lake

Three docker containers:
- Apache Spark master
- Apache Spark worker
- Delta Lake


## To start Docker Containers:
```
docker-compose up --build
```

## Start JupyterLab and create notebooks
```
http://localhost:8888
```
Enter the token provided by the delta-lake terminal logging

## Bring down the containers:
```
docker-compose down
```