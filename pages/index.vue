<template>
    <div>
        <div class="card bg-dark text-white" style="border-radius: 0;">
            <img class="card-img main-section-img" src="/assets/images/main-image.jpg" alt="Card image">
            <div class="dark-overlay"></div>
            <div class="card-img-overlay card-img-text">
                <div class="moto-container" style="display: flex; flex-direction: column;">
                    <div class="moto-card">
                        <div class="moto-title-size">
                            <h4 class="card-title main-moto">Anairo SRL</h4>
                        </div>
                        <div class="moto-description-size">
                            <p class="card-text moto-description">Fabrică de pâine dedicată producției de produse proaspete, gustoase și de calitate, realizate după rețete tradiționale și cu ingrediente atent selectate.</p>
                        </div>
                        <div class="moto-description-size">
                            <p class="card-text moto-description">Prin pasiunea pentru brutărie și respectul pentru clienți, aducem zilnic pe mesele oamenilor pâine sănătoasă și aromată.</p>
                        </div>    
                    </div>
                    <div class="contact-button">
                        <a href="tel:+40723147475">
                            <button class="top-section-button"> 
                                <Icon name="material-symbols:call" size="1.7rem" style="margin-right: 0.7rem;" /> 
                                <span>Contactați-ne</span>
                            </button>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <div id="aboutus" class="section-content" style="padding-top: 2.5rem;">
            <div class="text-content">
                <h1 class="page-title">Despre noi</h1>
                <p class="simple-text">
                    La Anairo SRL, facem pâine cu drag, după rețete simple și curate, așa cum se făcea odinioară. Credem că pâinea nu este doar un aliment, ci un simbol al bucuriei de a împărți, al grijii pentru familie și al momentelor frumoase petrecute împreună.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>De ce noi?</b>
                </p>
                <p class="simple-text" style="margin-left: 2rem;">
                    <b>• Ingrediente Alese cu Grijă:</b> Folosim făină de calitate și ingrediente naturale, pentru a păstra gustul autentic al pâinii de casă.
                </p>
                <p class="simple-text" style="margin-left: 2rem;">
                    <b>• Prospețime Zilnică:</b> Coacem zilnic, astfel încât fiecare pâine să ajungă pe masa ta caldă, aromată și plină de savoare.
                </p>
                <p class="simple-text" style="margin-left: 2rem;">
                    <b>• Pasiune și Tradiție:</b> Punem suflet în tot ce facem, păstrând tradiția brutăriei și aducând un strop de bucurie în fiecare felie.
                </p>
            </div>
            <div class="image-container">
                <img src="/assets/images/image10.jpeg" alt="Worker">
            </div>
        </div>
        <div id="products" class="section-content" style="padding-top: 2.5rem;">
            <div class="text-content">
                <h1 class="page-title">Produsele noastre</h1>
                <div class="products-grid">
                    <div class="product-card">
                        <div class="product-image">
                            <img src="/assets/images/image2.jpeg">
                        </div>
                        <h3 class="product-title">• Pâine albă •</h3>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="/assets/images/image3.jpeg">
                        </div>
                        <h3 class="product-title">• Pâine neagră •</h3>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="/assets/images/image1.jpeg">
                        </div>
                        <h3 class="product-title">• Pâine neagră cu tărâțe •</h3>
                    </div>
                </div>
                <div class="products-grid">
                    <div class="product-card">
                        <div class="product-image">
                            <img src="/assets/images/image4.jpeg">
                        </div>
                        <h3 class="product-title">• Pâine fără sare •</h3>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="/assets/images/image7.jpeg">
                        </div>
                        <h3 class="product-title">• Pâine cu secară •</h3>
                    </div>
                    <div class="product-card">
                        <div class="product-image">
                            <img src="/assets/images/image8.jpeg">
                        </div>
                        <h3 class="product-title">• Pâine graham •</h3>
                    </div>
                </div>
            </div>
        </div>
        <div id="contact" class="section-content">
            <div class="text-content">
                <h1 class="page-title">Contact</h1>
                <p class="simple-text">
                    La Anairo SRL, ne bucurăm să fim aproape de tine și să îți răspundem la orice întrebare. <br>
                    Fie că vrei să afli mai multe despre produsele noastre sau să devii partener, echipa noastră este aici pentru tine. <br>
                    Pentru noi, fiecare mesaj este o nouă ocazie de a împărtăși bucuria pâinii proaspete.
                </p>

                <div style="width: 100%; display: flex; flex-direction: row; align-items: center;">
                    <div style="width: 70%">
                        <p class="simple-text">
                            <b>Sediul social:</b>
                        </p>
                        <p class="simple-text" style="margin-left: 1rem;">
                            • Adresă: <b>Nicolae Titulescu, nr. 1, Targu Jiu, Gorj</b>
                            <br>• Telefon: <a class="simple-text" href="tel:+40723147475" style="text-decoration: none;"><b>+40 723 147 475</b></a> <b>/</b> <a class="simple-text" href="tel:+40722505851" style="text-decoration: none;"><b>+40 722 505 851</b></a>
                            <br>• Email: <b>anairosrl@yahoo.com</b>
                        </p>
                    </div>
                    <div class="pinmap" @click="openMapsSediu">
                        <img src="/assets/images/pinsediu.png">
                    </div>
                </div>

                <div style="width: 100%; display: flex; flex-direction: row;  align-items: center;">
                    <div style="width: 70%">
                        <p class="simple-text">
                            <b>Fabrica de paine ANAIRO:</b>
                        </p>
                        <p class="simple-text" style="margin-left: 1rem;">
                            • Adresă: <b>Aleea Iazului, nr. 6, Balesti, Gorj</b>
                            <br>• Telefon: <a class="simple-text" href="tel:+40723147475" style="text-decoration: none;"><b>+40 723 147 475</b></a> <b>/</b> <a class="simple-text" href="tel:+40722505851" style="text-decoration: none;"><b>+40 722 505 851</b></a>
                            <br>• Email: <b>anairosrl@yahoo.com</b>
                        </p>
                    </div>
                    <div class="pinmap" @click="openMapsFabrica">
                        <img src="/assets/images/pinfabrica.png">
                    </div>
                </div>
                <p class="simple-text">
                    Scrie-ne sau sună-ne cu încredere, îți vom răspunde cu drag și promptitudine.
                </p>
            </div>
            <div class="image-container">
                <img src="/assets/images/image9.jpeg" alt="Worker">
            </div>
        </div>
    </div>
