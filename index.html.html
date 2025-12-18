<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>🎄 Competencia Navideña 🎄</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #0b6623, #b30000);
      color: #fff;
      margin: 0;
      padding: 0;
      text-align: center;
      overflow-x: hidden;
    }
    header { padding: 30px 15px; }
    h1 { font-size: 2.2em; }
    h2 { font-size: 1.3em; }
    .container { display: flex; justify-content: center; padding: 15px; }
    .card {
      background: rgba(255,255,255,0.15);
      border-radius: 20px;
      width: 100%;
      max-width: 360px;
      padding: 25px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.4);
    }
    button {
      background: #ffffff;
      color: #b30000;
      border: none;
      padding: 14px 28px;
      border-radius: 30px;
      cursor: pointer;
      font-weight: bold;
      margin-top: 15px;
      width: 100%;
      font-size: 1em;
    }
    button:disabled { opacity: 0.5; cursor: not-allowed; }
    #resultado, #carta { display: none; margin: 30px 15px; }
    .winner {
      background: rgba(0,0,0,0.4);
      border-radius: 25px;
      padding: 25px;
      animation: aparecer 1.2s ease-out;
    }
    @keyframes aparecer {
      from { opacity: 0; transform: scale(0.9) translateY(20px); }
      to { opacity: 1; transform: scale(1) translateY(0); }
    }
    footer { margin: 30px 0; font-size: 0.9em; }

    /* Nieve */
    .snowflake {
      position: fixed;
      top: -10px;
      color: white;
      font-size: 1em;
      animation: fall linear infinite;
      z-index: 9999;
    }
    @keyframes fall {
      to { transform: translateY(110vh); }
    }
  </style>
</head>
<body>

<!-- Música -->
<audio id="music" loop>
  <source src="https://cdn.pixabay.com/download/audio/2022/12/06/audio_6c7f1c9b6f.mp3" type="audio/mpeg">
</audio>

<header>
  <h1>🎅🎄 Competencia Navideña de Regalos 🎄🎅</h1>
  <h2>Estimado Sr. Rafael 🎁</h2>
  <p>Una experiencia especial para elegir el regalo perfecto ✨</p>
  <button id="btnMusic">🎶 Música on / off</button>
</header>

<section class="container">
  <div class="card">
    <h3 id="titulo"></h3>
    <p id="descripcion"></p>
    <p id="opinion"></p>
    <button id="btnDetalle">🔍 Ver detalles</button>
    <button id="btnSiguiente" style="display:none">➡️ Siguiente opción</button>
    <button id="btnCarta" style="display:none">💌 Ver carta</button>
  </div>
</section>

<button id="btnGanador" disabled>🏆 Ver ganador 🏆</button>

<section id="resultado">
  <div class="winner">
    <h2>🎉🎄 El ganador es… 🎄🎉</h2>
    <h1>🎮 PlayStation 5 Slim 🎮</h1>
    <p>Única, útil y perfecta para disfrutar solo o con amigos 🎮❄️</p>
    <p><strong>Precio:</strong> 2.200.000 COP 💰</p>
    <p>Con cariño,<br><strong>Andrés</strong> ❤️🎅</p>
  </div>
</section>

<section id="carta">
  <div class="winner">
    <h2>💌 Carta para ti, pa 💌</h2>
    <p>Pa, todo lo de mi tía Yami va a salir bien 🙏🎄. Todo mejorará poco a poco.</p>
    <p>Eres un <strong>excelente padre</strong>, gracias por siempre estar ahí ❤️.</p>
    <p>Cambié la insistencia de la tarjeta gráfica por la Play porque me llamó más la atención como experiencia completa 🎮✨.</p>
    <p>Los precios pueden variar. En <strong>Gamerstop</strong> (cerca del Salvators de la 47) se consigue incluso con más accesorios por el mismo o menor precio de <strong>2.200.000 COP</strong>.</p>
    <p>Feliz Navidad 🎄🎁<br><strong>Andrés</strong> ❤️</p>
  </div>
</section>

<footer>
  <p>🎄 Feliz Navidad 🎄</p>
</footer>

<script>
  const productos = [
    { titulo: '🖥️ Tarjeta Gráfica RTX 5050', descripcion: 'Ideal para mejorar el rendimiento de una PC gamer.', opinion: 'Es una buena opción, pero no es lo que deseo como regalo ❄️' },
    { titulo: '🕶️ Meta Quest 3', descripcion: 'Realidad virtual inmersiva e innovadora.', opinion: 'Es una buena opción, pero no es lo que deseo ahora 🎄' },
    { titulo: '🎮 PlayStation 5 Slim', descripcion: 'Diversión asegurada con gran catálogo.', opinion: 'Esta es una excelente opción como regalo 🎅✨' }
  ];

  let index = 0;

  const titulo = document.getElementById('titulo');
  const descripcion = document.getElementById('descripcion');
  const opinion = document.getElementById('opinion');
  const btnDetalle = document.getElementById('btnDetalle');
  const btnSiguiente = document.getElementById('btnSiguiente');
  const btnCarta = document.getElementById('btnCarta');
  const btnGanador = document.getElementById('btnGanador');
  const btnMusic = document.getElementById('btnMusic');
  const music = document.getElementById('music');

  function cargar() {
    titulo.textContent = productos[index].titulo;
    descripcion.textContent = productos[index].descripcion;
    opinion.textContent = '';
    btnDetalle.disabled = false;
    btnSiguiente.style.display = 'none';
    btnCarta.style.display = 'none';
  }

  function verDetalle() {
    opinion.textContent = productos[index].opinion;
    btnDetalle.disabled = true;
    btnSiguiente.style.display = 'block';
  }

  function siguiente() {
    index++;
    if (index < productos.length) {
      cargar();
    }
    if (index === productos.length - 1) {
      btnGanador.disabled = false;
      btnSiguiente.style.display = 'none';
      btnCarta.style.display = 'block';
    }
  }

  function mostrarGanador() {
    const res = document.getElementById('resultado');
    res.style.display = 'block';
    window.scrollTo({ top: document.body.scrollHeight, behavior: 'smooth' });
  }

  function mostrarCarta() {
    const carta = document.getElementById('carta');
    carta.style.display = 'block';
    window.scrollTo({ top: document.body.scrollHeight, behavior: 'smooth' });
  }

  function toggleMusic() {
    if (music.paused) {
      music.play();
    } else {
      music.pause();
    }
  }

  btnDetalle.addEventListener('click', verDetalle);
  btnSiguiente.addEventListener('click', siguiente);
  btnCarta.addEventListener('click', mostrarCarta);
  btnGanador.addEventListener('click', mostrarGanador);
  btnMusic.addEventListener('click', toggleMusic);

  document.addEventListener('DOMContentLoaded', cargar);

  // Nieve
  setInterval(() => {
    const snow = document.createElement('div');
    snow.className = 'snowflake';
    snow.textContent = '❄️';
    snow.style.left = Math.random() * 100 + 'vw';
    snow.style.animationDuration = 3 + Math.random() * 5 + 's';
    document.body.appendChild(snow);
    setTimeout(() => snow.remove(), 8000);
  }, 300);
</script>

</body>
</html>
