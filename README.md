# springone-2021-highlights
Notes about my personal highlights of SpringOne 2021


### General observations

Find all video-recordings at https://springone.io/2021/schedule (you need to create an account, but most are also on Youtube)

* 

---



### Spring Boot & GraalVM Current Status

<a href="https://www.youtube.com/embed/TXyg6Nm4ZpQ" target="_blank"><img src="http://img.youtube.com/vi/TXyg6Nm4ZpQ/0.jpg" 
alt="Spring Native (SpringOne2021)" width="240" height="180" /></a>

__*"Spring Native"*__ by https://twitter.com/sdeleuze

https://github.com/spring-projects-experimental/spring-native

Spring Native Beta (March 2021):

![spring-native-beta](spring-native-beta.png)

https://spring.io/blog/2021/03/11/announcing-spring-native-beta

> While it is still considered as experimental, beta means that Spring now provides support for native on a subset of the Spring ecosystem. You can try it on your projects if they are using the supported dependencies and raise bugs or contribute pull requests if something goes wrong. A new release of Spring Native will happen for each patch release of the latest Spring Boot 2.x minor version. Spring Native 0.9.0 supports Spring Boot 2.4.3, Spring Native 0.9.1 will support Spring Boot 2.4.4, etc. Breaking changes will happen but we will document migration paths.

```
reflect-config.json
resource-config.json
native-image.properties
```


##### @NativeHint

> Some native configuration can not be inferred, for those cases we are introducing native hint annotations (see the Javadoc for more details) which allows Spring Native to support native configuration in a more maintainable, typesafe and flexible way than regular JSON based native image configuration.


##### Samples!

https://github.com/spring-projects-experimental/spring-native/tree/main/samples

__--> More details: https://github.com/jonashackt/springone-2020-highlights#spring-boot--graalvm__

https://github.com/jonashackt/spring-boot-graalvm

https://blog.codecentric.de/en/2020/05/spring-boot-graalvm/


---
