# Read Me First

The original idea is from  
https://medium.com/@knowledge.cafe/spring-boot-3-top-5-features-you-need-to-know-4e3337d0bd13

Add to application.properties

```
spring.context.exit-on-refresh=true
-XX:ArchiveClassesAtExit=app-cds.jsa
```

Run

```
java -Xshare:on -XX:SharedArchiveFile=app-cds.jsa -jar myapp.jar
```