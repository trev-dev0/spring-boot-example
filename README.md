## Spring Boot Example

### Purpose
<p>
To show how Spring Boot can be configured to use
resilience4j and micrometer to prevent
cascading failures and to extract useful metrics from your Spring Boot API.
</p>

### How to run

1. Clone the repo in IntelliJ or to local machine 
2. Make sure you have docker-compose installed

    ```docker-compose -v```

3. Give permission to the start.sh file

    ```chmod +x start.sh```
4. Run the start.sh file

    ```./start.sh```
5. Run the Spring Boot app in IntelliJ

### Viewing the API and metrics
* To access the api you can use a command like CURL, a tool like Insomnia REST (or Postman), or simply type in the request in your browser

   ```curl localhost:8080/api/v1/person```
* To view the metrics, access Prometheus in your browser at http://localhost:9090