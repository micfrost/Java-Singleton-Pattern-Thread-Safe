# Coffee Machine Singleton Application

## Overview
This Java-based project showcases the implementation of the Singleton design pattern through a coffee machine simulation. The Singleton pattern ensures that only one instance of the coffee machine is created, making the application an ideal example for understanding Singleton in a multithreaded environment.

## Features
- **Singleton Pattern**: Ensures one instance of CoffeeMachine.
- **Thread Safety**: Utilizes double-checked locking in `getInstance`.
- **Coffee Machine Operations**: Includes brewing, refilling beans, and water management.
- **Multithreading Simulation**: Demonstrates thread-safe operations in a simulated real-life scenario.

## Java Features

- **Singleton Pattern**: Implemented in the `CoffeeMachine` class to ensure a single instance.
- **Thread Safety**: Double-checked locking in the `getInstance` method.
- **Synchronized Methods**: Ensures thread-safe operations in a multithreaded context.
- **Multithreading**: Demonstrated in the `CoffeeApp` class using Java Threads.


## Structure
### `CoffeeMachine`
- Singleton class representing the coffee machine.
- Methods for brewing coffee, refilling beans, adding water, and checking water levels.

### `CoffeeApp`
- Main class to demonstrate the usage of `CoffeeMachine`.
- Simulates multiple threads interacting with the coffee machine.

## Running the Application
Execute the `CoffeeApp` main class. This will create multiple threads that interact with the singleton coffee machine, illustrating how the Singleton pattern operates in a multithreaded context.

## Purpose
The project is an educational tool for understanding the Singleton design pattern's application in Java, especially for scenarios requiring control over resource allocation in multithreaded environments.

Enjoy brewing your virtual coffee!

## Made by Michal Frost.