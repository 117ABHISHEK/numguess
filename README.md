
# 🎯 Number Guessing Game (C++)

A simple and interactive **Number Guessing Game** created using C++. The game challenges players to guess a randomly generated number within a limited number of attempts, based on the chosen difficulty level.

---

## 🧩 Features

- 🟢 **Difficulty Levels**:
  - Easy: 0–10 (3 chances)
  - Mid: 0–50 (10 chances)
  - Hard: 0–100 (20 chances)
- 🧠 Number generated randomly using current time as seed
- 🎮 User inputs name and plays until they win or run out of chances
- 🛡️ Input validation and feedback for out-of-bound guesses
- ❌ Game ends with win/loss and displays the correct number if lost

---

## ⚙️ Technologies Used

- C++ Standard Library (`iostream`, `ctime`)
- Windows-specific header: `windows.h`
- Terminal-based interface with `system("CLS")`

---

## 🚀 How to Run

### Requirements
- Windows OS
- C++ compiler (like `g++` from MinGW)

### Compile and Run

```bash
g++ -o guessing_game guessing_game.cpp
./guessing_game
```

---

## 🧠 Game Instructions

1. Enter your name.
2. Select difficulty:
   - Easy: 0–10
   - Mid: 0–50
   - Hard: 0–100
3. Try to guess the randomly generated number.
4. You get limited chances depending on the level.
5. Feedback is provided: whether your guess is too high or too low.
6. Win if you guess correctly. Otherwise, the game will show the correct number and end.

---

## 📸 Sample Output

```
====================  Welcome Number Guess Game ====================
Enter Your Name :- Chief

Enter the Level
1. Easy (0 to 10)
2. Mid (0 to 50)
3. Hard (0 to 100) :- 2

====== Now You Have only 10 chances to guess =====
Enter the number : 45
Good but Not perfect guess... Your guess Number is big..
--------------------------------------------------------
```

---

## ⚠️ Notes

- Uses `system("CLS")` to clear the terminal screen (Windows only).
- Make sure to input a number within the selected level range.
- Wrong inputs still count as attempts.

---

## 🔧 Enhancements Ideas

- Cross-platform compatibility (remove `windows.h`)
- Add scoring or timer-based challenge
- GUI using a graphics library like SFML or Qt
- Multiplayer mode

---

## 👨‍💻 Author

- **Abhishek**

---
