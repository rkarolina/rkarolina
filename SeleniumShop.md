## Testy eksploracyjne

### Opis 
[Selenium Shop](http://www.selenium-shop.pl) to platforma testowa do doskonalenia swoich umiejętności testowania oprogramowania. 
<p>Aplikacja jest sklepem internetowym, gdzie można zakupić ubrania i akcesoria sportowe.</p>

### Funkcjonalności aplikacji

1. Rejestracja nowego konta
2. Logowanie użytkownika
3. Możliwość zapamiętania hasła
4. Zmiana hasła
5. Przeglądanie produktów
6. Sortowanie produktów na stronie
7. Dodawanie produktów do koszyka
8. Wyświetlanie zdjęć produktów
9. Przeglądanie i aktualizacja koszyka zakupowego
10. Możliwość zastosowania kodu żniżkowego
11. Wybór sposobu dostawy
12. Przelicznie kosztów wysyłki (także za granicę)
13. Złożenie zamówienia
14. Ankieta sprzedażowa - możliwość podzielenia się opinią
15. Wyszukiwanie produktów 
16. Możliwość dodania opinii
17. Powrót do początku (góry strony)

### Znalezione błędy w aplikacji

#### Strona główna

- Pusty odnośnik "ZOBACZ"

![1_pusty_link.png](img%2FSeleniumShop%2F1_pusty_link.png)

- Puste odnośniki znajdują się również w stopce strony w sekcji Social Links.
#### Ankieta

- literówka w oknie z danymi przed potwierdzeniem formularza

![3_ankieta.png](img%2FSeleniumShop%2F3_ankieta.png)

#### Moje konto

- po utworzeniu konta nie można zresetować hasła

#### Sklep
- niewidoczny opis checkboxa dotyczącego zapamiętania danych przy dodawaniu kolejnych opinii
![2_checkbox_opinie.jpg](img%2FSeleniumShop%2F2_checkbox_opinie.jpg)

#### Zamówienie
- wyświetlana podpowiedź w polu wyszukiwania produktu jest w języku angielskim (strona nie ma innej wersji językowej niż polski)

![4_language.png](img%2FSeleniumShop%2F4_language.png)