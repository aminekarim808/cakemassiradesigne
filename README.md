<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cakemassiradesigne - Pâtisserie & Cake Design VIP</title>
    <style>
        /* === STYLES GÉNÉRAUX === */
        body { 
            margin: 0; 
            font-family: 'Helvetica Neue', Arial, sans-serif; 
            color: #333; 
            background-color: #fcf9f9; 
            scroll-behavior: smooth;
        }
        h1, h2, h3 { font-family: 'Georgia', serif; }
        a { text-decoration: none; color: inherit; }
        
        /* === EN-TÊTE (HEADER) === */
        header { 
            background-color: #fff; 
            padding: 20px 50px; 
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
            box-shadow: 0 2px 10px rgba(0,0,0,0.05); 
            position: sticky; 
            top: 0; 
            z-index: 1000; 
        }
        .logo { 
            font-size: 26px; 
            font-weight: bold; 
            color: #d4af37; /* Couleur Or */
            letter-spacing: 2px; 
            text-transform: uppercase; 
        }
        .nav-links a { 
            margin: 0 15px; 
            font-weight: bold; 
            color: #555;
            transition: color 0.3s; 
        }
        .nav-links a:hover { color: #d4af37; }
        
        /* === SECTION ACCUEIL (HERO) === */
        .hero { 
            height: 80vh; 
            /* Image de fond par défaut (gâteau élégant) */
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1578985545062-69928b1d9587?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80') center/cover; 
            display: flex; 
            flex-direction: column; 
            justify-content: center; 
            align-items: center; 
            color: white; 
            text-align: center; 
            padding: 0 20px; 
        }
        .hero h1 { font-size: 4em; margin-bottom: 10px; text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }
        .hero p { font-size: 1.5em; margin-bottom: 40px; font-weight: 300; }
        .btn { 
            padding: 15px 40px; 
            background-color: #d4af37; 
            color: white; 
            font-size: 1.1em;
            font-weight: bold; 
            border-radius: 30px; 
            transition: background 0.3s, transform 0.2s; 
        }
        .btn:hover { background-color: #b5952f; transform: scale(1.05); }

        /* === SECTION NOS CRÉATIONS === */
        .creations { 
            padding: 80px 20px; 
            text-align: center; 
            max-width: 1200px; 
            margin: 0 auto; 
        }
        .creations h2 { font-size: 2.8em; color: #222; margin-bottom: 50px; }
        .grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
            gap: 40px; 
        }
        .card { 
            background: white; 
            border-radius: 15px; 
            overflow: hidden; 
            box-shadow: 0 10px 20px rgba(0,0,0,0.08); 
            transition: transform 0.3s; 
        }
        .card:hover { transform: translateY(-10px); }
        .card img { width: 100%; height: 300px; object-fit: cover; }
        .card h3 { padding: 20px 0; margin: 0; color: #d4af37; font-size: 1.5em; }
        .card p { padding: 0 15px 20px; color: #666; line-height: 1.5; margin: 0; }

        /* === SECTION RÉSERVATION & CONTACT === */
        .contact { 
            background-color: #1a1a1a; 
            color: white; 
            padding: 80px 20px; 
            text-align: center; 
        }
        .contact h2 { color: #d4af37; font-size: 2.5em; margin-bottom: 20px; }
        .contact p { font-size: 1.2em; margin-bottom: 40px; color: #ccc; }
        .phone-numbers { display: flex; justify-content: center; flex-wrap: wrap; gap: 20px; }
        .phone-numbers a { 
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.3em; 
            padding: 15px 30px; 
            border: 2px solid #d4af37; 
            border-radius: 50px; 
            transition: all 0.3s;
        }
        .phone-numbers a:hover { background-color: #d4af37; color: #1a1a1a; font-weight: bold; }

        /* === PIED DE PAGE === */
        footer { background: #000; color: #555; padding: 20px; text-align: center; font-size: 0.9em; }

        /* === RESPONSIVE MOBILE === */
        @media (max-width: 768px) {
            header { flex-direction: column; padding: 20px; }
            .nav-links { margin-top: 15px; }
            .hero h1 { font-size: 2.5em; }
            .hero p { font-size: 1.2em; }
            .phone-numbers a { font-size: 1.1em; padding: 10px 20px; }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">Cakemassiradesigne</div>
        <nav class="nav-links">
            <a href="#accueil">Accueil</a>
            <a href="#creations">Nos Créations</a>
            <a href="#reservation">Réserver</a>
        </nav>
    </header>

    <section id="accueil" class="hero">
        <h1>Cakemassiradesigne</h1>
        <p>L'art de la Pâtisserie VIP & du Cake Design sur mesure</p>
        <a href="#reservation" class="btn">Commander votre gâteau</a>
    </section>

    <section id="creations" class="creations">
        <h2>Nos Spécialités</h2>
        <div class="grid">
            <div class="card">
                <img src="https://images.unsplash.com/photo-1621303837174-89787a7d4729?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Cake Design sur mesure">
                <h3>Cake Design</h3>
                <p>Des gâteaux personnalisés et spectaculaires pour vos mariages, anniversaires et événements uniques.</p>
            </div>
            
            <div class="card">
                <img src="https://images.unsplash.com/photo-1550617931-e17a7b70dce2?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Pâtisserie VIP">
                <h3>Pâtisserie VIP</h3>
                <p>Une sélection haut de gamme de pâtisseries raffinées, préparées avec des ingrédients d'exception.</p>
            </div>
            
            <div class="card">
                <img src="https://images.unsplash.com/photo-1519869325930-281384150729?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Tartes Artisanales">
                <h3>Tartes Signature</h3>
                <p>Des tartes fruitées, chocolatées ou caramélisées avec un visuel moderne et un goût inoubliable.</p>
            </div>
        </div>
    </section>

    <section id="reservation" class="contact">
        <h2>Passez Commande</h2>
        <p>Contactez-nous directement par téléphone ou WhatsApp pour réserver votre gâteau d'exception.</p>
        
        <div class="phone-numbers">
            <a href="tel:+212617870284">📞 06 17 87 02 84</a>
            <a href="tel:+212617542755">📞 06 17 54 27 55</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Cakemassiradesigne. Tous droits réservés.</p>
    </footer>

</body>
</html># cakemassiradesigne
