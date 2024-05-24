// Variáveis do oponente
let xRaqueteOponente = 585;
let yRaqueteOponente = 150;
let velocidadeYOponente = 0; // Velocidade inicial do oponente

// Variáveis da bolinha
let xBolinha = 300;
let yBolinha = 200;
let diametro = 22;
let raio = diametro / 2;

// Velocidade da bolinha
let velocidadeXBolinha = 5;
let velocidadeYBolinha = 5;

// Variáveis da raquete
let xRaquete = 5;
let yRaquete = 150;
let raqueteComprimento = 10;
let raqueteAltura = 90;

let colidiu = false;

function setup() {
  createCanvas(600, 400);
}

function draw() {
  background(0);
  mostraBolinha();
  movimentaBolinha();
  verificaColisaoBorda();
  mostraRaquete();
  movimentaMinhaRaquete();
  movimentaRaqueteOponente();
  verificaColisaoRaquete();
}

function mostraBolinha() {
  fill(255); // Cor branca para a bolinha
  circle(xBolinha, yBolinha, diametro);
}

function movimentaBolinha() {
  xBolinha += velocidadeXBolinha;
  yBolinha += velocidadeYBolinha;
}

function verificaColisaoBorda() {
  if (xBolinha + raio > width || xBolinha - raio < 0) {
    velocidadeXBolinha *= -1;
  }
  if (yBolinha + raio > height || yBolinha - raio < 0) {
    velocidadeYBolinha *= -1;
  }
}

function mostraRaquete() {
  fill(255); // Cor branca para a raquete
  rect(xRaquete, yRaquete, raqueteComprimento, raqueteAltura);
}

function movimentaMinhaRaquete() {
  if (keyIsDown(UP_ARROW) && yRaquete > 0) {
    yRaquete -= 10;
  }
  if (keyIsDown(DOWN_ARROW) && yRaquete + raqueteAltura < height) {
    yRaquete += 10;
  }
}

function movimentaRaqueteOponente() {
  // Move a raquete do oponente para cima ou para baixo de acordo com a posição da bolinha
  if (yBolinha > yRaqueteOponente + raqueteComprimento / 2) {
    velocidadeYOponente = 5; // Mover para cima
  } else {
    velocidadeYOponente = -5; // Mover para baixo
  }

  // Limita a movimentação da raquete do oponente dentro da tela
  yRaqueteOponente += velocidadeYOponente;
  if (yRaqueteOponente < 0) {
    yRaqueteOponente = 0;
  } else if (yRaqueteOponente + raqueteComprimento > height) {
    yRaqueteOponente = height - raqueteComprimento;
  }
}

function verificaColisaoRaquete() {
  // Verifica colisão entre a bolinha e a raquete do jogador
  colidiu = collideRectCircle(xRaquete, yRaquete, raqueteComprimento, raqueteAltura, xBolinha, yBolinha, raio);
  if (colidiu){
    velocidadeXBolinha *= -1;
  }

  // Verifica colisão entre a bolinha e a raquete do oponente
  colidiu = collideRectCircle(xRaqueteOponente, yRaqueteOponente, raqueteComprimento, raqueteAltura, xBolinha, yBolinha, raio);
  if (colidiu){
    velocidadeXBolinha *= -1;
  }
}

