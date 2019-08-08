# spring-boot-react-app
Test project for combining Spring Boot and React

* Backend: Spring Boot application, generated from https://start.spring.io/
* Frontend: React, generated from https://facebook.github.io/create-react-app/ 

The main thing was to package the frontend production build output into a jar which is then put into Spring Boot's classpath so that the React frontend can be served from the Spring Boot jar.
