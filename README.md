# Clock
ArduinoAlarmCLock


 
An Arduino Mega 2560-based alarm clock that uses an LCD, DS3231 RTC module, buzzer, and LEDs to display time and trigger an alarm.  

Features  
- Displays real-time clock on an LCD 1602A
- Uses DS3231 RTC for accurate timekeeping  
- Buzzer and LEDs activate at the set alarm time  
- Alarm can be turned off with a button  

Components  
- Arduino Mega 2560
- LCD 1602A module
- DS3231 RTC module
- Passive buzzer
- Two LEDs (Red & Yellow)
- Button**  
- 10k potentiometer**  
- 220Ω resistors**  
- Jumper wires & breadboard**  

Wiring Instructions  
1. Connect the LCD to the Arduino using the correct pins  
2. Wire the RTC module (SDA → Pin 20, SCL → Pin 21)  
3. Connect the buzzer to Pin 10
4. Wire the LEDs to Pins 8 & 9 with resistors  
5. Connect the button to Pin 7 & GND
