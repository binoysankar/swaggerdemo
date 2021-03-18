## Micronaut 2.4.0 Swagger Demo Application Documentation

Micronaut application for Swagger with native-image build

1) Run native image build using below command
    native-image --no-fallback -cp ..\build\libs\swaggerdemo-0.1-all.jar
2) Access swagger documentation using below url
   http://localhost:8080/swagger/swaggerdemo-0.0.yml
3) Access swagger-ui/redoc/rapidoc using the below url
   http://localhost:8080/[redoc|rapidoc|swagger-ui]
