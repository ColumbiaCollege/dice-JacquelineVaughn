//Dice Program
//Variables
PShape s;
PShape k;
PShape r;
PImage ov;
String[] x={"1","2","3","4","5","6"};
String[] m={"1","2","3","4","5","6"};
String[] e={"1","2","3","4","5","6"};
void setup(){
  size(900,600);
  background(#CC99FF);
  //3D Aspect of Dice 1
  strokeWeight(3);
  s=createShape();
  s.beginShape();
  s.fill(#ffffff);
  s.vertex(250,200);
  s.vertex(215,175);
  s.vertex(25,175);
  s.vertex(25,375);
  s.vertex(50,400);
  s.endShape(CLOSE);
  //3D Aspect of Dice 2
  k=createShape();
  k.beginShape();
  k.fill(#ffffff);
  k.vertex(550,200);
  k.vertex(515,175);
  k.vertex(325,175);
  k.vertex(325,375);
  k.vertex(350,400);
  k.endShape(CLOSE);
  //3D Aspect of Dice 3
  r=createShape();
  r.beginShape();
  r.fill(#ffffff);
  r.vertex(850,200);
  r.vertex(815,175);
  r.vertex(625,175);
  r.vertex(625,375);
  r.vertex(650,400);
  r.endShape(CLOSE);
  //Dice Background Dots
  ov=loadImage("oval.png");
  //Text Settings
  textAlign(CENTER,CENTER);
  textSize(60);
  frameRate(0.4);
}
void draw(){
  strokeWeight(3);
  fill(#FFFFFF);
  rectMode(CENTER);
  //Die 1
  shape(s,0,0);
  rect(150,300,200,200);
  line(50,200,25,175);
  image(ov,115,173,35,30);
  image(ov,30,208,25,45);
  image(ov,26,266,25,45);
  image(ov,21,325,25,45);
  //Die 2
  shape(k,0,0);
  rect(450,300,200,200);
  line(350,200,325,175);
  image(ov,415,173,35,30);
  image(ov,330,208,25,45);
  image(ov,326,266,25,45);
  image(ov,321,325,25,45);
  //Die 3
  shape(r,0,0);
  rect(750,300,200,200);
  line(650,200,625,175);
  image(ov,715,173,35,30);
  image(ov,630,208,25,45);
  image(ov,626,266,25,45);
  image(ov,621,325,25,45);
}
  //Rolling the Die
  void mouseClicked(){
   fill(#6666FF);
   text(x[int(random(6))],width/2,height/2);
   text(m[int(random(6))],width/6,height/2);
   text(e[int(random(6))],width/1.2,height/2);
  }
