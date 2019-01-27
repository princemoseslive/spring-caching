# spring-caching
Tutorial to make Caching with Spring

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes

``` 
git clone git@github.com:princemoseslive/spring-caching.git

mvn clean install package.

```

## Built With

* Ehcache 2.9
* Spring 4.1.4.RELEASE
* Logback 1.0.13
* Maven 3 / Gradle 2
* JDK 1.7
* Eclipse 4.4

## Getting Started (Short)
1.The Spring caching is in the spring-context.jar, to support Ehcache caching, you need to include the spring-context-support.jar as well.
2.A simple DAO to find a movie by director name.
3.Create a ehcache.xml file, to tell Ehcache how and where to cache the data.
4.Add @Cacheable on the method you want to cache.
5.Enable Caching with @EnableCaching and declared a EhCacheCacheManager.
6.In non-web application, you need to shut down the Spring context manually, so that Ehcache got chance to shut down as well, otherwise Ehcache manager will hang there.

