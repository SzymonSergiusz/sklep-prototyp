# ENGLISH
# Prototype of a site to support game sales
## The project is divided into
- [database project](https://github.com/SzymonSergiusz/sklep-database/tree/dfdea5fe882f436b23b86175ac17a261b9ec5d50)
- [server](https://github.com/SzymonSergiusz/sklep-serwer/tree/1bbd436025d4e1462de2b168ceb8e18445e5a24d)
- [aplikacje webową](https://github.com/SzymonSergiusz/sklep-aplikacja/tree/15020cb397332ae19f47288124be975c924422bd)
## The purpose of the project
- to design a database
- create a server to support REST
- create a simple UI in the form of a web application
- designing requirements diagrams using UML

## Technology stack
- Swift + [Vapor framework](https://vapor.codes/) - server
- Svelte/SvelteKit](https://kit.svelte.dev/) + [SkeletonUI](https://www.skeleton.dev/)- web application
- PostgreSQL - database
- UML - diagrams
- Postman

_Why such a stack?_

When choosing a framework to write a server, I decided on [Vapor](https://vapor.codes/) out of sheer curiosity and a desire to learn more about the Swift language. Vapor for many would certainly not be the first choice when Spring or Django are on the market. I was surprised by the clarity of Vapor's documentation and how easy it is to write a server to handle multiple queries.
Svelte is a relatively new framework and not as popular as React or Angular, but I couldn't resist at the opportunity to test such a [praised framework by other developers] in a project(https://survey.stackoverflow.co/2023/#section-admired-and-desired-web-frameworks-and-technologies).
## System logic diagram
![Logic Diagram](https://github.com/SzymonSergiusz/sklep-prototyp/blob/main/readme-assets/schematlogiczny.png?raw=true)
## Implementation
Due to the short time for implementation, it was not possible to implement all the functionalities that an online store system should have.
What we managed to implement:
- login system with encryption and BasicAuth protocol
- REST queries from the client to the server
- handling queries from the server to the database
- creation of new users (possibility of registration)
[Full documentation including screenshots of the web application can be found](https://github.com/SzymonSergiusz/sklep-prototyp/blob/main/dokumentacja.pdf)

# POLISH
# Prototyp strony do obsługi sprzedaży gier
## Projekt dzieli się na
- [projekt bazy danych](https://github.com/SzymonSergiusz/sklep-database/tree/dfdea5fe882f436b23b86175ac17a261b9ec5d50)
- [serwer](https://github.com/SzymonSergiusz/sklep-serwer/tree/1bbd436025d4e1462de2b168ceb8e18445e5a24d)
- [aplikacje webową](https://github.com/SzymonSergiusz/sklep-aplikacja/tree/15020cb397332ae19f47288124be975c924422bd)
## Cel projektu
- zaprojektowanie bazy danych
- stworzenie serwera do obsługi REST
- stworzenie prostego UI w formie aplikacji webowej
- zaprojektowanie diagramów wymagań przy wykorzystaniu UML

## Stack technologiczny
- Swift + [framework Vapor](https://vapor.codes/) - serwer
- [Svelte/SvelteKit](https://kit.svelte.dev/) + [SkeletonUI](https://www.skeleton.dev/)- aplikacja webowa
- PostgreSQL - baza danych
- UML - diagramy
- Postman

_Dlaczego taki stack?_

Przy wyborze frameworku do pisania serwera postanowiłem wybrać [Vapor](https://vapor.codes/) z czystej ciekawości oraz chęci poznania języka Swift. Vapor dla wielu na pewno nie byłby pierwszym wyborem, kiedy na rynku jest Spring czy Django. Byłem zaskoczony przejrzystością dokumentacji Vapora oraz z jaką łatwością można napisać serwer do obsługi wielu zapytań.
Svelte jest relatywnie nowym frameworkiem i nie tak popularnym jak React czy Angular, jednak nie mogłem się oprzeć przy możliwości przetestowania w projekcie tak [zachwalanego frameworku przez innych programistów](https://survey.stackoverflow.co/2023/#section-admired-and-desired-web-frameworks-and-technologies).
## Schemat logiczny systemu
![Schemat Logiczny](https://github.com/SzymonSergiusz/sklep-prototyp/blob/main/readme-assets/schematlogiczny.png?raw=true)
## Realizacja
Ze względu na krótki czas na realizacje nie udało się zaimplementować wszystkich funkcjonalności jakie powinien posiadać system sklepu internetowego.
To co się udało zaimplementować:
- system logowania wraz z szyfrowaniem i protokołem BasicAuth
- zapytania REST z klienta do serwera
- obsługa zapytań z serwera do bazy danych
- tworzenie nowych użytkownik (możliwość rejestracji)
[Pełna dokumentacja wraz z zrzutami ekranu aplikacji webowej znajduje się](https://github.com/SzymonSergiusz/sklep-prototyp/blob/main/dokumentacja.pdf)
