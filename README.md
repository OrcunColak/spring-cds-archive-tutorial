# Read Me First

The original idea is from  
https://medium.com/@knowledge.cafe/spring-boot-3-top-5-features-you-need-to-know-4e3337d0bd13

Add to application.properties

```
spring.context.exit-on-refresh=true
-XX:ArchiveClassesAtExit=app-cds.jsa
```

# Command Line

The original idea is from
https://medium.com/dev-genius/accelerate-spring-boot-app-start-time-simply-eb7345c051e7?source=explore---------2-98--------------------ae5f0f96_5770_416a_b763_1ab861bf9a04-------15

Run

```
java -XX:ArchiveClassesAtExit=app-cds.jsa "-Dspring.context.exit=onRefresh" -jar .\target\spring-cds-tutorial-0.0.1-SNAPSHOT.jar
java -Xshare:on -XX:SharedArchiveFile=app-cds.jsa -jar .\target\spring-cds-tutorial-0.0.1-SNAPSHOT.jar
```

# spring-boot-startup-report

Go to  
http://localhost:8080/startup-report