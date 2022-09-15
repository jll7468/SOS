# SOS
const pin_t MY_LED = D7;
SYSTEM_THREAD(ENABLED);
void setup() {
    pinMode(MY_LED, OUTPUT);
}
void loop() {
    digitalWrite(MY_LED, HIGH);
    delay(1s);
    digitalWrite(MY_LED, LOW);
    delay(1s);}
