


<main class="main" id="top">

<script>
export const prerender = true
import { base } from '$app/paths';
</script>

<!-- page Navigation -->
<nav class="navbar custom-navbar navbar-expand-md navbar-light fixed-top" data-spy="affix" data-offset-top="10">
    <div class="container">
        <a class="navbar-brand" href="/">
            <img src="home.png " alt="">
        </a>
        <button class="navbar-toggler ml-auto" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto ">                     
                <li class="nav-item">
                    <a class="nav-link" href="{base}/">Acceuil</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="{base}/images">Images</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="{base}/place">La région</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="{base}/gite">Le gîte</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="{base}/tarifs">Tarifs</a>
                </li>
            </ul>
        </div>
    </div>
</nav>
<!-- End Of Second Navigation -->
    <slot></slot>
<!-- Contact Section -->
<section id="contact" class="section has-img-bg pb-0">
    <div class="container">
        <div class="row align-items-center">
            <div class="col-md-5 my-3">
                <h6 class="mb-0">Phone</h6>
                <p class="mb-4">+33 (0)6 75 27 45 65</p>

                <h6 class="mb-0">Adresse</h6>
                <p class="mb-4">fabrice et colette Vayssieres 670 chemin d'audhuy 46700 Duravel</p>

                <h6 class="mb-0">Email</h6>
                <p class="mb-0">colette.vayssieres@wanadoo.fr</p>
                <p></p>
            </div>
           
        </div>
        <!-- Page Footer -->
        <footer class="mt-5 py-4 border-top border-secondary">
            <p class="mb-0 small">&copy; <script>document.write(new Date().getFullYear())</script>, LeadMark Created By Antly Site All rights reserved </p>     
        </footer>
        <!-- End of Page Footer -->  
    </div>
</section>
    
    
    </main>