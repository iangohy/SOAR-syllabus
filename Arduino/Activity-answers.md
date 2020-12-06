# Activity Answers

## Activity 1: Make a LED Blink

```c++
void setup() {
	pinMode(8, OUTPUT);   // sets digital pin 8 as output
}

void loop() {
	digitalWrite(8, HIGH);   // sets digital pin on
    delay(1000);             // waits for a second
    digitalWrite(8, LOW);    // sets digital pin off
    delay(1000);             // waits for a second
}
```

