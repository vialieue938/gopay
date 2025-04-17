<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GoPay - Solutions Financières Modernes</title>
  <style>
    /* Reset CSS */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      color: #333333;
      line-height: 1.6;
      background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)),
                  url('https://files.catbox.moe/gy9w94.jpeg');
      background-size: cover;
      background-position: center;
    }

    .contact-bar {
      background: #2ecc71;
      padding: 15px;
      display: flex;
      justify-content: space-around;
      align-items: center;
      flex-wrap: wrap;
    }

    .contact-bar a {
      color: white;
      text-decoration: none;
      margin: 5px;
      font-size: 1.1em;
    }

    .whatsapp-btn {
      background: #25D366;
      padding: 10px 20px;
      border-radius: 25px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    header {
      text-align: center;
      padding: 60px 20px;
      background: rgba(46, 204, 113, 0.9);
    }

    header h1 {
      color: white;
      font-size: 2.8em;
      margin-bottom: 20px;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
    }

    .wise-card {
      width: 100%;
      max-width: 500px;
      margin: 30px auto;
      border-radius: 15px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }

    nav {
      background: #27ae60;
      padding: 15px;
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      transition: transform 0.3s;
    }

    nav a:hover {
      transform: translateY(-2px);
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 30px;
      padding: 50px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .service-card {
      background: rgba(255,255,255,0.95);
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      border: 3px solid #2ecc71;
      transition: transform 0.3s;
    }

    .service-card:hover {
      transform: translateY(-5px);
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2em;
      }
      
      .contact-bar {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <div class="contact-bar">
    <a href="tel:+18092045157">
      📞 Service Client: +1 (809) 204-5157
    </a>
    <a href="https://wa.me/18092045157" class="whatsapp-btn">
      💬 Rejoindre notre Groupe WhatsApp
    </a>
  </div>

  <header>
    <h1>GoPay Financial Services</h1>
    <img src="https://files.catbox.moe/71bnvw.jpeg" alt="Carte Wise GoPay" class="wise-card">
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#tarifs">Tarifs</a>
    <a href="#contact">Contact</a>
    <a href="#faq">FAQ</a>
  </nav>

  <div class="services">
    <div class="service-card">
      <h3>Transferts Internationaux</h3>
      <p>Transactions rapides et sécurisées vers 150+ pays</p>
    </div>
    <div class="service-card">
      <h3>Portefeuille Électronique</h3>
      <p>Gestion multi-devises avec taux compétitifs</p>
    </div>
    <div class="service-card">
      <h3>Paiements en Ligne</h3>
      <p>Solution de paiement intégrée pour entreprises</p>
    </div>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GoPay - Meilleur Service de Carte Crédit</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <style>
    /* Base styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      color: #333;
      background: linear-gradient(rgba(255,255,255,0.97), rgba(255,255,255,0.97)),
                  url('https://files.catbox.moe/gy9w94.jpeg');
      background-size: cover;
    }

    /* Section Titres */
    .section-title {
      text-align: center;
      margin: 50px 0;
      font-size: 2.5em;
      color: #2ecc71;
      position: relative;
    }

    .section-title:after {
      content: '';
      width: 80px;
      height: 3px;
      background: #2ecc71;
      position: absolute;
      bottom: -15px;
      left: 50%;
      transform: translateX(-50%);
    }

    /* Témoignages */
    .testimonials {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 30px;
      padding: 40px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .testimonial-card {
      background: white;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 5px 15px rgba(46, 204, 113, 0.1);
      border: 2px solid #2ecc71;
      position: relative;
    }

    .testimonial-card:before {
      content: "“";
      font-size: 4em;
      color: #2ecc71;
      position: absolute;
      top: -20px;
      left: 10px;
      opacity: 0.3;
    }

    .client-info {
      display: flex;
      align-items: center;
      margin-top: 20px;
    }

    .client-photo {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      margin-right: 15px;
      border: 2px solid #2ecc71;
    }

    /* Section Meilleur Service */
    .best-service {
      background: rgba(46, 204, 113, 0.1);
      padding: 60px 20px;
      text-align: center;
      margin: 50px 0;
    }

    .best-service-content {
      max-width: 800px;
      margin: 0 auto;
    }

    .advantages {
      display: flex;
      justify-content: center;
      gap: 40px;
      margin: 40px 0;
      flex-wrap: wrap;
    }

    .advantage-item {
      flex: 1;
      min-width: 200px;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 3px 10px rgba(46, 204, 113, 0.1);
    }

    .advantage-item i {
      font-size: 2.5em;
      color: #2ecc71;
      margin-bottom: 15px;
    }

    .cta-button {
      background: #2ecc71;
      color: white!important;
      padding: 15px 40px;
      border-radius: 30px;
      text-decoration: none;
      display: inline-block;
      font-weight: bold;
      margin-top: 30px;
      transition: transform 0.3s;
    }

    .cta-button:hover {
      transform: translateY(-3px);
    }
  </style>
</head>
<body>

  <!-- Section Témoignages -->
  <h2 class="section-title">Témoignages Clients</h2>
  <div class="testimonials">
    <div class="testimonial-card">
      <p>"GoPay a révolutionné ma gestion financière. Les transferts internationaux sont instantanés !"</p>
      <div class="client-info">
        <img src="https://i.pravatar.cc/50" class="client-photo" alt="Client">
        <div>
          <h4 style="color: #2ecc71;">Marie Dupont</h4>
          <small>Entrepreneure</small>
        </div>
      </div>
    </div>

    <div class="testimonial-card">
      <p>"La meilleure carte multi-devises que j'ai jamais utilisée. Service client exceptionnel !"</p>
      <div class="client-info">
        <img src="https://i.pravatar.cc/50?img=2" class="client-photo" alt="Client">
        <div>
          <h4 style="color: #2ecc71;">Pierre Martin</h4>
          <small>Voyageur fréquent</small>
        </div>
      </div>
    </div>
  </div>

  <!-- Section Meilleur Service -->
  <div class="best-service">
    <div class="best-service-content">
      <h2 class="section-title" style="color: #2ecc71;">Pourquoi choisir GoPay ?</h2>
      
      <div class="advantages">
        <div class="advantage-item">
          <i class="fas fa-shield-alt"></i>
          <h3>Sécurité Maximale</h3>
          <p>Protection avancée contre la fraude</p>
        </div>
        
        <div class="advantage-item">
          <i class="fas fa-globe"></i>
          <h3>Acceptation Mondiale</h3>
          <p>Utilisable dans 200+ pays</p>
        </div>
        
        <div class="advantage-item">
          <i class="fas fa-clock"></i>
          <h3>Support 24/7</h3>
          <p>Assistance permanente en français</p>
        </div>
      </div>

      <a href="#contact" class="cta-button">
        <i class="fab fa-whatsapp"></i> Obtenir ma carte maintenant
      </a>
    </div>
  </div>

</body>
</html>
<script>
document.addEventListener('DOMContentLoaded', function() {
  // Réduction progressive du header au scroll
  const header = document.querySelector('header');
  const wiseCard = document.querySelector('.wise-card');
  const nav = document.querySelector('nav');
  let lastScroll = 0;

  window.addEventListener('scroll', () => {
    const currentScroll = window.pageYOffset;

    // Animation réduction header
    if (currentScroll > 100) {
      header.style.padding = '30px 20px';
      wiseCard.style.maxWidth = '300px';
      wiseCard.style.marginTop = '0';
      nav.style.padding = '8px 15px';
      header.style.boxShadow = '0 2px 10px rgba(0,0,0,0.1)';
    } else {
      header.style.padding = '60px 20px';
      wiseCard.style.maxWidth = '500px';
      wiseCard.style.marginTop = '30px';
      nav.style.padding = '15px';
      header.style.boxShadow = 'none';
    }

    // Parallax effect sur la carte
    wiseCard.style.transform = `translateY(${currentScroll * 0.3}px)`;
    lastScroll = currentScroll;
  });

  // Animation au survol des services
  document.querySelectorAll('.service-card, .advantage-item').forEach(card => {
    card.addEventListener('mousemove', (e) => {
      const rect = card.getBoundingClientRect();
      const x = e.clientX - rect.left;
      const y = e.clientY - rect.top;
      
      card.style.transform = `
        perspective(1000px)
        rotateX(${(y - rect.height/2) / 8}deg)
        rotateY(${-(x - rect.width/2) / 8}deg)
        scale(1.02)
      `;
    });

    card.addEventListener('mouseleave', () => {
      card.style.transform = 'none';
    });
  });

  // Scroll fluide
  document.querySelectorAll('nav a').forEach(link => {
    link.addEventListener('click', (e) => {
      e.preventDefault();
      const target = document.querySelector(link.getAttribute('href'));
      target.scrollIntoView({
        behavior: 'smooth',
        block: 'start'
      });
    });
  });

  // Animation d'apparition des témoignages
  const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px'
  };

  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.style.opacity = '1';
        entry.target.style.transform = 'translateY(0)';
      }
    });
  }, observerOptions);

  document.querySelectorAll('.testimonial-card, .service-card').forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(30px)';
    el.style.transition = 'all 0.6s cubic-bezier(0.23, 1, 0.32, 1)';
    observer.observe(el);
  });

  // Adaptation mobile
  function handleMobile() {
    if (window.innerWidth < 768) {
      wiseCard.style.maxWidth = '250px';
      nav.style.gap = '15px';
    } else {
      wiseCard.style.maxWidth = '500px';
      nav.style.gap = '30px';
    }
  }

  window.addEventListener('resize', handleMobile);
  handleMobile();
<span>
