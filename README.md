# dagonsMountain

A text-based roguelike for the terminal. Pick a class and fight your way up the mountain towards Dagon.

**Status:** Archived

This was the first program I wrote from scratch without any guidance, in my first semester of university in 2021.

## Gameplay

- Three classes: Mage, Warrior and Assassin, each with its own stats and abilities
- Six enemy types, from Slime to the Ghost of Spicy Curry, scaled to your level
- Turn-based combat: attack, use an ability or run
- Each level-up gives three points to spend on health, mana, attack, evasion, defence or perception

Dagon himself never made it in. The boss fight is still a `FIXME`, so the climb goes on until you die or head back down.

## Requirements

- A Java Development Kit (JDK)

## Usage

```sh
javac -d build dagonsMountain.java
java -cp build dagonsMountain.dagonsMountain
```

## Licence

Released under the MIT licence (see `LICENSE`).
