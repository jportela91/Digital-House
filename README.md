# Digital-House

var xPos = 200;
var yPos = 200;
var yPos1= 400;
var xPos1= 400;
function setup() {
    createCanvas(600, 600);
    noStroke();
}

draw = function() {
    background(29, 40, 115);
    fill(255, 242, 0);
    ellipse(mouseX, mouseY, 100, 100);
    ellipse(xPos1, yPos1, 10, 10);


    xPos--;
    yPos--;
    yPos1++;
    xPos1++;


};
