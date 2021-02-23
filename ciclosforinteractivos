//CICLOS FOR ANIDADOS INTERACTIVOS

float ancho;
float alto;
void setup() {
  size(400, 400);
  ancho = width/10;
  alto = height/10;
}
void draw() {
  for (int i = 0; i < 10; i++) {
    fill(mouseX*i);
    for (int y = 0; y < 10; y++) {
      rect(i*ancho, alto*y, ancho, alto);
    }
    rect(i*ancho, alto, ancho, alto);
  }
}
