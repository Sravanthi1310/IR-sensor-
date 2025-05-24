#define ir sensor=2;
#define buzzer=3;
#define relay=4;
#define led=5;

voidsetup(){
pinMode{2,input};
pinMode{3,OUTPUT};
pinMode{4,OUTPUT};
pinMode{5,OUTPUT};
}

void loop(){
if(digitalWrite(2)==HIGH)
digitalWrite(3,HIGH);
delay(4000)
digitalWrite(4,HIGH);
digitalWrite(5,HIGH);
}
