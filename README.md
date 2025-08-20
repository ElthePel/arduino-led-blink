# Arduino Multi-LED Blinking Project

This project demonstrates a simple Arduino Uno R3 application where four LEDs (Red, Yellow, Green, and Blue) blink simultaneously at 1-second intervals. It is designed as a beginner-friendly project for learning the basics of Arduino programming and circuit design.  

## 🔧 Components Used
- 1 × Arduino Uno R3  
- 1 × Red LED  
- 1 × Yellow LED  
- 1 × Green LED  
- 1 × Blue LED  
- 4 × 330Ω Resistors  
- Breadboard  
- Jumper wires  

## ⚡ Circuit Description
Each LED is connected to a digital output pin (2, 3, 4, 5) of the Arduino Uno through a 330Ω resistor to limit the current. All LEDs are switched ON and OFF simultaneously with a 1-second delay.  

## 📜 Code
```cpp
void setup() {
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
}

void loop() {
  digitalWrite(2, HIGH);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(5, HIGH);
  delay(1000); 

  digitalWrite(2, LOW);
  digitalWrite(3, LOW);
  digitalWrite(4, LOW);
  digitalWrite(5, LOW);
  delay(1000); 
}




![Screenshot_20250820_194345_Photos](https://github.com/user-attachments/assets/aa93356c-e7b3-4e7e-abe1-1229eb4dc9ac)
