This is the docker project to test all the microservices running together locally.

You need to have in the same folder all the repositories from this RSO-2024-25-skupina-03 project.
The directory tree will look somehting like this:

skupina-3

  |__docker-compose

  |__stock
  
  |__cart
  ...

To run it `docker compose up`

Apis are available at localhost/api/<microservice-name> and the documentations for apis are available at localhost/api/<microservice-name>/docs/
for rabbitMQ UI go to localhost/rabbitmq
similarily for other services for metrics
