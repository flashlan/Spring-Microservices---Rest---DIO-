# Spring-Microservices---Rest---DIO-
A microservices project made with with Spring Cloud Framework and based on a DigitalInovationOne tutorial series


Need start docker conteiner fisrt (See docker-compose.yml)


- To start docker image run from root project directory:

```
sudo chmod 666 /var/run/docker.sock
sudo systemctl start docker 
sudo systemctl status docker
docker-compose up
```

elasticsearch url: 

```
http://localhost:9200/
```

actuator health verification url:

```
http://localhost:8080/actuator/health
```
