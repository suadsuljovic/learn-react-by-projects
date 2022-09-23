# Hearthstone api

Important notes:

- Use context or any other state manager

- Use react-router or any other router library

- UI needs to be fully responsive

- The news posts on the landing page should be displayed in cards

- You are allowed to use a UI library of your own choosing.

API: https://develop.battle.net/documentation/hearthstone/game-data-apis

You will need to create a battle.net account and a client to be able to use this API.

Check that here: https://develop.battle.net/documentation/guides

## Intro

Hearthstone is a Blizzard's Trading card game with a lot of years of content. Your job as a intern at Blizzard is to make a simple and clean UI for our users so they can search and find all the beautiful cards we have created over the years.

You can get idea about what we are building here: https://hearthstone.blizzard.com/en-us/cards?set=standard

But that page is too old and we want you to build something to impress us.

## Modes

You will need to make different pages for each of the possible modes hearthstone has:
Card library, Mercenaries and Battlegrounds

There should be a way for users to go from one mode to another.

## Cards

This game would not exist without cards so you must be able to show the cards to the user in the highest quality possible.

User should be able to click on each card and see more specific data about it.

## Classes

Hearthstone has 10 classes and neutral class. Only neutral cards are playable by each class and other cards are only usable by one class.

You should display cards by class.

## Filters

Since Hearthstone has been there for a lot of years there are a lot of sets.

User should be able only to search cards from specific set.

Also each card have couple of things that define it like: health, attack, mana cost, spell type, minion type, spell school, rarity and keywords.

User should be able to filter cards by each of them.

These filters are not same for each game mode. So you should only use the available filters for the game mode.

## Bonus

This si not the only API we at Blizzard offer you to work with. Explore other and tell us what kind of projects you want to build more.

Also If would be amazing if you can allow existing players to login to your website and look at their collection of cards there.

They should also be able to filter them by all the ways described above with the main difference where they will be able to see if they own that card or not.
