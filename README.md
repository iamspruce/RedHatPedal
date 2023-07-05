# Petal E-Commerce Project

This project was developed using the following technologies; 

- Java 
- Spring Boot
- Thymeleaf rendering engine
- PostgresQL
- TailwindCSS

## To Run: 

Ensure you the data requirements settled, then use the `mvnw` bin or IntelliJ runner to start the application. 

# Data Requirements;

This application uses a PostgresQL database by default with it's connection credentials in the `application.properties` file.
Specify the following values to configure the datasource;

```yml
spring.datasource.url=jdbc:DB_CONNECTION_URL
spring.datasource.username=DB_USERNAME
spring.datasource.password=DB_PASSWORD
```

### Database

The database being used should have the following tables:

* bikes
* service_user
* bike_order

The `./ebike_data.sql` file contains SQL statements to create the columns within the aforementioned tables. 
The image below also shows the data diagram;

<img src="data-visualization.png" alt="Data Visualization" />