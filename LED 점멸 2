#define PIN_LED 7
unsigned int count, toggle;

void setup() {
  pinMode(PIN_LED, OUTPUT);
  count = toggle = 0;
  digitalWrite(PIN_LED, toggle); // turn off LED.
}

void loop() {
  toggle = toggle_state(toggle); // toggle LED value.
  toggle == 1 ;
  delay(1000);
  digitalWrite(PIN_LED, toggle); // turn off LED status.

  while (count < 12) {
    toggle = toggle_state(toggle); // toggle LED value.
    digitalWrite(PIN_LED, toggle); // turn off LED status.
    count ++ ;
    delay(200);
  }
  
  while(1){}
}

int toggle_state(int toggle) {
  if (toggle == 0){
    toggle = 1 ;}
    
  else if (toggle == 1){
    toggle = 0 ;
  }
  return toggle;
}
