# allegro-notifier

# THIS WAS PROGRAMMED/CODED BY JAKUB/EYESDEV

# HOW TO USE:
1. Right click an empty space in this folder and select "Open in terminal"
2. Do `npm install`
3. Find `users.txt` and open it
4. Replace all the accounts and write your account info in this format: `email:password`
5. Find `auctions.txt` and open it
6. Replace these links with the actual links to the allegro auctions
7. Tweak the `config.js` file to match your needs

Property | Type | Description

`quantityPerAccount` | number | How much of this item should a single account try to buy?
`maximalBuyingPrice` | number	| If price on the auction will be equal or less than this value bot will try to purchase
`priceCheckIntervalMs` | number | How often do you want the bot to check the price in milliseconds - Request rate formula: 1x http request every priceCheckIntervalMs per 1 auction in auctions.txt file
`accountsToUseCount` | number | How many of your accounts from accounts.txt file do you want to use?
`headless` | boolean | Whether to run the browser in the headless mode or not. Use false only when debugging


Useage - After all this, do `npm run start` in the terminal to start the program.

# JAK UŻYWAĆ:
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
