<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carlos Fonseca Amador - UNAN Managua</title>
    <style>
        :root {
            --rojo-sandinista: #b30000;
            --negro-profundo: #1a1a1a;
            --gris-claro: #f4f4f4;
            --dorado: #ffcc00;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--gris-claro);
            color: #333;
            line-height: 1.6;
        }

        /* Header section with background overlay */
        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                        url('https://upload.wikimedia.org/wikipedia/commons/3/3f/Carlos_Fonseca_Amador_%281970%29.jpg');
            background-size: cover;
            background-position: center 20%;
            color: white;
            padding: 100px 20px;
            text-align: center;
            border-bottom: 5px solid var(--rojo-sandinista);
        }

        header h1 {
            margin: 0;
            font-size: 3rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
        }

        /* Sticky Navigation Bar */
        nav {
            background: var(--negro-profundo);
            padding: 15px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--dorado);
        }

        /* Main Content Container */
        main {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
        }

        section {
            background: white;
            padding: 40px;
            margin-bottom: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            border-left: 6px solid var(--rojo-sandinista);
        }

        /* Button styles */
        .btn-saber-mas {
            background-color: var(--rojo-sandinista);
            color: white;
            border: none;
            padding: 12px 24px;
            font-size: 1rem;
            font-weight: bold;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s, transform 0.2s;
            margin-top: 15px;
        }

        .btn-saber-mas:hover {
            background-color: #8b0000;
            transform: scale(1.05);
        }

        #info-extra {
            display: none;
            margin-top: 20px;
            padding: 15px;
            background-color: #fff9f9;
            border-radius: 8px;
            border: 1px dashed var(--rojo-sandinista);
        }

        /* Responsive Gallery Grid */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .gallery-item {
            position: relative;
            overflow: hidden;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            background: #000;
        }

        .gallery img {
            width: 100%;
            height: 350px;
            object-fit: cover;
            display: block;
            transition: transform 0.5s ease, opacity 0.3s;
        }

        .gallery-item:hover img {
            transform: scale(1.1);
            opacity: 0.8;
        }

        .img-caption {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(0,0,0,0.7);
            color: white;
            padding: 10px;
            font-size: 0.85rem;
            text-align: center;
        }

        /* Footer and credits section */
        footer {
            background: var(--negro-profundo);
            color: white;
            padding: 60px 20px;
            text-align: center;
            margin-top: 60px;
            border-top: 5px solid var(--rojo-sandinista);
        }

        .footer-credits {
            max-width: 600px;
            margin: 0 auto;
            border: 2px solid var(--dorado);
            padding: 30px;
            border-radius: 10px;
            background: rgba(255, 255, 255, 0.05);
        }

        .footer-credits h3 {
            color: var(--dorado);
            margin-top: 0;
            text-transform: uppercase;
        }

        .creador-nombre {
            font-size: 1.5rem;
            color: #fff;
            font-weight: bold;
            display: block;
            margin-bottom: 10px;
        }

        .unan-link {
            display: inline-block;
            margin-top: 15px;
            background: var(--rojo-sandinista);
            color: white;
            text-decoration: none;
            padding: 10px 25px;
            border-radius: 50px;
            font-weight: bold;
            transition: background 0.3s;
        }

        .unan-link:hover {
            background: var(--dorado);
            color: var(--negro-profundo);
        }

        @media (max-width: 768px) {
            header h1 { font-size: 2rem; }
            nav a { display: block; margin: 10px 0; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Carlos Fonseca Amador</h1>
        <p>"Padre de la Revolución Popular Sandinista"</p>
    </header>

    <nav>
        <a href="#biografia">Biografía</a>
        <a href="#lucha">Lucha</a>
        <a href="#galeria">Galería Histórica</a>
    </nav>

    <main>
        <!-- Biography Section -->
        <section id="biografia">
            <h2>Biografía</h2>
            <div style="display: flex; gap: 20px; flex-wrap: wrap; align-items: center;">
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Carlos_Fonseca_Amador_%281970%29.jpg" alt="[Imagen de Carlos Fonseca Amador]" style="width: 250px; border-radius: 8px;">
                <div style="flex: 1; min-width: 300px;">
                    <p><strong>Nacimiento:</strong> 23 de junio de 1936, Matagalpa, Nicaragua.</p>
                    <p>Fue un destacado intelectual y educador que dedicó su vida a la justicia social y a la soberanía de Nicaragua.</p>
                    
                    <button class="btn-saber-mas" onclick="toggleInfo()">Saber más sobre su vida</button>
                    
                    <div id="info-extra">
                        <p>Fonseca fue el principal estratega del FSLN. Su legado no fue solo militar sino educativo, impulsando la alfabetización de los campesinos bajo el lema: <em>"También enséñenles a leer"</em>.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Revolution Section -->
        <section id="lucha">
            <h2>Lucha Revolucionaria</h2>
            <p>En 1961, fundó el <strong>Frente Sandinista de Liberación Nacional (FSLN)</strong>. Su visión permitió unir a distintos sectores sociales contra la dictadura somocista.</p>
        </section>

        <!-- Gallery Section -->
        <section id="galeria">
            <h2>Galería Histórica de la Vanguardia</h2>
            <div class="gallery">
                <div class="gallery-item">
                    <img src="https://via.placeholder.com/400x600?text=Comandante+Carlos" alt="[Imagen de Carlos Fonseca Amador]">
                    <div class="img-caption">Comandante Carlos Fonseca Amador</div>
                </div>
                <div class="gallery-item">
                    <img src="https://via.placeholder.com/400x600?text=Tomas+Borge" alt="[Imagen de Tomás Borge]">
                    <div class="img-caption">Comandante Tomás Borge Martínez</div>
                </div>
                <div class="gallery-item">
                    <img src="https://via.placeholder.com/400x600?text=Vanguardia+FSLN" alt="[Imagen de la Vanguardia Histórica FSLN]">
                    <div class="img-caption">Fundadores y Vanguardia Histórica</div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer with project credits and university link -->
    <footer>
        <div class="footer-credits">
            <h3>Créditos del Proyecto</h3>
            <span class="creador-nombre">Alexander Navarro</span>
            <p><strong>Integrantes:</strong> Estudiantes de marketing primer ingreso</p>
            <a href="https://www.unan.edu.ni/" target="_blank" class="unan-link">Visitar UNAN-MANAGUA</a>
        </div>
        <p style="margin-top: 40px; font-size: 0.8rem; opacity: 0.6;">&copy; 2024 Proyecto de Historia - Marketing Digital</p>
    </footer>

    <script>
        // Toggle additional info visibility
        function toggleInfo() {
            var info = document.getElementById("info-extra");
            var btn = document.querySelector(".btn-saber-mas");
            if (info.style.display === "none" || info.style.display === "") {
                info.style.display = "block";
                btn.textContent = "Mostrar menos";
            } else {
                info.style.display = "none";
                btn.textContent = "Saber más sobre su vida";
            }
        }
    </script>
</body>
</html>

