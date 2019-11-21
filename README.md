# Elastic Tran Bboss

数据交换模块

Bboss is a good elasticsearch Java rest client. It operates and accesses elasticsearch in a way similar to mybatis.

<https://esdoc.bbossgroups.com/#/README>

# Environmental requirements

JDK requirement: JDK 1.7+

Elasticsearch version requirements: 1.X,2.X,5.X,6.X,7.x,+

Spring booter 1.x,2.x,+

# Build from source code
First Get source code from https://github.com/bbossgroups/bboss-elasticsearch

Then change to cmd window under directory bboss-elasticsearch and run gradle build command：

```
gradle install
```

Gradle environmenet install and config document: https://esdoc.bbossgroups.com/#/bboss-build

# How to use Elasticsearch BBoss.

First add the maven dependency of BBoss to your pom.xml:

```xml
       <dependency>
            <groupId>com.bbossgroups.plugins</groupId>
            <artifactId>bboss-elasticsearch-rest-jdbc</artifactId>
            <version>5.9.3</version>
        </dependency>
```



 

## Elasticsearch技术交流群:166471282 

## Elasticsearch微信公众号:bbossgroup   
![GitHub Logo](https://static.oschina.net/uploads/space/2017/0617/094201_QhWs_94045.jpg)

## License

The BBoss Framework is released under version 2.0 of the [Apache License][].

[Apache License]: http://www.apache.org/licenses/LICENSE-2.0