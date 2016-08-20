Sample Repsoitory for https://github.com/spring-cloud/spring-cloud-netflix/issues/1276

For the configserver you have to edit the https://github.com/ukleeberger/unkown_issue/blob/master/configserver/src/main/resources/application.yml to point the `git.uri` to the right location

After staring Eureka, Configserver and the spring-boot-demo app the app is registered with UNKNOWN to Eureka
