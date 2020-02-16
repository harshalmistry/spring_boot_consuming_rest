# Welcome to Spring Boot consumer rest application

    Sample spring boot applicatio to consume rest application using RestTemplate
    
    Rest service used : https://gturnquist-quoters.cfapps.io/api/random
    
**To run locally**
 
    cd consuming-rest
    mvn clean install
    
    remove build error if any
    
    after successful build run following command
    
    cd target
    java -jar consuming-rest-0.0.1-SNAPSHOT.jar
    
**Sample response**
    
    Once spring boot application starts CommandLineRunner will invoke Quotation service and print Quote received as response to console.
    
![consume-rest-response](https://github.com/harshalmistry/support_resources/blob/master/rest-consume.png)
    