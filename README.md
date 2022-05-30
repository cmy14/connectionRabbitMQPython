# connectionRabbitMQPython
  test connection Rabbit  mq 
   utilisation d'un dockercompose pour lancer un rabbitmq 
# Connection   RabbitMQ

## Docker

 run docker-compose.yml

### Start docker

* docker-compose up

equals to docker-compose build  & docker-compose run

option -d to detatch

### Stop docker

* docker-composer stop

### To delete

* docker-compose down [option]
 remplace option by --volumes if you want erase the volume

### to list images

* docker-compose images

### to list containers

* docker-compose ps

## information  information

  port rabbitmQ 
  '5672:5672'

   doc reference https://www.section.io/engineering-education/dockerize-a-rabbitmq-instance/

   https://www.rabbitmq.com/tutorials/tutorial-one-python.html