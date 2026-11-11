# Smile_ohms_law_calculator# Ohm's Law and Power Calculator

## What it does
This Python program calculates voltage, current, resistance or power using Ohm's Law. The user picks what to find, enters the known values and gets the answer with units. The program repeats until the user chooses to quit, and it handles wrong input (such as letters or division by zero) without crashing.

## How to run it
Install Python 3, then run:

python ohms_law.py

## Sample output
(Replace this with a real run of YOUR program. Copy the text from your screen.)

```
1. Voltage (V)
2. Current (I)
3. Resistance (R)
4. Power (P)
5. Show history
6. Quit
What do you want to find? 1
Current in amps: 2
Resistance in ohms: 12
Voltage = 24.0 V

What do you want to find? 6

--- Session history ---
1. V = 24.0 V  (I = 2.0 A, R = 12.0 ohms)
Goodbye!
```

## My own twist
**Session history.** Every calculation is saved in a list while the program runs. The user can choose "Show history" at any time to review all results, and a full summary is printed automatically when they quit.

## What I learned
(Write 1 or 2 sentences in your own words. For example: what went wrong while testing, and how you fixed it.)

## Author
Prince smile, ND1 Mechatronics Engineering, YabaTech.
