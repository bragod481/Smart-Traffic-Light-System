int pin1 = 13;
int pin2 = 9;
int pin3 = 6;
int button = 4;
int delayTime = 100;

void setup() {
  pinMode(pin1, OUTPUT);
  pinMode(pin2, OUTPUT);
  pinMode(pin3, OUTPUT);
  pinMode(button, INPUT_PULLUP);
}

void loop() {
  for (int i = 0; i < 10; i++) {
    if (digitalRead(button) == LOW) {
      pedestrianCrossing();
      return;
    }
    digitalWrite(pin1, HIGH);
    digitalWrite(pin2, LOW);
    digitalWrite(pin3, LOW);
    delay(delayTime);
  }

  for (int i = 0; i < 10; i++) {
    if (digitalRead(button) == LOW) {
      pedestrianCrossing();
      return;
    }
    digitalWrite(pin1, LOW);
    digitalWrite(pin2, HIGH);
    digitalWrite(pin3, LOW);
    delay(delayTime);
  }

  for (int i = 0; i < 10; i++) {
    if (digitalRead(button) == LOW) {
      pedestrianCrossing();
      return;
    }
    digitalWrite(pin1, LOW);
    digitalWrite(pin2, LOW);
    digitalWrite(pin3, HIGH);
    delay(delayTime);
  }
}

void pedestrianCrossing() {
  digitalWrite(pin1, LOW);
  digitalWrite(pin2, LOW);
  digitalWrite(pin3, HIGH);
  delay(1000);
}
