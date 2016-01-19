void setup(){ 
  size(400,400); 
  background(0); 
  noLoop(); 
}

void draw(){
  
  stroke(200,200,200);
  strokeWeight(5);
  for(int x = 20; x < 410; x+=40){
    line(x, -40, x, 400);
  }
  for(int y = 20; y < 410; y+=40){
    line(-40, y, 400, y);
  }
  fill(255); 
  noStroke();
  for(int y = 20; y <=380; y+=40) { 
    for(int x = 20; x <=380; x+=40) { 
      ellipse(x,y,10,10); 
    } 
  }
}
