<template>
  <div>
    <div>
      <img src="img/images/contact1.jpg" alt="contact" class="contactpage" />
    </div>
    <div>
      <div class="row justify-content-around">
        <div class="col mt-5 " style="text-align: center;">
          <img src="img/images/ellipse1.png" />
          <h5>PISTON SANDRA</h5>
          <p style="font-size: 14px;">
            RESPONSABLE COMMERCIAL <br />
            01 48 26 34 55 <br />piston.sandra@goodmorning.fr
          </p>
        </div>

        <div class="col mt-5 " style="text-align: center;">
          <img src="img/images/ellipse2.png" />
          <h5>NGUYEN ERIC</h5>
          <p style="font-size: 14px;">
            RESPONSABLE COMMERCIAL <br />
            01 48 26 34 56 <br />nguyen.eric@goodmorning.fr
          </p>
        </div>
      </div>
    </div>

    <form>
      <div class="mb-3">
        <label for="name" class="form-label">Votre nom</label>
        <input
          type="text"
          id="name"
          style="text-align: center;"
          class="form-control"
        />
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Votre adresse mail</label>
        <input
          type="email"
          id="email"
          class="form-control"
          style="text-align: center;"
          placeholder="nguyeneric@goodmorning.com"
        />
      </div>

      <div class="mb-3">
        <label for="commentaire" class="form-label"> Votre commentaire</label>
        <textarea
          id="commentaire"
          class="form-control"
          style="text-align: center;"
        ></textarea>
      </div>
      <div class="mb-3 form-check">
        <input
          type="checkbox"
          style="text-align: center;"
          class="form-check-input"
          id="newsletter"
        />
        <label
          for="newsletter"
          style="text-align: center;"
          class="form-check-label"
          >Recevoir nos offres Promotionnelles!</label
        >
      </div>
      <button type="submit" class="btn-primary">Envoyer</button>
    </form>
  </div>
</template>
<script>
export default {
  name: "contact",
};
</script>
<style></style>
