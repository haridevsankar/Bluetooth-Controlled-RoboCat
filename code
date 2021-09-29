# Bluetooth-Controlled-RoboCat
Walking Code
//right back 1
2 // left frond 3
3 #include <Wire.h>
4 #include <Adafruit_PWMServoDriver.h>
5 Adafruit_PWMServoDriver pwm = Adafruit_PWMServoDriver();
6
7 #define SERVOMIN 125
8 #define SERVOMAX 575
9
10 // our servo # counter
11 uint8_t servonum = 0;
12 int p=40;
13 int q;
14 int r;
15 int s;
16 void setup() {
17 Serial.begin(9600);
18 Serial.println("16 channel Servo test!");
19
20 pwm.begin();
21
22 pwm.setPWMFreq(60);
23
24 //yield();
25 }
26
27
28 void loop() {
29
30
31
32
33 //left 1
34
35 pwm.setPWM(1, 0, angleToPulse(60 ) );
36
37 pwm.setPWM(2, 0, angleToPulse(40) );
38 pwm.setPWM(3, 0, angleToPulse(130 ) );
39
40 pwm.setPWM(4, 0, angleToPulse(90) );
41
42
43 ////another 2 paires
44 pwm.setPWM(7, 0, angleToPulse(50) );
45 delay(40);
46 pwm.setPWM(6, 0, angleToPulse(120) );
47 pwm.setPWM(7, 0, angleToPulse(140) );
48 delay(40);//b100
49 pwm.setPWM(9, 0, angleToPulse(90) );//b100
50 delay(40);
51 pwm.setPWM(8, 0, angleToPulse(50 ) );//b150
52 delay(500);
53
54
55
56
57
58 pwm.setPWM(2, 0, angleToPulse(90) );//b100
59 delay(40);
