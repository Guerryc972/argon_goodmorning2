<template>
  <footer class="footer-bas">
    <div>
      <div class="row">
        <div class="col-12" style="text-align: center;">
          <p class="suivnous">SUIVEZ NOUS !</p>
        </div>
        <div class="col-12" style="text-align: center;">
          <img src="img/images/facebook.png" alt="facebook" class="facebook" />
          <img src="img/images/snapchat.png" alt="snapchat" class="snap" />
          <img src="img/images/instagram.png" alt="insta" class="insta" />
        </div>
      </div>
      <div class="row  justify-content-around">
        <div class="col-4   textfoot">
          INFORMATION
          <p class="infotext">
            GOOD MORNING <br />6 rue de Gaulle <br />78140 Velizy <br />
            05 50 00 97 06
          </p>
        </div>
        <div class="col-4 textfoot ">
          ACCÈS RAPIDE
          <p class="infotext">
            SE CONNECTER <br />
            TARIFS <br />
            ACTU <br />
            CONTACT
          </p>
        </div>
      </div>
      <div
        class="row justify-content-center"
        style="font-size:6px; font-family:exo2; color:white ; margin-top:-15px;"
      >
        goodmornig@2021
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: "app-footer",
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style></style>
