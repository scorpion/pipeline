# https://github.com/rabbitmq/rabbitmq-server/blob/master/deps/rabbitmq_prometheus/docker/
# 
FROM rabbitmq:3.9-management-alpine
RUN rabbitmq-plugins enable \
    rabbitmq_shovel \
    rabbitmq_shovel_management \
    rabbitmq_management_agent \
    rabbitmq_prometheus \
    rabbitmq_web_dispatch
ADD ./config/rabbitmq.conf /etc/rabbitmq/rabbitmq.conf
# ADD ./config/rabbitmq-definitions.json /etc/rabbitmq/rabbitmq-definitions.json
EXPOSE 4369 5671 5672 25672 15671 15672