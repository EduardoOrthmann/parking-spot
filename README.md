# parking-spot
Java API boilerplate

# Como usar
Adicione no seu projeto dentro da pasta resources o arquivo application.properties e coloque a senha da sua conexão com banco de dados

spring.datasource.url= jdbc:postgresql://localhost:5432/parking_control_db
spring.datasource.username = postgres
spring.datasource.password = *sua senha*
spring.jpa.hibernate.ddl-auto = update

spring.jpa.properties.hibernate.jdbc.lob.non_contextual_creation = true
