# VANT-151-Project
This program is a UI system to motivate the electronic clothes drier that we built in class VANT 151, UBC. The program should be downloaded to Arduino. 

To connect wires:
  LCD J1-1 to Arduino TX 1, 
  LCD J1-3 to Arduino 5V, 
  LCD J2-5 to Arduino GND, 
  Arduino Pin 2 to right button, 
  Arduino Pin 3 to ok button, 
  Arduino Pin 4 to up button, 
  Arduino Pin 5 to down button, 
  Arduino Pin 6 to left button, 
  Arduino Pin 7 to limit switch 1, 
  Arduino Pin 10 to limit switch 2, 
  Arduino Pin 11 to a LED, 
  Arduino Pin 12 to DHT 11 sensor. 

/*The LED is used to represent the functioning of motor, fan, and heater, which I could not access yet. */
/*The "switch" limit switch is a emergency stop button. Whenever pressed, the program should immediately stop and then go back to main menu. */
/*The "door" limit switch is a sensor to detect whether the door is closed. In real model, the value of the boolean variable "door" should be 1 when door is closed (or when switch is pressed), right opposite from this program. */
