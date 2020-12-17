<template>
  <!-- <section class="section section-lg section-shaped overflow-hidden my-0"> -->
  <section>
    <div class="imghaut">
      <div class="row-12 ">
        <div class="col bodyhaut ">
          <p>LIVRAISON À DOMICILE <br />DE PAINS ET VIENNOISERIES !</p>
        </div>
        <div class="row-12">
          <div class="col-12 d-sm-block d-md-none d-lg-none youtubemobi">
            <iframe
              width="150px"
              height="60px"
              src="https://www.youtube.com/embed/aSjrFxkT7gE"
              frameborder="0"
              allow="accelerometer; autoplay=1 ;mute=0 ; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </div>
          <div
            class=" col-12 align-self-center d-none d-sm-none d-md-block d-lg-none youtubeipad"
          >
            <iframe
              width="300px"
              height="130px"
              src="https://www.youtube.com/embed/aSjrFxkT7gE"
              frameborder="0"
              allow="accelerometer; autoplay=1;mute=0; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </div>
          <div
            class="col-12 d-none d-sm-none d-md-none d-lg-block youtube"
            style="margin:0px;"
          >
            <iframe
              width="350px"
              height="250px"
              src="https://www.youtube.com/embed/aSjrFxkT7gE"
              frameborder="0"
              allow="accelerometer; autoplay=1;mute=0; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </div>
        </div>
        <div class="row">
          <div
            class="col-12 butinsc"
            style="text-align: center; margin-top:25px ;"
          >
            <a class="btn btn-warning btn-sm" href="#" role="button"
              >S'INSCRIRE</a
            >
            <a class="btn btn-warning btn-sm" href="#" role="button"
              >JE COMMANDE</a
            >
          </div>
        </div>
      </div>
    </div>
    <div class="image-bas">
      <p class="rapide">RAPIDE EN 3 ÉTAPES !</p>
    </div>

    <p></p>

    <b-container class="bv-example-row">
      <b-row>
        <b-col cols="12" md="4" class="text-center">
          <img
            v-lazy="'img/images/dekstop/iconesouris.png'"
            alt="Raised circle image"
            class=" rounded-circle shadow-lg"
            style="width: auto;"
          />
          <div class=" texte-forfait">
            <p>INSCRIT TOI ! <br />ET DÉCOUVRE CE NOUVEAU SERVICE !</p>
          </div>
        </b-col>
        <b-col cols="12" md="4" class="text-center">
          <img
            v-lazy="'img/images/dekstop/iconepc.png'"
            alt="Raised circle image"
            class="img-fluid rounded-circle shadow-lg"
            style="width: auto;"
          />
          <div class=" texte2">
            <p>CHOISIS TON FORFAIT ! <br />ENVOI TA COMMANDE !</p>
          </div>
        </b-col>
        <b-col cols="12" md="4" class="text-center">
          <img
            v-lazy="'img/images/dekstop/iconelivreur.png'"
            alt="Raised circle image"
            class="img-fluid rounded-circle shadow-lg"
            style="width: auto;"
          />
          <div class="texte3">
            <p>C'EST PARTI ! <br />TU N'AS PLUS QU'À ATTENDRE !</p>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";
import { BCard } from "bootstrap-vue/esm/components/card";
import { BContainer, BCol, BRow } from "bootstrap-vue/esm/components/layout";

export default {
  el: "#monapp",
  data: {
    message: "Hello Vue !",
  },
  components: {
    BCard,
    BContainer,
    BCol,
    BRow,
  },
};
</script>
<style></style>
