# Arduino
This is my repository dedicated to exploring the world of Arduino, an open-source electronics platform. Follow me on my [notion blog](https://shining-eagle-964.notion.site/Arduino-Journey-1c17a8dc30324e64a26387dd64261844).  

### [1. Blinking an LED](https://github.com/Ryan-Perera/Arduino/blob/main/BlinkingAnLED.ino)

The basic Arduino example. Turns an LED on for one second, then off for one second, and so on... We use pin 13 because, depending on your Arduino board, it has either a built-in LED or a built-in resistor so you need only an LED.

#### Code
```C++
int ledPin = 13; // LED connected to digital pin 13

void setup() {
    pinMode(ledPin, OUTPUT); // sets the digital pin as output
}

void loop() {
    digitalWrite(ledPin, HIGH); // sets the LED on
    delay(1000); // waits for a second
    digitalWrite(ledPin, LOW); // sets the LED off
    delay(1000); // waits for a second
}
```

#### Schematic
![image](https://github.com/Ryan-Perera/Arduino/assets/104118917/c098ff53-ba29-40ce-838d-ffd7dac1b747)