</template>

<script>
  export default {
    methods: {
        openMapsSediu() {
            const address = "Strada Nicolae Titulescu 1 27JJ+C4, Târgu Jiu, Gorj";
            const url = `https://www.google.com/maps/search/?api=1&query=${encodeURIComponent(address)}`;
            window.open(url, "_blank");
        },
        openMapsFabrica() {
            const address = "Aleea Iazului, nr. 6, Balesti, Gorj";
            const url = `https://www.google.com/maps/search/?api=1&query=${encodeURIComponent(address)}`;
            window.open(url, "_blank");
        },
    }
  }
  </script>

<style scoped>
    .mobile-only {
        display: none;
    }
    .main-section-img {
        height: 700px; 
        object-fit: cover;
    }
    .second-section-img {
        height: 600px; 
        object-fit: cover;
    }
    .dark-overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%; /* Full width to cover the image */
        height: 100%;
        background: linear-gradient(to right, rgb(0 0 0 / 45%), rgb(0 0 0 / 45%));
        pointer-events: none; /* Prevents interaction with the overlay */
    }
    .main-moto {
        font-size: 3rem;
        font-weight: 700;
        text-transform: uppercase;
    }
    .moto-description {
        font-size: 1.7rem;
        text-align: center;
    }
    .top-section-button {
        font-size: 1.5rem;
        font-weight: 600;
        color: white;
        background: transparent;
        border: 3px solid white;
        border-radius: 20px;
        padding: 0.4rem 1.2rem;
        margin-right: 1rem;
        display: inline-flex;
        align-items: center;
    }
    .card-button-size {
        width: 100%; 
        display: flex; 
        justify-content: center;
    }
    .card-button {
        font-size: 1.5rem;
        color: black;
        background: transparent;
        border-width: 2px;
        border-color: black;
        border-radius: 10px;
        padding: 0.4rem 1.2rem;
        margin-right: 1rem;
    }
    .card-button:hover {
        color: white;
        background: black;
    }
    .card-img-text {
        padding: 3rem 5rem;
        display: flex;
    }
    .main-section {
        padding: 1rem 5rem;
    }
    .main-section-title {
        width: 100%;
        font-size: 2rem;
        font-weight: 700;
        margin-bottom: 0.5rem;
        text-align: center;
    }

    .simple-text {
        font-size: 1.2rem;
        color: rgb(54, 54, 54);
        margin-top: 0;
    }

    .small-description {
        font-size: 1.4rem;
    }

    .page-title {
        margin-bottom: 1.2rem;
        color: #d52728;
    }

    .image-container {
        flex: 1;
        max-width: 700px;
        height: auto;
        overflow: hidden;
        border-radius: 5px;
    }

    .image-container img {
        max-height: 500px;
    }

    .section-content {
        display: flex;
        flex-wrap: wrap;
        gap: 2rem;
        align-items: center;
        padding: 2rem 5rem;
    }

    .text-content {
        flex: 1;
    }
    
    .feature-card {
        width: 30%;
        border-width: 3px;
        border-radius: 15px;
        border-color: #656262;
        padding: 2rem;
    }

    .contact-button {
        width: 100%; 
        margin-top: 2rem;
        display: flex;
        justify-content: center;
    }

    .moto-container {
        display: flex; 
        width: 100%;
        align-items: center;
        margin-top: 70px;
    }

    .moto-card {
        width: 50%;
    }

    .second-moto-container {
        display: flex; 
        width: 100%;
        justify-content: center;
    }

    .second-moto-card {
        width: 70%;
    }

    .second-moto-card .main-moto {
        color: white;
    }
    .moto-title-size {
        width: 100%; 
        margin-top: 1rem;
        text-align: center;
    }

    .moto-description-size {
        width: 100%; 
        margin-top: 1rem;
    }

    .second-moto .moto-title-size {
        width: 80%; 
        margin-top: 1rem;
    }

    .second-moto .moto-description-size {
        width: 80%; 
        margin-top: 1rem;
    }

    hr {
        margin: 0 5rem;
        border: 1px solid #ccc;
    }

    .products-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 5rem;
        padding: 2rem 2rem 0rem 2rem;
    }

    .image-container img, .product-image img {
        width: 100%;
        height: auto;
        object-fit: cover;
        border-radius: 30px;
    }

    .product-title {
        display: flex;
        justify-content: center;
        margin-top: 1rem;
        font-size: 2rem;
    }

    .pinmap {
        width: 30%; 
        cursor: pointer
    }

    .pinmap img {
        height: 100px;
        border-radius: 20px;
    }

    @media (max-width: 768px) {
    .page-title {
        margin-bottom: 1rem;
    }
    .section-content {
      padding: 1rem 2rem;
      flex-direction: column;
        gap: 1rem;
    }
    .image-container {
      max-width: 100%;
      max-height: 300px;
    }
    .image-container img {
        width: 100%;
    }
    .second-img-section {
        max-height: 700px !important;
        height: 700px;
    }
    .second-img-section .moto-title-size{
        width: 100%;
    }
    .second-img-section .moto-description-size{
        width: 100%;
    }
    .second-img-section img{
        max-height: 700px !important;
    }
    .simple-text {
      font-size: 1rem;
    }
    .moto-container {
        flex-direction: column;
        gap: 1rem;
        text-align: center;
    }
    .moto-card {
        width: 100%;
    }
    .moto-title-size {
        width: 100%;
    }
    .main-moto {
        font-size: 2rem;
    }
    .moto-description-size {
        width: 100%;
    }
    .moto-description, .small-description {
        font-size: 1rem;
    }

    .main-section-img {
        height: 480px;
    }
    .second-section-img {
        height: 800px; 
    }
    .feature-card {
        width: 100%;
        padding: 1rem;
    }
    .card-button {
        font-size: 1.2rem;
    }
    .top-section-button {
        font-size: 1.2rem;
        margin-right: 0;
    }
    .contact-button {
        margin-top: 1rem;
        justify-content: center;
        display: flex;
    }
    .main-section {
        padding: 1rem 1rem !important;
    }
    .card-img-text {
        padding: 1rem 1rem !important;
    }
    hr {
      margin: 0 2rem;
    }
    .pinmap img {
        height: 65px;
        border-radius: 10px;
        margin-left: 10px;
    }
}
</style>