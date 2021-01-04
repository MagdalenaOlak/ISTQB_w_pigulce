# POZIOM 1. Testy modułowe \(jednostkowe\)

## Podstawa testów

* wymagania na moduły
* projekt szczegółowy
* kod

## Obiekty testów

* moduły, programy
* programy do konwersacji lub migracji danych
* moduły bazodanowe.

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

Często przypadki testowe są przygotowywane i automatyzowane przed kodowaniem – jest to tak zwane **podejście "najpierw testuj"** lub **"wytwarzanie sterowane testowaniem"** opierające się na cyklach polegających na  wykonywaniu testów modułowych, poprawianiu usterek i powtarzaniu cyklu aż testy zostaną zaliczone

