<h1> :computer: Conexão com bancos de dados usando SpringBoot</h1>
  
#### 🟢 H2 (usado para testes)
```sql
spring.datasource.url=jdbc:h2:mem:teste
spring.datasource.username=sa
spring.datasource.password=

spring.h2.console.enabled=true
spring.h2.console.path=/h2-console

spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
```

#### 🟢 MySql
```sql
spring.datasource.url=jdbc:mysql://localhost:3306/teste
spring.datasource.username=root
spring.datasource.password=

spring.jpa.hibernate.ddl-auto=create
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
```

#### 🟢 PostgreSQL
```sql
spring.datasource.url=jdbc:postgresql://localhost:5432/teste
spring.datasource.username=postgres
spring.datasource.password=

spring.jpa.properties.hibernate.jdbc.lob.non_contextual_creation=true
spring.jpa.hibernate.ddl-auto=create
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
```
