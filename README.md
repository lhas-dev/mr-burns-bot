# Mr Burns Bot

![](https://upload.wikimedia.org/wikipedia/pt/a/a7/Montgomery_Burns.png)

This is a bot for tracking arbitration signals.

## Installation Guide

```
git clone git@github.com:lhas2/mr-burns-bot.git
cd mr-burns-bot/
npm install
```

## Running

```
node .
```

## How it works

The first step is to download symbols prices from all exchanges listed.

After that, the bot will organize these symbols prices with exchange data inside.

Then, it will order all exchange prices for the same symbol.

The highest price will be the Seller Exchange (SE).

The lowest price will be the Buyer Exchange (BE).

## Roadmap

- Initialize the application;
- Download all symbol prices from each exchange;
- Organize symbol prices into highest and lowest prices;
- Calculate taxes for withdraw and deposit for each exchange;
- Display the potential signals for the end user.

