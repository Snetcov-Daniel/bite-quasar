<template>
  <div class="row no-wrap main-block">
    <div class="description-wrapper column q-ml-lg q-mr-lg">
      <p class="howTo text-left">How to</p>
      <p class="slogan text-h2 text-weight-medium q-ml-sm">Easy as bite, brush, smile, repeat</p>
      <p class="description">
        Bite down on your Bit Brush with a wet toothbrush Smile and watch it
        foam up like magic Repeat twice a day, every day Shop now
      </p>
    </div>
    <img alt="Beautiful asian girl" src="../assets/beautifulGirl.gif" class="girl float-right" />
  </div>
</template>

<script>
export default {
  name: "Easybrush",
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
.main-block{
  margin: 234px 20px 0 70px;
  justify-content: space-between;
}

.howTo{
  font-size: 13px;
  letter-spacing: 2.08px;
  width: 54px;
  margin-top: 20px;
  margin-bottom: 61px;
  font-family: 'Roboto', sans-serif;
  border-bottom: 2px solid #F5B4A4;
  padding-bottom: 7px;
}

.slogan {
  width: 460px;
  letter-spacing: 5.12px;
  font-family: 'Roboto', sans-serif;
}

.description {
  width: 370px;
  height: 160px;
  font-size: 26px;
  margin: 91px 0 0 40px;
  font-family: 'Roboto', sans-serif;
}

.girl {
  width: 713px;
  height: 475px;
  margin-top: 110px;
  margin-right: 20px;
}
</style>
