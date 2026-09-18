# EXP — INTERFACING A 16×2 LCD WITH ARDUINO UNO R4 WIFI USING AN I2C MODULE FOR SENSOR DATA DISPLAY

## Aim

To interface a 16×2 LCD with Arduino UNO R4 WiFi using an I2C module and display data on the LCD.

# Hardware / Software Tools Required

* Arduino UNO R4 WiFi
* 16×2 LCD Display
* I2C LCD Module
* USB Cable
* Jumper Wires
* Breadboard
* Arduino IDE
* Wokwi Online Simulator

# Circuit Diagram

<img width="1536" height="1024" alt="ChatGPT Image Sep 8, 2026, 02_46_17 PM" src="https://github.com/user-attachments/assets/b46ab1c7-beaa-4044-a6a6-de27bae174ee" />


# Circuit Connections

| I2C LCD Pin | Arduino UNO R4 WiFi |
|-------------|----------------------|
| VCC | 5V |
| GND | GND |
| SDA | SDA |
| SCL | SCL |

# Working Principle

The 16×2 LCD is interfaced with the Arduino UNO R4 WiFi using an I2C module. The I2C interface reduces the number of connections required between the Arduino and LCD.

The system operates as follows:

```
Arduino UNO R4 WiFi
        ↓
   I2C Interface
        ↓
     16×2 LCD
        ↓
   Display Data
```
# Procedure

Step 1: Create the Wokwi Project
Open the Wokwi online simulator.
Create a new project using Arduino UNO R4 WiFi.
Add a 16×2 LCD with an I2C interface.
Connect the LCD to the Arduino UNO R4 WiFi.
Verify the circuit connections.

Step 2: Connect the I2C LCD
Connect the VCC pin of the I2C module to 5V.
Connect the GND pin to GND.
Connect the SDA pin to the Arduino SDA pin.
Connect the SCL pin to the Arduino SCL pin.

Step 3: Configure the Program
Open the Arduino IDE or Wokwi code editor.
Include the Wire.h library.
Include the LiquidCrystal_I2C.h library.
Create the LCD object using the I2C address 0x27.
Initialize the LCD.
Turn ON the LCD backlight.
Display the required message on the LCD.

Step 4: Run the Program
Start the Wokwi simulation.
The Arduino UNO R4 WiFi initializes the LCD.
The LCD backlight turns ON.
The message "Hello" is displayed on the LCD.
Observe the displayed message.

# Program 

```
#include <Wire.h>
#include <LiquidCrystal_I2C.h>

LiquidCrystal_I2C lcd(0x27, 16, 2);

void setup()
{
  lcd.init();
  lcd.backlight();

  lcd.setCursor(3, 0);
  lcd.print("GAME OVER");

  lcd.setCursor(2, 1);
  lcd.print("Score: 25");
}

void loop()
{
}
```

# Output 
<img width="900" height="1600" alt="WhatsApp Image 2026-09-08 at 2 41 19 PM" src="https://github.com/user-attachments/assets/3dcca46e-df9e-4285-bd43-bc2a605a4159" />


# Result

The 16×2 LCD was successfully interfaced with the Arduino UNO R4 WiFi using an I2C module. 
The LCD was initialized, its backlight was activated, and the message "Hello" was successfully displayed,
demonstrating I2C-based LCD interfacing with the Arduino UNO R4 WiFi.
