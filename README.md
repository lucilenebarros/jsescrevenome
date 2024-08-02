let palavra;

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
  
}

function palavraAleatoria() {
  
  let palavras = ["solto", "soltar", "soltando"];
  
  return random(palavras);
}

function inicializaCores() {
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER);
}
