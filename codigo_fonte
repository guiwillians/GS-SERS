#define PIR_PIN 14
#define LED_PIN 12

void setup() {
  Serial.begin(115200);
  pinMode(PIR_PIN, INPUT);
  pinMode(LED_PIN, OUTPUT);
}

void loop() {
  int movimento = digitalRead(PIR_PIN);

  if (movimento == HIGH) {
    digitalWrite(LED_PIN, HIGH);
    Serial.println("Movimento detectado!");
  } else {
    digitalWrite(LED_PIN, LOW);
  }

  delay(50);
}
