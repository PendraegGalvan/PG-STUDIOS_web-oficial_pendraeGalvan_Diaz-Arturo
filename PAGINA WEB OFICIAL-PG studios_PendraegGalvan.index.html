# PG-STUDIOS_web-oficial_pendraeGalvan_Diaz-Arturo
Pagina web oficial de el estudio desarrollador PG
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PG STUDIOS</title>
<style>
* {margin: 0; padding: 0; box-sizing: border-box; font-family: sans-serif;}
body {
  background-color: #0b3d0b;
  color: #fff;
}
header {background: #062; padding: 15px; text-align: center;}
nav {display: flex; justify-content: center; gap: 10px; margin-top: 10px;}
button {
  padding: 8px 12px; background: #0077ff; border: none; color: #fff; border-radius: 5px; cursor: pointer; transition: 0.3s;
}
button:hover {background: #005bbb;}
section {display: none; padding: 15px;}
.active {display: block; animation: fade 0.5s;}
@keyframes fade {from {opacity: 0;} to {opacity: 1;}}
footer {background: #062; text-align: center; padding: 10px; margin-top: 15px; font-size: 0.8em;}
input[type="password"], input[type="file"] {
  margin-top: 10px; padding: 7px; border-radius: 4px; border: 1px solid #555; background: #222; color: #fff; display: block;
}
.download-link {color: #0f0; display: block; margin-top: 5px; font-size: 0.9em;}
textarea {
  width: 100%; height: 300px; background: #111; color: #0f0; padding: 10px; border: 1px solid #444;
}
.audio-click {display: none;}
</style>
</head>
<body>

<audio id="clickSound" preload="auto">
  <source src="https://www.soundjay.com/buttons/button-3.mp3" type="audio/mpeg">
</audio>

<header>
  <h1>PG STUDIOS</h1>
  <p>Desarrollador: Pendraeg Galvan</p>
  <nav>
    <button onclick="showSection('inicio')">Inicio</button>
    <button onclick="showSection('novedades')">Novedades</button>
    <button onclick="showSection('recursos')">Recursos</button>
    <button onclick="accessCode()">Código raíz</button>
  </nav>
</header>

<section id="inicio" class="active">
  
  <h2>Bienvenido a PG STUDIOS</h2>
<p>
  Te damos la bienvenida oficial a la página de PG STUDIOS, un estudio independiente de desarrollo creado con esfuerzo, dedicación y pasión por los videojuegos, las historias, y el entretenimiento digital. Nuestra misión es ofrecer experiencias únicas, hechas desde el corazón y con ideas diferentes a lo que hoy en día abunda en la industria.
</p>
<p>
  Actualmente, estamos trabajando arduamente en uno de nuestros proyectos más ambiciosos hasta el momento: un videojuego multijugador en línea, de mundo abierto, con mecánicas únicas y personalización nunca antes vista. Este proyecto busca unir lo mejor del estilo sandbox con elementos de estrategia, construcción y combate. 
</p>
<p>
  Desde este sitio web oficial podrás seguir de cerca todo el proceso de desarrollo, acceder a novedades, obtener recursos oficiales como modelos 3D o texturas, y próximamente descargar prototipos funcionales del juego, los cuales iremos liberando a medida que vayamos avanzando. 
</p>
<p>
  PG STUDIOS es más que un simple equipo; es un proyecto hecho por verdaderos apasionados, dedicando cada hora de su tiempo libre a crear algo de calidad y diferente. Nos encontramos aún en fase temprana, pero cada día estamos más cerca de lograr nuestro objetivo. Hemos desarrollado motores de prueba, sistemas de carga, conceptos y módulos que pronto estarán al alcance de todos ustedes.
</p>
<p>
  Este estudio fue creado desde cero, sin apoyo externo de grandes compañías, demostrando que cuando las ideas son sólidas y el esfuerzo constante, los sueños pueden volverse realidad. Gracias por acompañarnos en este camino.
</p>
<p>
  Agradecemos especialmente a <strong>Anachuri Flores</strong>, quien ha colaborado directamente en la creación de esta página web, aportando su conocimiento y trabajo constante para que PG STUDIOS hoy tenga un espacio donde compartir sus avances con el mundo.
</p>
<p>
  ¡Esto recién comienza! Pronto mucho más. Gracias por visitarnos.
</p>
</section>

<section id="novedades">
  <h2>Novedades</h2>
  <p>Publica archivos o noticias importantes (requiere contraseña).</p>
  <input type="password" id="passNovedades" placeholder="Contraseña">
  <input type="file" id="fileNovedades">
  <button onclick="subirArchivo('novedades')">Subir archivo</button>
  <div id="novedadesArchivos"></div>
</section>

<section id="recursos">
  <h2>Recursos</h2>
  <p>Modelos 3D, texturas, archivos útiles (requiere contraseña).</p>
  <input type="password" id="passRecursos" placeholder="Contraseña">
  <input type="file" id="fileRecursos">
  <button onclick="subirArchivo('recursos')">Subir recurso</button>
  <div id="recursosArchivos"></div>
</section>

<section id="codigo">
  <h2>Código raíz</h2>
  <textarea readonly id="codigoRaiz"></textarea>
</section>

<footer>© PG STUDIOS 2025</footer>

<script>
const PASSWORD_GENERAL = "EDM2025";
const PASSWORD_CODIGO = "PG13";

function playClick() {
  const audio = document.getElementById("clickSound");
  if (audio) {
    audio.currentTime = 0;
    audio.play().catch(() => {});
  }
}

function showSection(id) {
  playClick();
  document.querySelectorAll('section').forEach(s => s.classList.remove('active'));
  document.getElementById(id).classList.add('active');
}

function subirArchivo(tipo) {
  playClick();
  const pass = tipo === 'novedades' ? document.getElementById('passNovedades').value : document.getElementById('passRecursos').value;
  if (pass !== PASSWORD_GENERAL) {
    alert("Contraseña incorrecta.");
    return;
  }
  const archivoInput = tipo === 'novedades' ? document.getElementById('fileNovedades') : document.getElementById('fileRecursos');
  const archivo = archivoInput.files[0];
  if (!archivo) {
    alert("Selecciona un archivo.");
    return;
  }
  const url = URL.createObjectURL(archivo);
  const contenedor = tipo === 'novedades' ? document.getElementById('novedadesArchivos') : document.getElementById('recursosArchivos');
  const link = document.createElement('a');
  link.href = url;
  link.download = archivo.name;
  link.className = 'download-link';
  link.textContent = "Descargar " + archivo.name;
  contenedor.appendChild(link);
  archivoInput.value = "";
}

function accessCode() {
  playClick();
  const clave = prompt("Contraseña del código raíz:");
  if (clave === PASSWORD_CODIGO) {
    showSection('codigo');
    document.getElementById('codigoRaiz').value = document.documentElement.outerHTML;
  } else {
    alert("Contraseña incorrecta.");
  }
}
</script>

</body>
</html>
