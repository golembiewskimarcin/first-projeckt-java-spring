Zadanie 1.

## Opis projektu
Jest to prosta aplikacja stworzona przy użyciu **Spring Boot**, która demonstruje podstawy działania kontrolerów, 
widoków HTML oraz integrację z Thymeleaf.
W zadniu przedstawiono i wykorzystano:
- Obsługę żądania HTTP GET na endpointach:
    - `/` - Zwraca prosty tekst powitalny.
    - `/greeting` - Zwraca dynamiczny widok HTML z możliwością przekazania parametru `name`.
- Wyświetlanie widoku HTML (`greeting.html`) z dynamiczną treścią.
- Wczytywanie i wyświetlanie obrazu z katalogu `static/images`.

Wykorzystano springinitzializr z zależnościami Spring Web, Lombok, Thymeleaf.
Uruchomienie projektu:
http://localhost:8080/greeting?name=Vistula 