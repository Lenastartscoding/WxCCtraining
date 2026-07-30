<!DOCTYPE html>
<!-- saved from url=(0100)https://storage.googleapis.com/gcp-wxcctoolkit-nprd-41927.appspot.com/projects/mHpS54HiKl/index.html -->
<html lang="de"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OCEAN DRIVE | Cyber Surf Hardware &amp; Gear</title>
    <style>
        /* --- GEN Z AESTHETIC: ACID CYBER SURF PALETTE --- */
        :root {
            --bg-dark: #090a0f;        /* Deep Pitch Onyx */
            --bg-card: #13141f;       /* Dark Violet-Charcoal Card Base */
            --primary-neon: #ccff00;   /* Acid Electric Lime / Volt */
            --secondary-neon: #00f0ff; /* Electric Cyan */
            --accent-pink: #ff007f;     /* Cyber Magenta */
            --text-main: #f4f5f9;     /* Ultra Crisp High-Contrast White */
            --text-muted: #9498ab;    /* Muted Lilac-Slate */
            --white: #ffffff;
            --font-main: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            --transition: all 0.35s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        /* --- BASIC RESET --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            font-size: 16px;
        }

        body {
            background-color: var(--bg-dark);
            color: var(--text-main);
            font-family: var(--font-main);
            line-height: 1.6;
            overflow-x: hidden;
        }

        a { text-decoration: none; color: inherit; }
        ul { list-style: none; }

        /* --- GLOBAL COMPONENTS --- */
        .container {
            width: 100%;
            max-width: 1300px;
            margin: 0 auto;
            padding: 0 40px;
        }

        .section-title {
            text-align: center;
            font-size: 3rem;
            margin-bottom: 60px;
            color: var(--white);
            font-weight: 900;
            letter-spacing: -1.5px;
            text-transform: uppercase;
        }

        .section-title span {
            color: var(--primary-neon);
        }

        /* --- NAVIGATION --- */
        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 90px;
            display: flex;
            align-items: center;
            background-color: rgba(9, 10, 15, 0.85);
            backdrop-filter: blur(16px);
            z-index: 1000;
            border-bottom: 1px solid rgba(204, 255, 0, 0.15);
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 100%;
        }

        .logo {
            font-size: 1.9rem;
            font-weight: 900;
            color: var(--primary-neon);
            text-transform: uppercase;
            letter-spacing: 2px;
            font-style: italic;
        }

        .logo span {
            color: var(--accent-pink);
        }

        .nav-links {
            display: flex;
            gap: 35px;
        }

        .nav-links a {
            font-size: 0.95rem;
            font-weight: 700;
            color: var(--text-main);
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: var(--transition);
        }

        .nav-links a:hover {
            color: var(--primary-neon);
            text-shadow: 0 0 10px rgba(204, 255, 0, 0.6);
            transform: translateY(-2px);
        }

        /* --- HERO SECTION WITH HIGH IMPACT GEN-Z BACKGROUND --- */
        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
            overflow: hidden;
            background-color: var(--bg-dark);
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            /* High-contrast action barrel ocean shot with cyan/lime glow overlays */
            background: 
                radial-gradient(circle at 50% 30%, rgba(204, 255, 0, 0.15) 0%, transparent 60%),
                linear-gradient(180deg, rgba(9, 10, 15, 0.3) 0%, rgba(9, 10, 15, 0.95) 100%), 
                url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?q=80&w=1920&auto=format&fit=crop') center/cover no-repeat;
            animation: heroZoom 20s ease-in-out infinite alternate;
            z-index: 1;
        }

        @keyframes heroZoom {
            0% { transform: scale(1); }
            100% { transform: scale(1.08); }
        }

        .hero-content {
            position: relative;
            z-index: 2;
        }

        .hero h1 {
            font-size: 5.5rem;
            font-weight: 900;
            line-height: 0.95;
            color: var(--white);
            margin-bottom: 25px;
            text-transform: uppercase;
            letter-spacing: -2px;
        }

        .hero h1 span {
            display: block;
            font-size: 2.5rem;
            color: var(--primary-neon);
            font-weight: 800;
            margin-top: 15px;
            letter-spacing: 3px;
            text-shadow: 0 0 25px rgba(204, 255, 0, 0.5);
        }

        .hero p {
            font-size: 1.25rem;
            color: var(--text-main);
            max-width: 650px;
            margin: 0 auto 40px;
            text-shadow: 0 2px 10px rgba(0, 0, 0, 0.9);
        }

        .btn-modern {
            display: inline-block;
            padding: 18px 45px;
            background-color: var(--primary-neon);
            color: var(--bg-dark);
            border: 2px solid var(--primary-neon);
            font-size: 1.1rem;
            font-weight: 900;
            border-radius: 50px;
            text-transform: uppercase;
            letter-spacing: 2px;
            cursor: pointer;
            transition: var(--transition);
            box-shadow: 0 0 25px rgba(204, 255, 0, 0.4);
        }

        .btn-modern:hover {
            background-color: var(--accent-pink);
            border-color: var(--accent-pink);
            color: var(--white);
            box-shadow: 0 0 35px rgba(255, 0, 127, 0.7);
            transform: scale(1.05) translateY(-3px);
        }

        /* --- GEAR GALLERY --- */
        .equipment {
            padding: 120px 0;
            background-color: var(--bg-dark);
        }

        .eq-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .eq-item {
            position: relative;
            height: 320px;
            border-radius: 16px;
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.1);
            background-color: var(--bg-card);
            transition: var(--transition);
        }

        .eq-item:hover {
            border-color: var(--primary-neon);
            transform: translateY(-8px) scale(1.02);
            box-shadow: 0 15px 35px rgba(204, 255, 0, 0.15);
        }

        .eq-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            opacity: 0.7;
            transition: var(--transition);
            filter: saturate(1.2);
        }

        .eq-item:hover img {
            transform: scale(1.08);
            opacity: 0.95;
        }

        .eq-label {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            padding: 25px 20px 20px;
            background: linear-gradient(to top, rgba(9, 10, 15, 0.95), transparent);
            color: var(--white);
            font-size: 1.25rem;
            font-weight: 800;
            letter-spacing: 0.5px;
            text-transform: uppercase;
        }

        /* --- SERVICES / ESSENTIALS --- */
        .services {
            padding: 120px 0;
            background-color: var(--bg-card);
            position: relative;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }

        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 25px;
        }

        .service-card {
            background-color: rgba(9, 10, 15, 0.7);
            padding: 40px 25px;
            border-radius: 16px;
            border: 1px solid rgba(255, 255, 255, 0.06);
            transition: var(--transition);
            display: flex;
            flex-direction: column;
        }

        .service-card:hover {
            border-color: var(--accent-pink);
            transform: translateY(-8px);
            background-color: rgba(9, 10, 15, 0.95);
            box-shadow: 0 12px 35px rgba(255, 0, 127, 0.2);
        }

        .service-card h3 {
            font-size: 1.4rem;
            color: var(--white);
            margin-bottom: 15px;
            font-weight: 800;
            text-transform: uppercase;
        }

        .service-card p {
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        .service-icon {
            font-size: 2.8rem;
            color: var(--primary-neon);
            margin-bottom: 20px;
        }

        /* --- WHY CHOOSE US --- */
        .why-us {
            padding: 90px 0;
            background-color: var(--bg-dark);
        }

        .benefit-row {
            display: flex;
            justify-content: space-around;
            text-align: center;
            gap: 30px;
            flex-wrap: wrap;
        }

        .benefit h4 {
            color: var(--white);
            font-size: 1.3rem;
            margin-bottom: 8px;
            text-transform: uppercase;
            font-weight: 800;
            letter-spacing: 1px;
        }

        .benefit p {
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        .benefit-icon {
            font-size: 2.8rem;
            color: var(--secondary-neon);
            margin-bottom: 15px;
        }

        /* --- CONTACT / CUSTOM ORDER --- */
        .contact {
            padding: 120px 0;
            background-color: var(--bg-card);
        }

        .contact-content {
            display: flex;
            gap: 60px;
            align-items: flex-start;
        }

        .contact-text {
            flex: 1;
        }

        .contact-text p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: var(--text-muted);
        }

        .contact-form {
            flex: 1.5;
            background-color: var(--bg-dark);
            padding: 45px;
            border-radius: 20px;
            border: 1px solid rgba(204, 255, 0, 0.2);
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5);
        }

        .form-group { 
            margin-bottom: 20px; 
        }

        .form-control {
            width: 100%;
            padding: 18px;
            background-color: rgba(19, 20, 31, 0.8);
            border: 1px solid rgba(255, 255, 255, 0.12);
            border-radius: 10px;
            color: var(--text-main);
            font-family: var(--font-main);
            font-size: 1rem;
            outline: none;
            transition: var(--transition);
        }

        .form-control:focus {
            border-color: var(--primary-neon);
            box-shadow: 0 0 18px rgba(204, 255, 0, 0.25);
            background-color: var(--bg-card);
        }

        /* --- FOOTER --- */
        footer {
            padding: 50px 0;
            background-color: var(--bg-dark);
            color: var(--text-muted);
            text-align: center;
            border-top: 1px solid rgba(255, 255, 255, 0.08);
            font-size: 0.9rem;
        }

        footer p {
            margin-bottom: 8px;
        }

        footer strong {
            color: var(--primary-neon);
        }

        /* --- RESPONSIVE ADAPTATIONS --- */
        @media (max-width: 1024px) {
            .eq-grid { grid-template-columns: repeat(2, 1fr); }
            .container { padding: 0 25px; }
        }

        @media (max-width: 768px) {
            .hero h1 { font-size: 3.2rem; }
            .hero h1 span { font-size: 1.5rem; letter-spacing: 2px; }
            .eq-grid { grid-template-columns: 1fr; }
            .contact-content { flex-direction: column; }
            .section-title { font-size: 2.2rem; }
            .nav-links { gap: 15px; }
            .nav-links a { font-size: 0.85rem; }
        }
    </style>
