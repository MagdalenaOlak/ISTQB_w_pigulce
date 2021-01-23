# POZIOM 1. Testy modułowe \(jednostkowe\)

## Podstawa testów

* projekt szczegółowy \(specyfikacje projektowe\)
* kod;
* model danych
* specyfikacje modułów \(wymagania na moduły\)

## Obiekty testów

* moduły, jednostki lub komponenty \(funkcjonalności\); 
* kod i struktury danych \(obiekty programów\); 
* klasy;
* moduły baz danych.

Testy modułowe/jednostkowe \(ang. component/unit testing\) są **wykonywane głównie przez deweloperów** w celu upewnienia się czy ich kod odpowiednio działa i czy spełnia wymagania użytkownika.

{% hint style="info" %}
Testowanie modułowe polega na testowaniu pojedynczych modułów oprogramowania.
{% endhint %}

#### Przykład: 

W aplikacji przechowującej dane studentów mogą istnieć dwa moduły – jeden, który rekordy pobiera rekordy z formularza rejestracyjnego oraz drugi, który te pobrane rekordy zapisuje. Każdy z tych modułów kodowany jest oddzielnie, więc w testach modułowych będą testowane oddzielnie.

## Testy modułowe:

* polegają na wyszukiwaniu błędów i weryfikacji funkcjonalności, które można testować oddzielnie
* mogą być wykonywane w izolacji od reszty systemu z użyciem sterowników testowych oraz symulatorów
* są wykonywane przy dostępie do kodu źródłowego i przy wsparciu środowiska rozwojowego \(np. narzędzi do debagowania\)
* usterki są usuwane od razu po wykryciu, bez formalnego zarządzania nimi
* przypadki testowe są projektowane na podstawie takich produktów jak: 
  * specyfikacja modułu
  * projekt oprogramowania 
  * model danych

Często przypadki testowe są przygotowywane i automatyzowane przed kodowaniem – jest to tak zwane **podejście "najpierw testuj"** lub **"wytwarzanie sterowane testowaniem"** opierające się na cyklach polegających na  wykonywaniu testów modułowych, poprawianiu usterek i powtarzaniu cyklu aż testy zostaną zaliczone.

## Cele testowania modułowego: 

* zmniejszanie ryzyka; 
* sprawdzanie zgodności zachowań funkcjonalnych i niefunkcjonalnych modułu z projektem i specyfikacjami; 
* budowanie zaufania do jakości modułu; 
* wykrywanie defektów w module; 
* zapobieganie przedostawaniu się defektów na wyższe poziomy testowania.

## Typowe defekty i awarie 

Przykładami typowych defektów i awarii wykrywanych w ramach testowania modułowego są:

* niepoprawna funkcjonalność \(np. niezgodna ze specyfikacją projektu\); 
* problemy z przepływem danych; 
* niepoprawny kod i logika.

