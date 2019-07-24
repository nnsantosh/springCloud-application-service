The eureka discovery server Spring Boot App must be running so that the application services can register themselves in the discovery server to be discovered and accessed by application client.

Run two instances of this service using "Run as Configurations" and add the below properties:
server.port=8081
service.instance.name=instance 1

server.port=8082
service.instance.name=instance 2