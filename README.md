# ECS796PLab2

Based upon <https://github.com/sajeerzeji/SpringBoot-GRPC>

Commands for preparing the enviornment (Assuming you are in the main folder e.g. the one with the pom.xml file in it)

## Update & Install

```bash
sudo apt update
```

```bash
sudp apt install default-jdk maven git
```

## From grpc-server folder

```bash
mvn package -Dmaven.test.skip=true
```

```bash
chmod 777 mvnw
```

```bash
./mvnw spring-boot:run -Dmaven.test.skip=true
```

## From grpc-client folder

```bash
mvn package -Dmaven.test.skip=true
```

```bash
chmod 777 mvnw
```

```bash
./mvnw spring-boot:run -Dmaven.test.
skip=true
```
