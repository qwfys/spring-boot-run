# spring-boot-run
演示mvn spring-boot:run与spring.profiles结合问题。

# run

## default environment

```
mvn spring-boot:run
```

## production environment

```
mvn spring-boot:run -Dspring-boot.run.profiles=prod
```

## test environment

```
mvn spring-boot:run -Dspring-boot.run.profiles=test
```
