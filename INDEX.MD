[FIRSTDAY](https://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-09%2012-08-54.png)
[SECONDAY](https://github.com/jebinjosep/bad/blob/main/bad)
[THIRDDAY](https://www.tinkercad.com/things/2sYzoTlYzfy-led-blink/editel)

# 10 DAY INTERNSHIP FOR GOVT POLYTECHNIC, KUNNAMKULAM FROM 08-05-2023 to 08-05-2023 TO 20-05-2023
 
 
## DAY 1(09-05-2023)
# TINKER CADEhttps://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-15%2014-30-21.png
- CREATED ACCOUNT
- LED GLOWED USING BATTERY SIMULATION MADE
![alt bad](https://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-09%2012-08-54.png)
# DAY 2
- AND GATE VERIFICATION SIMULATION
![alt hii](https://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-11%2010-47-47.png)
> ARDUINO INTERFACTINGhttps://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-15%2014-30-21.png
- LED BLINKING USING ARDUINO USING CODE AND SIMULATION MADE
![alt smm](https://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-11%2013-58-43.png)
![alt hii](https://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-11%2013-58-53.png)
![alt yy](https://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-11%2013-56-15.png)
# DAY 3
> introduction to AL & ML
- Introduced a programming platform named as blocky
![blocky](https://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-12%2010-34-11.png)
- The platform like Blockly are mostly used by fresher's in programming
- It's like a game
- The blockly helps to know about the programming easly
- To create a multifunction program like a calculator 
![alt gg](https://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-12%2012-21-17.png)
- AI & ML
> STM 32 NUCLEO DEVELOPMENT BOARD ![IMAGE]
# DAY 4
![alt hh](https://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-15%2014-30-21.png)
 # DAY 5
 - copy of arduino 7 segment display
 
 ![alt gg](https://github.com/jebinjosep/bad/blob/main/Screenshot%20from%202023-05-16%2009-15-07.png)
 
unsigned const int A = 13;
unsigned const int B = 12;
unsigned const int C = 11;
unsigned const int D = 10;
unsigned const int E = 9;
unsigned const int F = 8;
unsigned const int G = 7;
unsigned const int H = 6;


void setup(void)
{
  pinMode(A, OUTPUT);
  pinMode(B, OUTPUT);
  pinMode(C, OUTPUT);
  pinMode(D, OUTPUT);
  pinMode(E, OUTPUT);
  pinMode(F, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(H, OUTPUT);
}

//My Functions

void zero(void) {
  digitalWrite(A, LOW);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void one(void) {
  digitalWrite(A, LOW);
  digitalWrite(B, LOW);
  digitalWrite(C, LOW);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, LOW);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void two(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, LOW);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, LOW);
  digitalWrite(H, LOW);
}

void three(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, LOW);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void four(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, LOW);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, LOW);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void five(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, LOW);
  digitalWrite(E, LOW);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void six(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, LOW);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void seven(void) {
  digitalWrite(A, LOW);
  digitalWrite(B, LOW);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, LOW);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void eight(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, HIGH);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

void nine(void) {
  digitalWrite(A, HIGH);
  digitalWrite(B, HIGH);
  digitalWrite(C, HIGH);
  digitalWrite(D, HIGH);
  digitalWrite(E, LOW);
  digitalWrite(F, HIGH);
  digitalWrite(G, HIGH);
  digitalWrite(H, LOW);
}

// Start
void loop(void)
{
  zero();
  delay(1000);
  
  one();
  delay(1000);
  
  two();
  delay(1000);
  
  three();
  delay(1000);
  
  four();
  delay(1000);
  
  five();
  delay(1000);
  
  six();
  delay(1000);
  
  seven();
  delay(1000);
  
  eight();
  delay(1000);
  
  nine();
  delay(1000);
}
