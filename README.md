void setup(){
 size(1000,800); 
 background(#2F5218);
}


void draw(){
stroke(#E3E3E0); 
strokeWeight(6);

line(mouseX,mouseY,pmouseX,pmouseY);
}

void keyPressed(){
background(#2F5218);

if(mousePressed){ //only if mouse and any key is pressed on it works
  
  line(mouseX,mouseY,pmouseX,pmouseY);
  background(#136EEA);
}
  }

    
