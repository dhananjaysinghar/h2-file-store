# h2-file-store
~~~
spring:
  jpa:
    hibernate:
      ddl-auto: update
      dialect: org.hibernate.dialect.MySQL5Dialect
    show-sql: true
  datasource:
    platform: h2
    driver-class-name: org.h2.Driver
    username: sa
    password:
    url: jdbc:h2:file:C:\database\h2\user_db;MODE=MYSQL
  h2:
    console:
      path: /h2-console
      enabled: true
~~~
