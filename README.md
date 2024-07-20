# Snake Water Gun Game

This is a simple Python implementation of the classic "Snake, Water, Gun" game where you play against the computer.

# How to Play
1. Run the script.
2. Enter your choice:
   - `s` for Snake
   - `w` for Water
   - `g` for Gun
3. The computer will randomly choose Snake, Water, or Gun.
4. The winner is determined based on the following rules:
   - Snake drinks Water
   - Water douses Gun
   - Gun kills Snake
5. The game will display the choices and the result.

# Code Explanation
- The computer randomly selects its choice using `random.choice([-1, 0, 1])`.
- The user inputs their choice which is then mapped to a corresponding value:
  - `s` maps to `1` (Snake)
  - `w` maps to `-1` (Water)
  - `g` maps to `0` (Gun)
- The game compares the user's choice and the computer's choice to determine the result.

# Example

Enter your choice: s
you chose Snake
computer chose Water
you win!


