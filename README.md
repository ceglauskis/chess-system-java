# Chess System (Java)

This project implements the core logic of a Chess game using object-oriented design in Java.  
It focuses on encapsulating domain rules and modeling a chessboard, pieces, and valid moves following classical OOP principles.

---

## 🧩 Overview

The Chess System models:

- Chess pieces with movement rules  
- A board representation  
- Game logic to validate moves  
- Domain objects that represent chess concepts (positions, pieces, colors, etc.)

This project was developed as a standalone application to practice and demonstrate:
- Object-Oriented Design
- Encapsulation of business rules
- Clear domain modeling in Java

---

## 🧠 Design Highlights

### 🔹 Domain Separation

The code is structured to separate **domain logic** from any presentation or UI layer:

- **Models:** Represent core concepts (Piece, Position, Color)
- **Rules:** Each piece encapsulates its specific movement logic
- **Game Logic:** Validates moves and enforces rules

This approach helps ensure:
- Testability
- Maintainable logic
- Separation of concerns

---

## 📦 Tech Stack

- Java (object-oriented design)
- Core Java libraries
- No external dependencies

---

## 🧪 Testing

There are no automated tests in the repository yet, but the structure encourages adding:

- Unit tests for move validation
- Integration tests for game flow

Future enhancements should include a test suite to ensure correctness of rules.

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/ceglauskis/chess-system-java.git
```

2.	Navigate to the project directory and compile:
```bash
javac -d out src/main/java/**/*.java
```

3.	Run the application:
```bash
java -cp out com.ceglauskis.chess.Main
```
(Paths may vary based on your local setup)

## Project Structure

- entities — Core chess entities (Board, Piece, Position)
- enums — Enumerations such as Color or PieceType
- logic / services — Movement rules and validation logic
- Main.java — Application entry point

This structure follows patterns commonly used in larger Java applications,
focusing on clarity and responsibility separation.


## Testing

Automated tests are not yet implemented, but the current structure allows for:

- Unit tests for individual piece movement rules
- Integration tests for full game flow

Adding tests with JUnit is a natural next step.

