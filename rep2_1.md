# Report 2-1
## 안동대학교 컴퓨터공학과 20171132 정인길
```
void setup() {

  size(800, 350);

  textSize(60);
}

int i, dir=1, sp=1;

void draw() {

  fill(255,0,0);

  background(255, 255, 0);

  text("Graphic", i, 200);

  if (i>width) dir=-1;

  if (i<0) dir=1;

  i = i+dir*sp;
}
void keyPressed(){

sp = key-'0'; 
}
```

### 리포트소감
* 재밌고 신기한 프로세싱 열심히 배우겠습니다.
[markdown](https://github.com/ingil8386/processing/blob/master/rep2_1.md)
