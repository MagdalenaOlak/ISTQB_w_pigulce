# POZIOM 2. Testy integracyjne

## Podstawa testów

* projekt oprogramowania i systemu
* architektura na poziomie modułów i systemu
* przepływ procesów \(przepływy pracy\)
* diagramy sekwencji
* specyfikacje interfejsów
* definicje interfejsów zewnętrznych
* przypadki użycia \(use cases\)

## Obiekty testów

* implementacja baz danych podsystemów
* infrastruktura, interfejsy \(zasady łączenia\)
* konfiguracja systemu i dane konfiguracyjne. 
* wykonywane **na poziomie modułów i systemów**.

Testy integracyjne sprawdzają interfejsy pomiędzy modułami, interakcje z innymi częściami systemu \(takimi jak system operacyjny, system plików i sprzęt\) oraz interfejsy pomiędzy systemami.

**Przykład:** 

W aplikacji przechowującej dane studentów istnieją dwa moduły – jeden, który pobiera rekordy z formularza rekrutacyjnego oraz drugi, który te pobrane rekordy zapisuje. Testy integracyjne sprawdzają czy po połączeniu moduły prawidłowo ze sobą współpracują, na przykład czy pobrane rekordy są poprawnie zapisywane w bazie z danymi studentów.

#### **Testowanie integracji modułów** 

sprawdza interakcje pomiędzy modułami i jest wykonywane po testach modułowych

#### **Testowanie integracji systemów** 

sprawdza interakcje pomiędzy różnymi systemami lub pomiędzy sprzętem a oprogramowaniem i może być wykonywane po zakończeniu testów systemowych

Im większy jest zakres integracji, tym trudniejsze może być określenie, który moduł lub system zawiera defekt, co zwiększa ryzyko i wydłuża czas rozwiązywania problemów.

Testerzy koncentrują się wyłącznie na samej integracji, a nie na funkcjonalności poszczególnych modułów \(lub systemów\), ponieważ była ona sprawdzona wcześniej w testach modułowych \(lub systemowych\)

Testerzy powinni rozumieć architekturę i mieć wpływ na planowanie integracji. Jeżeli testy integracyjne planowane są zanim moduły lub systemy zostały wyprodukowane, można ich rozwój ustawić w kolejności pozwalającej na najbardziej efektywne testowanie.

Cele testowania integracyjnego 

* zmniejszanie ryzyka; 
* sprawdzanie zgodności zachowań funkcjonalnych i niefunkcjonalnych interfejsów z projektem i specyfikacjami; 
* budowanie zaufania do jakości interfejsów; 
* wykrywanie defektów \(które mogą występować w samych interfejsach lub w modułach/systemach\); 
* zapobieganie przedostawaniu się defektów na wyższe poziomy testowania.

