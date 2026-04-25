#  Java Swing Blackjack

A robust, desktop-based implementation of the classic Blackjack card game. This project focuses on clean **Object-Oriented Programming (OOP)**, efficient **State Management**, and dynamic **GUI Rendering** using Java's Swing and AWT libraries.



##  Key Features

* **Intelligent Game Logic**: 
    * **Smart Ace Handling**: Automatically detects when a hand exceeds 21 and "reduces" Ace values from 11 to 1 to keep the player in the game.
    * **Automated Dealer (AI)**: The dealer follows standard casino rules, automatically hitting until their hand reaches a minimum value of 17.
* **Dynamic Visuals**: 
    * Renders card assets dynamically using image paths based on card values.
    * Features a "Hidden Card" mechanic where the dealer's first card is masked until the player chooses to "Stay."
* **User Interface**: 
    * Functional **Hit**, **Stay**, and **Reset** buttons.
    * Responsive game state updates (Repainting only when necessary).



##  Technical Stack

* **Language**: Java 17
* **Framework**: Java Swing & AWT (Abstract Window Toolkit)
* **Architecture**: Encapsulated Inner Classes and Event-Driven Programming.

##  Project Structure

```text
BLACKJACK/
├── bin/            # Compiled .class files (ignored by git)
├── src/            # Source code
│   ├── cards/      # PNG card assets
│   ├── App.java    # Application entry point
│   └── BlackJack.java # Core game engine and GUI logic
├── .gitignore      # Prevents build artifacts from being uploaded
└── README.md       # Project documentation
