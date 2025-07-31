
let circleA = 400;
let circleB = 100;


function setup() { 
  createCanvas(400, 300);
  
  }

function draw() {  
  background('pink');
  noStroke();
  //circle 1
  fill(255);
  circle(circleA, 50, 64);
  
  //circle 2
  fill(255);
  circle(circleB, 115, 64);
  
  //circle 3
  fill(255);
  circle(circleA, 180, 64);
  
  //circle 4
  fill(255);
  circle(circleB, 245, 64);
  
  circleA -= 1
  circleB ++
  
}



