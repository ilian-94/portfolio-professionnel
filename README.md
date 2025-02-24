<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Portfolio Professionnel</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <div class="container">
            <h1>Bienvenue sur Mon Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#accueil">Accueil</a></li>
                    <li><a href="#cv">CV</a>
                        <ul class="submenu">
                            <li><a href="#cv-ilian">CV de Ilian</a></li>
                            <li><a href="#cv-sabri">CV de Sabri</a></li>
                        </ul>
                    </li>
                    <li><a href="#portfolio">Portfolio</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="accueil">
            <h2>Bienvenue</h2>
            <p>Je suis un développeur passionné et créatif. Sur ce site, vous découvrirez mes projets professionnels et mes parcours à travers mes CV et mon portfolio.</p>
        </section>

        <section id="cv">
            <h2>Mes CV</h2>
            <div id="cv-ilian">
                <h3>CV de Ilian</h3>
                <p><a href="assets/cv_ilian.pdf" target="_blank">Télécharger le CV de Ilian</a></p>
            </div>
            <div id="cv-sabri">
                <h3>CV de Sabri</h3>
                <p><a href="assets/cv_sabri.pdf" target="_blank">Télécharger le CV de Sabri</a></p>
            </div>
        </section>

        <section id="portfolio">
            <h2>Mon Portfolio</h2>
            <div class="portfolio-item">
                <h3>Projet 1</h3>
                <img src="assets/portfolio_images/projet1.jpg" alt="Projet 1">
                <p>Description du projet 1</p>
            </div>
            <div class="portfolio-item">
                <h3>Projet 2</h3>
                <img src="assets/portfolio_images/projet2.jpg" alt="Projet 2">
                <p>Description du projet 2</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Mon Portfolio. Tous droits réservés.</p>
    </footer>

    <script src="script.js"></script>
</body>

</html>
