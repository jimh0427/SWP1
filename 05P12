int led = 7;         // the PWM pin the LED is attached to
int brightness = 0;  // how bright the LED is
int fadeAmount = 5;  // how many points to fade the LED by

// the setup routine runs once when you press reset:
void setup() {
  // declare pin 9 to be an output:
  pinMode(7, OUTPUT);
  
}

// the loop routine runs over and over again forever:
void loop() {
  int x=0;
  // set the brightness of pin 9:
  digitalWrite(7,HIGH);
  delay(1000);
  digitalWrite(7,LOW);
  while(1){
    digitalWrite(7,HIGH);
    delay(200);
    digitalWrite(7,LOW);
    delay(200);
    x=x+1;
    if (x==6){
      break;
    }

  
  }
  exit(0);

}
