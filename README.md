Sprint Boot + RabbitMQ example
=
### Setup

1. Download and install RabbitMQ as described [here](https://www.rabbitmq.com/download.html)
1. Start RabbitMQ
1. Launch this application using `mvn spring-boot:run` command

### RabbitMQ [Management Interface](https://www.cloudamqp.com/blog/2015-05-27-part3-rabbitmq-for-beginners_the-management-interface.html)

1. Enable [management plugin](https://www.rabbitmq.com/management.html) with `./rabbitmq-plugins.bat enable rabbitmq_management` command
1. Management UI will be available on `http://localhost:15672/`
1. Log in using `guest` login and password
1. Enjoy
