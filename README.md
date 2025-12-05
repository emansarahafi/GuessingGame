# Guessing Game

A JavaFX desktop application featuring two interactive games, developed for Windows Programming (CMPE 361) course.

## Features

### 1. Guess The Number

- Random number generation between 0 and 100
- Interactive guessing with feedback
- "Give Up" option to reveal the answer
- Pop-up prompts to continue or quit after each round

### 2. Math Quiz Game

- User authentication with username entry
- Solve equations in the form: ax = b
- **Basic Mode**: a ranges from 0 to 10
- **Advanced Mode**: a ranges from 11 to 100
- Customizable settings:
  - Adjustable font size
  - Theme selection

## Technologies

- **Language**: Java
- **Framework**: JavaFX
- **IDE**: Eclipse

## Project Structure

```
GuessingGame/
├── src/
│   └── application/
│       ├── Main.java
│       └── application.css
├── bin/
│   └── application/
│       └── application.css
├── build.fxbuild
├── LICENSE
└── README.md
```

## Setup & Installation

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- JavaFX SDK
- Eclipse IDE (recommended)

### Running the Application

1. Clone this repository

   ```bash
   git clone https://github.com/emansarahafi/GuessingGame.git
   ```

2. Open the project in Eclipse
3. Ensure JavaFX is properly configured in your build path
4. Run `Main.java` as a Java Application

## How to Play

1. Launch the application
2. Select a game from the menu:
   - **Guess The Number**: Try to guess the random number with hints
   - **Math Quiz Game**: Solve algebraic equations
3. Follow on-screen instructions for each game
4. Use the menu to switch between games or exit

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

## Course Information

**Course**: CMPE 361 - Windows Programming  
**Project Type**: Educational/Academic
