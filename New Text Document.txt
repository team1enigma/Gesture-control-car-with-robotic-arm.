int A=10,B=9,C=8,D=7;

void setup() {
  Serial.begin(9600);  
  pinMode(A,OUTPUT);
  pinMode(B,OUTPUT);
  pinMode(C,OUTPUT);
  pinMode(D,OUTPUT);
}
void P()
          {
      digitalWrite(A,HIGH);
      digitalWrite(B,LOW);
      digitalWrite(C,HIGH);
      digitalWrite(D,LOW);
          }
void Q()
        {
      digitalWrite(A,LOW);
      digitalWrite(B,HIGH);
      digitalWrite(C,LOW);
      digitalWrite(D,HIGH);
          }
void R()
        {
      digitalWrite(A,LOW);
      digitalWrite(B,HIGH);
      digitalWrite(C,HIGH);
      digitalWrite(D,LOW);
          }
void S(){
      digitalWrite(A,HIGH);
      digitalWrite(B,LOW);
      digitalWrite(C,LOW);
      digitalWrite(D,HIGH);
          }
void T(){
      digitalWrite(A,LOW);
      digitalWrite(B,LOW);
      digitalWrite(C,LOW);
      digitalWrite(D,LOW);
          }
          


