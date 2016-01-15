void setup(){
  size(400,400);
  background(0);
  noLoop();
}

void draw(){
  fill(255);
  for(int y = 20; y <=380; y+=40)
  {
    for(int x = 20; x <=380; x+=40)
    {
      ellipse(x,y,10,10);
    } 
  }
  
}
