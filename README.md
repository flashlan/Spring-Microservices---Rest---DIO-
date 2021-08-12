# Spring-Microservices---Rest---DIO-
A microservices project made with with Spring Cloud Framework and based on a DigitalInovationOne tutorial series from [Oswaldo Neto](https://github.com/oswaldoneto).



You will need start docker conteiner fisrt (See docker-compose.yml) to sucesfull test the project.


- To start docker image providing elasticsearch and redis services run the commands below inside the root project directory:

```
sudo chmod 666 /var/run/docker.sock
sudo systemctl start docker 
sudo systemctl status docker
docker-compose up
```
---

!!!Usefull URIs

elasticsearch url: 

> http://localhost:9200

Config-Server health verification url:

> http://localhost:8080/actuator/health

actuator health verification url:
  
> http://localhost:8082/actuator/health

check if config-server is pointed to the right config file url (on a git repo here): 

> http://localhost:8888/product-catalog/default

eureka dashboard:

> http://localhost:9000

---

DIO - Digital Inovation One Url:

> https://digitalinnovation.one/
