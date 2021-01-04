# 7 zasad testowania

## Zasady testowania \(wg ISTQB\):

1. Testowanie ujawnia usterki.
2. Testowanie gruntowne jest niemożliwe.
3. Wczesne testowanie oszczędza czas i pieniądze.
4. Kumulowanie się błędów .
5. Paradoks pestycydów.
6. Testowanie zależne od kontekstu.
7. Przekonanie o braku błędów jest błędem.

![](../.gitbook/assets/7-zasad-testowania.jpg)



## I. Testowanie ujawnia usterki

Nigdy nie można stwierdzić, że oprogramowanie jest w 100% wolne od błędów. Testowanie może pokazać, że w oprogramowaniu istnieją defekty, ale nie może dowieść, że oprogramowanie ich nie posiada. Zmniejsza prawdopodobieństwo występowania w oprogramowaniu niewykrytych defektów, ale nawet jeśli żadne nie zostały znalezione, nie stanowi to dowodu, że nie mogą wystąpić.

## II. Testowanie gruntowne jest niemożliwe

Przetestowanie wszystkiego \(wszystkich możliwych scenariuszy, kombinacji, warunków początkowych, ustawień itd.\) najczęściej jest niemożliwe lub jest możliwe jedynie w bardzo mało skomplikowanych przypadkach. Nie należy planować przetestowania wszystkich możliwych kombinacji, ale wykorzystać analizę ryzyka i priorytetyzację.

## III. Wczesne testowanie oszczędza czas i pieniądze

Najlepiej, jeśli usterki zostaną wykryte jak najwcześniej. Może to skutkować bardzo dużymi oszczędnościami, odpowiednim nakierowaniem pracy programistów, uniknięciem nakładu czasu pracy na implementację funkcji niezgodnie z wymaganiami i ostatecznie zadowoleniem klienta z oprogramowania dostarczonego terminowo i działającego zgodnie z jego oczekiwaniami. Testowanie może zostać rozpoczęte w cyklu rozwoju oprogramowania tak wcześnie, jak to tylko jest możliwe.

## IV. Kumulowanie się błędów

– zasada ma odzwierciedlenie w powszechnie stosowanej tzw. „zasadzie Pareto” \(zasada 80 na 20\) Niewielka liczba modułów zwykle zawiera większośc defektów znalezionych przed wydaniem wersji oprogramowania lub jest odpowiedzialna za większość awarii na produkcji. Pracochłonność testowania jest dzielone proporcjonalnie do spodziewanej oraz zaobserwowanie gęstości błędów w poszczególnych modułach. Ta zasada ma odzwierciedlenie w powszechnie stosowanej tzw. "Zasadzie Pareto" \(znana również jako zasada 80/20 lub 80 na 20 – zasada opisująca wiele zjawisk, zgodnie z którą 80% wyników pochodzi z 20% działań\)

## V. Paradoks pestycydów

Jeżeli te same testy są powtarzane bez zmian, to po pewnym czasie przestaną znajdować nowe usterki. Jeżeli używamy tych samych pestycydów, to po pewnym czasie szkodniki się na nie uodparniają i przestają na nie reagować. Aby przezwyciężyć "paradoks pestycydów", testy muszą być regularnie przeglądane i uaktualniane, uwzględniając np. nowe funkcjonalności i scenariusze, aby umożliwić odszukanie nowych usterek, które mogą wystąpić w danych obszarze oprogramowania.

## VI. Testowanie zależne od kontekstu

Testowanie wykonuje się w różny sposób w różnym kontekście. Oprogramowanie i jego przeznaczenie znacząco różni się od siebie, np. podczas testowania aplikacji bankowej dużo większy nacisk należy położyć na bezpieczeństwo i zabezpieczenie wrażliwych danych, natomiast przy testowaniu strony internetowej większe znaczenie może mieć odpowiednia prezentacja treści i multimediów, bo w tym przypadku może to mieć kluczowe znaczenie dla klienta i użytkownika.

## VII. Przekonanie o braku błędów jest błędem

Nawet jeśli uważamy, że oprogramowanie jest wolne od defektów \(a najpewniej nie jest\), nie oznacza to, że system nadaje się do użytkowania i spełnia wszystkie wymagania i oczekiwania użytkownika. Może okazać się, że oprogramowanie działa prawidłowo z perspektywy braku usterek, ale nie jest przyjazne użytkownikowi lub nie posiada funkcji pożądanych przez klienta, a więc z jego punktu widzenia jest bezużyteczne.

