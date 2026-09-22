# 🐰 Carrot Collector

**Carrot Collector** is a simple 2D Unity game where the player controls a bunny and collects carrots around the map.

The goal is simple: **collect all 6 carrots to win the game!**

## 🎮 Gameplay

The player controls a bunny using an on-screen joystick. There are **6 carrots** placed around the level.

When the bunny touches a carrot:

* 🥕 The carrot is collected.
* 🥕 The carrot disappears from the scene.
* 🔢 The collected carrot count increases.
* 🏆 After all 6 carrots are collected, a **Win** message appears.

## ✨ Features

* Simple 2D bunny character
* Android joystick movement
* Carrot collection system
* Carrots disappear after collection
* Score/collection tracking
* Win condition after collecting all 6 carrots
* Win text displayed when the game is completed

## 🕹️ Controls

### Android

Use the **on-screen joystick** to move the bunny around the map.

Move the bunny toward a carrot to collect it automatically.

## 🥕 Win Condition

There are a total of **6 carrots** in the game.

The player wins when all collected.

Once all carrots have been collected, the **Win Text** will appear on the screen.

## 🔧 Implementation

The project uses simple Unity mechanics such as:

* `FixedJoystick` for Android player movement
* `OnCollisionEnter2D()` for detecting carrot collection
* A score variable for tracking collected carrots
* `Destroy()` for removing collected carrots
* `GameObject.SetActive()` for displaying the win message

## 🛠️ Built With

* **Unity**
* **C#**
* **Unity 2D**
* **Fixed Joystick**
* **Android Controls**

## 🚀 Getting Start
