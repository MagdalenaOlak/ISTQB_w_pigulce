# Zgadywanie błędów

Zgadywanie błędów to technika, w której tester korzysta ze swojego doświadczenia, zgadując, jakie potencjalne błędy mogły zostać popełnione podczas projektowania i tworzenia kodu.

Na przykład jeżeli tester spodziewa się, że w oprogramowaniu będą występować awarie w przypadku wprowadzenia niepoprawnego hasła, zaprojektuje testy polegające na wprowadzaniu różnego rodzaju wartości w polu hasła w celu sprawdzenia, czy rzeczywiście popełniono taki błąd i czy poskutkował on defektem powodującym awarię po uruchomieniu testu.

Uporządkowane podejście do zgadywania błędów polega na sporządzeniu listy możliwych defektów i na zaprojektowaniu testów, które atakują te defekty. To systematyczne podejście jest nazywane **atakiem usterkowym**.

Listy defektów i awarii można budować na podstawie doświadczenia, dostępnych danych na temat usterek i awarii oraz na ogólnej wiedzy dlaczego oprogramowanie nie działa.

### **Obszar zastosowania**

Zgadywanie błędów stosuje się przede wszystkim podczas testów integracyjnych i systemowych, można to jednak robić na dowolnym poziomie testowania. Ta technika często jest stosowana razem z innymi technikami i ułatwia poszerzenie zasięgu istniejących przypadków testowych. Zgadywanie błędów może się także okazać skuteczne podczas testowania nowej wersji oprogramowania pod kątem częstych pomyłek i błędów przed rozpoczęciem bardziej rygorystycznego testowania z udokumentowanymi testami.

