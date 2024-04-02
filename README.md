function setup(){
    createCanvas(600,400)
  }
  function draw(){
    background("white");
    drawboxes();
  }
  function drawboxes() {
  //numarul 1
  stroke("");
  fill("lime");
  square(5, 5, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("1", 5 + 25, 5 + 25);

  //numarul 2
  fill("silver");
  square(60, 5, 50)
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("2", 60 + 25, 5 + 25);

  //numarul 3
  fill("lightblue");
  square(115, 5, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("3", 115 + 25, 5 + 25);

  //numarul 4
  fill("darkgreen");
  square(170, 5, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("4", 170 + 25, 5 + 25);

  //numarul 5
  fill("orange");
  square(225, 5, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("5", 225 + 25, 5 + 25);

  //numarul 6
  fill("brown");
  square(280, 5, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("6", 280 + 25, 5 + 25);

  //numarul 7
  fill("hotpink");
  square(335, 5, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("7", 335 + 25, 5 + 25);
  }
