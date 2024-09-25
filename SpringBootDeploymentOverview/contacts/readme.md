
## Run prod profile:
```
java -jar target/contacts-0.0.1-SNAPSHOT.jar --spring.profiles.active=prod
```

# Set Memory DB User and Pass:

## bash
```bash
export DB_USERNAME=user
export DB_PASSWORD=pass
java -jar target/contacts-0.0.1-SNAPSHOT.jar
```

## Windows Command Prompt cmd
```sh
set DB_USERNAME=user
set DB_PASSWORD=pass
java -jar target/contacts-0.0.1-SNAPSHOT.jar
```

## Windows PowerShell
```sh
$env:DB_USERNAME="user"
$env:DB_PASSWORD="pass"
java -jar target/contacts-0.0.1-SNAPSHOT.jar
```