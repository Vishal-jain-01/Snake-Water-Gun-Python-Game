# Snake Water Gun - Python Game

A simple and fun command-line based **Snake, Water, Gun** game written in Python. This is a variation of the classic Rock-Paper-Scissors game, where:
- 🐍 Snake drinks water
- 💧 Water drowns gun
- 🔫 Gun kills snake

## Features

- Player vs. Computer gameplay
- Random computer choices using Python’s `random` module
- Score tracking
- Clear win/lose/draw logic
- User-friendly command-line interface

## Tech Stack

- 🐍 Python 3.x
- 🖥️ Command Line / Terminal

## Game Rules

| Player Choice | Computer Choice | Result        |
|---------------|------------------|---------------|
| Snake         | Water            | Player Wins   |
| Water         | Gun              | Player Wins   |
| Gun           | Snake            | Player Wins   |
| Same          | Same             | Draw          |
| Else          |                  | Computer Wins |

## How to Run

1. Clone the repo:
```bash
git clone https://github.com/Vishal-jain-01/snake-water-gun-python-game
cd snake-water-gun-python-game
