# Laundry-
This C++ program simulates the Laundry ABC self-service system. Users can buy or top up a card, choose washer settings by weight and temperature, and select dryer heat levels. The program stores selected services, calculates total cost, and displays a receipt.
# Laundry ABC Self-Service System

This C++ program simulates a self-service laundry system called **Laundry ABC**. It allows users to purchase and top up a laundry card, choose washer options based on laundry weight and water temperature, and select dryer options based on heat level.

## Features

- 💳 Purchase laundry card (RM2)
- 💰 Top up laundry card with custom amount
- 🧺 Washer service based on weight (10kg, 15kg, 20kg) and temperature (Cold, Warm, Hot)
- 🔥 Dryer service based on heat (Low, Medium, High)
- 🧾 Receipt with total cost and service breakdown

## How It Works

1. User is prompted to start the service.
2. User goes through four steps:
   - Card Purchase
   - Card Top-Up
   - Washer Selection
   - Dryer Selection
3. Program stores selected options and prices.
4. Displays a formatted receipt with all selected services and the total cost.

## Example Output

============= Laundry ABC =============
Service Detailed Price(RM)
Card 1 2.00
Top up - 10.00
Washer 15 kg 8.00
Dryer High 8.00
Total(RM): 28.00
Thank you for using our service. Please come again :)


## Notes

- Input validation is included, but some logic may require refinement.
- This program is designed for console execution using standard C++ libraries.

## Requirements

- C++ Compiler (e.g. g++, clang++)
- Standard C++ Library

## How to Run

```bash
g++ laundry_service.cpp -o laundry
./laundry

Fatin Qistina Binti Mohd Kamarul
Diploma in Computer Science - UiTM Jasin
Semester 1 Final Project
