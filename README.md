<!DOCTYPE html>
<html>
  <head>
    <style>
      .container {
        position: relative;
        width: 100%;
      }
      
      .imagem {
        width: 100%;
        height: auto;
      }
      
      .texto-sobreposto {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        color: white;
        font-size: 24px;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <img class="imagem" src="https://i.pinimg.com/736x/15/27/32/1527324d513b19367e35238ef51ea686.jpg" alt="Sua Imagem">
      <div class="texto-sobreposto">Seu Texto Aqui</div>
    </div>
  </body>
</html>
