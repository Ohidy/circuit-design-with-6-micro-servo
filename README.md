# circuit-design-with-6-micro-servo
a simple design with 6 micro servo using Tinkercad
I used tinkercad to do this circuit atfirst i did the circuit and i did not faced any hard times 
i did not undrestand why it did not move but after writing the code it went smoth 
#include <Servo.h>
Servo servo1;
Servo servo2;
Servo servo3;
Servo servo4;
Servo servo5;
Servo servo6;

void setup() {
  
  servo1.attach(0);
  servo2.attach(1);
  servo3.attach(2);
  servo4.attach(3);
  servo5.attach(4);
  servo6.attach(5);
}

void loop() {
 
  for (int pos = 0; pos <= 180; pos+= 1) {
    servo1.write(pos);
    servo2.write(pos);
    servo3.write(pos);
    servo4.write(pos);
    servo5.write(pos);
    servo6.write(pos);
    delay(15); 
  }
  for (int pos = 180; pos >= 0; pos-= 1) {
    servo1.write(pos);
    servo2.write(pos);
    servo3.write(pos);
    servo4.write(pos);
    servo5.write(pos);
    servo6.write(pos);
    delay(15); 
  }
}
![Screenshot 2024-07-09 150111](https://github.com/Ohidy/circuit-design-with-6-micro-servo/assets/173767059/ed690454-5aff-47da-b8b2-4f4b2e53e3e8)
![Screenshot 2024-07-09 150132](https://github.com/Ohidy/circuit-design-with-6-micro-servo/assets/173767059/0072c8c0-236a-4c1e-a0da-1939ad0beaeb)
my work link https://www.tinkercad.com/things/cASZiWOTLUM-neat-luulia-esboo/editel?returnTo=%2Fthings%2FcASZiWOTLUM-neat-luulia-esboo&sharecode=zlBeeFttpFvkeEELpsrVvfMclTlx8Uufq1soHG23kVY
