# 👀 Googley Eyes — Multiplayer Network Game

## Project Overview

Googley Eyes is a multiplayer network game developed using **Java Socket Programming** and **Java Swing GUI**.

The game allows multiple players to connect to a central server and compete in a visual challenge where players must quickly identify the **different number hidden in a grid of similar numbers**.

Players join a waiting room, start the game together, and compete to find the correct number before others to gain points.

This project was developed as part of a **Computer Networks university course project**.

---

## Game Concept

During each round, players are shown a large grid containing mostly identical digits.
One digit is different from the rest.

The goal of the game is to **quickly identify the different number and submit the correct answer**.

Players gain points for correct answers, and the first player to reach the winning score wins the game.

---

## Features

### Multiplayer Networking

* Client–server architecture
* Multiple players connected to a central server
* Real-time communication using **Java sockets**

### Game Flow

* Player registration with username
* Connected players screen
* Waiting room before the game starts
* Multiplayer gameplay rounds
* Score tracking and leaderboard
* Winner announcement

### User Interface

* GUI built with **Java Swing**
* Custom fonts and styled components
* Interactive game screen
* Countdown timers for rounds
* Score display for all players

---

## Technologies Used

### Programming Language

![Java](https://img.shields.io/badge/Java-orange?style=flat-square\&logo=openjdk)

### Networking

* Java Socket Programming
* Client–Server Architecture

### User Interface

* Java Swing

---

## Project Structure

```
GoogleyEyes-Network-Game
│
├── GameServer.java
├── GameClient.java
├── RegistrationFrame.java
├── ConnectedPlayersFrame.java
├── WaitingRoomFrame.java
└── (Game logic classes)
```

---

## My Contribution

Raghad Aldajani

* Implemented parts of the **client-side interface**
* Contributed to **game logic and networking communication**
* Assisted with **multiplayer synchronization and testing**
