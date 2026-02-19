Electrical Load Monitoring System
Week 1 Implementation
Overview

This project is a menu-driven C++ console application developed for the Electrical Load Monitoring capstone project.

Week 1 focuses on building the basic structure of the system, allowing users to register electrical appliances and view the list of registered appliances.

Features Implemented (Week 1)

Appliance structure definition using struct

Dynamic storage using vector

Menu-driven interface

Register appliance feature

View all registered appliances

Input validation for:

Empty appliance name

Power rating must be greater than zero

Usage hours must be between 0 and 24

Technologies Used

C++ programming language

Standard libraries:

<iostream>

<vector>

<string>

<iomanip>

<limits>

How the Program Works

The program displays a menu.

The user can register an appliance by entering:

Appliance name

Power rating (Watts)

Usage hours per day

Registered appliances are stored in memory using a vector.

The user can view all registered appliances in a formatted table.

The program runs in a loop until the user chooses to exit.

Project Structure (Week 1)
main.cpp
README.md

Sample Menu
1. Register appliance
2. View all appliances
0. Exit

Week 1 Objective

The goal of Week 1 is to establish a working foundation for the system before adding calculations, billing, and file persistence in later weeks.