void setup() {
  size(800, 300);
  textSize(70);
}
int i, dir=1, sp=1;
void draw() {
  fill(255,255,0);
  background(255,0,0);
  text("Graphics", i, 200);
  if (i>width) dir=-1;
  if (i<0) dir=1;
  i=i+dir*sp;
}
void keyPressed() {
  sp = key-'0';
}
