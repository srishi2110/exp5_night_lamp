void setup()
{
pinMode(13,OUTPUT);
Serial.begin(9600);


}
void loop()
{
int d=analogRead(A0);
Serial.println(d);
delay(2000);
if(d>600)
{
digitalWrite(13,HIGH);
}
else
{
digitalWrite(13,LOW);
}



}
