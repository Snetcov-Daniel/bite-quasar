<template>
  <q-page>
    <q-page-section>
      <Noplasic></Noplasic>
      <banners-advertize/>
    </q-page-section>
  </q-page>
</template>

<script>
import Noplasic from 'src/components/Noplasic.vue';
import BannersAdvertize from "components/BannersAdvertize";

export default {
    name: "PageIndex",
    data() {
        return {};
    },
    methods: {},

    components: {
      Noplasic,
    BannersAdvertize
    }
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

</style>
