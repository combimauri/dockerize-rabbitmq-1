FROM rabbitmq

# enable management plugin
#RUN rabbitmq-plugins enable --offline rabbitmq_management
 
# enable mqtt plugin
#RUN rabbitmq-plugins enable --offline rabbitmq_mqtt

ENV RABBITMQ_NODENAME=my-rabbit

EXPOSE 15672 5672

#docker run -it -p 5672:5672 -p 15672:15672 myrabbit
#docker run -it -h rabbitmqhost -p 5672:5672 -p 15672:15672 myrabbit

# FROM rabbitmq:3-management
# RUN apt-get update
# RUN apt-get install -y curl 
# EXPOSE 4369 5671 5672 25672 15671 15672