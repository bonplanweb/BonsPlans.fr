<html><head><base href="https://bonsplans.local/">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>Recevez les Meilleurs Bons Plans et Offres Locales en Avant-Première !</title>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');
    
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    body {
        font-family: 'Roboto', sans-serif;
        line-height: 1.6;
        color: #333;
        background-color: #f4f4f4;
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
    }

    header {
        background: linear-gradient(135deg, #3498db, #2980b9);
        color: #fff;
        padding: 60px 0;
        text-align: center;
    }

    h1 {
        font-size: 2.8em;
        font-weight: 700;
        margin-bottom: 20px;
        animation: fadeInDown 1s ease-out;
    }

    h2 {
        font-size: 1.6em;
        font-weight: 300;
        margin-bottom: 30px;
        animation: fadeInUp 1s ease-out;
    }

    .cta-button {
        display: inline-block;
        padding: 15px 30px;
        background-color: #e74c3c;
        color: #fff;
        text-decoration: none;
        font-size: 1.2em;
        font-weight: 700;
        border-radius: 5px;
        transition: all 0.3s ease;
        animation: pulse 2s infinite;
    }

    .cta-button:hover {
        background-color: #c0392b;
        transform: scale(1.05);
    }

    .value-prop {
        background-color: #fff;
        padding: 60px 0;
        text-align: center;
    }

    .value-prop p {
        font-size: 1.3em;
        max-width: 800px;
        margin: 0 auto 40px;
    }

    .benefits {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
        margin-top: 40px;
    }

    .benefit-item {
        flex-basis: 22%;
        margin-bottom: 30px;
        padding: 25px;
        background-color: #f9f9f9;
        border-radius: 10px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        transition: all 0.3s ease;
    }

    .benefit-item:hover {
        transform: translateY(-5px);
        box-shadow: 0 6px 15px rgba(0,0,0,0.15);
    }

    .benefit-item i {
        font-size: 2.5em;
        color: #3498db;
        margin-bottom: 15px;
    }

    .testimonials {
        background-color: #ecf0f1;
        padding: 60px 0;
        text-align: center;
    }

    .testimonial {
        max-width: 700px;
        margin: 0 auto;
        font-style: italic;
        font-size: 1.2em;
    }

    .social-proof {
        font-weight: 700;
        margin-top: 30px;
        font-size: 1.3em;
        color: #2c3e50;
    }

    .limited-offer {
        background-color: #e74c3c;
        color: #fff;
        padding: 30px 0;
        text-align: center;
    }

    .limited-offer h3 {
        font-size: 2em;
        margin-bottom: 15px;
        animation: pulse 2s infinite;
    }

    #countdown {
        font-size: 2.5em;
        font-weight: 700;
    }

    .signup-form {
        background-color: #fff;
        padding: 60px 0;
        text-align: center;
    }

    .signup-form form {
        max-width: 500px;
        margin: 0 auto;
    }

    .signup-form input {
        display: block;
        width: 100%;
        padding: 12px;
        margin-bottom: 20px;
        border: 2px solid #ddd;
        border-radius: 5px;
        font-size: 1em;
        transition: all 0.3s ease;
    }

    .signup-form input:focus {
        border-color: #3498db;
        outline: none;
    }

    .signup-form input[type="submit"] {
        background-color: #2ecc71;
        color: #fff;
        font-weight: 700;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }

    .signup-form input[type="submit"]:hover {
        background-color: #27ae60;
    }

    .how-it-works {
        background-color: #f9f9f9;
        padding: 60px 0;
        text-align: center;
    }

    .steps {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
        margin-top: 40px;
    }

    .step {
        flex-basis: 30%;
        margin-bottom: 30px;
    }

    .step i {
        font-size: 3.5em;
        color: #3498db;
        margin-bottom: 20px;
    }

    footer {
        background-color: #34495e;
        color: #fff;
        padding: 60px 0;
        text-align: center;
    }

    .footer-content {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
    }

    .footer-section {
        flex-basis: 30%;
        margin-bottom: 30px;
    }

    .footer-section h3 {
        margin-bottom: 20px;
        font-size: 1.3em;
    }

    .footer-section ul {
        list-style-type: none;
    }

    .footer-section ul li {
        margin-bottom: 10px;
    }

    .footer-section ul li a {
        color: #fff;
        text-decoration: none;
        transition: color 0.3s ease;
    }

    .footer-section ul li a:hover {
        color: #3498db;
    }

    .legal {
        margin-top: 40px;
        font-size: 0.9em;
        opacity: 0.7;
    }

    @keyframes fadeInDown {
        from {
            opacity: 0;
            transform: translateY(-20px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

    @keyframes fadeInUp {
        from {
            opacity: 0;
            transform: translateY(20px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

    @keyframes pulse {
        0% {
            transform: scale(1);
        }
        50% {
            transform: scale(1.05);
        }
        100% {
            transform: scale(1);
        }
    }

    @media (max-width: 768px) {
        h1 {
            font-size: 2em;
        }

        h2 {
            font-size: 1.3em;
        }

        .cta-button {
            font-size: 1em;
            padding: 12px 24px;
        }

        .value-prop p {
            font-size: 1.1em;
        }

        .benefits, .steps {
            flex-direction: column;
        }

        .benefit-item, .step {
            flex-basis: 100%;
            margin-bottom: 20px;
        }

        .testimonial {
            font-size: 1em;
        }

        .social-proof {
            font-size: 1.1em;
        }

        .limited-offer h3 {
            font-size: 1.5em;
        }

        #countdown {
            font-size: 2em;
        }

        .footer-content {
            flex-direction: column;
        }

        .footer-section {
            flex-basis: 100%;
            margin-bottom: 30px;
        }
    }

    @media (max-width: 480px) {
        h1 {
            font-size: 1.8em;
        }

        h2 {
            font-size: 1.2em;
        }

        .cta-button {
            font-size: 0.9em;
            padding: 10px 20px;
        }
    }
</style>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Recevez les Meilleurs Bons Plans et Offres Locales en Avant-Première !</h1>
            <h2>Inscrivez-vous gratuitement et soyez parmi les 100 premiers à profiter d'offres exclusives et personnalisées, directement par email ou SMS !</h2>
            <a href="#signup" class="cta-button">Je veux mes Bons Plans !</a>
        </div>
    </header>

    <section class="value-prop">
        <div class="container">
            <p>Accédez aux offres locales et personnalisées avant tout le monde. Recevez des alertes sur les meilleures réductions, les événements exclusifs, et les nouveautés près de chez vous.</p>
            <div class="benefits">
                <div class="benefit-item">
                    <i class="fas fa-thumbs-up"></i>
                    <p>Offres personnalisées selon vos préférences</p>
                </div>
                <div class="benefit-item">
                    <i class="fas fa-bell"></i>
                    <p>Alertes instantanées par email et SMS</p>
                </div>
                <div class="benefit-item">
                    <i class="fas fa-star"></i>
                    <p>Exclusivité : recevez les bons plans avant tout le monde</p>
                </div>
                <div class="benefit-item">
                    <i class="fas fa-piggy-bank"></i>
                    <p>Économies garanties sur vos achats locaux</p>
                </div>
            </div>
        </div>
    </section>

    <section class="testimonials">
        <div class="container">
            <div class="testimonial">
                <p>"Grâce à ce service, j'ai économisé 150€ sur mes achats locaux en un mois seulement !" - Julie, Paris</p>
            </div>
            <div class="social-proof">
                <p>Déjà 500+ abonnés satisfaits dans votre région.</p>
            </div>
        </div>
    </section>

    <section class="limited-offer">
        <div class="container">
            <h3>Seulement 100 places gratuites restantes !</h3>
            <div id="countdown">23:59:59</div>
        </div>
    </section>

    <section id="signup" class="signup-form">
        <div class="container">
            <h2>Inscrivez-vous maintenant !</h2>
            <form id="subscribe-form">
                <input type="text" placeholder="Prénom" required>
                <input type="email" placeholder="Email" required>
                <input type="tel" placeholder="Téléphone (optionnel)">
                <input type="submit" value="Oui, je veux profiter des bons plans !">
            </form>
        </div>
    </section>

    <section class="how-it-works">
        <div class="container">
            <h2>Comment ça marche</h2>
            <div class="steps">
                <div class="step">
                    <i class="fas fa-user-plus"></i>
                    <h3>1. Inscrivez-vous gratuitement</h3>
                </div>
                <div class="step">
                    <i class="fas fa-envelope-open-text"></i>
                    <h3>2. Recevez des alertes personnalisées</h3>
                </div>
                <div class="step">
                    <i class="fas fa-gift"></i>
                    <h3>3. Profitez de réductions exclusives</h3>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Avantages</h3>
                    <ul>
                        <li>Offres personnalisées</li>
                        <li>Alertes instantanées</li>
                        <li>Exclusivité</li>
                        <li>Économies garanties</li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Liens utiles</h3>
                    <ul>
                        <li><a href="https://bonsplans.local/about">À propos</a></li>
                        <li><a href="https://bonsplans.local/faq">FAQ</a></li>
                        <li><a href="https://bonsplans.local/contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Inscrivez-vous maintenant</h3>
                    <a href="#signup" class="cta-button">Je m'inscris !</a>
                </div>
            </div>
            <div class="legal">
                <p>&copy; 2023 Bons Plans Locaux. Tous droits réservés. | <a href="https://bonsplans.local/privacy">Politique de confidentialité</a> | <a href="https://bonsplans.local/terms">Conditions d'utilisation</a></p>
            </div>
        </div>
    </footer>

    <script>
        // Countdown Timer
        function startCountdown() {
            const countdownElement = document.getElementById('countdown');
            let time = 24 * 60 * 60; // 24 hours in seconds

            function updateCountdown() {
                const hours = Math.floor(time / 3600);
                const minutes = Math.floor((time % 3600) / 60);
                const seconds = time % 60;

                countdownElement.textContent = `${hours.toString().padStart(2, '0')}:${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;

                if (time > 0) {
                    time--;
                    setTimeout(updateCountdown, 1000);
                }
            }

            updateCountdown();
        }

        startCountdown();

        // Smooth scroll for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Form submission
        document.getElementById('subscribe-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Merci de votre inscription ! Vous recevrez bientôt vos premiers bons plans.');
            this.reset();
        });

        // Intersection Observer for animations
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('animate');
                }
            });
        }, {
            threshold: 0.1
        });

        document.querySelectorAll('.benefit-item, .step').forEach(item => {
            observer.observe(item);
        });
    </script>
</body>
</html>
