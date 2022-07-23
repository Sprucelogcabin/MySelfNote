# SSM框架

SSM = Spring + Spring MVC + MyBatis       maven/gradle    tomcat

Spring Boot自学的，Spring Boot的原理和Spring MVC功能很像，只是Spring Boot封装了很多功能

Spring Boot一般不用tomcat，

```
Spring boot内部集成了Tomcat
Spring Spring + Spring MVC + MyBatis
Spring + Spring boot + MyBatis
```

Spring MVC负责和前端交互，代替Servlet，底层实现借助Servlet

MyBatis和数据库交互数据，代替JDBC，底层实现借助JDBC，

spring充当什么东西呢？凡是见到说Spring是容器的，都不太对，其功能相当于操作系统的内核，提供了很多方法功能，基于它提供的这些底层方法支撑和数据结构，基于这些东西我们得以实现spring mvc和mybatis，通过这些方法，我们得以实现这些功能。

很多框架的功能实现都需要Spring提供的功能。因此我们在引入maven的jar包的时候，首先要引入Spring的jar包，这样我们才可以使用maven。

Servlet是自带的，是Tomcat支持的

```
servlet ----> Struct2(有缺陷，被淘汰) ----->Spring MVC ----->Spring boot
除了servlet中，这三种都带controller，现在正在将Spring MVC向Spring Boot过渡
```

在Spring中，存在两种概念，IOC和AOP，现在在网上的解释都很官方，很泛泛，不能照着网上的背，因为网上的解释都差不多，因此面试官就会觉得你在背，而没有真正的理解，因此我们一定要有自己的理解。

如今复杂性的，原理性的东西，我们一定要有自己的理解，而不是一味的照着网上的说，照着网上的说法说相当于在给自己挖坑，因为这样一来面试官会觉得你没有自己的理解，然后就会不断的追问。

在学校内属于无经验，毕业第一年需要补Java基础，熟悉框架使用，毕业第一年一般都在干这些东西。

毕业两到三年，就开始会自己搭建框架了，复杂系统，Redis。源码啥的并不会。目前是相当于有两三年经验，水准是可以有的。

```
在工作中，一般是组长搭建SSM框架，写完整的样例Demo -- 前端和厚度按的交互，包含post，get请求样例，包含简单数据类型的传输例子，多参数数据类型传输样例，对于数据库的增删改查样例：单条数据批量操作，比如批量查询，单条查询，单条更改，批量更改
并且加上注释说明：XX是哪方面的demo
后端传来的数据解析demo
list操作
这样一来有demo之后，组员就可以照着组长的demo写了。以后工作之后可以练练带人的能力
每个组在开发的时候一定要统一环境，我们一定要能够完全的版本统一，团队中的各种环境一定要版本统一
组长申请腾讯git，然后让大家加入
```

进了公司第一件事先和公司的人问版本，问各种环境的版本
