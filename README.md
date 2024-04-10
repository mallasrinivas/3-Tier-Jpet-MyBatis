# MyBatis JPetStore SpringBoot app

![mybatis-jpetstore](https://mybatis.org/images/mybatis-logo.png)

JPetStore 6 is a full web application built on top of MyBatis 3, Spring 5 and Stripes.

## Essentials

- [See the docs](http://www.mybatis.org/jpetstore-6)

## Other versions that you may want to know about

- JPetstore on top of Spring, Spring MVC, MyBatis 3, and Spring Security https://github.com/making/spring-jpetstore
- JPetstore with Vaadin and Spring Boot with Java Config https://github.com/igor-baiborodine/jpetstore-6-vaadin-spring-boot
- JPetstore on MyBatis Spring Boot Starter https://github.com/kazuki43zoo/mybatis-spring-boot-jpetstore

## Run on Application Server

Running JPetStore sample under Tomcat (using the [cargo-maven2-plugin](https://codehaus-cargo.github.io/cargo/Maven2+plugin.html)).

- Clone this repository

  ```
  $ git clone https://github.com/mybatis/jpetstore-6.git
  ```

- Build war file

  ```
  $ cd jpetstore-6
  $ ./mvnw clean package
  ```

- Startup the Tomcat server and deploy web application

  ```
  $ ./mvnw cargo:run -P tomcat90
  ```

- Run application in browser http://localhost:8080/jpetstore/
- Press Ctrl-C to stop the server.

## Run on Docker

```
docker build . -t jpetstore
docker run -p 8080:8080 jpetstore
```

or with Docker Compose:

```
docker compose up -d
```

## Try integration tests

Perform integration tests for screen transition.

```
$ ./mvnw clean verify -P tomcat90
```

Jenkis - CI pipeline

![image](https://github.com/mallasrinivas/3-Tier-Jpet-MyBatis/assets/90713944/a9a59808-fbb7-4cc6-89e1-87c51ee0bb11)

Jenkins-CD - Kubernets
![image](https://github.com/mallasrinivas/3-Tier-Jpet-MyBatis/assets/90713944/3752532a-6ccb-4ea2-b046-9f8241c401a4)

Sonarcube- Scanner
![image](https://github.com/mallasrinivas/3-Tier-Jpet-MyBatis/assets/90713944/e4a1f6dc-0629-4660-b8b7-f1b56c1c2106)

email notification 
![image](https://github.com/mallasrinivas/3-Tier-Jpet-MyBatis/assets/90713944/7c004caa-deca-4ef3-bd5e-b2ce1af86ce8)

Output
![image](https://github.com/mallasrinivas/3-Tier-Jpet-MyBatis/assets/90713944/a1869cd6-b9a3-4a81-b796-e0649c30fe72)

![image](https://github.com/mallasrinivas/3-Tier-Jpet-MyBatis/assets/90713944/2f3f3066-1bff-4710-8cc6-cd24c05273e5)

![image](https://github.com/mallasrinivas/3-Tier-Jpet-MyBatis/assets/90713944/aded596d-63ee-4da9-b787-15fe7cef1212)

![image](https://github.com/mallasrinivas/3-Tier-Jpet-MyBatis/assets/90713944/41839daf-0afd-4346-b2b5-28ff18297939)

![image](https://github.com/mallasrinivas/3-Tier-Jpet-MyBatis/assets/90713944/8309525c-60ba-470d-b71a-fc5a14a48607)










Thanks to MyBatis for this project and Ajay Kumar Y
