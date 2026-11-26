# hovik
https://dzone.com/articles/building-a-web-ui-for-mysql-databases-in-plain-jav-2

## Budowanie

Projekt jest przeznaczony dla JDK 8. Wrapper pobiera Maven przy pierwszym uruchomieniu:

```sh
./mvnw clean package
```

Na nowszych wersjach Javy stary Spring Boot może nie uruchomić testu kontekstu. Aby tylko zbudować plik WAR, można użyć `./mvnw clean package -DskipTests`. Uruchomienie aplikacji wymaga również skonfigurowanej bazy MySQL i tabeli `customers`.
