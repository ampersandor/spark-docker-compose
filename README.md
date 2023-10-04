# Spark with Docker-compose
This repository provides Dockerfile and docker-compose.yml file that helps you construct a mock spark cluster with standalone manager. Not only can you experience the client mode with jupyter-lab environment, furthermore you can submit your spark programming through cluster mode to spark://localhost:7077

## Features
It provides jars folder containing aws redshift drivers for your convinence.  
https://docs.aws.amazon.com/ko_kr/redshift/latest/mgmt/jdbc20-download-driver.html  
  
Happy test and examine your spark programming!

## Prerequisite

* **Docker Engine v24.02**
* **Docker Compose v2.19.1**
* **Mac OS** or **Linux**

## Installation
```bash
chmod +x ./build.sh
./build.sh
docker-compose up
```

## Links
- [jupyterlab](http://localhost:9999)
- [masterUI](http://localhost:9090)
- [worer1UI](http://localhost:9091)
- [worer2UI](http://localhost:9092)
- [applicationUI](http://localhost:4040)



## Contributors
- [ampersandor](https://github.com/ampersandor)
