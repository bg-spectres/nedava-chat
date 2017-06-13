# nedava-chat
A very chatty webapp :)


## instructions and notes
#### Prerequisites
- [Spring Boot CLI](http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#getting-started-installing-the-cli) was used to init the project -- `spring init --force --dependencies web,security nedava-chat` 
- maven
- Java IDE [STS plugins](https://spring.io/tools/sts/all) help..

#### Importing to IDE
* like any other maven project -- `mvn eclipse:eclipse`

#### Running
```
mvn spring-boot:run
```
or, pack into a jar and run it..
```
mvn package
java -jar target/*.jar
```

#### sources and javadocs for libraries
```
mvn dependency:sources
mvn dependency:resolve -Dclassifier=javadoc
```
repeat mvn eclipse:eclipse safter this to refresh build path and libraries
