# Digital Clock Application

This is a simple digital clock application built using PyQt5 and with the help of Bro Code and tutorials from his YouTube channel (https://www.youtube.com/@BroCodez).
The application displays the current time in a visually appealing digital style. It uses a custom font and updates every second.


Features:
1. Live Digital Clock:
  The application displays the current time in the format hh:mm:ss AP (with AM/PM notation).
2. Custom Font:
  The digital clock uses a stylish custom font (DS-DIGIT.TTF) for a classic digital clock appearance.
3. Themed Design:
  Background: Black.
  Font Color: Green (similar to retro digital clocks).
4. Real-Time Updates:
  Time updates every second using QTimer.


Prerequisites:
To run this application, ensure the following:

1. Python 3.6 or later.
2. PyQt5 library installed. Install it with: pip install pyqt5
3. Custom Font File:
Place the DS-DIGIT.TTF font file in the same directory as the script. You can download a similar digital font here: https://www.dafont.com/ds-digital.font .


How to Run:
1. Clone or download the repository.
2. Place the DS-DIGIT.TTF file in the same folder as the script.
3. Run the script using: python Project_01_Digital_clock.py


File Structure:
1. main.py: The Python script for the digital clock.
2. DS-DIGIT.TTF: The custom digital clock font.


Dependencies:
PyQt5: Python bindings for the Qt application framework.


Output:
When the application runs, you'll see a black window displaying the current time in a digital clock style. The time will update every second.


Customization:
You can modify the font color, size, or background by updating the setStyleSheet calls in the initUI method.
Adjust the window size or position by modifying the setGeometry parameters.



