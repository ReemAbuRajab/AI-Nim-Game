# Matchstick Game

A simple web-based game where a player competes against an AI to remove matchsticks. The game ends when all matchsticks are removed, and the player who takes the last matchstick wins.

## Prerequisites

- Python 3 installed on your machine. You can download Python from [the official website](https://www.python.org/downloads/).

## Setup and Run

1. **Clone the Repository**: If you have this game in a Git repository, you can clone it using:
    ```
    git clone <repository-url>
    cd <repository-directory>
    ```
   If you've downloaded the game as a zip file, unzip it and navigate to the root directory in your terminal or command prompt.

2. **Start the Python Server**: From the root directory of the game, run the following command to start a simple HTTP server:
    ```
    python -m http.server 8000
    ```
   If you're using Python 2 (though it's recommended to use Python 3), the command would be:
    ```
    python -m SimpleHTTPServer 8000
    ```

3. **Access the Game in a Web Browser**: Open a web browser and navigate to:
    ```
    http://localhost:8000
    ```

4. **Play the Game**: You'll now see the game interface. Follow the on-screen instructions to play against the AI.

5. **Stop the Server**: Once you're done playing or wish to stop the server, return to your terminal or command prompt and press `Ctrl+C`.

## Game Rules

1. On each turn, the player can remove matchsticks from any row.
2. The AI then makes its move, also removing matchsticks.
3. The game continues until all matchsticks are removed.
4. The player who removes the last matchstick wins the game.

---

Note: you can also open the index.html file using a browser and it should work.
