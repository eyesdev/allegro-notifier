# JAK UŻYWAĆ:

[Czytaj po angielsku](https://github.com/eyesdev/allegro-notifier/edit/main/README.md)

1. Kliknij prawym przyciskiem myszy puste miejsce w tym folderze i wybierz „Otwórz w terminalu”
2. Wykonaj `npm install`
3. Znajdź plik `users.txt` i otwórz go
4. Zastąp wszystkie konta i wpisz informacje o koncie w następującym formacie: `e-mail:hasło`
5. Znajdź plik `auctions.txt` i otwórz go
6. Zastąp te linki rzeczywistymi linkami do aukcji Allegro
7. Dostosuj plik `config.js` do swoich potrzeb

Nieruchomość | Wpisz | Opis

quantityPerAccount | numer | Ile tego przedmiotu należy kupić za pomocą jednego konta?
maximalBuyingPrice | numer | Jeśli cena na aukcji będzie równa lub niższa od tej wartości, bot podejmie próbę zakupu
priceCheckIntervalMs | numer | Jak często bot ma sprawdzać cenę w milisekundach - Formuła współczynnika żądań: 1x żądanie http przy każdej cenieCheckIntervalMs na 1 aukcję w pliku aukcje.txt
accountsToUseCount | numer | Ile kont z pliku account.txt chcesz używać?
headless | boolean (wartość logiczna) | Czy uruchomić przeglądarkę w trybie bezgłowym, czy nie. Używaj false tylko podczas debugowania


Użycie - Po wszystkim, wykonaj `npm run start` w terminalu, aby uruchomić program.
