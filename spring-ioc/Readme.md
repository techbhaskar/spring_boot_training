# How to run spring Ioc example
Clone the project project from git to your local -> Import the spring-ioc project as maven project into your workspace -> then run com.training.spring.Test java file.
# Result as shown
![](https://github.com/techbhaskar/Spring-with-Spring-Boot/blob/master/spring-ioc/spring-ioc-res.JPG)

# What we are going to learn from this example

Spring IoC is responsible to instantiate and configure all the objects (beans).
There are two types of IoC containers
	One is ApplicationContext and the another one is BeanFactory.

The org.springframework.beans.factory.BeanFactory and the  org.springframework.context.ApplicationContext interfaces acts as the IoC container. The ApplicationContext interface is built on top of the BeanFactory interface.  It adds some extra functionality than  BeanFactory such as simple integration  with Spring's AOP
