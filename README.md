# 🎲 Tenzies Game

Tenzies is a simple and addictive dice game built with React. The goal is to roll until all dice show the same number. Players can "hold" dice to freeze their values between rolls, allowing for strategic gameplay and a bit of luck.

## Live Demo

👉 [Play Tenzies Online](https://your-deployment-link.com)

## 📸 Screenshot

![Tenzies Game Screenshot](./assets/screenshot.png)


## Features

- Generates 10 dice with random values from 1 to 6
- Clickable dice to toggle their `held` state
- Rolls only the dice that are not held
- Win condition: all dice are held and have the same value
- Confetti animation on win using `react-confetti`
- Button changes to "New Game" after winning
