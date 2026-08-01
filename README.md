# OOPtask
# Garage Management System (CLI App)

## Description

A Python-based interactive Command Line Interface (CLI) application designed to efficiently manage a garage containing racing cars and support vehicles. This application implements Object-Oriented Programming (OOP) principles, data validation, and automated performance tracking for different vehicle types.

## Features

* **Check In a Car:** Add new vehicles to the garage by selecting between two distinct types:
  * **Racing Cars:** Tracks specialized metrics including race counts and total laps automatically calculated from races.
  * **Support Vehicles:** Tracks crew member counts and reliability ratings (0 to 10).
* **View the Garage:** Display a structured breakdown of all currently checked-in racing cars and support vehicles along with their calculated performance scores.
* **Tune-Up:** Update the attributes, specifications, and performance metrics of any existing car using its unique ID.
* **Retire:** Remove a vehicle from the garage inventory permanently by entering its ID.
* **Find a Car:** Search for a specific vehicle by its ID to view its complete details instantly.
* **Garage Report:** Generate an analytical summary displaying total checked-in cars, average performance scores across the entire garage, and a breakdown of vehicle counts per team.

## Requirements & Technologies

* Python 3.x (Built entirely with core Python using Object-Oriented Programming principles and core data structures).

## How to Run

1. Ensure Python is installed on your system.
2. Clone this repository or download the script file.
3. Open your terminal in the script directory and run:
   ```bash
   python main.py
