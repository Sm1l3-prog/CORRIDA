# CORRIDA
function setup(){
  createCanvas(400, 400);
}
let xjog1=0
let xjog2=0
let xjog3=0

function draw() {
  background(220); 
  fill(235,228,228)
  textSize(40)
text("🎮",xjog1 , 40)
text("☠️",xjog2, 200)
text("🔫",xjog3, 350)
rect(350,0,10,400)
 xjog1 = xjog1 + random(3);
  xjog2 = xjog2 + random(3);
 xjog3 = xjog3 + random(3);
 fill(8,80,124)
  textSize(30)
    if (xjog1> 350) {
   text("PLAYER 1 WIN 🏆", 50, 200);
   noLoop();
  }
  if (xjog2 > 350) {
   text("PLAYER 2 WIN 🏆!", 50, 200);
   noLoop();
  }
  if (xjog3 > 350) {
   text("PLAYER 3 WIN 🏆!", 50, 200);
   noLoop();
  
  
  
  
  }
  
  
  
}
