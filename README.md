<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elementos de Marca McDonald's</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #DA291C; /* Color de fondo de McDonald's */
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background-color: #FFC72C; /* Color amarillo de McDonald's */
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            text-align: center;
            color: #DA291C; /* Títulos en rojo de McDonald's */
        }
        ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
        }
        li {
            display: inline-block;
            margin: 10px;
        }
        .button {
            padding: 10px 20px;
            background-color: #DA291C;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #a31c15; /* Un rojo más oscuro */
        }
        .content-section {
            display: none; /* Oculto por defecto */
            border: 1px solid #ddd;
            padding: 20px;
            margin-top: 20px;
            border-radius: 8px;
            background-color: #fff;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Elementos de Marca de McDonald's</h1>
        
        <h2>Elementos Tangibles</h2>
        <ul>
            <li><button class="button" onclick="showContent('logo')">Logo</button></li>
            <li><button class="button" onclick="showContent('tipografia')">Tipografía</button></li>
            <li><button class="button" onclick="showContent('color')">Color</button></li>
            <li><button class="button" onclick="showContent('empaquetado')">Empaquetado</button></li>
            <li><button class="button" onclick="showContent('marketing')">Materiales de marketing</button></li>
        </ul>

        <h2>Elementos Intangibles</h2>
        <ul>
            <li><button class="button" onclick="showContent('sonido')">Sonido</button></li>
            <li><button class="button" onclick="showContent('sonologo')">Sonologo</button></li>
            <li><button class="button" onclick="showContent('olfativa')">Marca olfativa</button></li>
            <li><button class="button" onclick="showContent('tono')">Tono de voz</button></li>
            <li><button class="button" onclick="showContent('personalidad')">Personalidad de la marca</button></li>
            <li><button class="button" onclick="showContent('experiencia')">Experiencia del usuario</button></li>
            <li><button class="button" onclick="showContent('cultural')">Identidad cultural</button></li>
            <li><button class="button" onclick="showContent('valores')">Valores y misión</button></li>
        </ul>

        <h2>Otros Elementos</h2>
        <ul>
            <li><button class="button" onclick="showContent('patrocinios')">Patrocinios y alianzas</button></li>
            <li><button class="button" onclick="showContent('eventos')">Eventos y experiencias</button></li>
            <li><button class="button" onclick="showContent('contenido')">Contenido de marca</button></li>
        </ul>
        
        <div id="logo" class="content-section">
            <h3>Logo</h3>
            <p>El logo icónico de McDonald's son los **Arcos Dorados (Golden Arches)**. Este símbolo es reconocido mundialmente y está diseñado para ser visto fácilmente, incluso desde la distancia. Representa los arcos de una "M", inicial de la marca.</p>
        </div>
        
        <div id="tipografia" class="content-section">
            <h3>Tipografía</h3>
            <p>McDonald's usa una tipografía principal llamada **Lovin' Sans**, inspirada en la tipografía de su antiguo logo. Es una tipografía redondeada y amigable que evoca un sentimiento de diversión y cercanía.</p>
        </div>
        
        <div id="color" class="content-section">
            <h3>Color</h3>
            <p>Los colores de McDonald's son principalmente el **rojo** y el **amarillo**. El rojo evoca energía y el amarillo representa felicidad. La combinación es llamativa y apetitosa.</p>
        </div>
        
        <div id="empaquetado" class="content-section">
            <h3>Empaquetado</h3>
            <p>El empaquetado de McDonald's es muy reconocible. Las cajas de la **Cajita Feliz**, las envolturas de hamburguesas y las bolsas de papel con los arcos dorados son parte de la identidad de la marca. Recientemente, han cambiado a un diseño más simple y colorido.</p>
        </div>
        
        <div id="marketing" class="content-section">
            <h3>Materiales de marketing</h3>
            <p>Sus materiales de marketing incluyen sus carteleras con los arcos dorados, los menús en las tiendas y las promociones impresas y digitales. Siempre usan los colores corporativos y su tipografía amigable.</p>
        </div>
        
        <div id="sonido" class="content-section">
            <h3>Sonido</h3>
            <p>El sonido más conocido de McDonald's es el famoso jingle **"I'm lovin' it"**. Es una melodía simple y pegadiza que se usa en todas sus campañas de publicidad a nivel global.</p>
        </div>
        
        <div id="sonologo" class="content-section">
            <h3>Sonologo</h3>
            <p>El "ba da ba ba baa" que se canta al final del jingle "I'm lovin' it" es un **logotipo sonoro** distintivo que identifica la marca sin necesidad de decir el nombre.</p>
        </div>
        
        <div id="olfativa" class="content-section">
            <h3>Marca olfativa</h3>
            <p>El olor a papas fritas y hamburguesas es un elemento olfativo clave de McDonald's. Este aroma se asocia directamente con la experiencia de comer en sus restaurantes.</p>
        </div>
        
        <div id="tono" class="content-section">
            <h3>Tono de voz</h3>
            <p>El tono de voz de McDonald's es **amigable, positivo y divertido**. Se enfoca en crear un ambiente familiar y accesible, usando un lenguaje sencillo y cercano en sus anuncios y redes sociales.</p>
        </div>
        
        <div id="personalidad" class="content-section">
            <h3>Personalidad de la marca</h3>
            <p>La personalidad de la marca es **alegre, familiar y conveniente**. Se posiciona como un lugar donde la gente puede disfrutar de comida rápida y accesible en un ambiente casual.</p>
        </div>
        
        <div id="experiencia" class="content-section">
            <h3>Experiencia del usuario</h3>
            <p>La experiencia se centra en la **rapidez y la comodidad**. La introducción de quioscos de auto-pedido, servicio a domicilio y la aplicación móvil ha mejorado la conveniencia para el cliente.</p>
        </div>
        
        <div id="cultural" class="content-section">
            <h3>Identidad cultural</h3>
            <p>McDonald's se ha integrado en la cultura popular globalmente. Sus restaurantes son a menudo puntos de encuentro en muchas ciudades y sus productos, como la Big Mac, son íconos culturales.</p>
        </div>
        
        <div id="valores" class="content-section">
            <h3>Valores y misión</h3>
            <p>Sus valores se centran en la **calidad, el servicio, la limpieza y el valor**. La misión de la empresa es ser el lugar favorito de sus clientes para comer y beber.</p>
        </div>
        
        <div id="patrocinios" class="content-section">
            <h3>Patrocinios y alianzas</h3>
            <p>McDonald's patrocina eventos importantes como los **Juegos Olímpicos y la Copa Mundial de la FIFA**. También tienen colaboraciones con celebridades como Travis Scott y BTS para promociones especiales.</p>
        </div>
        
        <div id="eventos" class="content-section">
            <h3>Eventos y experiencias</h3>
            <p>Un evento clave es la promoción de la **Cajita Feliz** con juguetes de películas y series populares. Esto crea una experiencia especial para los niños y fomenta la lealtad a la marca desde temprana edad.</p>
        </div>
        
        <div id="contenido" class="content-section">
            <h3>Contenido de marca</h3>
            <p>Su contenido de marca se centra en publicidad televisiva y campañas en redes sociales. Publican videos cortos, imágenes de productos y memes para conectar con su audiencia de una manera divertida y actual.</p>
        </div>

    </div>

    <script>
        function showContent(id) {
            // Oculta todas las secciones de contenido
            var sections = document.querySelectorAll('.content-section');
            sections.forEach(function(section) {
                section.style.display = 'none';
            });

            // Muestra solo la sección que se solicitó
            var contentToShow = document.getElementById(id);
            contentToShow.style.display = 'block';
        }
    </script>

</body>
</html>
