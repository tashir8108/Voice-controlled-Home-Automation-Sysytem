#define bulb1 2
#define bulb2 3

void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  pinMode(bulb1, OUTPUT);
  pinMode(bulb2, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  if(Serial.available() == 1)
  {
    String val = Serial.readString();
    Serial.println(val);
    if(val == "bulb1 on")
    {
      digitalWrite(bulb1, HIGH);
    }
    if(val == "bulb1 off")
    {
      digitalWrite(bulb1, LOW);
    }
    if(val == "bulb2 on")
    {
      digitalWrite(bulb2, HIGH);
    }
    if(val == "bulb1 off")
    {
      digitalWrite(bulb1, LOW);
    }
    if(val == "all on")
    {
      digitalWrite(bulb1, HIGH);
      digitalWrite(bulb2, HIGH);
    }
    if(val == "all off")
    {
      digitalWrite(bulb2, LOW);
      digitalWrite(bulb1, LOW);
    }
  }
}
