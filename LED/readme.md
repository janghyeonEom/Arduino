# LED 연습

## LED 깜박이기
![](./images/led00.png)

```c
// C++ code
#define LED 8


void setup()
{
  pinMode(LED, OUTPUT);
  
}

void loop()
{
  digitalWrite(LED, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED, LOW);
  delay(1000); // Wait for 1000 millisecond(s)

}
```
## LED 경찰봉 구현하기
![](./images/led01.png)
