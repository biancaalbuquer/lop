/* 
    Equipe: 
        Bianca Santos de Albuquerque - Subturma d (Líder)  
        Etapa 1 e 2
*/

var x=30;
var y=350;
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background('rgb(100%,0%,10%)');
  ellipse(x,y,50,50);
   if (keyIsDown(LEFT_ARROW)) {
    x = x-5;
  }

  if (keyIsDown(RIGHT_ARROW)) {
    x = x+5;
  }

  if (keyIsDown(UP_ARROW)) {
    y = y-5;
  }

  if (keyIsDown(DOWN_ARROW)) {
    y = y+5;
  }

  rect(80, 80, 80, 80);
  fill(20, 10, 200, 200);
  stroke(120, 63, 120);
}
