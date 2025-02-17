<!DOCTYPE html>
<html>
  <head>

    <meta http-equiv="content-type" content="text/html; charset=windows-1252">
    <title>Footer LTTA</title>
    <style>
 /* a fix for google sites vertical scroll bar on mobile version when embeding code */
 html,
body {
   padding: 0;
   margin: 0;
   height: 100vh;
   min-height: 100vh;  // for extra vigilance because some browsers are finicky
}

    /* Metodo Flexbox (consigliato) */
    .container {
      display: flex;
      align-items: stretch;
      width: 100%;
      height: 100%;
    }

    /* Stili comuni ai due div */
    .div1, .div2 {
      border: 1px solid black;
      box-sizing: border-box;
      padding: 20px;
      text-align: left; /* Mantiene l'allineamento del testo al centro */
      /* Centratura verticale e orizzontale con Flexbox */
      display: flex;
      flex-direction: column;
      justify-content: center;
      overflow: hidden;

    }

    /* Regole per la dimensione dei div*/
    .div1 { flex: 6; } /* Div1 occupa 4 unità di spazio */
    .div2 { flex: 4; } /* Div2 e Div2 occupano 2 unità di spazio ciascuno */

    /* Stile per il primo div */

    .div1 img {
      max-width: 100%;
      max-height: 100px;
      object-fit: contain;
      margin: auto;
      display: block;
    }
    
    /* Stile per le ancore nel div2 (immagini) */

    .div2 img {
      max-width: 40%;
      max-height: 100px;
      object-fit: contain;
      display: block;
      margin: 5px auto;
    }
  </style>
  </head>
  <body>
    <div class="container">
      <div class="div1"> <a class="a-left" href="https://www.google.it">
          <img
src="https://raw.githubusercontent.com/fabiocasciano/logos/refs/heads/main/loghi%20coesione%20larghi_DA%20USARE.svg"
            alt="Logo LTTA"> </a> </div>
      <div class="div2"> <a class="a-right"
          href="https://www.art-er.it/" target="_blank"> <img
src="https://raw.githubusercontent.com/fabiocasciano/logos/refs/heads/main/logo%20art-er_oriz%20IT.svg"
            alt="Logo ARTER"> </a> </div>
    </div>
  </body>
</html>
