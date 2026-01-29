<img width="701" height="394" alt="스크린샷 2026-01-29 123542" src="https://github.com/user-attachments/assets/0d5ecef7-0c4e-41d9-ac06-8a97e4bd64c6" />
void setup() {
// initialize digital pin LED_BUILTIN as an output.
pinMode(2, OUTPUT);
}
void loop() {
digitalWrite(2, HIGH); // turn the LED on (HIGH is the voltage level)
delay(1000); // wait for a second
digitalWrite(2, LOW); // turn the LED off by making the voltage LOW
delay(1000); // wait for a second
}
