const int led1 = 5;
const int led2= 4;
const int led3= 3;
void setup(){

  pinMode(5,OUTPUT);
  pinMode(4,OUTPUT);
  pinMode(3,OUTPUT);
}
void loop(){
digitalWrite(led1,HIGH);
delay(2000);
digitalWrite(led1,LOW);
delay(2000);
digitalWrite(led2,HIGH);
delay(1000);
digitalWrite(led2,LOW);
delay(1000);
digitalWrite(led3,HIGH);
delay(3000);
digitalWrite(led3,LOW);
delay(3000);

}
