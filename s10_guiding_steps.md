#Steps to Create a RESTful API Connected to a MySQL Database

1. Create a Spring Boot-based project using [Spring Initializr](https://start.spring.io/) with the folloing values:
    *Project: Maven
    *Language: Java
    *Spring Boot: 3.5.0
    *Project Meta:
        *Group:        com.acme
        *Artifact:     catchup-platform
        *Name:         catchup-platform
        *Description:  RESTful API using Spring Boot
        *Package name: 
    *Packaging: Jar
    *Java: 24

    ##Dependencies:
    * Spring Data JPA
    * Validation
    * Spring Web
    * Spring Boot DevTools
    * MySQL Driver
    * Lombok
    
    Note: Also add the dependencies [OpenAPI](https://mvnrepository.com/artifact/org.springdoc/springdoc-openapi-starter-webmvc-ui) and [pluralize](https://mvnrepository.com/artifact/io.github.encryptorcode/pluralize). If Spring Initializr does not have them, add the corresponding code on the pom.xml file to get them.
    


   Create a directory java/com/acme/catchup/platform
   

    
          
3. 
