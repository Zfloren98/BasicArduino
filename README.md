# BasicArduino
I'm going to learn how to use an Arduino, and make awesome things with it!


## TableofContents
* [TableOfContents](#TableOfContents)
* [HelloArduino](#HelloArduino)
* [FiniteLEDBlink](#FiniteLEDBlink)

## HelloArduino

### Description & Code

```C++

```

### Evidence
[Here is my code on Arduino Create](https://create.arduino.cc/editor/helmstk1/9a3831dd-4b86-42f2-be49-c28b84874092/preview)

### Image or Wiring
<img src="http://troybaverstock.com/wp-content/uploads/2019/04/arduino-servo-button-red-green-RGB-LED-wiring-diagram.png" width="300px" /> 
<img src="https://github.com/Helmstk1/BasicArduino/blob/main/images/LED%20Blink.PNG?raw=true" width="300px" /> 

Image credit belongs to [Troy Baverstock](https://troybaverstock.com/learn/fritzing-circuit-diagrams/)

### Reflection
I learned how to use the term counter to make it stop at 5.

## FiniteLEDBlink

### Description & Code

```C++
#define LED 3
int delayVar = 1000;
int counter = 0;
void setup() {
  Serial.begin(9600);
  pinMode(LED, OUTPUT);
}

void loop() {

  if (counter < 5) {
    digitalWrite(LED, HIGH);
    delay(delayVar);
    digitalWrite(LED, LOW);
    delay(delayVar);
    counter++ ;
  
  }
  Serial.println(counter);
}
```

### Evidence

### Image or Wiring

### Reflection
