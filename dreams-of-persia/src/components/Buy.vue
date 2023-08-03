<template>
  <div class="card buy">
    <div class="buy__row">
      <div class="card__text">
        <div class="card__title">{{ title }}</div>
        <p>You can find Dreams of Persia at many great retailers:</p>
      </div>
      <div class="buy__column">
        <div class="buy__column--amazon">Amazon</div>
        <div class="buy__column--bookbaby">bookbaby</div>
        <div class="buy__column--bn">barnes and noble</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "WHERE TO BUY",
      //   card_imgURL: url("@/assets/img/Mosque.png"),
    };
  },
};
</script>
