# Wykonywanie testów

* Wykonywanie testu \(ang. test execution\) to proces przeprowadzenia testu na module lub systemie, w wyniku którego otrzymujemy rzeczywiste rezultaty.
* Test jest wykonywany według przypadku testowego.
* Test jest wykonywany z użyciem środowiska testowego określonego w planie testów i skonfigurowanego zgodnie z testowaną wersją.
* Wykonywanie testu rozpoczyna się po spełnieniu warunków wstępnych \(preconditions\) .
* Wykonywanie testu może być raportowane za pomocą narzędzi do wykonywania testów.
* Status kroków \(Passed lub Failed\).
  * Status całego testu jest uznawany jako zaliczony \(Passed\) dopiero wtedy, kiedy wszystkie kroki mają status Passed.
* Jedno żądanie zmiany \(ang. change request, CR\) może mieć powiązany ze sobą więcej niż jeden przypadek testowy .

{% hint style="info" %}
Aby status żądania zmiany mógł zostać uznany jako przetestowany \(np. Tested, Done\), wszystkie powiązane przypadki testowe muszą zostać wykonane i posiadać status Passed.
{% endhint %}

