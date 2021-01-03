# Planowanie testów

## Cele:

* ustalenie zakresu i ryzyka oraz zidentyfikowanie celów testowania
* zdefiniowanie ogólnego podejścia do testowania włącznie z definicją poziomów testów oraz kryteriów wejścia i zakończenia
* integrowanie i koordynowanie zadań testowych z innymi zadaniami cyklu życia oprogramowania: zakupami, dostawami, rozwojem, działaniem produkcyjnym oraz pielęgnacją
* podejmowanie decyzji co testować, którym rolom będą przypisane które zadania testowe, jak zadania testowe powinny być wykonane oraz jak powinno się oceniać wyniki testów
* harmonogramowanie analizy i projektowania testów
* harmonogramowanie implementacji, wykonania i oceny testów
* przydzielanie zasobów do zdań testowych
* definiowanie ilości, poziomu szczegółowości, struktury oraz wzorców dokumentacji testowej
* wybór metryk do monitorowania i kontroli przygotowania i wykonania testów, naprawy defektów oraz elementów ryzyka
* decydowanie o poziomie szczegółowości procedur testowych, aby dostarczyć wystarczającą ilość informacji dla powtarzalnego przygotowania I wykonania testów

### Testy planuje się, by określić:

1. cele i zakres testów,
2. harmonogram testowania,
3. podejście \(sposób przeprowadzenia testów\), 
4. techniki projektowania i wykonania testów, 
5. zasoby niezbędne do realizacji czynności testowych, 
6. produkty prac testowych, 
7. ryzyka związane z testowaniem.

{% hint style="info" %}
**Ważnym elementem planowania testów jest ustalenie kryteriów wejścia i wyjścia.**
{% endhint %}

### **Kryteria wejścia – definicja i warunki**

Kryteria wejścia definiują warunki pozwalające na rozpoczęcie testów na początku poziomu testów lub, gdy zbiór testów jest gotowy do wykonania.

**1.**      dostępność i gotowość środowiska testowego i narzędzi,

**2.**      dostępność testowalnego kodu,

**3.**      dostępność danych testowych.

### **Kryteria wyjścia – definicja i warunki**

Kryteria zakończenia określają warunki, które muszą być spełnione, by móc zakończyć testy na danym poziomie lub by stwierdzić, iż zbiór testów osiągnął określony cel. Kryteria wyjścia mogą być elementem składowym METRYK.

1. miary staranności \(pokrycie kodu, funkcjonalności lub ryzyka\),
2.  estymata \(oszacowanie\) gęstości błędów \(miary niezawodności\),
3. koszt \(zużycie budżetu\),
4. istniejące ryzyko \(np. niepoprawione usterki lub brak pokrycia pewnych obszarów\),
5. harmonogram \(np. czas do wypuszczenia produktu na rynek\).

### Podejścia do szacowania pracochłonności testów

* oparte na metrykach - bazuje na pomiarach minionych lub podobnych projektów lub na typowych wartościach
* oparte na ekspertach - szacowanie zadań przez ich przyszłych wykonawców lub przez ekspertów

### Typowe podejścia do testów

Podejście do testów jest definiowane i uszczegóławiane w planach testów oraz projektach testów. 

Zwykle zawiera decyzje podejmowane na podstawie celów projektu \(testowego\) oraz oceny ryzyka. Stanowi ono punkt wyjściowy do planowania procesu testowania, wyboru technik projektowania testów i stosowanych typów testów, a także do definiowania kryteriów wejścia i zakończenia.

#### **●   analityczne**

- \(testy oparte na ryzyku\), w którym testowanie jest kierowane na obszary o największym ryzyku

#### **●   oparte na modelach**

- \(testowanie stochastyczne\) wykorzystujące informacje statystyczne na temat współczynników awarii lub wykorzystania oprogramowania

#### **●   metodyczne**

 - podejścia oparte na awariach, oparte na doświadczeniu, na listach kontrolnych lub na atrybutach jakościowych

#### **●   zgodne ze standardem lub procesem**

- takie jak te określone przez standardy przemysłowe lub metodyki zwinne

#### **●   dynamiczne i heurystyczne**

– \(testowanie eksploracyjne\), w których testowanie bardziej reaguje na zdarzenia podczas testów niż jest wykonywane według planu i w których wykonywanie testów i ocena wyników dzieją się równolegle

#### **●   konsultatywne**

- pokrycie testowe jest sterowane głównie przez wskazówki i porady ekspertów technologicznych lub biznesowych z zewnątrz zespołu testowego

#### **●   regresywne**

 - w których używa się powtórnie istniejących materiałów testowych, rozbudowanej automatyzacji regresywnych testów funkcjonalnych oraz standardowych zestawów testów

