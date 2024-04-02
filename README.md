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

  //numarul 8
  fill("gray");
  square(5, 60, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("8", 5 + 25, 60 + 25);

  //numarul 9
  fill("purple");
  square(60, 60, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("9", 60 + 25, 60 + 25);

  //numarul 10
  fill("orange");
  square(115, 60, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("10", 115 + 25, 60 + 25);

  // numarul 11
  fill("blue");
  square(170, 60, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("11", 170 + 25, 60 + 25);

  //numarul 12
  fill("lightblue");
  square(225, 60, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("12", 225 + 25, 60 + 25);

  //numarul 13
  fill("orange");
  square(280, 60, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("13", 280 + 25, 60 + 25);

  //numarul 14 
  fill("lightpink");
  square(335, 60, 50);
  fill("white");
  textSize(20);
  textAlign(CENTER, CENTER);
  text("14", 335 + 25, 60 + 25);
  }
