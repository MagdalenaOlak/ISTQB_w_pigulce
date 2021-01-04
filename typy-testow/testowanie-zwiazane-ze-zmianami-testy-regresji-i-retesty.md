# Testowanie związane ze zmianami - testy regresji i retesty

## Retesty \(potwierdzające\)

Testowanie potwierdzające \(ang. confirmation testing\) - po wykryciu i naprawieniu defektu, powinien zostać wykonany retest, żeby potwierdzić usunięcie usterki, jest to nazywane testami potwierdzającymi.

## Testowanie regresji \(ang. regression testing\) 

To powtórzenie testów na już przetestowanym programie wykonywane po modyfikacjach żeby wykryć nowe usterki lub usterki odsłonięte na skutek wykonanych zmian. Usterki te mogą występować w testowanym oprogramowaniu, jak również w innych powiązanych lub niepowiązanych modułach. Testy regresywne wykonuje się po zmianach w oprogramowaniu, a także po zmianach w jego środowisku.

{% hint style="info" %}
Testy, które mają być stosowane w testowaniu potwierdzającym i regresywnym muszą być powtarzalne
{% endhint %}

Zakres testów regresywnych wynika z ryzyka nieznalezienia usterek w oprogramowaniu, które poprzednio działało poprawnie.

{% hint style="info" %}
Testy regresywne można wykonywać na wszystkich poziomach testów i dla wszystkich typów testów: funkcjonalnych, niefunkcjonalnych i strukturalnych. 
{% endhint %}

Zestawy testów regresywnych są wykonywane wiele razy i są stosunkowo niezmienne, wobec czego **są dobrymi kandydatami do automatyzacji**.

