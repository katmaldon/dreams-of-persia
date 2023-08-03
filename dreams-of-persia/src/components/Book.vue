<template>
  <div class="card book">
    <div class="card__text">
      <div class="card__title">{{ title }}</div>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
        commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
        velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
        occaecat cupidatat non proident, sunt in culpa qui officia deserunt
        mollit anim id est laborum.
      </p>
    </div>
    <div class="book__gallery">gallery</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "THE BOOK",
      //   card_imgURL: url("@/assets/img/Mosque.png"),
    };
  },
};
</script>
