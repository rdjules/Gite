
<section class="section" id="about">
  <div class="container mt-4">
      <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
          <div class="carousel-inner">
              <div class="carousel-item active">
                  <img class="d-block w-100" src="assets/imgs/carousel/chambre.webp" alt="Chambre">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/coucher soleil piscine.webp" alt="Coucher de soleil piscine">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/cuisine .webp" alt="Cuisine">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/cuisine salon.webp" alt="Cuisine salon">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/côté terrasse.webp" alt="Côté terrasse">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/about-1.webp" alt="Intérieur salon">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/piscine 2.webp" alt="Piscine 2">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/piscine.webp" alt="Piscine">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/piscine_vue_de_la_terrasse.webp" alt="Piscine vue de la terrasse">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/terrasse.webp" alt="Terrasse">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/about-2.webp" alt="Village">
              </div>
              <div class="carousel-item">
                  <img class="d-block w-100" src="assets/imgs/carousel/about.webp" alt="Vue extérieur">
              </div>
          </div>
          <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Précédent</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Suivant</span>
          </a>
      </div>
  </div>
</section>



<script>
    // Importer toutes les images du dossier carousel
    const images = [
    'chambre.webp',
    'coucher soleil piscine.webp',
    'cuisine .webp',
    'cuisine salon.webp',
    'côté terrasse.webp',
    'about-1.webp', 
    'piscine 2.webp',
    'piscine.webp',
    'piscine_vue_de_la_terrasse.webp',
    'terrasse.webp',
    'about-2.webp', 
    'about.webp' 
];
</script>

<section class="section" id="about">
    <div class="container">
        <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                {#each images as image, index}
                    <div class="carousel-item {index === 0 ? 'active' : ''}">
                        <img class="d-block w-100" src={`assets/imgs/carousel/${image}`} alt={image}>
                    </div>
                {/each}
            </div>
            <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Précédent</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Suivant</span>
            </a>
        </div>
    </div>
</section>


