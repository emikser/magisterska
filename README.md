# EduConnector - aplikacja internetowa wspomagająca naukę poprzez zabawę

## Słowa kluczowe
edukacja, zabawa, tłumaczenie, zadanie, aplikacja, czas rzeczywisty, javascript, node.js, socket.io

## Streszczenie
Praca przedstawia aplikację internetową "EduConnector" do wspomagania nauki poprzez zabawę. Aplikacja ma na celu ułatwienie przekazywania wiedzy uczniom za pośrednictwem Internetu. Projekt przeznaczony jest dla uczniów i nauczycieli. Aplikacja składa się z graficznych interaktywnych predefiniowanych łamigłówek/zagadek jak na przykład przekładanie zapałek w celu ułożenia poprawnego równania matematycznego czy mieszanie ze sobą substancji chemicznych w celu wywołania odpowiedniej reakcji chemicznej. Przebieg każdego zadania odbywa się w czasie rzeczywistym, dzięki temu uczniowie mogą współpracować na bieżąco w grupie, czekając na swoją kolej. Dostępny jest również ranking aktywności, który motywuje do zaliczania kolejnych etapów. Komunikację pomiędzy uczniami z danej grupy zapewnia czat, który widoczny jest w każdym widoku aplikacji. Czat wykorzystywany może być także do wyświetlania informacji o zadaniach domowych i nadchodzących sprawdzianach. Od strony technicznej aplikacja uruchamia się w przeglądarce internetowej i bazuje na dwóch technologiach - Node.js oraz Socket.IO. Warstwa prezentacji stworzona została w języku HTML i CSS.

## Wstęp
Nowe technologie zachaczają o każdą dziedzinę życia i zajmują jego coraz większy obszar. Atrakcyjna forma rozrywki jaką serwują najnowsze urządzenia sprawia, że sięgają po nie dzieci w bardzo wczesnym wieku. Aplikacja "EduConnector" powstała w celu wykorzystania tego zjawiska w pożyteczny sposób. Ma za zadanie przekazywać wiedzę poprzez zabawę.

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
3. "Node.js w praktyce. Tworzenie skalowalnych aplikacji sieciowych." - Azat Mardan
4. "UML 2.0. Wprowadzenie." - Russ Miles, Kim Hamilton
5. "E-learning w edukacji. Jak stworzyć multimedialną i w pełni interaktywną treść dydaktyczną." - Zbigniew Zieliński
6. "E-learning dla nauczycieli." - Szabłowski Stanisław
7. https://pl.wikipedia.org/wiki/Czas_rzeczywisty (2016.09.21)
