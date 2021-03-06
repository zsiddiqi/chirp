# Chirp Server

This server hosts the Chirp API. To start the server, navigate to the `springboot` directory and run:

```
mvn clean install spring-boot:run
```

Then, navigate to http://localhost:8080/v1/

Alternately, you could use the [CDK](https://developers.redhat.com/products/cdk/overview/) to host both the API and the client locally.

## Background
This server was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.  
By using the [OpenAPI-Spec](https://github.com/swagger-api/swagger-core), you can easily generate a server stub.  
This is an example of building a swagger-enabled server in Java using the SpringBoot framework.  

The underlying library integrating swagger to SpringBoot is [springfox](https://github.com/springfox/springfox)  

Start your server as an simple java application  

You can view the api documentation in swagger-ui by pointing to  
http://localhost:8080/  

Change default port value in application.properties
