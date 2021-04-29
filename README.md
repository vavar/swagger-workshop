# Swagger Workshop

## Swagger UI Docker command

```
docker run --rm -p 9000:8080 -e SWAGGER_JSON=/mnt/petstore.yaml -v $PWD:/mnt swaggerapi/swagger-ui
```