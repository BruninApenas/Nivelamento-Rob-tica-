# Nivelamento-Robótica

int vermelho = 2;
int verde = 3;
int amarelo = 4;
void setup() {
  pinMode(vermelho, OUTPUT);
  pinMode(verde, OUTPUT);
  pinMode(amarelo, OUTPUT);
  // put your setup code here, to run once:

}

void loop() {
  digitalWrite(vermelho, HIGH);
  digitalWrite(verde, LOW);
  digitalWrite(amarelo, LOW);
  delay(1000);

  digitalWrite(vermelho,LOW);
  digitalWrite(verde, HIGH);
  digitalWrite(amarelo, LOW);
  delay(1000);

  digitalWrite(vermelho,LOW);
  digitalWrite(verde, LOW );
  digitalWrite(amarelo, HIGH);
  delay(1000);
