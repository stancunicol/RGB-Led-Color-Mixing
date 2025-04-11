![image](https://github.com/user-attachments/assets/86c75cc4-8e36-4614-9bc8-4d0ca76489d2)


# 🎨 Arduino RGB LED Controller with Potentiometers
This project demonstrates how to use three potentiometers to control the color of an RGB LED using PWM signals from an Arduino UNO. Each potentiometer adjusts the intensity of one color channel: red, green, or blue.

# 🧰 Required Components
1 x Arduino UNO

1 x Breadboard

3 x 10kΩ Potentiometers

3 x 220Ω Resistors

1 x RGB LED (common cathode)

Jumper wires

USB cable for uploading the sketch

# 🔌 Circuit Description
Red pin of the RGB LED → Arduino pin 11 through a 220Ω resistor

Green pin → Arduino pin 10 through a 220Ω resistor

Blue pin → Arduino pin 9 through a 220Ω resistor

The cathode (GND) of the RGB LED is connected to GND on the breadboard

Potentiometer 1 (A0): Controls red intensity

Potentiometer 2 (A1): Controls green intensity

Potentiometer 3 (A2): Controls blue intensity

Each potentiometer has:

Middle pin → Analog input (A0, A1, A2)

One side → 5V

Other side → GND
