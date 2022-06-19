<template>
  <div class="column relative-position">
    <p
      class="text-h2 text-center q-mt-lg"
      style="
        margin: 100px auto 17px auto;
        letter-spacing: 4px;
        width: 310px;
        justify-content: center;
      "
    >
      No plastic ever
    </p>
    <p
      class="text-center"
      style="margin: 0 auto; width: 600px; font-size: 31px"
    >
      We’ve delivered millions of smiles without a single plastic tube entering
      a landfill.
    </p>
    <div class="row no-wrap justify-center">
      <div class="relative-position">
        <img
          alt="medicine"
          src="../assets/medicine1.png"
          style="
            height: 300px;
            width: 220px;
            margin-right: 15vw;
            margin-left: 7vw;
          "
        />
        <img
          alt="medicine"
          src="../assets/shadowMedicine1.png"
          class="absolute"
          style="height: 280px; width: 220px; opacity: 0.9; left: 7vw"
        />
        <img alt="pill3" src="../assets/tablet3.png" class="pill_three" />
        <img alt="pill4" src="../assets/tablet4.png" class="pill_four" />
      </div>
      <div class="cutImage-wrapper">
        <img alt="medicine" src="../assets/medicine2.png" class="cutImage" />
        <img src="../assets/shadowMedicine1.png" class="cutImageShadow" />
      </div>
      <div class="cutImage-wrapper-two">
        <img
          alt="medicine"
          src="../assets/medicine2.png"
          class="absolute wrapped-image"
        />
        <div class="shadowImage-wrapper-two">
          <img
            alt="shadow"
            class="shadowImage"
            src="../assets/shadowMedicine1.png"
          />
        </div>
          <img alt="pill1" src="../assets/tablet1.png" class="pill_one absolute" />
      </div>
      <img alt="pill2" src="../assets/tablet2.png" class="pill_two absolute" />
    </div>
    <q-btn
      color="primary"
      label="Why this matters"
      class="absolute-center vertical-bottom"
      style="top: 480px"
    />
  </div>
</template>

<script>
export default {
  name: "Noplastic",
  data() {
    return {};
  },
};
</script>

<style lang="scss">
.cutImage-wrapper {
  width: 300px;
  height: 260px;
  overflow: hidden;
  position: relative;
  margin-top: 40px;

  .cutImage {
    width: 300px;
    height: 400px;
    top: -25%;
    object-fit: cover;
    object-position: 0 0;
    position: absolute;
  }
  .cutImageShadow {
    width: 300px;
    height: 400px;
  }
}

.cutImage-wrapper-two {
  width: 330px;
  height: 265px;
  overflow: hidden;
  position: relative;
  margin-left: 5vw;
  .wrapped-image {
    width: 300px;
    height: 400px;
    top: -35%;
    position: absolute;
  }
  .shadowImage-wrapper-two {
    overflow: hidden;
    width: 330px;
    height: 400px;
    margin-top: -35%;
    .shadowImage {
      width: 300px;
      height: 400px;
    }
  }
}

.pill_one {
  width: 32px;
  height: 34px;
  left: 50%;
  top: 5%;
}

.pill_two {
  width: 32px;
  height: 29px;
  top: 30%;
  left: 70%;
}

.pill_three {
  position: absolute;
  width: 32px;
  height: 29px;
  left: 60%
}

.pill_four {
  position: absolute;
  width: 32px;
  height: 29px;
  top: 5%;
  left: 45%;
}

</style>
