# Smart-Doorlock
🔐 Smart Password Door Lock using Arduino
This project implements a smart electronic door lock system using Arduino and a 4x4 keypad for password entry. It enhances home or office security by requiring a correct numeric password to unlock the door, with options for adding an LCD display, buzzer alerts, and a servo motor or relay for controlling the lock.

🚪 Features
Unlocks the door only when the correct password is entered

Password can be easily changed in code

Optional LCD display shows lock status

Buzzer alerts for wrong attempts

Uses a servo motor or relay to control physical locking mechanism

Ideal for lockers, cabinets, or home doors

🧰 Components Used
Arduino Uno or Nano

4x4 Matrix Keypad (or 4x3)

Servo motor (SG90) or Relay module (for electronic strike lock)

16x2 LCD display (optional)

Buzzer (optional for feedback)

Breadboard, jumper wires

Power supply (USB or 9V battery)

🔐 How It Works
User Input: The user enters a 4-digit password via the keypad.

Password Verification: Arduino compares input with the stored password.

Lock Control:

If correct → Unlocks the door for a short duration

If incorrect → Buzzer sounds and lock remains engaged

Display Feedback: (Optional) LCD shows messages like "Enter Password", "Access Granted", or "Wrong Password".
