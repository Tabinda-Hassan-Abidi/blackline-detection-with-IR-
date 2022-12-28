# blackline-detection-with-IR-
void setup() { 
// put your setup code here, to run once:
pinMode(13,INPUT); 
Serial.begin(9600); 
} 
void loop() { 
// put your main code here, to run repeatedly: 
int value=digitalRead(13); 
if(value == HIGH){ 
Serial.println("black line."); 
} 
else if(value == LOW){ 
Serial.println("White or No Black line."); 
} 
}
