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
[Pełna dokumentacja wraz z zrzutami ekranu aplikjacji webowej znajduje się](https://github.com/SzymonSergiusz/sklep-prototyp/blob/main/dokumentacja.pdf)