</head>
<body>

    <header>
        <div class="container nav-container">
            <a href="https://storage.googleapis.com/gcp-wxcctoolkit-nprd-41927.appspot.com/projects/mHpS54HiKl/index.html#" class="logo">OCEAN<span>DRIVE</span></a>
            <nav>
                <ul class="nav-links">
                    <li><a href="https://storage.googleapis.com/gcp-wxcctoolkit-nprd-41927.appspot.com/projects/mHpS54HiKl/index.html#hero">Home</a></li>
                    <li><a href="https://storage.googleapis.com/gcp-wxcctoolkit-nprd-41927.appspot.com/projects/mHpS54HiKl/index.html#gear">Surf Gear</a></li>
                    <li><a href="https://storage.googleapis.com/gcp-wxcctoolkit-nprd-41927.appspot.com/projects/mHpS54HiKl/index.html#services">Services</a></li>
                    <li><a href="https://storage.googleapis.com/gcp-wxcctoolkit-nprd-41927.appspot.com/projects/mHpS54HiKl/index.html#contact">Custom Board</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero" class="hero">
        <div class="container hero-content">
            <h1>
                Ride The Wave
                <span>Cyber Surf Hardware &amp; Gear</span>
            </h1>
            <p>Dein Spezialist für handgeshapte Boards, Hochleistungs-Wetsuits und authentischen Lifestyle direkt an der Küste.</p>
            <a href="https://storage.googleapis.com/gcp-wxcctoolkit-nprd-41927.appspot.com/projects/mHpS54HiKl/index.html#gear" class="btn-modern">Gear Entdecken</a>
        </div>
    </section>

    <section id="gear" class="equipment">
        <div class="container">
            <h2 class="section-title">Unser <span>Equipment</span></h2>
            <div class="eq-grid">
                <div class="eq-item">
                    <img src="./OCEAN DRIVE _ Cyber Surf Hardware &amp; Gear_files/photo-1531722569936-825d3dd91b15" alt="Surfboards">
                    <div class="eq-label">Custom Surfboards</div>
                </div>
                <div class="eq-item">
                    <img src="./OCEAN DRIVE _ Cyber Surf Hardware &amp; Gear_files/photo-1516149893016-813d9a01d5d3" alt="Wetsuits Neopren">
                    <div class="eq-label">Wetsuits &amp; Neopren</div>
                </div>
                <div class="eq-item">
                    <img src="./OCEAN DRIVE _ Cyber Surf Hardware &amp; Gear_files/photo-1455729552865-3658a5d39692" alt="Surf Fins Leashes">
                    <div class="eq-label">Finnen &amp; Leashes</div>
                </div>
                <div class="eq-item">
                    <img src="./OCEAN DRIVE _ Cyber Surf Hardware &amp; Gear_files/photo-1507525428034-b723cf961d3e" alt="Surf Skate">
                    <div class="eq-label">Surfskates &amp; Carve</div>
                </div>
                <div class="eq-item">
                    <img src="./OCEAN DRIVE _ Cyber Surf Hardware &amp; Gear_files/photo-1520116468816-95b69f847357" alt="Apparel &amp; Wear">
                    <div class="eq-label">Beachwear &amp; Apparel</div>
                </div>
                <div class="eq-item">
                    <img src="./OCEAN DRIVE _ Cyber Surf Hardware &amp; Gear_files/photo-1506929562872-bb421503ef21" alt="Travel Bags Zubehör">
                    <div class="eq-label">Travel Bags &amp; Wax</div>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="services">
        <div class="container">
            <h2 class="section-title">Unsere <span>Services</span></h2>
            <div class="service-grid">
                <div class="service-card">
                    <div class="service-icon">🌊</div>
                    <h3>Custom Shaping</h3>
                    <p>Maßgeschneiderte Boards – abgestimmt auf deine Größe, Erfahrung und Welle.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">⚙</div>
                    <h3>Ding Repair</h3>
                    <p>Professionelle Reparatur von Epoxy- und Polyester-Board-Schäden aller Art.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🏄</div>
                    <h3>Board Rental</h3>
                    <p>Teste die neuesten Shapes für ein Wochenende oder deinen Surftrip.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">☀</div>
                    <h3>Surf Guiding</h3>
                    <p>Lokales Wissen, Spot-Tipps und Coaching für alle Skill-Level.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="why-us">
        <div class="container benefit-row">
            <div class="benefit">
                <div class="benefit-icon">🌅</div>
                <h4>Eco Friendly</h4>
                <p>Nachhaltige Materialien &amp; Bio-Wachs.</p>
            </div>
            <div class="benefit">
                <div class="benefit-icon">🏆</div>
                <h4>Shaper Quality</h4>
                <p>Handcrafted von Profi-Shapern.</p>
            </div>
            <div class="benefit">
                <div class="benefit-icon">★</div>
                <h4>Ocean Tested</h4>
                <p>Von Surfern für Surfer entwickelt.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container contact-content">
            <div class="contact-text">
                <h2 class="section-title" style="text-align: left;">Custom Board <span>anfragen</span></h2>
                <p>Du suchst ein perfektes Board oder hast Fragen zu unserem Gear? Schreib uns deine Vorstellungen und wir shapen dein nächstes Traumboard.</p>
            </div>
            <form class="contact-form" action="https://storage.googleapis.com/gcp-wxcctoolkit-nprd-41927.appspot.com/projects/mHpS54HiKl/index.html#" method="POST">
                <div class="form-group">
                    <input type="text" class="form-control" placeholder="Dein Name" required="">
                </div>
                <div class="form-group">
                    <input type="email" class="form-control" placeholder="Deine E-Mail" required="">
                </div>
                <div class="form-group">
                    <textarea class="form-control" rows="5" placeholder="Welches Board / Gear suchst du? (Skill-Level, Spot, Wünsche)..." required=""></textarea>
                </div>
                <button type="submit" class="btn-modern" style="width: 100%;">Anfrage Absenden</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p><strong>OCEAN DRIVE Surf Supply</strong> | Coastal Highway 42, 24105 Kiel</p>
            <p>© 2026 OCEAN DRIVE. Good Waves Only.</p>
        </div>
    </footer>


</body></html>
