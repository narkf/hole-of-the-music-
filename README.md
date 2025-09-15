<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Home of the Music</title>
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Courier+Prime&family=Dancing+Script&family=Metal+Mania&family=Oswald&family=Orbitron&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
/* General */
body {
  font-family: 'Roboto', sans-serif;
  margin: 0;
  padding: 0;
  background: #0f172a;
  color: #f1f5f9;
  scroll-behavior: smooth;
}
header {
  background: linear-gradient(90deg, #1e3a8a, #9333ea);
  text-align: center;
  padding: 30px;
  color: white;
}
header h1 { margin:0; font-size:2.5rem;}
nav { background: #1e293b; text-align: center; padding: 10px; position: sticky; top:0; z-index:100;}
nav a { color: #f1f5f9; text-decoration: none; margin: 0 12px; font-weight: bold; transition: color 0.3s; }
nav a:hover { color: #38bdf8; }
section { padding: 50px 20px; max-width:1000px; margin:auto; border-radius:12px; margin-bottom:20px; transition: transform 0.3s; }
section:hover { transform: scale(1.01); }
section h2 { border-bottom: 2px solid #38bdf8; padding-bottom:10px; margin-bottom:20px; }
.gallery { display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:20px; margin-top:20px; }
.gallery img { width:100%; border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.5); transition: transform 0.3s; }
.gallery img:hover { transform:scale(1.05); }
footer { background:#1e293b; text-align:center; padding:20px; margin-top:30px; }

/* Fuentes y estilos según género */
#rock { font-family: Georgia, 'Times New Roman', serif; background:#2c2c2c; padding:40px; line-height:1.6; color:#f1f5f9;}
#pop { font-family: 'Verdana', Geneva, sans-serif; background:#ff6f91; padding:40px; line-height:1.6; color:#fff; }
#jazz { font-family: 'Courier Prime', monospace; background:#3b3b58; padding:40px; line-height:1.6; color:#f1f5f9; }
#electronica { font-family: 'Orbitron', sans-serif; background:#0ff; color:#0f172a; padding:40px; line-height:1.6; }
#rap { font-family: 'Oswald', sans-serif; background:#222; color:#ffda55; padding:40px; line-height:1.6; }
#clasica { font-family: 'Dancing Script', cursive; background:#fdf6e3; color:#333; padding:40px; line-height:1.6; }
#metal { font-family: 'Metal Mania', cursive; background:#1a1a1a; color:#e63946; padding:40px; line-height:1.6; }

/* Efectos hover en enlaces de sección */
nav a { position: relative; }
nav a::after { content: ''; position: absolute; width: 0; height: 2px; background: #38bdf8; left: 0; bottom: -3px; transition: width 0.3s; }
nav a:hover::after { width: 100%; }
</style>
</head>
<body>

<header>
  <h1>🎶 Home of the Music</h1>
  <p>Descubre la magia de la música en un solo lugar</p>
</header>

<nav>
  <a href="#generos">Géneros</a>
  <a href="#artistas">Artistas</a>
  <a href="#rock">Rock</a>
  <a href="#pop">Pop</a>
  <a href="#jazz">Jazz</a>
  <a href="#electronica">Electrónica</a>
  <a href="#rap">Rap</a>
  <a href="#clasica">Clásica</a>
  <a href="#metal">Metal</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="generos">
  <h2>🎵 Géneros Musicales</h2>
  <p>La música tiene una gran variedad de estilos, cada uno con su esencia única:</p>
  <ul>
    <li><a href="#rock" style="color:#38bdf8; text-decoration:none;">🎸 Rock</a></li>
    <li><a href="#pop" style="color:#38bdf8; text-decoration:none;">🎤 Pop</a></li>
    <li><a href="#jazz" style="color:#38bdf8; text-decoration:none;">🎷 Jazz</a></li>
    <li><a href="#electronica" style="color:#38bdf8; text-decoration:none;">🎧 Electrónica</a></li>
    <li><a href="#rap" style="color:#38bdf8; text-decoration:none;">🎙️ Rap</a></li>
    <li><a href="#clasica" style="color:#38bdf8; text-decoration:none;">🎼 Clásica</a></li>
    <li><a href="#metal" style="color:#38bdf8; text-decoration:none;">🤘 Metal</a></li>
  </ul>
</section>

<section id="artistas">
  <h2>🌟 Artistas Famosos</h2>
  <div class="gallery">
    <img src="https://occ-0-8407-92.1.nflxso.net/dnm/api/v6/Z-WHgqd_TeJxSuha8aZ5WpyLcX8/AAAABcT_ama_saEb3OUlmIUz23bzPGjxROArk4at7HZKNL1gkak8KLs4cZytGNrMQyPa7r3L4B99t1v1IQqpiZQXpjRr7VouRilVWT5I.jpg?r=de3" alt="Freddie Mercury">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/Michael_Jackson_in_1988.jpg/250px-Michael_Jackson_in_1988.jpg" alt="Michael Jackson">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSDjTqNfAF7y6BeUiaPyXiKKYMwVchXJER2Xg&s" alt="System of a Down">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/16/Louis_Armstrong_in_Color_%28restored%29.jpg/1200px-Louis_Armstrong_in_Color_%28restored%29.jpg" alt="Louis Armstrong">
  </div>
</section>

<!-- Rock -->
<section id="rock">
  <h2>🎸 Rock</h2>
  <p>La historia del rock comienza a mediados del siglo XX en Estados Unidos, cuando diferentes estilos como el blues, rhythm and blues, gospel y country se mezclaron dando origen al rock and roll. Artistas como Chuck Berry, Little Richard y Elvis Presley definieron el sonido inicial, capturando la rebeldía juvenil. Durante los años sesenta la invasión británica con The Beatles y The Rolling Stones expandió el género, mientras que el rock psicodélico y progresivo introdujeron nuevas texturas. En los setenta surgieron el hard rock y heavy metal con Led Zeppelin y Black Sabbath, y el punk recuperó la energía cruda de la música. Los ochenta trajeron el glam metal, post punk y rock alternativo, mientras que los noventa introdujeron grunge y britpop. En el siglo XXI, bandas indie y latinoamericanas mantienen vivo el espíritu del rock como símbolo cultural y de libertad.</p>
</section>

<!-- Pop -->
<section id="pop">
  <h2>🎤 Pop</h2>
  <p>El pop nace como un estilo comercial y accesible en los años cincuenta y sesenta, tomando influencias del rock, rhythm and blues y música ligera, con melodías pegadizas, estructuras simples y producción orientada al público masivo. Artistas como Michael Jackson, Madonna y Britney Spears consolidaron el pop mundial, combinando espectáculo visual, coreografías y letras que reflejan emociones universales. Con los años, el pop ha incorporado elementos de electrónica, rap y música urbana, manteniendo su capacidad de adaptarse a tendencias y generaciones, y se ha convertido en un género global que define la cultura musical popular.</p>
</section>

<!-- Jazz -->
<section id="jazz">
  <h2>🎷 Jazz</h2>
  <p>El jazz surge a comienzos del siglo XX en Nueva Orleans como una mezcla única de ritmos africanos, blues, ragtime y música europea, caracterizándose por la improvisación, la libertad expresiva y la interacción constante entre los músicos, desde sus primeros años reflejó la experiencia de la comunidad afroamericana, convirtiéndose en un lenguaje musical capaz de transmitir emociones profundas y contar historias sin palabras. Durante décadas se diversificó en swing, bebop, cool jazz y hard bop. Artistas como Louis Armstrong, Duke Ellington, Charlie Parker, Miles Davis y John Coltrane lo llevaron a nivel internacional, y con subgéneros como jazz fusión y free jazz sigue influyendo en la música y la cultura global.</p>
</section>

<!-- Electrónica -->
<section id="electronica">
  <h2>🎧 Electrónica</h2>
  <p>La música electrónica surge a partir de experimentos con sintetizadores y tecnología musical en el siglo XX, alcanzando popularidad en los setenta y ochenta con géneros como techno, house y trance. Kraftwerk, Daft Punk y The Prodigy definieron un sonido caracterizado por ritmos repetitivos y paisajes futuristas. La electrónica se fusiona con pop, hip hop y otros estilos, creando experiencias de baile, festivales y cultura digital global.</p>
</section>

<!-- Rap -->
<section id="rap">
  <h2>🎙️ Rap</h2>
  <p>El rap nace en los años setenta en el Bronx como parte de la cultura hip hop, combinando rimas habladas con ritmos de DJs y samples. Desde sus inicios transmitió mensajes sociales y culturales sobre desigualdad, resistencia y vida urbana. Tupac, Notorious B.I.G., Eminem y Kendrick Lamar expandieron su alcance. Con subgéneros como trap y gangsta rap, sigue siendo un medio poderoso de expresión y cultura global.</p>
</section>

<!-- Clásica -->
<section id="clasica">
  <h2>🎼 Clásica</h2>
  <p>La música clásica se desarrolla desde la Edad Media hasta la actualidad, incluyendo Barroco, Clasicismo, Romanticismo y Modernismo. Compositores como Bach, Mozart, Beethoven y Tchaikovsky definieron estructuras armónicas y sinfónicas que aún inspiran. La clásica transmite emociones profundas, narrativas dramáticas y belleza estética, y sigue siendo un pilar de la formación musical y la cultura artística mundial.</p>
</section>

<!-- Metal -->
<section id="metal">
  <h2>🤘 Metal</h2>
  <p>El metal surge como evolución del hard rock en los años sesenta y setenta, con guitarras distorsionadas, riffs potentes y baterías intensas. Bandas como Black Sabbath, Led Zeppelin y Deep Purple sentaron las bases. Posteriormente surgieron subgéneros como thrash, death, black, power y nu metal. El metal combina virtuosismo técnico, creatividad sonora y pasión intensa, convirtiéndose en un fenómeno cultural que define moda, festivales y la identidad de sus seguidores.</p>
</section>

<section id="contacto">
  <h2>📩 Contacto</h2>
  <p>¿Quieres saber más sobre el proyecto? Escríbenos a:</p>
  <p><a href="mailto:info@homeofthemusic.com" style="color:#38bdf8;">info@homeofthemusic.com</a></p>
</section>

<footer>
  <p>© Home of the Music - Proyecto Escolar</p>
</footer>

</body>
</html>
