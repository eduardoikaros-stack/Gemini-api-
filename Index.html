
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cruzamento de Carros Animado</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      font-family: Arial, sans-serif;
    }

    .container {
      text-align: center;
    }

    h1 {
      color: white;
      margin-bottom: 20px;
      font-size: 32px;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
    }

    .cruzamento {
      position: relative;
      width: 500px;
      height: 500px;
      background: #90EE90;
      border: 8px solid #333;
      margin: 0 auto;
      overflow: hidden;
      box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
    }

    /* Ruas */
    .rua-h {
      position: absolute;
      width: 100%;
      height: 150px;
      background: #444;
      top: 175px;
      left: 0;
    }

    .rua-v {
      position: absolute;
      width: 150px;
      height: 100%;
      background: #444;
      left: 175px;
      top: 0;
    }

    /* Faixa branca */
    .faixa-h {
      position: absolute;
      width: 100%;
      height: 3px;
      background: repeating-linear-gradient(
        90deg,
        white 0px,
        white 30px,
        transparent 30px,
        transparent 60px
      );
      top: 250px;
      z-index: 2;
    }

    .faixa-v {
      position: absolute;
      width: 3px;
      height: 100%;
      background: repeating-linear-gradient(
        0deg,
        white 0px,
        white 30px,
        transparent 30px,
        transparent 60px
      );
      left: 250px;
      z-index: 2;
    }

    /* Semáforos */
    .semaforo {
      position: absolute;
      width: 40px;
      height: 100px;
      background: #222;
      border-radius: 8px;
      padding: 8px;
      display: flex;
      flex-direction: column;
      justify-content: space-around;
      z-index: 10;
    }

    .semaforo-topo-esq {
      top: 20px;
      left: 20px;
    }

    .semaforo-topo-dir {
      top: 20px;
      right: 20px;
    }

    .semaforo-bot-esq {
      bottom: 20px;
      left: 20px;
    }

    .semaforo-bot-dir {
      bottom: 20px;
      right: 20px;
    }

    .luz {
      width: 24px;
      height: 24px;
      border-radius: 50%;
      background: #555;
      margin: 0 auto;
    }

    .luz.vermelho {
      background: #ff4444;
      box-shadow: 0 0 15px #ff4444;
    }

    .luz.amarelo {
      background: #ffdd44;
      box-shadow: 0 0 15px #ffdd44;
    }

    .luz.verde {
      background: #44ff44;
      box-shadow: 0 0 15px #44ff44;
    }

    /* Carros */
    .carro {
      position: absolute;
      width: 60px;
      height: 40px;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 24px;
      z-index: 5;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }

    /* Carro 1 - Direita (vermelho) */
    .carro1 {
      background: linear-gradient(135deg, #ff6b6b, #ff4444);
      animation: mover-direita 5s infinite;
      top: 210px;
    }

    /* Carro 2 - Esquerda (azul) */
    .carro2 {
      background: linear-gradient(135deg, #4ecdc4, #2ba89f);
      animation: mover-esquerda 5s infinite 0.5s;
      top: 260px;
    }

    /* Carro 3 - Baixo (amarelo) */
    .carro3 {
      background: linear-gradient(135deg, #ffd93d, #ffb700);
      animation: mover-baixo 5s infinite 1s;
      left: 210px;
    }

    /* Carro 4 - Cima (verde) */
    .carro4 {
      background: linear-gradient(135deg, #95e1d3, #6cc8b8);
      animation: mover-cima 5s infinite 1.5s;
      left: 260px;
    }

    /* Carro 5 - Direita (rosa) */
    .carro5 {
      background: linear-gradient(135deg, #ff85a2, #ff5a7e);
      animation: mover-direita 5s infinite 2s;
      top: 260px;
    }

    /* Carro 6 - Esquerda (laranja) */
    .carro6 {
      background: linear-gradient(135deg, #ffa500, #ff8c00);
      animation: mover-esquerda 5s infinite 2.5s;
      top: 210px;
    }

    /* Animações de movimento */
    @keyframes mover-direita {
      0% {
        left: -80px;
      }
      100% {
        left: 500px;
      }
    }

    @keyframes mover-esquerda {
      0% {
        right: -80px;
      }
      100% {
        right: 500px;
      }
    }

    @keyframes mover-baixo {
      0% {
        top: -80px;
      }
      100% {
        top: 500px;
      }
    }

    @keyframes mover-cima {
      0% {
        top: 500px;
      }
      100% {
        top: -80px;
      }
    }

    .info {
      color: white;
      margin-top: 25px;
      font-size: 16px;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
    }

    .controls {
      margin-top: 20px;
      display: flex;
      gap: 10px;
      justify-content: center;
    }

    button {
      padding: 12px 24px;
      background: white;
      color: #667eea;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
      font-weight: bold;
      transition: all 0.3s;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    button:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
    }

    .animacao-ativa {
      animation-play-state: running !important;
    }

    .animacao-parada {
      animation-play-state: paused !important;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>🚦 Cruzamento de Carros 🚦</h1>

    <div class="cruzamento" id="cruzamento">
      <!-- Ruas -->
      <div class="rua-h"></div>
      <div class="rua-v"></div>

      <!-- Faixas -->
      <div class="faixa-h"></div>
      <div class="faixa-v"></div>

      <!-- Semáforos -->
      <div class="semaforo semaforo-topo-esq">
        <div class="luz verde"></div>
        <div class="luz amarelo"></div>
        <div class="luz vermelho"></div>
      </div>

      <div class="semaforo semaforo-topo-dir">
        <div class="luz vermelho"></div>
        <div class="luz amarelo"></div>
        <div class="luz verde"></div>
      </div>

      <div class="semaforo semaforo-bot-esq">
        <div class="luz amarelo"></div>
        <div class="luz verde"></div>
        <div class="luz vermelho"></div>
      </div>

      <div class="semaforo semaforo-bot-dir">
        <div class="luz verde"></div>
        <div class="luz vermelho"></div>
        <div class="luz amarelo"></div>
      </div>

      <!-- Carros -->
      <div class="carro carro1 animacao-ativa">🚗</div>
      <div class="carro carro2 animacao-ativa">🚕</div>
      <div class="carro carro3 animacao-ativa">🚙</div>
      <div class="carro carro4 animacao-ativa">🚌</div>
      <div class="carro carro5 animacao-ativa">🚗</div>
      <div class="carro carro6 animacao-ativa">🚕</div>
    </div>

    <div class="info">
      <p>✨ Carros passando pelo cruzamento com movimento contínuo! ✨</p>
    </div>

    <div class="controls">
      <button onclick="pausarAnimacao()">⏸️ Pausar</button>
      <button onclick="iniciarAnimacao()">▶️ Iniciar</button>
    </div>
  </div>

  <script>
    function pausarAnimacao() {
      const carros = document.querySelectorAll('.carro');
      carros.forEach(carro => {
        carro.classList.remove('animacao-ativa');
        carro.classList.add('animacao-parada');
      });
    }

    function iniciarAnimacao() {
      const carros = document.querySelectorAll('.carro');
      carros.forEach(carro => {
        carro.classList.remove('animacao-parada');
        carro.classList.add('animacao-ativa');
      });
    }
  </script>
</body>
</html>
