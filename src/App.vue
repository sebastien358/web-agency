<template>
  <div class="page">
    <!-- header avec menu principal -->
    <header>
      <img id="agency_logo" src="@/assets/images/entete/logo.png" alt="logo WebAgency"/>
      <nav>
        <ul>
          <li><a href="#home">Accueil</a></li>
          <li><a href="#services_section">Services</a></li>
          <li><a href="#projects">Portfolio</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <!-- section accueil -->
    <section id="home">
      <div id="slides">
        <div class="slide" id="slide1">
          <img src="@/assets/images/entete/fond_accueil.jpg" alt="fille qui sourit en montrant ses mains pleines de peinture"/>
        </div>
        <div class="slide" id="slide2">
          <img src="@/assets/images/entete/bg2.jpg" alt="garçon qui crie dans un porte-voix"/>
        </div>
        <div id="presentation">
          <h1><span id="name">WebAgency</span> : l'agence de tous vos projets !</h1>
          <p>Vous avez un projet web ? La WebAgency vous aide à le réaliser !</p>
          <a class="button" id="info_button" href="#services_section">Plus d'infos</a>
        </div>
        <div class="background_small_resolution">
          <img id="background" src="@/assets/images/entete/cta2-bg.jpg" alt="fond décoratif"/>
        </div>
        <div class="background_small_resolution">
          <img id="streamer" src="@/assets/images/entete/cta2-img.png" alt="mains d'enfants peintes avec des visages colorés et souriants"/>
        </div>
        <div id="chevrons">
          <div class="chevron" id="chevron_left">
            <i class="fas fa-chevron-left"></i>
          </div>
          <div class="chevron" id="chevron_right">
            <i class="fas fa-chevron-right"></i>
          </div>
        </div>
        <div id="progress_bar">
          <div id="progress_item"></div>
        </div>
      </div>
    </section>
    <!-- section services -->
    <section class="section" id="services_section">
      <div class="section_title">
        <h2>Nos services</h2>
        <div class="deco">
          <div class="blue_round"></div>
        </div>
        <p>De la conception à la mise en service : toute notre équipe est à votre écoute à chaque étape de la réalisation de votre projet.</p>
      </div>
      <div id="services">
        <div id="computer_img">
          <img id="computer" src="@/assets/images/services/main-feature.png" alt="ordinateur"/>
        </div>
        <div id="services_list">
          <div class="service_type">
            <div class="icon">
              <i class="fas fa-chart-line"></i>
              <div class="small_blue_round"></div>
            </div>
            <div class="service_description">
              <h3>UX design</h3>
              <p>Nous analysons le profil de vos futurs utilisateurs afin de créer un site "sur mesures" répondant au mieux à leurs attentes spécifiques.</p>
            </div>
          </div>
          <div class="service_type">
            <div class="icon">
              <i class="fas fa-cubes"></i>
              <div class="small_blue_round"></div>
            </div>
            <div class="service_description">
              <h3>UI design</h3>
              <p>Nous élaborons votre site en combinant un visuel agréable et attractif et une navigation fluide et intuitive.</p>
            </div>
          </div>
          <div class="service_type">
            <div class="icon">
              <i class="fas fa-chart-pie"></i>
              <div class="small_blue_round"></div>
            </div>
            <div class="service_description">
              <h3>SEO</h3>
              <p>Grâce au référencement naturel, nous optimisons la visibilté de votre site dans les résultats des moteurs de recherche.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- section projets -->
    <section class="section" id="projects">
      <div class="section_title">
        <h2>Nos Projets</h2>
        <div class="deco">
          <div class="blue_round"></div>
        </div>
        <p>Quelques exemples de nos réalisations : présentation d'associations, promotion d'entreprises, portfolio...</p>
      </div>
      <nav id="projects_menu">
        <ul>
          <li class="project_selection"><a href="#">All Works</a><div class="triangle"></div></li>
          <li class="project_selection"><a href="#">Creative</a><div class="triangle"></div></li>
          <li class="project_selection"><a href="#">Corporate</a><div class="triangle"></div></li>
          <li class="project_selection"><a href="#">Portfolio</a><div class="triangle"></div></li>
        </ul>
      </nav>
      <div id="portfolio">
        <figure class="project">
          <img src="@/assets/images/projets/01.jpg" alt="lunettes de déguisement avec nez et sourcils"/>
          <figcaption class="info" >
            <span class="portfolio_title">C la fête !</span>
            <p>Site e-commerce : articles de fête</p>
            <a href="#"><div class="eye round_container"><i class="far fa-eye"></i></div></a>
          </figcaption>
        </figure>
        <figure class="project">
          <img src="@/assets/images/projets/02.jpg" alt="personnage déguisé en lapin rose"/>
          <figcaption class="info" >
            <span class="portfolio_title">Ecole primaire "Isaac Newton"</span>
            <p>Site vitrine</p>
            <a href="#"><div class="eye round_container"><i class="far fa-eye"></i></div></a>
          </figcaption>
        </figure>
        <figure class="project">
          <img src="@/assets/images/projets/03.jpg" alt="logo original pompadour"/>
          <figcaption class="info" >
            <span class="portfolio_title">Vélo club</span>
            <p>Site vitrine d'association</p>
            <a href="#"><div class="eye round_container"><i class="far fa-eye"></i></div></a>
          </figcaption>
        </figure>
        <figure class="project">
          <img src="@/assets/images/projets/04.jpg" alt="cahier avec des graphiques"/>
          <figcaption class="info" >
            <span class="portfolio_title">Anti-fuite</span>
            <p>Présentation d'activité : Plombier</p>
            <a href="#"><div class="eye round_container"><i class="far fa-eye"></i></div></a>
          </figcaption>
        </figure>
        <figure class="project">
          <img src="@/assets/images/projets/05.jpg" alt="deux sacs de courses en papier"/>
          <figcaption class="info" >
            <span class="portfolio_title">Noir et Blanc</span>
            <p>Site e-commerce : Habillement</p>
            <a href="#"><div class="eye round_container"><i class="far fa-eye"></i></div></a>
          </figcaption>
        </figure>
        <figure class="project">
          <img src="@/assets/images/projets/06.jpg" alt="dessin avec différents types de bâtiments"/>
          <figcaption class="info" >
            <span class="portfolio_title">BatiBien</span>
            <p>Présentation d'activité : Architecte</p>
            <a href="#"><div class="eye round_container"><i class="far fa-eye"></i></div></a>
          </figcaption>
        </figure>
        <figure class="project">
          <img src="@/assets/images/projets/07.jpg" alt="dessin graphique d'une fusée qui décolle"/>
          <figcaption class="info" >
            <span class="portfolio_title">John Doe</span>
            <p>Porfolio : Photographe</p>
            <a href="#"><div class="eye round_container"><i class="far fa-eye"></i></div></a>
          </figcaption>
        </figure>
        <figure class="project">
          <img src="@/assets/images/projets/08.jpg" alt="objets de bureau bien alignés"/>
          <figcaption class="info" >
            <span class="portfolio_title">Nouveau départ</span>
            <p>Site vitrine d'association</p>
            <a href="#"><div class="eye round_container"><i class="far fa-eye"></i></div></a>
          </figcaption>
        </figure>
      </div>
    </section>
    <!-- section contact -->
    <section class="section" id="contact">
      <iframe id="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d12483.886659845393!2d2.35024751629433!3d48.86938601900249!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47e66e145ccb3091%3A0x9495beee8c96ec27!2s25+Rue+d&#39;Hauteville%2C+75010+Paris!5e0!3m2!1sfr!2sfr!4v1558538311923!5m2!1sfr!2sfr" allowfullscreen></iframe>
      <div id="blue_layer"></div>
      <form action="#" method="post">
        <h2>Contact Info</h2>
        <div id="address">
          <strong>WebAgency SAS</strong>
          <p>25 Rue d'Hauteville 78010 Paris</p>
          <a href="tel:+33102030405"><span id="tel">Tel :</span> 01 02 03 04 05</a>
        </div>
        <p>
          <input autofocus type="text" name="name" placeholder="Name"/>
        </p>
        <p>
          <input type="text" name="email" placeholder="Email"/>
        </p>
        <p>
          <input type="text" name="subject" placeholder="Subject"/>
        </p>
        <p>
          <textarea name="message" cols="30" rows="6" maxlength="400" placeholder="Message"></textarea>
        </p>
        <button class="button" type="submit">Send Message</button>
      </form>
    </section>
    <footer>
      <a href="#">Mentions légales</a>
    </footer>
  </div>
</template>

<script setup lang="ts">
</script>

<style scoped lang="scss">
.page {
  display: block;
  max-width: 1440px;
  margin: auto;
}
</style>
