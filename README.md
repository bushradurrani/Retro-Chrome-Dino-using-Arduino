#  Arduino Dino Jump Game (16x2 LCD Version)

A mini jump game inspired by the Chrome Dino, built using Arduino and a 16x2 LCD.  
Jump to avoid Obstacles, track your score, and see if you can beat your high score.

---

##  Gameplay

- Press the button to **jump**.
- If the dino hits a tree on the ground, **Game Over**.
- Your **high score** is displayed after each round.
- Buzzer plays a tone on jump for feedback.

---

##  Components Used

| Component           | Quantity |
|---------------------|----------|
| Arduino Uno         | 1        |
| 16x2 LCD Display     | 1        |
| Push Button         | 1        |
| Buzzer              | 1        |
| Jumper Wires        | Several  |
| Breadboard          | 1        |
| USB Cable / 5V Power| 1        |
we just connected it to a powerbank, to ensure mobility.
---

## 🔌 LCD Pin Mapping

```cpp
LiquidCrystal lcd(12, 11, 5, 4, 3, 2);
