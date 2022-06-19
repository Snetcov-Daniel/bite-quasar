<template>
<div class="q-banner">
  <div class = "qb-part1">
    <h2 class = "qb-heading">Better for your wallet, better for our planet</h2>
    <span class = qb-subtitle>Our subscription is the most eco-friendly and affordable way to kick the tube.</span>
    <q-btn color="primary" class="qb-button" label="Get Started" />
    <span class = "qb-bsubtitle">Save 38% — starting from $7.50 per month</span>
  </div>
  <div class="qb-part2">
    <div class="qb-p2_waves"></div>
  </div>
  <div class="qb-part3">
    <div class="qb-p3_adverts">
      <div class="qb-p3_advert">
        <img class="qb-p3_advert_ico" src="../assets/adv1.png">
        <h3 class="qb-p3_advert_head">Choose your flavor</h3>
        <span class="qb-p3_advert_span">Choose from Fresh Mint or Activated Charcoal with Fresh Mint.</span>
      </div>
      <div class="qb-p3_advert">
        <img class="qb-p3_advert_ico" src="../assets/adv2.png">
        <h3 class="qb-p3_advert_head">Get a refill every 4 months</h3>
        <span class="qb-p3_advert_span">We send you fresh Bits every 4 months so you never run out of bits.</span>
      </div>
      <div class="qb-p3_advert">
        <img class="qb-p3_advert_ico" src="../assets/adv3.png">
        <h3 class="qb-p3_advert_head" >Pause or cancel anytime</h3>
        <span class="qb-p3_advert_span">Going on vacation? You can adjust, postpone, or cancel your subscription at any time, hassle-free.</span>
      </div>
    </div>
    <div class="qb-p3_toothpaste">
      <img src="../assets/toothpaste.png" alt="">
      <h2>One billion toothpaste tubes are thrown out each year </h2>
      <span>We want to end this plastic waste, give you a healthier smile, and build the world's most sustainable oral care company.</span>
      <a href="#">Sustainability at Bite</a>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "BannersAdvertize"
}
</script>

<style scoped>
.qb-part1{
  font-family: 'Roboto';

  display: flex;
  flex-direction: column;
  background: url("../assets/banners-bg1.png");
  background-size: 100% 100%;
  background-repeat: no-repeat;
  height: 700px;
  width: 100%;
  align-items: center;

}

.qb-heading{
  font-style: normal;
  font-weight: 400;
  font-size: 55px;
  line-height: 44px;
  margin-top: 612px;
  /* or 80% */

  text-align: center;
  letter-spacing: 2.74151px;

  color: #172345;
  width: 509px;
  height: 132px;
}
.qb-subtitle{
  font-style: normal;
  font-weight: 400;
  font-size: 25px;
  line-height: 32px;
  width: 465px;
  margin-top: 65px;
  /* or 126% */

  text-align: center;

  color: #172345;
}
.qb-bsubtitle{
  width: 359px;
  height: 18px;
  margin-top: 31px;

  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 17px;
  /* identical to box height, or 143% */

  text-align: center;
  letter-spacing: 2.08354px;
  text-transform: uppercase;

  color: #172345;
}

.qb-button{
margin-top: 33px
}

.qb-part2{
  background: #D3E1E6;
  height: 587px;
  width: 100%;
  display: flex;
  flex-direction: column-reverse;
}
.qb-p2_waves{
  background-image: url("../assets/waves.png");
  background-size: 100% 100%;
  width: 100%;
  height: 224.36px;
}

.qb-part3{
  background: #FDF8F5;
  border-radius: 0px;
  width: 100%;
  height: 1100px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.qb-p3_adverts{
  width: 80%;
  display: flex;
  justify-content: space-between;
}

.qb-p3_advert{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.qb-p3_advert_span{
  width: 238px;
  font-style: normal;
  font-weight: 400;
  font-size: 11px;
  line-height: 25px;
  /* or 224% */

  text-align: center;

  color: #172345;

}
.qb-p3_advert_head{
  font-style: normal;
  font-weight: 400;
  font-size: 23px;
  line-height: 26px;
  /* identical to box height, or 114% */

  text-align: center;

  color: #172345;
}
.qb-p3_toothpaste{
  display: flex;
  flex-direction: column;
  width: 80%;
  align-items: center;
}

.qb-p3_toothpaste h2{
  width: 1183px;

  font-style: normal;
  font-weight: 400;
  font-size: 70px;
  line-height: 110px;
  /* or 157% */

  text-align: center;
  letter-spacing: 5.48301px;

  color: #172345;
}

.qb-p3_toothpaste span{
  width: 676px;
  height: 119px;

  font-style: normal;
  font-weight: 400;
  font-size: 23px;
  line-height: 39px;
  /* or 172% */

  text-align: center;
  letter-spacing: 1.31592px;

  color: #172345;
}

.qb-p3_toothpaste a{
  width: 220px;
  height: 40px;
  margin-top: 7px;

  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 39px;
  text-decoration: none;
  /* identical to box height, or 164% */

  text-align: center;

  color: #324477;
}



</style>
