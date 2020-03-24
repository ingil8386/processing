# Report 2-2
## 20171132 컴퓨터공학과 정인길

```
PFont f;
void setup() {
  size(800, 800);
  textSize(40);
  f = createFont("궁서",40);
  textFont(f);
}
int i, dir=1, sp=1;
void draw() {
  fill(255,0,0);
  background(255, 255, 0);
  text("안동대 컴공 사랑합니다" ,200,i);
  if (i>height) i=0;
  i = i+dir*sp;
}
void keyPressed(){

sp = key-'0'; 
}
```

###소감문
* 점점 재밌어지는 컴퓨터그래픽스수업 다음수업이 기대됩니다.
