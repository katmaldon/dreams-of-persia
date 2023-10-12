<template>
  <div class="card buy">
    <div class="card__text">
      <div class="card__title">{{ title }}</div>
      <p>You can find our book at many great retailers:</p>
    </div>
    <div class="buy__row">
      <div class="buy__column--amazon">
        <a
          href="https://store.bookbaby.com/book/dreams-of-persia"
          target="blank"
          ><img src="/src/assets/img/BookBabyLogo.svg"
        /></a>
      </div>
      <div class="buy__column--bookbaby">
        <a
          href="https://store.bookbaby.com/book/dreams-of-persia"
          target="blank"
          ><img src="/src/assets/img/BookBabyLogo.svg"
        /></a>
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

.buy {
    min-height: 3rem;
    background-image: linear-gradient(#881c2d, #a72b3e);

    &__row {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        padding: 0rem 5rem 5rem 5rem;
        column-gap: 5rem;
    }

    &__column {
        display: flex;
        flex-direction: column;
        row-gap: 3rem;
        min-width: 50%;
        padding-top: 3rem;
        align-items: center;

        &--amazon {
            width: 100px;
            height: 50px;
            outline: #fff;
            background-image: "/scr/assets/img/BookBabyLogo.svg";
        }

        &--bookbaby {
            width: 100px;
            height: 50px;
            background-image: "/scr/assets/img/BookBabyLogo.svg";
        }
    }
}
