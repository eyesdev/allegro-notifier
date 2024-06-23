# allegro-notifier

[Read in Polish/Czytaj po Polsku](https://github.com/eyesdev/allegro-notifier/blob/main/README_POLSKI.md)


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


Usage - After all this, do `npm run start` in the terminal to start the program.
