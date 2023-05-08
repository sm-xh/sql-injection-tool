Wykrywanie różnych typów ataków - aplikacja powinna umożliwiać wykrycie wybranych typów ataków SQL Injection, tj. Boolean-based, Error-based, Union-Based, Out-of-band.

Możliwość dostosowania - aplikacja wspiera ataki na wybrane typy bazy danych, tj. SQLLite, Microsoft SQL Server, PostgreSQL, MySQL.
    
Wyszukiwanie potencjalnych podatności - aplikacja powinna umożliwiać wyszukiwanie potencjalnych podatności SQL Injection poprzez analizowanie zapytań SQL i parametrów przekazywanych do bazy danych.

Mozliwość bezpośredniego podłączenia do bazy danych poprzez podanie danych do uwierzytelnienia, adresu IP, portu oraz nazwy bazy danych

Możliwość parsowania formularzy HTML w celu przetestowania możliwości przeprowadzenia ataku poprzez modyfikację parametrów wysyłanych w formularzu.
    
Ustawienia aplikacji mogą zostać zapisane w dedykowanym pliku, w celu ułatwienia obsługi dla użytkownika końcowego. Plik konfiguracyjny zawiera konfigurację, którą standardowo użytkownik może wprowadzić za pomocą flag w linii poleceń.
    
Strona, która powinna zostać przeskanowana powinna zostać przekazana jako parametr dostarczany przez użytkownika aplikacji.
 
Raportowanie wyników - aplikacja powinna umożliwiać raportowanie wyników detekcji podatności SQL Injection dla użytkownika końcowego, w tym informacji o miejscach wystąpienia podatności, typie ataku oraz innych szczegółach.
    
Automatyzacja testów - aplikacja powinna umożliwiać automatyzację testów w celu szybkiego wykrycia podatności SQL Injection podczas testów bezpieczeństwa w procesie CI/CD.

Ochrona przed false positive - aplikacja powinna posiadać skuteczne mechanizmy redukcji false positive, aby minimalizować ilość błędnych wykryć podatności SQL Injection.

Kompatybilność z wybranym system operacyjnym - Linux.
    
Zapisywanie wyników - aplikacja powinna umożliwiać zapisywanie wyników w celu późniejszego analizowania i raportowania.

Analiza użytych dependencji w kodzie źródłowym aplikacji pod kątem różnych CVE związanych z atakiem SQL Injection.
