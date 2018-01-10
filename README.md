# appengine-meet-spring-boot
This is a bootstrap-type project to  get a spring-boot application to run locally using dev app engine.

App Engine in the cloud (flex) can run a jar OK. 

Dev app engine demands a war! 
See https://docs.spring.io/spring-boot/docs/current/reference/html/howto-traditional-deployment.html 
on how to produce a deployable war.

## Prerequisites: 
Install Google Cloud SDK:  https://cloud.google.com/sdk/

## Run with local appengine:
```
mvn appengine:run
```

