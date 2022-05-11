# Mulearn IOT Level 1

<!---
-->
----
## Experiment 1:
### **Hello world LED Blinking**
Components:
<!--ul -->
* Arduino Uno Board
* USB Cable
* LED (Any Color) x 1 Nos
* 220 OHM Resistor X 1 Nos
* Breadboard
* Jumper Wires (Male to Male ) X 2 Nos

#### Code:
<!---->
int ledPin = 10;<!---->
void setup()<!---->
{
pinMode(ledPin, OUTPUT);

}<!---->
void loop()<!---->
{
digitalWrite(ledPin, HIGH);<!---->
delay(1000); <!---->
digitalWrite(ledPin, LOW);<!---->
delay(1000);<!---->
}



<!---->

Remarks 
<!---->
The code has been verified and uploaded to the arduino uno board
<!---->
----
