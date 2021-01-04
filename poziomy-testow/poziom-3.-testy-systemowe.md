# POZIOM 3. Testy systemowe

## Podstawa testów

* wymagania na system i oprogramowanie
* przypadki użycia \(use cases\) 
* specyfikacja funkcjonalna
* raporty z analizy ryzyka

## Obiekty testów

* podręczniki systemowe, użytkownika i operacyjne
* konfiguracje systemu i dane konfiguracyjne

Testy systemowe zajmują się zachowaniem systemu, zakres testów powinien być jasno określony w planie testów.

**Przykład**

W systemie przechowującym dane studentów istnieją różne moduły – pobierający rekordy z formularza rekrutacyjnego, zapisujący pobrane rekordy, umożliwiający dodanie nowego studenta manualnie. Testy systemowe sprawdzają na przykład czy przypadek użycia polegający na dodaniu nowego studenta manualnie, a następnie pobraniu danych dla tego samego studenta z formularza rekrutacyjnego nadpisuje dane studenta dodanego manualnie \(gdyż jest to zgodne z wymaganiami i specyfikacją\).

## Testy systemowe mogą zawierać

* testy oparte na:
  *  ryzyku
  * wymaganiach
  * procesie biznesowym
* przypadkach użycia lub innych wysokopoziomowych opisach zachowania systemu
* interakcji z systemem operacyjnym, zasobami systemowymi itp.

{% hint style="info" %}
Testy powinny sprawdzać funkcjonalne jak i niefunkcjonalne wymagania, które mogą być wyrażone w formie tekstu lub modeli.
{% endhint %}

Testerzy powinni potrafić dobrać odpowiednie techniki dla testowanego aspektu systemu.

