# _EasyBlocks_ – interaktywne tworzenie responsywnych stron internetowych

## Słowa kluczowe
strony internetowe, strony mobilne, responsywność, aplikacja, bootstrap, czas rzeczywisty, html, css, javascript, node.js, socket.io

## Streszczenie
Praca przedstawia aplikację internetową „EasyBlocks” do tworzenia responsywnych stron internetowych. Aplikacja ma na celu wspomaganie nauki tworzenia stron z wykorzystaniem biblioteki Bootstrap. Projekt przeznaczony jest dla osób, które chcą zdobyć wiedzę w sposób praktyczny. Aplikacja składa się z panelu zarządzania projektem z gotowymi komponentami biblioteki Bootstrap, które można umieszczać na siatce projektu. Komponenty to fragmenty kodu HTML i CSS, których właściwości można w dowolny sposób modyfikować w panelu. Oprócz komponentów, użytkownik może dodawać własny kod. Aplikacja umożliwia także podgląd w czasie rzewczywistym na urządzeniach mobilnych. Dzięki temu od razu widzać rezultat działań na różnych ekranach.

Moją motywacją była przyjazna i intuicyjna forma poruszania się po aplikacji. Dzięki temu użytkownicy w łatwy sposób mogą przyswoić sobie wiedzę na temat sposobu działania responsywnych stron internetowych. Dodatkowy podgląd sprawia, że

Od strony technicznej aplikacja uruchamia się w przeglądarce internetowej, napisana jest w języku JavaScript i bazuje na dwóch technologiach - Node.js oraz Socket.IO. Dane aplikacji przechowywane są w bazie danych MySQL. Warstwa prezentacji stworzona została za pomocą HTML Drag and Drop API oraz biblioteki Bootstrap.

## Wstęp
Nowe technologie zachaczają o każdą dziedzinę życia i zajmują jego coraz większy obszar. Atrakcyjna forma rozrywki jaką serwują najnowsze urządzenia sprawia, że sięgają po nie dzieci w bardzo wczesnym wieku. Aplikacja „EduConnector” powstała w celu wykorzystania tego zjawiska w pożyteczny sposób. Ma za zadanie przekazywać wiedzę poprzez zabawę.

Jednym z mediów, z którego korzysta prawie każdy młody człowiek jest Internet. Dlatego też aplikacja działa w zwykłej przeglądarce internetowej, aby zapewnić jak najłatwiejszy dostęp do jej zasobów. Kolejną ważną kwestią jest interakcja z innymi użytkownikami. Dzięki temu pojawia się rywalizacja, która w pozytywny sposób motywuje do nauki. 

Projekt wyróżnia się poprzez sposób dostepu do informacji. Większość stron internetowych pobiera dane do wyświetlania z serwera WWW jednorazowo z każdym odświeżeniem strony. Jednak zdarza się też, że pewne informacje docierają do nas na bieżąco, nie ma wtedy potrzeby odświeżania strony w celu sprawdzenia czy dane na stronie są nadal aktualne. Mówimy wtedy, że takie aplikacje internetowe działają w czasie rzeczywistym. Niniejszy projekt również korzysta z tego rozwiązania.  W dalszej części zostanie omówiony sposób w jaki działają takie aplikacje.

## Spis treści
1. Wstęp
2. Opis zagadnienia
3. Przedstawienie technologii
  1. Porównanie dostepnych rozwiązań
  2. Zastosowanie praktyczne
4. Projekt i analiza
  1. Aktorzy i przypadki użycia
  2. Diagram klas
  3. Diagram modelu danych
  4. Interfejs użytkownika
5. Implementacja
  1. Opis działania
  2. Użyte technologie
  3. Architektura
6. Testy
  1. Scenariusz testów
  2. Raport z testów
7. Wkład własny
8. Bibliografia

## Literatura
1. Dokumentacja techniczna biblioteki Node.js
2. Dokumentacja techniczna biblioteki Socket.IO
3. „Node.js w praktyce. Tworzenie skalowalnych aplikacji sieciowych.” - Azat Mardan
4. „UML 2.0. Wprowadzenie.” - Russ Miles, Kim Hamilton
5. http://getbootstrap.com/components/ (2017.01.22)
6. https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API (2017.01.22)
7. https://developer.mozilla.org/pl/docs/Web/JavaScript (2017.01.22)
8. https://www.mysql.com/ (2017.01.22)
9. https://pl.wikipedia.org/wiki/Czas_rzeczywisty (2017.01.22)
