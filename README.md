# MATLAB Coffee Machine Simulator

A graphical coffee machine simulator developed using **MATLAB App Designer**. 
The application simulates the process of purchasing coffee, inserting coins, 
tracking the machine's available money, and automatically calculating the 
correct change.

## Project Overview

This project represents a virtual coffee machine with an interactive graphical 
user interface. Users can select from different coffee beverages, insert money 
using available coin denominations, and complete or cancel their purchase.

The machine keeps track of its internal state, including the available coins 
and money, allowing it to calculate and return appropriate change based on the 
money currently available inside the machine.

## Available Drinks

| Drink      | Price |
|---|---:|
| Espresso   | 2.00 KM |
| Cappuccino | 3.00 KM |
| Latte      | 3.00 KM |
| Macchiato  | 3.00 KM |
| Ristretto  | 2.00 KM |
| Americano  | 2.50 KM |

## Payment System

The coffee machine accepts the following coin denominations:

- 0.50 KM
- 1 KM
- 2 KM
- 5 KM

The inserted money is displayed on the machine interface. Once enough money 
has been inserted, the user can select and purchase a coffee.

The machine also maintains information about the coins currently available 
inside it. This allows the system to determine whether it can provide the 
required change.

## Change Calculation

The simulator includes a change-making system that calculates the customer's 
change based on the coins available in the machine.

The system attempts to provide change using the available denominations while 
updating the machine's internal coin balance.

This makes the payment system more realistic than simply calculating change 
without considering the machine's available coins.

## Graphical User Interface

The application was developed using **MATLAB App Designer** and provides an 
interactive interface that includes:

- Coffee selection buttons
- Coffee images
- Coffee prices
- Inserted-money display
- Coin buttons
- Machine status messages
- Coffee preparation animations
- Audio feedback
- Date and time display

## Machine Data

The coffee machine maintains persistent data about its current state.

The project uses data files to store information such as:

- Available money inside the machine
- Available coins for returning change
- Machine state between sessions
- Transaction-related information

This allows the simulator to start with a predefined amount of money and 
maintain the machine's state during use.

## Audio Feedback

The application uses audio effects to make the simulation more interactive.

Different sounds are used for events such as:

- Inserting coins
- Starting coffee preparation
- Completing a coffee
- Cancelling a transaction
- Insufficient funds
- Returning change

## Technologies Used

- **MATLAB**
- **MATLAB App Designer**
- MATLAB App Designer UI Components
- MATLAB audio functions
- MATLAB data/file handling
- Image assets and animations

## How to Run

1. Install **MATLAB** with App Designer support.
2. Clone or download this repository.
3. Make sure all required images, audio files, and data files are located in 
   the correct project directories.
4. Open the `.mlapp` file in MATLAB App Designer.
5. Run the application.

## Preview

![Coffee Machine Interface](images/coffee-machine-preview.png)

## Project Goals

The main goals of this project were to:

- Develop an interactive GUI using MATLAB App Designer.
- Simulate a real-world coffee machine.
- Implement user interaction and event handling.
- Implement a payment and coin-management system.
- Calculate and return change based on available coins.
- Manage persistent machine data.
- Provide an interactive and visually appealing user experience.

## Authors

Developed as a university project using MATLAB App Designer.

## 📄 License

This project was developed for educational purposes.
