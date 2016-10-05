# Spring4 MVC XML Example

Simple example to try and get a spring 4 mvc app up and running on a tomcat image from Red Hat

## How to run...

```
oc new-app jboss-webserver30-tomcat8-openshift:latest~https://github.com/welshstew/spring4-mvc-xml-example.git
oc expose svc/spring4-mvc-xml-example
```