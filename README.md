# Kerala IOT Challenge

> Foxlab Makerspace in association with GTech - Group of Technology Companies in Kerala is launching our prestigious program “Kerala IoT Challenge 2021”, with a vision to mould 100 IoT experts in Kerala, hosting on the µLearn platform. Kerala IoT Challenge is a program designed in 4 levels followed by a hackathon to identify and train quality industry leaders in the IoT domain, while any novice learner can start with layer 1 and others can enter laterally to the desired layer after an evaluation.
# About Me

>Hi , Iam Alan Martin,3rd year Computer Science and Engineering Student, Toc H Institute of Science and Technology,My major area of interests are IOT,Android App Development,Cyber Security and Programming 

## Experiment 1 : Hello World LED Blinking

> A basic program similar to printing "*Hello World*" in any programming language. The aim is to blink an LED using **Arduino Uno Board**.

## Components Required  
* Arduino Uno Board 
* USB Cable 
* LED (Any Color) x 1 Nos
* 220 OHM Resistor X 1 Nos
* Breadboard 
* Jumper Wires (Male to Male ) X 2 Nos

## Circuit Diagram

![Expriment 1](https://github.com/Alanmartin7007/Kerala-IOT-Challenge/blob/main/1.png)


## Code

int ledPin = 10; // define digital pin 10.

void setup()

{
pinMode(ledPin, OUTPUT);// define pin with LED connected as output.

}

void loop()
{

digitalWrite(ledPin, HIGH); // set the LED on.

delay(1000); // wait for a second.

digitalWrite(ledPin, LOW); // set the LED off.

delay(1000); // wait for a second

}



## Output
[[![video1](https://img.youtube.com/vi/LYO3MBzF8Gk/0.jpg)](https://youtube.com/shorts/LYO3MBzF8Gk)


## Experiment 2 - Traffic Light
### Components
* Arduino Uno
* Breadboard
* LED RED BLUE GREEN
* Jumper wire
* Restsor 220 ohm

### Circuit
![Expriment 2](https://github.com/Alanmartin7007/Kerala-IOT-Challenge/blob/main/2.png)


### Code

int redled =10; // initialize digital pin 8.

int yellowled =7; // initialize digital pin 7.

int greenled =4; // initialize digital pin 4.

void setup()

{

pinMode(redled, OUTPUT);// set the pin with red LED as “output”

pinMode(yellowled, OUTPUT); // set the pin with yellow LED as “output”

pinMode(greenled, OUTPUT); // set the pin with green LED as “output”

}

void loop()

{

digitalWrite(greenled, HIGH);//// turn on green LED

delay(5000);// wait 5 seconds



digitalWrite(greenled, LOW); // turn off green LED

for(int i=0;i<3;i++)// blinks for 3 times

{

delay(500);// wait 0.5 second

digitalWrite(yellowled, HIGH);// turn on yellow LED

delay(500);// wait 0.5 second

digitalWrite(yellowled, LOW);// turn off yellow LED

} 

delay(500);// wait 0.5 second

digitalWrite(redled, HIGH);// turn on red LED

delay(5000);// wait 5 seconds

digitalWrite(redled, LOW);// turn off red LED

}


###output

[[![video1](https://img.youtube.com/vi/xx9oFRN1428/0.jpg)](https://youtube.com/shorts/xx9oFRN1428)



