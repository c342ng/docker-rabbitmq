# docker-rabbitmq

docker run -d --name=rabbitmq-server -p 5672:5672 -p 15672:15672 -e RABBITMQ_DEFAULT_USER=rabbit -e RABBITMQ_DEFAULT_PASS=mq_passwd c3t3m3/docker-rabbitmq
