<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ISC EXAMEN ORDINARIO</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Global Styles */
        body {
            margin: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
        }

        h1, h2 {
            color: #f0f6fc;
        }

        p {
            line-height: 1.6;
            color: #8b949e;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            background: linear-gradient(145deg, #161b22, #0d1117);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 20px;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            animation: fadeInDown 2s ease-out;
        }

        .hero p {
            font-size: 1.5rem;
            max-width: 800px;
            animation: fadeInUp 2s ease-out;
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Introduction Section */
        .introduction {
            padding: 60px 20px;
            background-color: #161b22;
            text-align: center;
        }

        .introduction p {
            max-width: 800px;
            margin: 0 auto 30px;
            font-size: 1.2rem;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% {
                opacity: 1;
            }
            50% {
                opacity: 0.5;
            }
        }

        /* Image Gallery Section */
        .image-gallery {
            padding: 60px 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            background-color: #0d1117;
        }

        .image-item {
            background: #21262d;
            border-radius: 8px;
            overflow: hidden;
            position: relative;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .image-item img {
            width: 100%;
            height: auto;
            display: block;
            filter: grayscale(100%);
            transition: transform 0.3s ease, filter 0.3s ease;
        }

        .image-item:hover img {
            transform: scale(1.1);
            filter: grayscale(0%);
        }

        .image-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.3);
        }

        .special-section img {
            width: 80%;
            margin: 0 auto;
            display: block;
            border: 4px solid #f0f6fc;
            border-radius: 15px;
            animation: bounce 3s infinite;
        }

        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }

        /* Footer */
        footer {
            background-color: #161b22;
            color: #8b949e;
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
        }

        footer a {
            color: #58a6ff;
        }

        footer a:hover {
            color: #1f6feb;
        }
    </style>
	<style>
    /* Global Styles */
    h2 {
        font-size: 2rem;
        background: linear-gradient(90deg, #ffc107, #17a2b8, #007bff);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        animation: colorShift 5s infinite alternate;
    }

    @keyframes colorShift {
        0% {
            background-position: 0% 50%;
        }
        100% {
            background-position: 100% 50%;
        }
    }

    /* Animations for Texts */
    p {
        animation: fadeIn 2s ease-in-out, pulse 3s infinite;
    }

    @keyframes fadeIn {
        from {
            opacity: 0;
            transform: translateY(10px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

    @keyframes pulse {
        0%, 100% {
            opacity: 1;
        }
        50% {
            opacity: 0.8;
        }
    }

    /* Special Section for NUESTRA IDEA TERMINADA */
    .special-section img {
        width: 80%;
        margin: 0 auto;
        display: block;
        border: 4px solid #f0f6fc;
        border-radius: 15px;
        animation: glow 3s infinite alternate;
    }

    @keyframes glow {
        from {
            box-shadow: 0 0 10px #ffc107;
        }
        to {
            box-shadow: 0 0 30px #17a2b8;
        }
    }
</style>





</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <h1>EXAMEN ORDINARIO</h1>
        <p>REPORTE FINAL</p>
    </section>

    <!-- Introduction Section -->
    <section class="introduction">
        <h2>INTRODUCCION</h2>
        <p>
            Se realizó una máquina de proyección a presión, la cual tendrá forma de camión de carga que tendrá un sensor de temperatura y dos pantallas LCD que indicarán la temperatura del vapor que realizará la proyección del mismo.
Para realizar el cuerpo con forma de camión hicimos un dibujo en un software de tipo tipo CAD el cual imprimimos con PLA, a continuación se explicará el desarrollo y todos los materiales que ocupamos, así como todas las propiedades, integraremos los cálculos y las ecuaciones que ocupamos.
Para realizar la estructura del camión se usó un software de tipo CAD utilizando las herramientas…….
para la impresión contactamos a la empresa llamada “KÓDIKA” con la cual realizamos la impresión, se ocupó el material PLA
        </p>
    </section>

    <!-- Image Gallery Section -->
    <section class="image-gallery">
        <div class="image-item">
            <img src="https://i.imgur.com/42nRzxC.jpeg" alt="1">
        </div>
        <div class="image-item">
            <img src="https://i.imgur.com/LRv6HoV.jpeg" alt="3">
        </div>
        <div class="image-item">
            <img src="https://i.imgur.com/tCRL1Vs.jpeg" alt="3">
        </div>
    </section>

    <!-- Introduction Section -->
    <section class="introduction">
        <h2>PLA</h2>
        <p>
          El PLA es un material que se ocupa en tecnologías de tipo FDM el cual es un termoplástico biodegradable,está hecho por materiales naturales y renovables, principalmente por almidón de maíz, caña de azúcar y raíz de tapioca.
El PLA es usado principalmente para impresión en 3D pero también se usa para dentro de otras industrias como en la agricultura, industria mercantil, en la industria robótica también la podemos encontrar, y se ha convertido en un elemento muy importante dentro de la industria de la medicina donde lleva más de 25 años siendo ocupado para hacer implantes temporales, ya que es biocompatible y este mismo se degrada dentro del cuerpo, también se ocupa para hacer prótesis.
        </p>
    </section>

    <!-- Image Gallery Section -->
    <section class="image-gallery">
        <div class="image-item">
            <img src="https://i.imgur.com/JPnvv6X.jpeg" alt="1">
        </div>
      
        <div class="image-item">
            <img src="https://i.imgur.com/BxdyH61.png" alt="2">
        </div>
    </section>

    <!-- Introduction Section -->
    <section class="introduction">
        <h2>ARDUINO UNO</h2>
        <p>
            Para poder usar las las pantallas LCD y el sensor de temperatura IM35 tuvimos que usar un Arduino Uno, esta es una de las placas más populares debido a su versatilidad y simplicidad.
Conectividad:
 Usa unMicro controlador modelo ATmega328P, una arquitectura de 8 bits, tenemos un conector tipo B para comunicación y alimentación, 1 puerto serial (RX, TX), un soporte de de comunicación I2C (A4 - SDA, A5 - SCL), y un soporte para comunicación SPI (pines dedicados: 10, 11, 12, 13),Se programa a través del puerto USB, compatible con software Arduino IDE y variantes, usa un lenguaje basado en C y o C++ con funciones simplificadas.Las pantallas LCD son dispositivos electrónicos que utilizan tecnología de cristal líquido para mostrar gráficos (Liquid Crystal Display).
 Utilizan una capa de cristal líquido que modifica la luz al recibir una señal eléctrica, no emiten luz propia por lo que necesitan una fuente de iluminación externa.

        </p>
    </section>

    <!-- Image Gallery Section -->
    <section class="image-gallery">
        <div class="image-item">
            <img src="https://i.imgur.com/Qc2ilUh.jpeg" alt="NUESTRO MODELO">
        </div>
      
        <div class="image-item">
            <img src="https://i.imgur.com/tiKUIj4.jpeg" alt="Placeholder Image 3">
        </div>
    </section>


<!-- Introduction Section -->
    <section class="introduction">
        <h2>1.Ecuacion Para un Gas Ideal en un Cuerpo Cerrado</h2>
<p>P = nRT/V</p>
<p>P: Presión interna del gas.</p>
<p>n: Cantidad de sustancia (moles).</p>
<p>R: Constante universal de los gases ().</p>
<p>T: Temperatura absoluta del gas (en kelvins).</p>
<p>V: Volumen del cuerpo cerrado.</p>
<p>Este modelo es útil si el gas se comporta idealmente (sin interacciones intermoleculares significativas).</p>
    </section>


<!-- Introduction Section -->
    <section class="introduction">
        <h2>2.Ecuación de Estado de los Gases Ideales</h2>
<p>PV = nRT</p>
<p>P: Presión del gas.</p>
<p>V: Volumen del gas.</p>
<p>n: Número de moles.</p>
<p>R: Constante universal de los gases ().</p>
<p>T: Temperatura absoluta (en kelvins).</p>
<p>Es la fórmula básica para describir el comportamiento de un gas ideal.</p>
    </section>

<!-- Introduction Section -->
    <section class="introduction">
        <h2>3. Ley de Boyle (a temperatura constante)</h2>
<p>(P_1)(V_1) = (P_2)(V_2)</p>
<p>Si la temperatura y la cantidad de gas se mantienen constantes, la presión es inversamente proporcional al volumen.</p>

    </section>
<!-- Introduction Section -->
    <section class="introduction">
        <h2>4.Ley de Charles (a presión constante)</h2>
<p>\(V1)/(T1) = (V2)/(T2)</p>
<p>Si la presión y la cantidad de gas son constantes, el volumen es directamente proporcional a la temperatura absoluta.</p>
    </section>

<!-- Introduction Section -->
    <section class="introduction">
        <h2>5.Ley de Gay-Lussac (a volumen constante)</h2>
<p>(P1)/(T1) = (P2)/(T2)</p>
<p>Si el volumen y la cantidad de gas son constantes, la presión es directamente proporcional a la temperatura absoluta.</p>

    </section>
<!-- Introduction Section -->
    <section class="introduction">
        <h2>6. Ley Combinada de los Gases</h2>
<p>(P1)(V1)/(T_1) = (P2)(V2)/(T_2)</p>
<p>Combina las leyes de Boyle, Charles y Gay-Lussac para describir un gas que sufre cambios en presión, volumen y temperatura.</p>
    </section>

<!-- Introduction Section -->
    <section class="introduction">
        <h2>7.Mezcla de Gases en un Cuerpo Cerrado (Ley de Dalton)</h2>
<p>Si el cuerpo cerrado contiene una mezcla de gases, la presión total es la suma de las presiones parciales de cada gas:</p>
<p>donde: Pi=niRT/V </p>
<p>ni:moles del gas i.</p>
    </section>
<!-- Introduction Section -->
    <section class="introduction">
        <h2>8. Relación de Presión con Fuerza y Área:</h2>
<p>Si la presión está relacionada con una fuerza en las paredes del cuerpo cerrado:</p>
<p>P =(F)/(A)</p>
<p>F: Fuerza ejercida sobre las paredes internas.</p>
<p>A: Área de las paredes.</p>

    </section>

    <!-- Special Section -->
    <section class="introduction special-section">
        <h2>MUCHAS GRACIAS POR SU ATENCION</h2>
        <p>SC0776 GONZALEZ RODRIGUEZ ANGEL DAVID</p>
	<p>SC0770 BOBADILLA GARAY PEDRO TADEO</p>
	<p>SC0749 CORONA SANCHEZ YENNSEN ADOLFO</p>
	<p>SC0774 MATAMOROS FARQUET MARIO</p>
	<p>SC0767 SERRANO LOPEZ JOSE DAVID</p>
    </section>

    <!-- Footer -->
    <footer>
    </footer>
</body>
</html>

