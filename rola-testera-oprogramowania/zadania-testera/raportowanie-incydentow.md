# Raportowanie incydentów

## Zasady podstawowe

{% hint style="warning" %}
#### WSZELKIE incydenty znalezione podczas wykonywania testu muszą zostać przez testera odpowiednio zaraportowane i udokumentowane
{% endhint %}

{% hint style="info" %}
Status **Failed** dla przypadku testowego.
{% endhint %}

{% hint style="info" %}
Status **Rework** dla żądania zmiany.
{% endhint %}

Tester ma obowiązek raportować każdy napotkany problem w systemie/module i każde zachowanie systemu/modułu niezgodne z wymaganiami.

Jeśli znaleziony problem wymaga osobnych zmian w kodzie, tester rejestruje nowy problem \(issue\), najczęściej za pomocą narzędzia do raportowania błędów \(np. JIRA, Bugzilla\).

## Rejestrowanie incydentów

Przy rejestrowaniu nowego problemu \(ang. issue\) tester musi podać informacje i scenariusze niezbędne do powtórzenia problemu, m.in.:

* Projekt i wersję, w których problem został znaleziony.
* Moduł, w którym problem został znaleziony.
* Środowisko, na którym został wykonany test.
* Podsumowanie znalezionego problemu.
* Opis problemu.
* Dane osoby rejestrującej problem \(issue\) oraz data zarejestrowania.
* Ocena zarejestrowanego incydentu/problemu \(issue evaluation\), priorytet \(priority\) i stopień krytyczności \(severity\).
* Powstanie żądania zmiany dla danego problemu.

