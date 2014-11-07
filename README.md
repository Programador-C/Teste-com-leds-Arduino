Teste-com-leds-Arduino
======================

int val = 0;
  int ledPin = 13;
  int potPin = 2;
  int ledPin2 = 12;
  int ledPin3 = 11;

void setup() {
  // put your setup code here, to run once


}

void loop() {
  // put your main code here, to run repeatedly: 
val = analogRead(potPin);
digitalWrite(ledPin2,HIGH);
delay(val*3);
digitalWrite(ledPin2,LOW);
delay(val/5);
digitalWrite(ledPin3,HIGH);
delay(val);
digitalWrite(ledPin3, LOW);
delay(val/5);
digitalWrite(ledPin, HIGH);
delay(val*2);
digitalWrite(ledPin,LOW);
delay(val/5);
}

  
  
