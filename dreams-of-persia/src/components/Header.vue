<template>
  <header class="header">
    <span class="header__title">DREAMS OF PERSIA</span>
  </header>
  <span
    ><div class="enter-text" v-if="showText">
      <h3>{{ text }}</h3>
    </div></span
  >
</template>

<script>
export default {
  data() {
    return {
      showText: false,
      text: "scroll down to enter",
    };
  },
  created() {
    setTimeout(() => {
      this.showText = true;
    }, 2000);
  },
};
</script>
