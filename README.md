# sylon-wealth-management-backend-mock

Wiremock stubs for developing sylon-wealth-management-api service

## Run
Select appropriate free port
```
mvn process-resources wiremock:run -Dparams="--port 8081 --verbose --global-response-templating"
```
